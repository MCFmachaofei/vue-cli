<template>
  <div id="app">
    <router-view></router-view>
  </div>
  
</template>

<script>
export default {
  name: 'app'
}
</script>

<style less>
*{
  margin:0;
  padding:0;
  border:none;
}
  li{
    list-style: none;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
}

</style>
