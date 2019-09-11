<template>
  <div id="app">
    <HelloWorld />
    <info1/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import info1 from './components/info1'

export default {
  name: 'app',
  components: {
    HelloWorld,
    info1
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
