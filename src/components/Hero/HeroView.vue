<script setup>
import ButtonContact from '../ButtonContact.vue'
</script>

<template>
  <section class="bg-white pt-8 antialiased dark:bg-gray-900 md:pt-16">
    <div
      class="mx-auto max-w-screen-xl px-4 pb-8 md:grid-cols-12 lg:gap-12 lg:pb-16 xl:gap-0 flex flex-col md:flex-row justify-between"
    >
      <!-- Gambar Group 3 untuk mobile -->
      <div class="flex justify-center md:hidden mb-6">
        <img :src="group3" alt="shopping illustration" />
      </div>

      <div class="content-center justify-self-start md:col-span-7 md:text-start">
        <p
          class="mb-4 max-w-2xl font-semibold text-[#faca15] dark:text-gray-400 md:mb-12 md:text-lg lg:mb-5 lg:text-xl"
        >
          CAREER ACELERATE
        </p>
        <h1
          class="my-8 text-2xl font-medium leading-none tracking-tight dark:text-white md:max-w-2xl md:text-5xl xl:text-6xl"
        >
          Meningkatkan Karir Anda di SISTEM Bootcamp
        </h1>
        <p
          class="mb-4 max-w-2xl text-gray-500 dark:text-gray-400 md:mb-8 md:text-lg lg:mb-2 lg:text-xl"
        >
          Pelajari dari ahli Teknik Perangkat Lunak yang berpengalaman di SEA dan mempercepat karir
          Anda sebagai Software Engineer.
        </p>

        <div class="py-4 lg:py-8 mx-auto max-w-screen-xl px-4">
          <div
            class="grid grid-cols-2 gap-8 text-gray-900 sm:gap-12 md:grid-cols-3 lg:grid-cols-6 dark:text-gray-700"
          >
            <a href="#" class="flex justify-center items-center">
              <img :src="buildIcon" alt="" />
              <span class="font-bold ms-2 tracking-wide">Build Community</span>
            </a>
            <a href="#" class="flex justify-center items-center">
              <img :src="ShareIcon" alt="" />
              <span class="font-bold ms-2 tracking-wide">Share Events</span>
            </a>
            <a href="#" class="flex justify-center items-center">
              <img :src="GetIcon" alt="" />
              <span class="font-bold ms-2 tracking-wide">Get Information</span>
            </a>
          </div>
        </div>

        <ButtonContact />
      </div>

      <!-- Gambar Group 3 untuk desktop -->
      <div class="hidden md:col-span-5 md:mt-0 md:flex">
        <img :src="group3" alt="shopping illustration" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      group3: './img/Group 3.svg',
      buildIcon: './img/icon.png',
      ShareIcon: './img/icon-1.png',
      GetIcon: './img/icon-2.png'
    }
  }
}
</script>
