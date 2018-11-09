<template>
  <div id="app">
    <p>欢迎来到wedding.com 系统后台</p>
    <Welcome :name="name"></Welcome>
  </div>
</template>

<script>
import Welcome from './components/Welcome.vue'

export default {
  name: 'app',
  components: {
    Welcome
  },
  data(){
    return{
      name:'wz'
    }
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
  margin-top: 60px;
}
</style>
