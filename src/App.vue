<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="https://media3.giphy.com/media/SWKyABQ08mbXW/200.gif"
    >
    <HelloWorld msg="bajs" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Consolas, ui-monospace;

  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
