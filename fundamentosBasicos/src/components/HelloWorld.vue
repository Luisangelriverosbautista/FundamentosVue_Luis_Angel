<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="container">
  <h1> HOLA SOY LUIS</h1>

  <P class="parrafo">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
    Praesentium hic minus beatae recusandae vel optio,
     laudantium exercitationem culpa accusantium quia omnis fuga laborum eum consectetur. 
     Dignissimos reprehenderit exercitationem numquam quas?
  </P></div>
</template>

<style scoped>
.parrafo{
  text-align: center;
  color: red;
}
.read-the-docs {
  color: #888;
}
</style>
