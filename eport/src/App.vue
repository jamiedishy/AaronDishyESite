<template>
  <div id="app">
    <Header />
    <Bio />
    <Info />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Bio from './components/Bio.vue'
import Info from './components/Info.vue'

export default {
  name: 'App',
  components: {
    Header,
    Bio,
    Info
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: black;
  margin-top: 60px;
}
</style>
