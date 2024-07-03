<script setup>
import Footer from "./components/Footer.vue";
</script>

<template>
  <main>
    <div
      class="grid grid-rows-3 my-[88px] mx-auto w-[87%] rounded-[6px] overflow-hidden sm:my-[171px] max-w-[919px] sm:grid-cols-2 sm:grid-rows-2 lg:grid-cols-3 lg:grid-rows-1"
    >
      <div class="bg-brightOrange p-[48px_50px] sm:p-[48px_49px]">
        <img
          src="/images/icon-sedans.svg"
          alt="sedans"
          class="w-[64px] h-[40px]"
        />
        <div
          class="text-veryLightGray font-bigShoulders mt-[26px] text-[41px] uppercase tracking-[0.9px] font-semibold"
        >
          Sedans
        </div>
        <p
          class="text-transparentWhite text-[15px] leading-[25px] mt-[19px] sm:mt-[17px]"
        >
          Choose a sedan for its affordability and excellent fuel economy. Ideal
          for cruising in the city or on your next road trip.
        </p>
        <button
          class="text-brightOrange bg-white mt-[26px] p-[12px_29px] rounded-[23px] sm:mt-[83px] hover:bg-transparent hover:text-veryLightGray hover:outline-2 hover:outline-transparentWhite hover:outline focus:bg-transparent focus:text-veryLightGray focus:outline-2 focus:outline-transparentWhite focus:outline"
        >
          Learn More
        </button>
      </div>
      <div class="bg-darkCyan p-[48px_50px] sm:p-[48px_49px]">
        <img src="/images/icon-suvs.svg" alt="suvs" class="w-[64px] h-[40px]" />
        <div
          class="text-veryLightGray font-bigShoulders mt-[26px] text-[41px] uppercase tracking-[0.9px] font-semibold"
        >
          SUVs
        </div>
        <p
          class="text-transparentWhite text-[15px] leading-[25px] mt-[19px] sm:mt-[17px]"
        >
          Take an SUV for its spacious interior, power, and versatility. Perfect
          for your next family vacation and off-road adventures.
        </p>
        <button
          class="text-darkCyan bg-white mt-[26px] p-[12px_29px] rounded-[23px] sm:mt-[83px] hover:bg-transparent hover:text-veryLightGray hover:outline-2 hover:outline-transparentWhite hover:outline focus:bg-transparent focus:text-veryLightGray focus:outline-2 focus:outline-transparentWhite focus:outline"
        >
          Learn More
        </button>
      </div>
      <div class="bg-veryDarkCyan p-[48px_50px] sm:p-[48px_49px]">
        <img
          src="/images/icon-luxury.svg"
          alt="luxury"
          class="w-[64px] h-[40px]"
        />
        <div
          class="text-veryLightGray font-bigShoulders mt-[26px] text-[41px] uppercase tracking-[0.9px] font-semibold"
        >
          Luxury
        </div>
        <p
          class="text-transparentWhite text-[15px] leading-[25px] mt-[19px] sm:mt-[17px]"
        >
          Cruise in the best car brands without the bloated prices. Enjoy the
          enhanced comfort of a luxury rental and arrive in style.
        </p>
        <button
          class="text-veryDarkCyan bg-white mt-[26px] p-[12px_29px] rounded-[23px] sm:mt-[83px] hover:bg-transparent hover:text-veryLightGray hover:outline-2 hover:outline-transparentWhite hover:outline focus:bg-transparent focus:text-veryLightGray focus:outline-2 focus:outline-transparentWhite focus:outline"
        >
          Learn More
        </button>
      </div>
    </div>
  </main>
  <Footer />
</template>
<!-- 
<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style> -->
