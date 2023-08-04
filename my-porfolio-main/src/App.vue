<template>
  <div id="app">
     <Home> </Home>
     <Portfolio> </Portfolio>
  </div>
</template>

<script>
import Home from './components/MyIdentity.vue'
import Portfolio from './components/MyPortfolio.vue'

export default {
  name: 'App',
  components: {
    Home,
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}

</style>
