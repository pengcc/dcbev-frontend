<script setup lang="ts">
import LoginForm from '@/components/LoginForm.vue'
</script>
<template>
  <div class="admin">
    <LoginForm />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .admin {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>
