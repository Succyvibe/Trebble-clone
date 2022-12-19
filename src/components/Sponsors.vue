<template>
  <section class="h-[20vh] w-full">
    <div class="">
      <div class="my-4 text-center">
        <h1 class="font-bold mt-20">Sponsors</h1>
      </div>
      <div class="overflow-hidden">
        <div class="grid grid-flow-col items-center">
          <img
            src="../assets/images/slack.png"
            loading="lazy"
            srcset="../assets/images/slack.png"
            sizes="(max-width: 479px) 200px, 210px"
            alt=""
            class="scrolling-logo-image content"
          />

          <img
            src="../assets/images/netflix.png"
            loading="lazy"
            srcset="../assets/images/netflix.png"
            sizes="(max-width: 479px) 200px, 210px"
            alt=""
            class="scrolling-logo-image content"
          />

          <img
            src="../assets/images/fitbit.png"
            loading="lazy"
            id="w-node-d866617d-0d92-dbdf-40ba-1ac031fd1287-fcb6f0b6"
            srcset="../assets/images/fitbit.png"
            sizes="(max-width: 479px) 200px, 210px"
            alt=""
            class="scrolling-logo-image content"
          />

          <img
            src="../assets/images/google.png"
            loading="lazy"
            srcset="../assets/images/google.png"
            sizes="(max-width: 479px) 200px, 210px"
            alt=""
            class="scrolling-logo-image content"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Sponsors",
};
</script>

<style scoped>
.content {
  animation: move 10s linear infinite;
}

@keyframes move {
  0% {
    transform: translateX(0);
  }

  /* 50% {
    transform: translate(120vw);
  } */
  100% {
    transform: translate(100vw);
  }
}
</style>
