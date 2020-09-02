<template>
  <div id="app">
    <Calculator/>
  </div>
</template>

<script>
import Calculator from '@/components/Calculator'

export default {
  name: 'App',
  components: {
    Calculator
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
h1{
  font-size: 3em;
}
body{
  width: 100vw;
  height: 100vh;
  font-size: 2.5vw;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
