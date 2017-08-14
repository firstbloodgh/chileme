<template>
  <div id="app">
    <router-view></router-view>
    <index-header></index-header>
  </div>
</template>


<script>
import indexHeader from "./components/IndexHeader"

export default {
  name: 'app',
  components: {
    indexHeader
  }
}
</script>

<style>
@import "./assets/style/global.scss";

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>