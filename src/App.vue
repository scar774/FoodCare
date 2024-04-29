<template>
  <img alt="FoodCare logo" src="./assets/LogoTransparente.png">
  <HelloWorld msg="Welcome to FoodCare"/>
  <SpeedInsights />
</template>

<script>
import { SpeedInsights } from '@vercel/speed-insights/vue';
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
</style>
