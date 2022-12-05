<template>
  <div>
    <HeroSection />
    <ScrollTablet />
    <Sponsors />
    <ApiRequest />
  </div>
</template>

<script>
// @ is an alias to /src
import HeroSection from "@/components/HeroSection.vue";
import ScrollTablet from "@/components/ScrollTablet.vue";
import Sponsors from "@/components/Sponsors.vue";
import ApiRequest from "@/components/ApiRequest.vue";

export default {
  name: "HomeView",
  components: {
    HeroSection,
    ScrollTablet,
    Sponsors,
    ApiRequest,
  },
};
</script>
