<template>
  <div id="app">
    <Init id="home"/>
    <Time id="time"/>
    <Price id="price"/>
    <Contacts id="contacts"/>
  </div>
</template>

<script>
import Init from './components/Main.vue'
import Time from './components/Time.vue'
import Price from './components/Price.vue'
import Contacts from './components/Contacts.vue'

export default {
  name: 'App',
  components: {
    Init,
    Time,
    Price,
    Contacts
  }
}
</script>

<style>
html {
  scroll-behavior: smooth;
}

#app {
  text-align: center;
  margin-top: 60px;
}
</style>
