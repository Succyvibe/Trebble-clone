<template>
  <Navbar />
  <router-view />
</template>

<script>
import Navbar from "../src/components/Navbar.vue";
import HomeView from "../src/views/HomeView.vue";
export default {
  components: {
    Navbar,
    HomeView,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
