<script setup>

import card from './components/card.vue'
import card_componente from './components/CardEnComponente/card_componente.vue';
</script>

<template>
  
  <!-- <card/> -->
  <card_componente/>
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
</style>
