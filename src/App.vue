<template>
  <div id="app">
<!--     <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
 <!--    <saurav></saurav> -->
    <navupper></navupper>
    <navlower></navlower>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import saurav from './components/saurav.vue'
import navupper from './components/navupper.vue'
import navlower from './components/navlower.vue'

export default {
  name: 'app',
  components: {
    navupper,
    navlower
  }
}
</script>

<!-- <style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style> -->
