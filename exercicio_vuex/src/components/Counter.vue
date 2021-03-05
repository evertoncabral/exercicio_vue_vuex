<template>
  <div>
    <h1>Counter: {{ counter }}</h1>
    <button @click="increment">Incrementar</button>
    <button @click="decrement">Decrementar</button>
  </div>
</template>

<script>
import { mapGetters, mapActions } from "vuex";
export default {
  name: "Counter",

  computed: {
    ...mapGetters(["counter"]),
  },

  methods: {
    ...mapActions(["decrement", "increment"]),
  },
};
</script>

<style>
</style>