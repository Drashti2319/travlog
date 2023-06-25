<template>
  <div>
    <div
      id="home"
      class="w-full md:min-h-screen h-auto flex md:flex-row flex-col md:px-28 px-5"
    >
      <div
        class="md:w-1/2 w-full md:min-h-screen h-auto flex flex-col md:justify-center justify-start md:pt-0 pt-10"
      >
        <div>
          <button
            class="md:shadow-xl shadow-lg rounded-full flex flex-row justify-center md:border-2 border border-pink"
          >
            <span class="md:p-3 p-2 text-pink"> Explore the world! </span>
            <span class="md:p-4 p-2">
              <img
                src="~/assets/images/portfolio.png"
                alt="Explore the world"
                class="h-5 w-5"
              />
            </span>
          </button>
        </div>

        <div>
          <h4
            class="text-black font-sans md:text-8xl text-4xl leading-tight py-4"
          >
            Travel <span class="text-pink">top destination</span>
            of the world
          </h4>

          <p class="md:text-xl text-lg text-gray-500 opacity-70">
            We always make our customer happy by providing<br />
            as many choices as possible
          </p>
        </div>

        <div class="flex flex-row md:pt-10 pt-5">
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

      <div
        class="md:flex hidden md:w-1/2 w-full md:min-h-screen h-auto py-20 justify-center"
      >
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

      <div class="block md:hidden">
        <div class="w-full flex flex-row justify-around space-x-2 space-y-4">
          <div class="pt-4">
            <img
              src="~/assets/images/heroSection/image-1.jpg"
              alt="Image 1"
              class="shadow rounded-xl max-w-full h-40 align-middle border-none"
            />
          </div>
          <div>
            <img
              src="~/assets/images/heroSection/image-2.jpg"
              alt="Image 2"
              class="shadow rounded-xl max-w-full h-40 align-middle border-none"
            />
          </div>
          <div>
            <img
              src="~/assets/images/heroSection/image-3.jpg"
              alt="Image 3"
              class="shadow rounded-xl max-w-full h-40 align-middle border-none"
            />
          </div>
        </div>
      </div>
    </div>

    <div id="#discover" class="w-full md:py-0 py-10">
      <div class="flex flex-row justify-evenly justify-items-center">
        <div>
          <img
            src="~/assets/images/section2/image-1.png"
            alt="Trip Advisor"
            class="md:h-10 h-5 w-auto"
          />
        </div>
        <div>
          <img
            src="~/assets/images/section2/image-2.png"
            alt="Airbnb"
            class="md:h-10 h-5 w-auto"
          />
        </div>
        <div>
          <img
            src="~/assets/images/section2/image-3.png"
            alt="Expedia"
            class="md:h-10 h-5 w-auto"
          />
        </div>
      </div>
    </div>

    <div
      id="specialDeals"
      class="w-full h-auto flex md:flex-row flex-col justify-center md:px-28 px-5 md:py-20 py-10"
    >
      <div class="md:w-1/3 w-full flex flex-col justify-center md:text-start text-center">
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
      <div class="md:w-2/3 w-full flex md:flex-row flex-col justify-center md:space-y-0 space-y-2 md:pt-0 pt-3">
        <div
          class="h-80 hover:border-2 hover:border-pink max-w-full px-5 py-5 justify-center md:shadow-xl shadow-inner rounded-xl md:mx-4 mx-0"
        >
          <img
            src="~/assets/images/section3/image-2.png"
            alt="Best Tour Guide"
            class="h-14 w-14 rounded-full object-contain object-center mx-auto"
          />

          <h4 class="text-2xl text-center py-5 font-medium">Best Tour Guide</h4>

          <p
            class="text-center text-xl pb-4 text-gray-500 opacity-70 font-normal"
          >
            What looked like a small <br />
            patch of purple glass, <br />
            above five feet.
          </p>
        </div>
        <div
          class="h-80 hover:border-2 hover:border-pink max-w-full px-5 py-5 justify-center md:shadow-xl shadow-inner rounded-xl"
        >
          <img
            src="~/assets/images/section3/image-1.png"
            alt="Best Tour Guide"
            class="h-14 w-14 rounded-full object-contain object-center mx-auto"
          />

          <h4 class="text-2xl text-center py-5 font-medium">Easy Booking</h4>

          <p
            class="text-center text-xl pb-4 text-gray-500 opacity-70 font-normal"
          >
            Square, was moving <br />
            across the sand in their <br />
            direction.
          </p>
        </div>
      </div>
    </div>

    <div id="contact" class="w-full md:px-28 px-5 pb-10">
      <div class="w-full h-auto flex flex-col justify-center">
        <h4 class="md:text-2xl text-xl text-pink tracking-widest text-center font-medium">
          SUBSCRIBE TO OUR NEWSLETTER
        </h4>
        <p class="md:text-5xl text-3xl text-center leading-snug py-5 font-bold">
          Prepare yourself & let's explore the<br />
          beauty of the world
        </p>
      </div>
      <div class="w-full flex flex-row justify-center">
        <input
          type="text"
          class="py-2 text-sm h-12 text-black bg-white rounded-md pl-10 focus:outline-none focus:bg-white focus:text-gray-900 border border-gray-300 mr-5"
          placeholder="Your Email"
        />
        <button class="bg-purple-800 px-5 py-3 rounded-xl text-white">
          Subscribe
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>