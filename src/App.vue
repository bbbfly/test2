<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <img class="test-img" src="./assets/logo.png" alt="">
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less" scoped >
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  .test-img{
    width: 190px;
    height: 180px;
  }
}
</style>
