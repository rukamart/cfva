<template>
  <div id="app">
    <VueFixedHeader
    :threshold="propsData.threshold"
    :hideScrollUp="propsData.hideScrollUp"
    >
    <nav>
      <el-menu>
        <el-menu-item class="menu-brand" index="1">
          <a href="#time"><img src="https://img.icons8.com/ios-filled/30/fa314a/calendar.png"/></a>
        </el-menu-item>
        <el-menu-item class="menu-brand" index="2">
          <a href="#price"><img src="https://img.icons8.com/ios-filled/30/fa314a/low-price.png"/></a>
        </el-menu-item>
      </el-menu>
    </nav>
  </VueFixedHeader>
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
import VueFixedHeader from 'vue-fixed-header'

const createData = () => ({
  threshold: 0,
  hideScrollUp: false
});

export default {
  name: 'App',
  components: {
    Init,
    Time,
    Price,
    VueFixedHeader
  },
  data() {
    return {
      propsData: { ...createData() }
    }
  },
}
</script>

<style>
html {
  scroll-behavior: smooth;
}

#app {
  text-align: center;
}

nav {
  width: 100vw;
  margin: 0;
  padding: 0;
  background: #191919;
  border-bottom: solid 1px red;
  margin-left: auto;
  margin-right: 0;
}

nav.vue-fixed-header--isFixed {
  position: fixed;
  left: 0;
}

.menu-brand {
  margin: 1%;
}
</style>
