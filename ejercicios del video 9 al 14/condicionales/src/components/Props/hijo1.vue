<script setup>
import { ref } from 'vue';

defineProps({
      edad: String,

    })

</script>

<template>
   
   <h6>soy el componente hijo 1</h6>
   <p>{{ edad }}</p>
</template>
<style>

</style>