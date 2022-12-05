<template>
  <div>
    <HeroSection />
    <ScrollTablet />
  </div>
</template>

<script>
// @ is an alias to /src
import HeroSection from "@/components/HeroSection.vue";
import ScrollTablet from "@/components/ScrollTablet.vue";

export default {
  name: "HomeView",
  components: {
    HeroSection,
    ScrollTablet,
  },
};
</script>
