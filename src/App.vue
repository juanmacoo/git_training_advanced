<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Endava msg="This is an Endava Test Vue.js App"/>
  </div>
</template>

<script>
import Endava from './components/Endava.vue'

export default {
  name: 'app',
  components: {
    Endav
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
