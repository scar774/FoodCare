
<!--<script setup>
import { SpeedInsights } from '@vercel/speed-insights/vue';
</script>-->

<template>
  <div class="image-container">
    <img alt="FoodCare logo" src="./assets/LogoTransparente.png" class="responsive-image">
  </div>
  
  <HelloWorld msg="Welcome to FoodCare"/>
  <!--<SpeedInsights />-->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.image-container {
    max-width:100%; /* Ensure the container does not exceed the width of its parent */
    overflow: hidden; /* Hide any overflow to prevent horizontal scrolling */
    margin: 0 auto; /* Centra el contenedor horizontalmente */
    max-width: 500px; /* Establece el ancho máximo del contenedor */
}

.responsive-image {
    width: 100%; /* Ensure the image takes up the full width of its container */
    height: auto; /* Maintain the aspect ratio of the image */
    display: block; /* Ensure the image behaves as a block element */
}
</style>
