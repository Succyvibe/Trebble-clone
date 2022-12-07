<template>
  <div>
    <HeroSection />
    <ScrollTablet />
    <Sponsors />
    <ApiRequest />
    <GetStarted />
    <Testimonial />
    <Enroll />
  </div>
</template>

<script>
// @ is an alias to /src
import HeroSection from "@/components/HeroSection.vue";
import ScrollTablet from "@/components/ScrollTablet.vue";
import Sponsors from "@/components/Sponsors.vue";
import ApiRequest from "@/components/ApiRequest.vue";
import GetStarted from "@/components/GetStarted.vue";
import Testimonial from "@/components/Testimonial.vue";
import Enroll from "@/components/Enroll.vue";

export default {
  name: "HomeView",
  components: {
    HeroSection,
    ScrollTablet,
    Sponsors,
    ApiRequest,
    GetStarted,
    Testimonial,
    Enroll,
  },
};
</script>
