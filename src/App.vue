<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
   <Janela />
  </div>
</template>

<script>
import Janela from './components/Janela.vue'

export default {
  name: 'App',
  components: {
    Janela
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
