<template>
  <div id="app">
    <companymansys />
  </div>
</template>

<script>
import companymansys from "./components/companymansys.vue";
export default {
  name: "App",
  components: {
    companymansys,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
