<template>
  <section class="bg-white dark:bg-gray-900">
    <div class="py-4 lg:py-8 mx-auto max-w-screen-xl px-4">
      <h2
        class="mb-4 lg:mb-8 text-3xl font-semibold tracking-tight leading-tight text-center text-gray-900 dark:text-white md:text-4xl"
      >
        Berbagai Mitra Untuk Mendukung Ekosistem Digital SISTEM
      </h2>
      <Vue3Marquee
        class="grid grid-cols-2 gap-4 text-gray-500 sm:gap-8 md:grid-cols-3 lg:grid-cols-6 dark:text-gray-400"
      >
        <img height="200" :src="mitra1" />
        <img height="200" :src="mitra2" />
        <img height="200" :src="mitra3" />
        <img height="200" :src="mitra4" />
        <img height="200" :src="mitra5" />
        <img height="200" :src="mitra6" />
      </Vue3Marquee>
    </div>
  </section>
</template>

<script>
import { Vue3Marquee } from 'vue3-marquee'

export default {
  components: {
    Vue3Marquee
  },
  data() {
    return {
      mitra1: './img/mitra-1.png',
      mitra2: './img/mitra-2.png',
      mitra3: './img/mitra-3.png',
      mitra4: './img/mitra-4.png',
      mitra5: './img/mitra-5.png',
      mitra6: './img/mitra-6.png'
    }
  }
}
</script>
