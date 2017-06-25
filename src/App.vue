<template>
  <div id="app">
    <img src="./assets/logo.png">
    test 123
    <hello></hello>
    <mycomponent></mycomponent>
  </div>
</template>

<script>
import Hello from './components/Hello'
import mycomponent from './components/mycomponent'
export default {
  name: 'app',
  components: {
    Hello,
    mycomponent
  }
}
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
