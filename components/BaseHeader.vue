<template>
  <header class="top-0 sticky shadow-lg bg-white h-20 z-10">
    <nav class="w-full h-full flex flex-row justify-evenly align-middle pt-5">
      <div class="md:w-1/3 w-full flex justify-center align-middle">
        <img
          src="~/assets/images/logo.png"
          class="h-10 w-auto object-contain object-center"
        />
      </div>
      <div class="md:w-1/3 w-full md:block hidden">
        <ul class="flex flex-row justify-evenly align-middle pt-3">
          <li>
            <nuxt-link href="#home">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link href="#discover">Discover</nuxt-link>
          </li>
          <li>
            <nuxt-link href="#specialDeals">Special Deals</nuxt-link>
          </li>
          <li>
            <nuxt-link href="#contact">Contact</nuxt-link>
          </li>
        </ul>
      </div>
      <div class="md:w-1/3 w-full">
        <div class="flex flex-row justify-center">
          <button class="bg-transparent mx-4">Log in</button>

          <button class="bg-purple-800 rounded-full px-5 py-3 text-white">
            Sign Up
          </button>
        </div>
      </div>

      <div class="block md:hidden align-middle">
        <button
          v-if="!viewMenu"
          class="flex justify-center p-3"
          @click.native="viewMenu = true"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M3.75 9h16.5m-16.5 6.75h16.5"
            />
          </svg>
        </button>

        <button v-if="viewMenu" @click.native="viewMenu = false" class="flex justify-center p-3">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M6 18L18 6M6 6l12 12"
            />
          </svg>
        </button>
      </div>
    </nav>
    <div v-if="viewMenu" class="bg-white md:hidden block h-auto w-full">
      <transition name="fade-transition">
        <div class="text-lg px-5">
          <ul class="flex flex-col justify-evenly space-y-5 align-middle">
            <li>
              <nuxt-link href="#home">Home</nuxt-link>
            </li>
            <li>
              <nuxt-link href="#discover">Discover</nuxt-link>
            </li>
            <li>
              <nuxt-link href="#specialDeals">Special Deals</nuxt-link>
            </li>
            <li>
              <nuxt-link href="#contact">Contact</nuxt-link>
            </li>
          </ul>
        </div>
      </transition>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      viewMenu: false,
    };
  },
  watch: {
    viewMenu(val) {
      console.log(val);
    },
  },
};
</script>

<style>
</style>