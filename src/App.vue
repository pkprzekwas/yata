<template>
  <div id="app">
    <page-layout />
  </div>
</template>

<script>
import PageLayout from "./components/PageLayout.vue";

export default {
  name: "App",
  components: {
    PageLayout,
  },
};
</script>

<style>
*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

#app {
  font-family: Jost, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
