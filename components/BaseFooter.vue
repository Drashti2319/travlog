<template>
  <footer class="bg-white w-full justify-center mx-auto md:px-20 px-5 pt-5 shadow-inner">
    <div class="w-full flex md:flex-row flex-col justify-evenly">
      <div class="md:w-1/4 w-full">
        <div class="w-full h-full flex flex-col justify-center">
          <div class="">
            <img
              src="~/assets/images/logo.png"
              class="h-10 w-auto object-contain"
            />
          </div>
          <div class="pt-4">
            <p>
              Contrary to popular belief,<br />
              Lorem Ipsum is not simply random text.<br />
              It has roots in a piece of classical<br />
              Latin literature from 45 BC.
            </p>
          </div>
        
        </div>
      </div>

      <div class="md:w-1/4 w-full md:pt-0 pt-5">
        <div class="w-full h-full flex flex-col justify-center">
          <h4 class="text-2xl font-semibold">Company</h4>
          <ul class="md:pt-14 pt-5">
            <li class="hover:underline cursor-pointer">
              <nuxt-link to="#about"> About </nuxt-link>
            </li>
            <li class="hover:underline cursor-pointer py-4">
              <nuxt-link to="#career">Career</nuxt-link>
            </li>
            <li class="hover:underline cursor-pointer">
              <nuxt-link to="#mobile">Mobile</nuxt-link>
            </li>
          </ul>
        </div>
      </div>

     

      <div class="md:w-1/4 w-full md:pt-0 pt-5">
        <div class="w-full h-full flex flex-col justify-center">
          <h4 class="text-2xl font-semibold">Contact</h4>
          <ul class="md:pt-10 pt-5">
            <li class="hover:underline cursor-pointer">
              <nuxt-link to="#whyTravlog"> Why Travlog?</nuxt-link>
            </li>
            <li class="hover:underline cursor-pointer py-4">
              <nuxt-link to="#partnerWithUs">Partner with us</nuxt-link>
            </li>
            <li class="hover:underline cursor-pointer">
              <nuxt-link to="#faqs">FAQ's</nuxt-link>
            </li>
            <li class="hover:underline cursor-pointer pt-4">
              <nuxt-link to="#blog">Blog</nuxt-link>
            </li>
          </ul>
        </div>
      </div>

      <div class="md:w-1/4 w-full md:pt-0 pt-4">
        <div class="w-full h-full flex flex-col justify-center">
          <h4 class="text-2xl font-semibold">Meet Us</h4>
          <ul class="md:pt-10 pt-5">
            <li class="hover:underline cursor-pointer">
              <a href="tel:0092123456789">+00 92 1234 56789</a>
            </li>
            <li class="hover:underline cursor-pointer py-4">
              <a href="mailto:info@travlog.com">info@travlog.com</a>
            </li>
            <li class="hover:underline cursor-pointer">
              <address>
                205. R Street, New York<br />
                BD23200
              </address>
            </li>
            
          </ul>
        </div>
      </div>

     
    </div>
    <div class="w-full">
        <div class="w-full flex flex-row justify-start pt-5">
            <button class="rounded-full bg-purple-800 h-8 w-8 mr-2">
              <img
                src="~/assets/images/socialMediaIcons/facebook.png"
                class="h-5 w-5 mx-auto object-contain object-center"
              />
            </button>

            <button class="rounded-full bg-purple-800 h-8 w-8 mr-2">
              <img
                src="~/assets/images/socialMediaIcons/twitter.png"
                class="h-5 w-5 mx-auto object-contain object-center"
              />
            </button>

            <button class="rounded-full bg-purple-800 h-8 w-8">
              <img
                src="~/assets/images/socialMediaIcons/instagram.png"
                class="h-5 w-5 mx-auto object-contain object-center"
              />
            </button>
          </div>
      </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
</style>