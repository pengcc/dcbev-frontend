<template>
  <div class="players">
    <PlayerTableVue />
  </div>
</template>

<script setup lang="ts">
import PlayerTableVue from '@/components/PlayerTable.vue'
</script>

<style>
@media (min-width: 1024px) {
  .players {
    min-height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>
