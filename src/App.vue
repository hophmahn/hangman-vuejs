<template>
  <div id="app">
    <HangmanContainer />
  </div>
</template>

<script>
import HangmanContainer from './components/HangmanContainer.vue'

export default {
  name: 'app',
  components: {
    HangmanContainer
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
