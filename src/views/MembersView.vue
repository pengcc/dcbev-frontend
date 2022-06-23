<template>
  <div class="members">
    <MemberTableVue />
  </div>
</template>

<script setup lang="ts">
import MemberTableVue from '@/components/MemberTable.vue'
</script>

<style>
@media (min-width: 1024px) {
  .members {
    min-height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>
