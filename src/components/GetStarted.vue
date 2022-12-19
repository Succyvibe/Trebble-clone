<template>
  <section class="bg-[#f0f2f7]">
    <div class="container mx-auto">
      <div class="w-[85%] max-w-[1120px] mx-auto py-[140px]">
        <h2
          class="text-[36px] md:text-[58px] lg:text-[64px] text-[#1b1b25] font-semibold leading-[50px] mb-10"
        >
          Get started with Treblle
        </h2>
        <div>
          <div
            class="w-full max-w-[720px] mb-[32px] px-[20px] md:px-[40px] py-[18px] flex items-center rounded-[3px] bg-white shadow-[0 10px 60px 0 hsl(0)] space-x-4"
            data-aos="fade-right"
          >
            <div class="w-[30%]">
              <div
                class="bg-blue-800 md:w-[55%] h-[80px] md:h-[100px] poly flex justify-center items-center text-white rounded-xl"
              >
                <h1 class="text-4xl md:text-6xl font-bold">1</h1>
              </div>
            </div>
            <div class="flex-1">
              <div class="flex flex-col gap-2 md:gap-4">
                <h3 class="text-lg md:text-2xl font-bold">Standard One</h3>
                <p class="text-gray-400 font-medium text-sm md:text-[18px]">
                  We support more than 17 different platforms including JS, PHP,
                  Laravel, .NET, Strapi, Cloudflare workers and others
                </p>
              </div>
            </div>
          </div>
          <div
            class="w-full max-w-[720px] xl:ml-[200px] mb-[32px] px-[20px] md:px-[40px] py-[18px] flex items-center rounded-[3px] bg-white shadow-[0 10px 60px 0 hsl(0)] space-x-4"
            data-aos="fade-right"
          >
            <div class="w-[30%]">
              <div
                class="bg-blue-800 md:w-[55%] h-[80px] md:h-[100px] poly flex justify-center items-center text-white rounded-xl"
              >
                <h1 class="text-4xl md:text-6xl font-bold">2</h1>
              </div>
            </div>
            <div class="flex-1">
              <div class="flex flex-col gap-2 md:gap-4">
                <h3 class="text-lg md:text-2xl font-bold">Standard Two</h3>
                <p class="text-gray-400 font-medium text-sm md:text-[18px]">
                  We support more than 17 different platforms including JS, PHP,
                  Laravel, .NET, Strapi, Cloudflare workers and others
                </p>
              </div>
            </div>
          </div>
          <div
            class="w-full max-w-[720px] xl:ml-[400px] mb-[32px] px-[20px] md:px-[40px] py-[18px] flex items-center rounded-[3px] bg-white shadow-[0 10px 60px 0 hsl(0)] space-x-4"
            data-aos="fade-right"
          >
            <div class="w-[30%]">
              <div
                class="bg-blue-800 md:w-[55%] h-[80px] md:h-[100px] poly flex justify-center items-center text-white rounded-xl"
              >
                <h1 class="text-4xl md:text-6xl font-bold">2</h1>
              </div>
            </div>
            <div class="flex-1">
              <div class="flex flex-col gap-2 md:gap-4">
                <h3 class="text-lg md:text-2xl font-bold">Standard Three</h3>
                <p class="text-gray-400 font-medium text-sm md:text-[18px]">
                  We support more than 17 different platforms including JS, PHP,
                  Laravel, .NET, Strapi, Cloudflare workers and others
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import AOS from "aos";
AOS.init({
  offset: 400,
  duration: 800,
});
export default {
  name: "GetStarted",
};
</script>

<style scoped>
.blue-bg {
  margin-bottom: 0;
  padding: 22px 42px 22px 28px;
  background-image: url(https://uploads-ssl.webflow.com/632b4064ad80128baa…3003ec4c97812c6f_How%20It%20Works%20Rectangle.svg);
  background-position: 0 50%;
  background-size: contain;
  background-repeat: no-repeat;
  color: #fff;
}

.poly {
  -webkit-clip-path: polygon(0% 0%, 75% 0%, 100% 50%, 75% 100%, 0% 100%);
  clip-path: polygon(0% 0%, 75% 0%, 100% 50%, 75% 100%, 0% 100%);
  inset: (0% 45% 0% 45% round 10px);
}
</style>
