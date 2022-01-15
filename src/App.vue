<template>
  <div id="app">
    <GPSynth msg="Synth goes here"/>
  </div>
</template>

<script>
import GPSynth from './components/GPSynth.vue'

export default {
  name: 'App',
  components: {
    GPSynth
  }
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
</style>
