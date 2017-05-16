<template>
  <div id="app">
    <!--<router-view></router-view>-->
    <myheader></myheader>
  </div>
</template>

<script>
import myheader from './components/header/myheader.vue'
export default {
  name: 'app',
  components: {
    myheader
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}

body {
  margin: 0;
  padding: 0;
}
</style>
