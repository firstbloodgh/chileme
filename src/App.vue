<template>
  <div id="app">
    <router-view></router-view>
    <index-header></index-header>
    <index-type></index-type>
    <index-recgoods></index-recgoods>
    <index-footer></index-footer>
  </div>
</template>


<script>
import indexHeader from "./components/IndexHeader"
import indexType from "./components/IndexType"
import indexRecgoods from "./components/IndexRecgoods"
import indexFooter from "./components/IndexFooter"

export default {
  name: 'app',
  components: {
    indexHeader , indexType , indexRecgoods , indexFooter
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