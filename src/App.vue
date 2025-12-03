<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
  <HelloWorld msg="Vue Training" />
  <label class="label">Vue Learning</label>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.label {
  font-size:12px;
}
</style>
