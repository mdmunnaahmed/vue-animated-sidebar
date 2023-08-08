<template>
  <the-sidebar></the-sidebar>
  <router-view></router-view>
</template>

<script>
import TheSidebar from './components/TheSidebar.vue'

export default {
  name: 'App',
  components: {
    TheSidebar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
