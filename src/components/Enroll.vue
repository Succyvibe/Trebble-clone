<template>
  <section
    class="bg-[#0047bb] w-full max-w-full xl:h-[650px] mb-20 relative group"
  >
    <div
      className="absolute top-0  -inset-full h-full w-1/2 z-5 block transform -skew-x-12 bg-gradient-to-l from-transparent to-blue-500 opacity-40 group-hover:animate-shine"
    />
    <div class="w-full h-full flex justify-center items-center">
      <div
        class="w-[90%] max-w-[1260px] mx-auto bg-[#f0f2f7] flex flex-col lg:flex-row pb-3 pt-5 px-5 group-hover:shadow-xl transition-shadow duration-300 ease-in-out"
        data-aos="zoom-in"
        data-aos-duration="800"
        data-aos-easing="ease"
      >
        <div class="md:flex-1 md:p-20 lg:p-8">
          <div class="text-center xl:text-start">
            <h1
              class="md:text-[54px] lg:text-[30px] xl:text-[44px] font-semibold text-[#333] mt-5 md:mt-0"
            >
              Don't waste time in roaming around, start learning Backed dev now
            </h1>
            <div
              class="mt-10 mb-10 md:mb-0 flex flex-col items-center justify-center gap-3 md:flex-row space-x-2"
            >
              <button
                class="bg-blue-800 px-[40px] py-[16px] border-[3px] border-blue-800 text-white text-lg lg:text-sm xl:text-lg rounded-[3px] cursor-pointer hover:bg-white hover:text-blue-800"
              >
                Get Started Now
              </button>
              <button
                class="border-4 border-blue-800 px-[40px] py-[16px] rounded-[3px] cursor-pointer text-lg lg:text-sm xl:text-lg text-blue-800 hover:bg-blue-800 hover:text-white"
              >
                Book a Demo
              </button>
            </div>
          </div>
        </div>
        <div class="mx-auto lg:mx-0">
          <div class="inline-block">
            <div
              class="md:w-[480px] lg:w-[440px] p-[32px] h-[550px] overflow-hidden rounded-lg shadow-md bg-white hover:shadow-xl transition-shadow duration-300 ease-in-out"
            >
              <div class="">
                <div class="flex">
                  <img
                    src="https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/632b4065ad8012bb685e2dac_Group%20158.svg"
                    loading="lazy"
                    alt=""
                    class="review-stars"
                  />
                </div>
                <div class="mt-10">
                  <p class="font-semibold text-lg md:text-[20px]">
                    “...out of all the people, out of all the devs, I find
                    Treblle the most useful. Because I am not technical. Just
                    when you get to see what APIs are being called and when, and
                    what the responses are, the fact that you get to see this
                    live is quite interesting.”
                  </p>
                </div>

                <div class="flex space-x-3 mt-20">
                  <div class="w-[64px] h-[64px] rounded-full">
                    <img
                      src="https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/634a33cf37a6534aba7953e8_annarrah.jpeg"
                      loading="lazy"
                      alt=""
                      class="w-full h-full rounded-full object-cover"
                    />
                  </div>
                  <div class="flex flex-col space-y-3">
                    <div class="text-[18px] text-[#333]">Odumeje Paffey</div>
                    <div class="text-[18px] text-[#333] font-bold">
                      Animation warlord
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style></style>
