<template>
  <div class="">
    <img class="logo" alt="logo" src="../assets/logo.png">
    <div class="div_menu">
      <a href="#time"><img src="https://img.icons8.com/ios-filled/50/fa314a/calendar.png"/></a>
      <a href="#price"><img src="https://img.icons8.com/ios-filled/50/fa314a/low-price.png"/></a>
      <a href="#contacts"><img src="https://img.icons8.com/ios-filled/50/fa314a/apple-contacts.png"/></a>
    </div>
    <parallax>
      <img src="../assets/back3.jpeg">
    </parallax>
  </div>
</template>

<script>
import Parallax from 'vue-parallaxy'

export default {
  name: 'App',
  components: {
    Parallax
  }
}
</script>

<style>
.logo {
  height: 20%;
  width: 20%;
}

.div_menu {
  position: absolute;
  bottom: 10%;
  width: 70%;
}

.div_menu a {
  margin: 5%;
}
</style>
