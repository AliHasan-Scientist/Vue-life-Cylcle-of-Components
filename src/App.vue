<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <hook />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import hook from "./components/hook.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    hook,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
} 
</style>
