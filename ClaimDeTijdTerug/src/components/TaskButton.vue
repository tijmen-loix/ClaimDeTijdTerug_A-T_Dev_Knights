<script setup lang="ts">
import ProgressBar from '@/components/ProgressBar.vue'
</script>

<template>
  <router-link to="/task">
    <div class="main-task">
      <h2>Web advanced Pokedex</h2>

      <span>Subtasks: 2/6</span>
      <span>Deadline: 14/12/2026</span>
      <ProgressBar /></div
  ></router-link>
</template>

<style scoped>
template a {
  text-decoration: none;
}

.main-task {
  border: 3px solid black;
  width: 450px;
  height: 150px;
  border-radius: 15px;
  text-decoration: none;
}

.main-task a {
  text-decoration: none;
}
</style>
