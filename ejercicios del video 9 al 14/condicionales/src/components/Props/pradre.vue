<script setup>
import { ref } from 'vue';
import hijo1 from './hijo1.vue';
import hijo2 from './hijo2.vue';
defineProps({
      nombre: String,

    })

</script>
<template>
   <div class="container">
    <h1>soy el componente padre</h1>
    <hijo1 class="mt-4" edad="18"/>
    <hijo2 class="mt-4" edad="15"/>
</div>

</template>
<style>

</style>