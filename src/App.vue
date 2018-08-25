<template>
  <div id="app">
    <game-output></game-output>
    <user-input></user-input>
  </div>
</template>

<script>
import GameOutput from '@/components/GameOutput'
import UserInput from '@/components/UserInput'

export default {
  name: 'app',
  components: {
    GameOutput,
    UserInput
  }
}
</script>

<style>
body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  background: black;
  color: white;
  padding: 0;
  margin: 0;
}
</style>
