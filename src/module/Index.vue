<template>
  <div id="app">
    <img src="../assets/logo.png">
    <div>主页内容</div>
    <a href="/user/index.html">用户</a>
    <hello></hello>
  </div>
</template>

<script>
  import Hello from '@/components/Hello/Hello'

  export default {
    name: 'index',
    components: {
      Hello
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
