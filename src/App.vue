<template>
  <div id="app">
    <background-audio></background-audio>
  </div>
</template>

<script>

import BackgroundAudio from '@/components/BackgroundAudio'

export default {
  name: 'app',
  components: {
    BackgroundAudio
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
