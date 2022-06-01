<template>
  <div id="app">

    <HelloWorld msg="Ellefanter?" />
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
