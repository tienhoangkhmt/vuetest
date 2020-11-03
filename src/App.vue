<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld/>
    <Menu/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Menu from "@/components/Menu";
export default {
  name: 'App',
  components: {
    HelloWorld,
    Menu
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
