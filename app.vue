<template>
  <div>
    <h1>App</h1>
    <Comp></Comp>
  </div>
</template>

<script>
import Comp from "./src/Comp.vue";
import FromGroup from 'y'

export default {
  name: "App",
  components: {
    // Comp
    Comp: Comp
  },
  data() {
    return {};
  },
  methods: {},
  computed: {},
  watch: {},
  mounted() {},
  created() {},
  destroyed() {},
  updated() {},
  beforeDestroy() {},
};
</script>

<style>
</style>