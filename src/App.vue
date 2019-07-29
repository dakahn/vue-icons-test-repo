<template>
  <div id="app">
    <Bee32 />
  </div>
</template>

<script>
import Bee32 from "@carbon/icons-vue/es/bee/32";

export default {
  name: "app",
  components: {
    Bee32
  }
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