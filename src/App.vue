<template>
  <div id="app">
    <h1>Vue.js</h1>
    <HelloWeb/>
  </div>
</template>

<script>
import HelloWeb from './components/HelloWeb.vue'

export default {
  name: 'App',
  components: {
    HelloWeb
  }
}
</script>

<style>
* {
    background: #000;
}
#app {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  color: #2491ff;
  margin-top: 60px;
}
</style>
