<template>
  <div id="app">
    <Counter />
  </div>
</template>

<script>
import Counter from "./components/Counter";

export default {
  name: "App",
  components: {
    Counter,
  },
};
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
