<template>
  <div id="app">
    <v-home></v-home>
    <!-- <router-view/> -->
  </div>
</template>

<script>
import homepage from './components/homepage'

export default {
  name: 'App',
   components: {
    'v-home':homepage
  }
}
</script>

<style>
#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
