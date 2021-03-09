<template>
  <div id="app">
    <HelloWorld/>
    <CalculadoraNova/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CalculadoraNova from './components/CalculadoraNova'
export default {
  name: 'App',
  components: {
    HelloWorld,
    CalculadoraNova

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
