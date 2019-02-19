<template>
  <section>
    <app-header />
    <app-tech />
  </section>
</template>

<script>
import AppHeader from "../components/header";
import AppTech from "../components/tech";

export default {
  components: {
    AppHeader,
    AppTech
  }
};
</script>

<style scoped>
body {
  width: 100vw;
  overflow: hidden;
}

body section {
  width: 100vw;
  overflow: hidden;
}

* {
  margin: 0;
  padding: 0;
  display: block;
}
</style>
