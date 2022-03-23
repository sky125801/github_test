<template>

  <ExampleDemo flag=false isActive=false hasError=true activeClass='active' errorClass='error'></ExampleDemo>
  
</template>

<script>
import ExampleDemo from './components/example3-6.vue'

export default {
  name: 'App',
  components: {
    'ExampleDemo': ExampleDemo
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
