<template>

    <div id="app">
    <Weather />
  </div>
</template>

<script>

import Weather from './components/Weather.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    Weather
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
