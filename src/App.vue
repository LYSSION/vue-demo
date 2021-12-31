<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <div>输出：{{info.aaa ?? 'empty'}}</div>
    <!-- <div>输出：{{info.title ?? 'empty'}}</div> -->
    <!-- <div>输出：{{info?.title?.text}}</div> -->
    <!-- <div>输出：{{BigInt(99109910991099109910)}}</div> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  },
  data() {
    return {
      info: {
        title: 'test',
      }
    }
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
