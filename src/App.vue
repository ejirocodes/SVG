<template>
  <div id="app">
    <SvgComponent />
  </div>
</template>

<script>
import SvgComponent from "./components/svg.vue";

export default {
  name: "App",
  components: {
    SvgComponent,
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
