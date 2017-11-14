<template>
  <div id="app">
    <img src="./assets/Pig-PNG-Pic.png">
    <h2>{{msg}}</h2>
    NEJ
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data() {
      return {
          msg: 'Anders äger!'
      };
  }
}
</script>

<style>
#app {
  font-family: 'Calibri', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
h2 {
    font-weight: 100;
    text-decoration: underline;
}
</style>
