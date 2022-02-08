<template>
  <div id="app">
    <Statues/>
  </div>
</template>

<script>

import Statues from './components/Statues.vue'

export default {
  name: 'App',
  components: {
    Statues
  },
  data(){
    return{
      route: "Statues"
    }
  },
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
table{
  margin: auto;
}
button{
  color: rgb(243, 1, 1);
  background-color: rgb(253, 253, 253);
  height: 30px;
  font-size: 15px;
}
body{
  background-color: rgb(243, 215, 215);
  font-size: 20px;
}
input{
  width: 20pc;
  text-align: center;
  font-size: 16px;
}
</style>
