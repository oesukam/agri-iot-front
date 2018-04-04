<template>
  <div id="app">
    <top-nav />
    <router-view/>
    <bottom-footer/>
  </div>
</template>

<script>
import TopNav from './components/TopNav'
import BottomFooter from './components/BottomFooter'
export default {
  name: 'App',
  components: {
    TopNav,
    BottomFooter
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
  margin-top: 50px;
  min-height: 100vh;
  margin-bottom: -50px;
  position: relative;
}
.button .is-primary {
  background-color: #424242 !important;
}
</style>
