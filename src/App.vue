<template>
  <div id="app">
    <TestMap></TestMap>
  </div>
</template>

<script>
import TestMap from './components/TestMap.vue'

export default {
  name: 'App',
  components: {
    TestMap
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
  margin-top: 0px;
}
</style>
