<template>
  <div id="app">
    <img id="logo" alt="logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <parallax>
      <img src="./assets/back3.jpeg" alt="very cool bg">
    </parallax>
    <img id="img" alt="logo" src="./assets/horario.png">
    <parallax :fixed=true>
      <img src="./assets/back3.jpeg" alt="very cool bg">
    </parallax>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/Main.vue'
import Parallax from 'vue-parallaxy'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Parallax
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: brown;
  margin-top: 60px;
}
#img {
  height: 450px;
  width: 50%;
}
#logo {
  height: 10%;
  width: 10%;
}
</style>
