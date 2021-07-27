<template>
    <div>
      <img id="img" alt="logo" src="../assets/horario.png">
      <div class="div_time">
        <a href="#home"><img src="https://img.icons8.com/ios-filled/50/fa314a/home.png"/></a>
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

<style scoped>
#img {
  height: 80%;
  margin: auto;
  width: 70%;
  padding: 50px;
}

.div_time a {
  margin: 5%;
}
</style>
