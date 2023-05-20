<template>
  <h2>Hello Vue</h2>
  <TestComponent />
</template>

<script>
import TestComponent from "./components/composition/TestComponent.vue";
export default {
  name: "App",
  components: {
    TestComponent,
  },
};
</script>

<style></style>
