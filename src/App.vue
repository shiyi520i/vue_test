<template>
  <div id="app">
    <Login></Login>
<!--    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <router-link to="/login">Go to Foo</router-link>
    <router-view></router-view>-->
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Login from './views/Login'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    Login
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
