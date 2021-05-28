<template>
  <article>
    <card></card>
  </article>
</template>

<script>
import Card from "./components/Card";

export default {
  name: "App",
  components: {
    Card,
  },
};
</script>

<style>
body {
  background: #e2e1e0;
  text-align: center;
}
</style>