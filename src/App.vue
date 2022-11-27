<template>
  <div id="app">
    <PageIndex></PageIndex>
  </div>
</template>

<script>
import PageIndex from './page/pageIndex.vue'

export default {
  name: 'App',
  components: {
    PageIndex
  }
}
</script>

<style>
body{
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
