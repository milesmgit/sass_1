<!-- format for creating comments in HTML -->

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <!-- pulling in components and assigning props values -->
  <HelloWorld
    msg="Welcome to Your Vue.js App"
    lesson="Look at me learn this stuff!"
    bool="true"
    value="23"
    ,
  />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
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
