<template>
  <footer class="py-20">
    <div class="w-[90%] max-w-[1260px] mx-auto pb-3 pt-5 px-5">
      <div class="w-full borderbtm">
        <div class="flex flex-col md:flex-row justify-between pb-20">
          <div
            class="w-[30%] max-w-[360px] flex flex-col items-start mb-20 md:mb-0"
          >
            <router-link to="/" class="h-[36px]">
              <img
                class="h-full object-contain"
                src="	https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/632b9c9f2f1daf281360aa54_navbar-logo.svg
"
                alt=""
              />
            </router-link>
          </div>
          <div class="flex-1">
            <div class="w-full flex flex-col md:flex-row gap-4 justify-between">
              <div class="flex flex-col">
                <h4 class="text-[#33333] font-bold text-[18px]">Product</h4>
                <ul
                  class="flex flex-col gap-4 text-[#6c7285] text-[18px] mt-5 font-semibold"
                >
                  <router-link to="/product"
                    >API Monitoring & Observability</router-link
                  >
                  <router-link to="/product"
                    >Auto-generated API Docs</router-link
                  >
                  <router-link to="/product">API Analytics</router-link>
                  <router-link to="/product">Trebble API Score</router-link>
                  <router-link to="/product">Native Trebble Apps</router-link>
                  <router-link to="/product"
                    >API Lifecircle Collaboration
                  </router-link>
                </ul>
              </div>
              <div class="flex flex-col">
                <h4 class="text-[#33333] font-bold text-[18px]">Company</h4>
                <ul
                  class="flex flex-col gap-4 text-[#6c7285] text-[18px] mt-5 font-semibold"
                >
                  <router-link to="/product">About</router-link>
                  <router-link to="/product">Contact</router-link>
                  <router-link to="/product">Privacy Policy</router-link>
                  <router-link to="/product">Trebble API Score</router-link>
                  <router-link to="/product">Terms of Service</router-link>
                </ul>
              </div>
              <div class="flex flex-col">
                <h4 class="text-[#33333] font-bold text-[18px]">Resources</h4>
                <ul
                  class="flex flex-col gap-4 text-[#6c7285] text-[18px] mt-5 font-semibold"
                >
                  <router-link to="/product">Blog</router-link>
                  <router-link to="/product">Ebooks</router-link>
                  <router-link to="/product">Case Studies</router-link>
                  <router-link to="/product">Community</router-link>
                  <router-link to="/product">System Status</router-link>
                  <router-link to="/product">Support</router-link>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="w-full">
        <div
          class="w-full flex flex-col md:flex-row items-center md:justify-between mt-10"
        >
          <div>
            <p class="text-[#6c7285] leading-[150%]">© Treblle</p>
          </div>
          <ul class="flex items-center">
            <a
              href="https://www.linkedin.com/company/treblle/"
              target="_blank"
              class="flex w-[40px] h-[40px] max-w-full mr-[12px] justify-center items-center"
              ><img
                src="https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/63349270469c3d44a88b9873_Vector-4.svg"
                loading="lazy"
                alt=""
                class="max-w-full"
            /></a>
            <a
              href="https://twitter.com/treblleapi"
              target="_blank"
              class="flex w-[40px] h-[40px] max-w-full mr-[12px] justify-center items-center"
              ><img
                src="https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/633492707ab88eef92340476_Vector-2.svg"
                loading="lazy"
                alt=""
                class="max-w-full"
            /></a>
            <a
              href="https://www.youtube.com/@treblle"
              target="_blank"
              class="footer_social-links last w-inline-block"
              ><img
                src="https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/637cb2614547e425cbcf5f23_icons8-youtube%20(1).svg"
                loading="lazy"
                alt=""
                class="max-w-full"
            /></a>
            <a
              href="https://www.facebook.com/treblle"
              target="_blank"
              class="flex w-[40px] h-[40px] max-w-full mr-[12px] justify-center items-center"
              ><img
                src="https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/6334927073b63efb99429813_Vector.svg"
                loading="lazy"
                alt=""
                class="max-w-full"
            /></a>
            <a
              href="https://www.instagram.com/treblleapis/"
              target="_blank"
              class="footer_social-links last w-inline-block"
              ><img
                src="https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/63349270cb90584e2703fa36_Vector-3.svg"
                loading="lazy"
                alt=""
                class="max-w-full"
            /></a>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.borderbtm {
  border-bottom: 1px solid #f0f2f7;
}
</style>
