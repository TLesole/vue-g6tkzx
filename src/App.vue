<template>
  <div id="app">
    <h1>Hello World</h1>
    <h2>Welcome to my first VUE.js project
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: serif;
  text-align: center;
  color: #800080;
  margin-top: 60px;
}
</style>
