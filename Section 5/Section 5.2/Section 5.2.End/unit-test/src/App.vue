<template>
  <div id="app" class="starter-template">
    <img src="./assets/logo.png">

    <router-link to="/">Home</router-link> | 
    <router-link to="/counter">Counter</router-link>

     <router-view></router-view>
     <router-view name="my-component"></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
