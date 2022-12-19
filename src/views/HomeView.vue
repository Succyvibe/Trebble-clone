<template>
  <div>
    <Main />
    <ScrollTablet />
    <ApiRequest />
    <GetStarted />
    <Testimonial />
    <Blog />
    <Enroll />

    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Main from "@/components/Main.vue";

import ScrollTablet from "@/components/ScrollTablet.vue";

import ApiRequest from "@/components/ApiRequest.vue";
import GetStarted from "@/components/GetStarted.vue";
import Testimonial from "@/components/Testimonial.vue";
import Enroll from "@/components/Enroll.vue";
import Blog from "@/components/Blog.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "HomeView",
  components: {
    Main,
    ScrollTablet,

    ApiRequest,
    GetStarted,
    Testimonial,
    Enroll,
    Blog,
    Footer,
  },
};
</script>
