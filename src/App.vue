<template>
  <div id="app">
<!--     <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
 <!--    <saurav></saurav> -->
    <navupper></navupper>
    <navlower></navlower>
    <slider></slider>
    <benifits></benifits>
    <whatweoffer></whatweoffer>
    <amazingworks></amazingworks>
    <values></values>
    <workdone></workdone>
    <ourteam></ourteam>
    <progressbar></progressbar>
    <brands></brands>
    <purchasenow></purchasenow>
    <footerup></footerup>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import saurav from './components/saurav.vue'
import navupper from './components/navupper.vue'
import navlower from './components/navlower.vue'
import slider from './components/slider.vue'
import benifits from './components/benifits.vue'
import whatweoffer from './components/whatweoffer.vue'
import amazingworks from './components/amazingworks.vue'
import values from './components/values.vue'
import workdone from './components/workdone'
import ourteam from './components/ourteam'
import progressbar from './components/progressbar'
import brands from './components/brands'
import purchasenow from './components/purchasenow'
export default {
  name: 'app',
  components: {
    navupper,
    navlower,
    slider,
    benifits,
    whatweoffer,
    amazingworks,
    values,
    workdone,
    ourteam,
    progressbar,
    brands,
    purchasenow
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
