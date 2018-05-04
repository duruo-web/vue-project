<template>
  <div id="app">
    <img src="./assets/logo.png">
    this is testes
    nihao ,zheshi master分支
    你好，这是试验，嘿嘿，如果成功的话太开心了
    希望这次成功
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
  $background: #cccccc;
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background: $background;
}
</style>
