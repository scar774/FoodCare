<template>
  <img alt="FoodCare logo" src="./assets/LogoTransparente.png">
  <HelloWorld msg="Welcome to FoodCare"/>
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

<script setup>
import { SpeedInsights } from '@vercel/speed-insights/vue';
</script>
 
<template>
  <SpeedInsights />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
