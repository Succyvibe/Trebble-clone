<template>
  <main class="h-[100vh]">
    <HeroSection />
    <sponsors />
  </main>
</template>

<script>
import HeroSection from "./HeroSection.vue";
import Sponsors from "./Sponsors.vue";
export default {
  name: "Main",
  components: {
    HeroSection,
    Sponsors,
  },
};
</script>

<style></style>
