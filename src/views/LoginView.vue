<script setup lang="ts">
import LoginForm from '../components/LoginForm.vue'

</script>

<template>
  <main>
    <div class="login">
      <h1>This is the LOGIN page</h1>
    </div>

    <LoginForm />

  </main>
</template>

<style>
@media (min-width: 1024px) {
  .login {
    text-align: center;
  }
}
</style>
