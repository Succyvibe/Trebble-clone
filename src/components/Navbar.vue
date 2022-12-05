<template>
  <div>
    <div class="bg-white shadow-md">
      <nav
        class="container px-6 py-8 mx-auto md:flex md:justify-between md:items-center"
      >
        <div class="flex items-center justify-between">
          <router-link to="/">
            <img
              class=""
              src="	https://uploads-ssl.webflow.com/632b4064ad80128baa5e2d27/632b9c9f2f1daf281360aa54_navbar-logo.svg
"
              alt=""
            />
          </router-link>
          <!-- Mobile menu button -->
          <div @click="showMenu = !showMenu" class="flex md:hidden">
            <button
              type="button"
              class="text-gray-800 hover:text-gray-400 focus:outline-none focus:text-gray-400"
            >
              <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                <path
                  fill-rule="evenodd"
                  d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                ></path>
              </svg>
            </button>
          </div>
        </div>

        <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
        <ul
          :class="showMenu ? 'flex' : 'hidden'"
          class="flex-col mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0 text-lg font-bold text-[#1b1b25] navbar-menu-wrapper"
        >
          <router-link to="/product">Product</router-link>
          <router-link to="/developers">Developers</router-link>
          <router-link to="/pricing">Pricing</router-link>
          <router-link to="/resources">Resources</router-link>
        </ul>

        <div class="hidden md:flex">
          <button class="text-[#1b1b25] text-lg font-bold">Log In</button>
          <button
            class="border-[3px] border-blue-800 py-3 px-6 rounded-md text-blue-800 ml-4 text-lg font-bold"
          >
            Sign Up
          </button>
        </div>
      </nav>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      showMenu: false,
    };
  },
};
</script>

<style scoped>
.navbar-menu-wrapper {
  transform: translateY(0px) translateX(0px);
  transition: transform 400ms ease 0s;

  /* box-shadow: 0 100px 100px 0 rgb(11 11 11 / 40%); */
}
</style>
