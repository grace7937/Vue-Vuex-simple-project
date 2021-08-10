<template>
  <button>plus</button>
  <button>minus</button>
</template>

<script>
export default {
  name: "Button",
  data() {
    return {
      counter: 0,
    };
  },
  methods: {
    plusNum() {
      this.counter + 1;
    },
    minusNum() {
      this.counter - 1;
    },
  },
};
</script>

<style>
</style>