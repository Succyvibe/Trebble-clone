<template>
  <section>
    <div
      class="md:w-[90%] mx-auto md:pt-[80px] pr-[50px] pl-[50px] max-w-7xl flex flex-col justify-between"
    >
      <div>
        <div class="max-w-full header-wrapper">
          <h2
            class="center-h2-heading text-[36px] md:text-[58px] lg:text-[64px] mb-[40px] text-center"
          >
            All-in-one platform for the entire API lifecycle
          </h2>

          <div class="md:max-w-[560px] md:mx-auto">
            <p class="w-full text-[#6c7285] text-center text-lg font-normal">
              Treblle is a lightweight SDK that helps Engineering and DevOps
              teams build, ship &amp; maintain REST based APIs faster
            </p>
          </div>
          <div
            class="mt-10 flex flex-col items-center justify-center gap-3 md:block"
          >
            <button
              class="bg-blue-800 px-[40px] py-[16px] border-[3px] border-blue-800 text-white text-lg rounded-[3px] cursor-pointer"
            >
              Get Started Now
            </button>
            <button
              class="border-4 border-blue-800 px-[40px] py-[16px] rounded-[3px] cursor-pointer text-lg text-blue-800"
            >
              Book a Demo
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
.header-wrapper {
  animation: slideIn 0.5s ease-out forwards;
  opacity: 0;

  margin-right: auto;
  margin-left: auto;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  flex-direction: column;
  -webkit-box-align: center;
  align-items: center;
  width: 100%;
  display: flex;
}

.center-h2-heading {
  /* font-family: 'SF Pro',sans-serif; */

  line-height: 100%;
  font-weight: 600;
  letter-spacing: -0.32px;

  display: block;

  margin-block-start: 0.83em;
  margin-block-end: 0.83em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}

@keyframes slideIn {
  0% {
    opacity: 0;
    transform: translateY(5rem);
  }
  100% {
    opacity: 1;
    transform: none;
  }
}
</style>
