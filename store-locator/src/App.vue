<template>
  <div id="app">
    <NavBar />
    <Home />
    <router-view/>
  </div>
</template>

<script>

import NavBar from './components/NavBar'
// import StoreDetail from './components/StoreDetail'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Home,
    // StoreDetail
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
