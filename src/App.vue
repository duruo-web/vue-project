<template>
  <div id="app">
    <img src="./assets/logo.png">
    重新开始
    想把master分支的commit合并到另一个分支
    这是在hebing里提交的分支
    这是新的master
    <HelloWorld/>

    我想合并两个分支
    这是新的master
    <HelloWorld/>
    我想成功合并，祝福我吧
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
