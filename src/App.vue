<template>
  <div id="app">
    <app-bar></app-bar>
    <main-content></main-content>
  </div>
</template>

<script>
  import AppBar from './components/AppBar'
  import MainContent from './components/MainContent'
  export default {
    name: 'app',
    components: {
      AppBar,
      MainContent
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
