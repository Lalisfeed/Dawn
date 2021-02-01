<template>
  <div class="app">
    <Header/>
    <Serbar/>
    <Noload/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Serbar from './components/Serbar.vue'
import Noload from './components/Noload.vue'

export default {
  name: 'App',
  components: {
    Header,
    Serbar,
    Noload
  }
}
</script>

<style>
.app {
  width: 100vw;
  min-height: 100vh;
  height: 100%;
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  color: #fefefe;
}

*::selection, *::-moz-selection, *::selection, *::-moz-selection {
  color: #fefefe;
  background: #ec1d24;
}
</style>
