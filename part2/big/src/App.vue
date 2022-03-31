<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TheFooter></TheFooter>
  </div>
</template>

<script>
import TheFooter from './components/TheFooter.vue'

export default {
  name: 'App',
  components: {
    TheFooter
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
