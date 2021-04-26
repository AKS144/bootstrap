<template>
  <div id="app">
    <h1>Bootstrap</h1>
    <boots />
  </div>
</template>

<script>
import boots from './components/boots.vue'

export default {
  name: 'App',
  components: {
    boots,
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
