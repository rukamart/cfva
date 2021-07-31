<template>
    <div>
      <img id="img" alt="logo" src="../assets/horario.png">
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
</style>
