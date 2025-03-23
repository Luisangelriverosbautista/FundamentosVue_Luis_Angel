<script setup>
import principal from './components/pagina_principal.vue'
import principalcom from './components/pagina utilizando componentes/principalcom.vue'
</script>

<template>
  <!-- pagina utizlizando componentes -->
  <principalcom/>
  <!-- <principal msg="Vite + Vue" /> -->
  
  
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
