<script setup>
import { ref } from 'vue'
import CardEvent from '../CardEvent.vue'

const courses = ref([
  {
    title: 'Quality Assurance',
    image: './img/be-1.png',
    classType: 'Live Class',
    duration: '3 Bulan',
    subs: 3000
  },
  {
    title: 'Project Manager',
    image: './img/be-2.png',
    classType: 'Live Class',
    duration: '3 Bulan',
    subs: 3000
  },
  {
    title: 'Development Operation',
    image: './img/be-3.png',
    classType: 'Live Class',
    duration: '3 Bulan',
    subs: 3000
  },
  {
    title: 'Full Stack Developer',
    image: './img/be-4.png',
    classType: 'Live Class',
    duration: '3 Bulan',
    subs: 3000
  }
])
</script>

<template>
  <section class="bg-white pt-8 antialiased dark:bg-gray-900 md:pt-16">
    <div class="mx-auto max-w-screen-xl px-4 2xl:px-0">
      <!-- Heading & Filters -->
      <h2
        class="mb-2 lg:mb-4 text-3xl font-semibold tracking-tight leading-tight text-center text-gray-900 dark:text-white md:text-4xl"
      >
        Pilih Pengalaman Event Terbaik
      </h2>
      <p
        class="mb-4 lg:mb-8 text-sm font-light tracking-tight leading-tight text-center text-gray-900 dark:text-white md:text-lg"
      >
        Cari berbagai macam event teknologi terbaik yang diadakan oleh komunitas dan di dukung oleh
        banyak perusahaan besar lainnya
      </p>
      <div class="mb-4 flex flex-wrap justify-around gap-4">
        <CardEvent v-for="(course, index) in courses" :key="index" :course="course" />
      </div>
    </div>
  </section>
</template>
