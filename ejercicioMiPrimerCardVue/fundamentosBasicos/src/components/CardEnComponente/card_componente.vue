<script setup>
import cardsCom from './cardsCom.vue';

</script>

<template>
  <div class="container">
    <h1 class="text-center"> MASCOTAS </h1>
    <!-- cominezo de row -->
    <div class="row">
      <div class="col-md-6">
        <div class="card">
          <div class="card-header" style="background-color: greenyellow;">
            <h6>Gatos</h6>
          </div>
          <div class="card-body">
            <img
              src="https://images.ctfassets.net/denf86kkcx7r/4IPlg4Qazd4sFRuCUHIJ1T/f6c71da7eec727babcd554d843a528b8/gatocomuneuropeo-97"
              alt="" style="width: 200px;height: 200px;">
            <p>Los gatos son felinos ágiles, inteligentes y sigilosos. Son conocidos por su independencia y curiosidad.
              Tienen un excelente sentido del equilibrio, garras retráctiles y una gran habilidad para trepar. Su
              ronroneo puede ser un signo de felicidad y relajación. </p>
          </div>

        </div>
      </div>
      <div class="col-md-6">
        <div class="card">
          <div class="card-header " style="background-color: greenyellow;">
            <h6>Perros</h6>
          </div>
          <div class="card-body">
            <img
              src="https://cdn.sanity.io/images/5vm5yn1d/pro/5cb1f9400891d9da5a4926d7814bd1b89127ecba-1300x867.jpg?fm=webp&q=80"
              alt="" style="width: 200px;height: 200px;">
            <p>Los perros son leales y sociables. Son animales domesticados desde hace miles de años y se destacan por
              su capacidad de aprendizaje y obediencia. Existen muchas razas con características únicas, desde pequeños
              chihuahuas hasta grandes san bernardos. Son compañeros ideales para el ser humano.</p>
          </div>

        </div>
      </div>

    </div>
    <!-- cierre del primer row -->
    <!-- cominezo del row 2 -->
    <cardsCom />
    
    <!-- cierre del segundo row -->

  </div>


</template>

<style scoped></style>
