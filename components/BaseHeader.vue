<template>
  <header class="top-0 sticky shadow-lg bg-white h-20">
    <nav class="w-full h-full flex flex-row justify-evenly align-middle pt-5">
    <div class="w-1/3 flex justify-center align-middle">
     <img src="~/assets/images/logo.png" class="h-10 w-auto object-contain object-center" />
    </div>
    <div class="w-1/3">
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
    <div class="w-1/3">
      <div class="flex flex-row justify-center">

        <button class="bg-transparent mx-4">
          Log in
        </button>
  
        <button class="bg-purple-800 rounded-full px-5 py-3 text-white">Sign Up</button>
      </div>
    </div>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
</style>