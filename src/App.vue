<template>
  <div id="app">
    <h3>JsPlumb + D3js实现自定义节点，自动树状布局</h3>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
html, body {
  height: 100%;
  padding: 0;
  margin: 0;
}

#app {
  height: 100%;
}

h3 {
  text-align: center;
}
</style>
