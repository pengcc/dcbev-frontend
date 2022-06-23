<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/admin">Admin</RouterLink>
        <RouterLink to="/members">Members</RouterLink>
        <RouterLink to="/players">Players</RouterLink>
      </nav>
    </div>
  </header>
</template>
