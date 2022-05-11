<template>
<div id="app" ></div>
<Conversor moeda-a="usd" moeda-b="brl" />
</template>

<script>
import conversor from "./components/Conversor.vue";
import Conversor from "./components/Conversor.vue";
export default {
  name: 'App',
  components: {
    conversor,
    Conversor
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
