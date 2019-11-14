<template>
  <div id="app">
    <HelloWord></HelloWord>
    <login></login>
<extra></extra>
  </div>



</template>

<script>
  import extra from './components/extra'
  import login from './components/login'
  import HelloWord from './components/HelloWorld'
export default {
  name: 'app',
  components: {
    login,
    HelloWord,
    extra
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
