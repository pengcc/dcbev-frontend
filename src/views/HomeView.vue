<script setup lang="ts">
import TheWelcome from '@/components/TheWelcome.vue'
import LoginForm from '@/components/LoginForm.vue'
</script>

<template>
  <main>
    <TheWelcome />
    <div class="home">
      <LoginForm />
    </div>
  </main>
</template>

<style>
  .home {
    min-height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>