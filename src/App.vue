<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <HelloWorld msg="Welcome to Your Vue.js App" />
  <Swatches />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Swatches from "./components/Swatches/Swatches.vue";

export default {
  name: "App",
  components: {
    //   HelloWorld,
    Swatches
  }
};
</script>

<style>
@import "./index.css";
</style>
