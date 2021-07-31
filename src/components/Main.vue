<template>
  <div class="">
    <img class="logo" alt="logo" src="../assets/logo.png">
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
  height: 400px;
  width: 400px;
  margin-top: 10%
}

.div_menu {
  margin-top: 25%;
}
</style>
