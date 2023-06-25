<template>
  <div>
    <div class="w-full min-h-screen flex flex-row px-28">
      <div class="w-1/2 min-h-screen flex flex-col justify-center">
        <div>
          <button
            class="shadow-xl rounded-full flex flex-row justify-center border-2 border-pink"
          >
            <span class="p-3 text-pink"> Explore the world! </span>
            <span class="p-4">
              <img
                src="~/assets/images/portfolio.png"
                alt="Explore the world"
                class="h-5 w-5"
              />
            </span>
          </button>
        </div>

        <div class="">
          <h4 class="text-black font-sans text-8xl leading-tight py-4">
            Travel <span class="text-pink">top destination</span>
            of the world
          </h4>

          <p class="text-xl text-gray-500 opacity-70">
            We always make our customer happy by providing<br />
            as many choices as possible
          </p>
        </div>

        <div class="flex flex-row pt-10">
          <button
            class="bg-purple-800 text-white text-lg px-5 py-3 rounded-full mr-4"
          >
            Get Started
          </button>
          <button
            class="flex flex-row rounded-full border-2 border-gray-200 px-5 py-3"
          >
            <span class="pr-3 flex justify-center"
              ><img
                src="~/assets/images/play-button.png"
                alt="Watch Demo"
                class="h-5 w-5 object-contain object-center" /></span
            ><span>Watch Demo</span>
          </button>
        </div>
      </div>

      <div class="w-1/2 min-h-screen py-20 flex justify-center">
        <div class="flex flex-wrap flex-col justify-center">
          <div class="px-4">
            <img
              src="~/assets/images/heroSection/image-1.jpg"
              alt="Image 1"
              class="shadow rounded-xl max-w-full h-80 align-middle border-none"
            />
          </div>
          <div class="pt-4 px-4">
            <img
              src="~/assets/images/heroSection/image-2.jpg"
              alt="Image 1"
              class="shadow rounded-xl max-w-full h-80 align-middle border-none"
            />
          </div>
        </div>

        <div class="flex flex-wrap justify-center pt-60">
          <div class="px-4">
            <img
              src="~/assets/images/heroSection/image-3.jpg"
              alt="Image 1"
              class="shadow rounded-xl max-w-full h-80 align-middle border-none"
            />
          </div>
        </div>
      </div>
    </div>

    <div class="w-full">
      <div class="flex flex-row justify-evenly justify-items-center">
        <div>
          <img
            src="~/assets/images/section2/image-1.png"
            alt="Trip Advisor"
            class="h-10 w-auto"
          />
        </div>
        <div>
          <img
            src="~/assets/images/section2/image-2.png"
            alt="Trip Advisor"
            class="h-10 w-auto"
          />
        </div>
        <div>
          <img
            src="~/assets/images/section2/image-3.png"
            alt="Trip Advisor"
            class="h-10 w-auto"
          />
        </div>
      </div>
    </div>

    <div class="w-full h-auto flex flex-row justify-center px-28 py-20">
      <div class="w-1/3 flex flex-col justify-center">
        <div>
          <h3 class="text-pink text-2xl tracking-widest font-medium">
            SERVICES
          </h3>
          <p class="text-4xl leading-snug pt-4">
            Our top value <br />
            categories for you
          </p>
        </div>
      </div>
      <div class="w-2/3 flex flex-row justify-center">
        <div
          class="h-80 hover:border-2 hover:border-pink max-w-full px-5 py-5 justify-center shadow-xl rounded-xl mx-4"
        >
          <img
            src="~/assets/images/section3/image-2.png"
            alt="Best Tour Guide"
            class="h-14 w-14 rounded-full object-contain object-center mx-auto"
          />

          <h4 class="text-2xl text-center py-5 font-medium">Best Tour Guide</h4>

          <p class="text-center text-xl pb-4 text-gray-500 opacity-70 font-normal">
            What looked like a small <br />
            patch of purple glass, <br />
            above five feet.
          </p>
        </div>
        <div
          class="h-80 hover:border-2 hover:border-pink max-w-full px-5 py-5 justify-center shadow-xl rounded-xl"
        >
          <img
            src="~/assets/images/section3/image-1.png"
            alt="Best Tour Guide"
            class="h-14 w-14 rounded-full object-contain object-center mx-auto"
          />

          <h4 class="text-2xl text-center py-5 font-medium">Easy Booking</h4>

          <p class="text-center text-xl pb-4 text-gray-500 opacity-70 font-normal">
            Square, was moving <br />
            across the sand in their <br />
            direction.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>