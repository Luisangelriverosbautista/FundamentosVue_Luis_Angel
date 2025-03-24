<script setup>
import { ref } from 'vue'

// defineProps({
//   msg: String,
// })
const bienvenida = ref("bienvenido a la seccion de condicionales")
const nombre =("luis angel")
const apellido =("riveros bautista")
</script>

<template>
  <div class="container">
    <h2 class="text-center">{{ bienvenida }}</h2>
    <div class="row">
      <div class="col-md-6">
        <h6>{{ nombre }}</h6>
        <h6>{{ apellido }}</h6>
      </div>
    </div>
  </div>
  
</template>

<style scoped>

</style>
