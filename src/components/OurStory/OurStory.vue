<script setup>
import { ref } from 'vue'
import StoryCard from '../StoryCard.vue'

const stories = ref([
  {
    name: 'Syihabudin Ahmad',
    image: './img/story-1.png',
    job: 'Project Manager Solutionlabs',
    desc: 'Program Sistem Top Markotop, selama belajar cara penyampaian dan arahan mentor unik selain itu mentor juga siap membantu kami jika ada kesulitan.'
  },
  {
    name: 'Annastasya KW',
    image: './img/story-2.png',
    job: 'Project Manager Solutionlabs',
    desc: 'Dulu sebelum belajar tentang PM di SISTEM sering kesuliatan buat manage project, setelah ikut bootcamp sistem jadi tau gimana biar project itu bisa selesai dan achive'
  },
  {
    name: 'Tasya WA',
    image: './img/story-3.png',
    job: 'Quality Assurance Solutionlabs',
    desc: 'Kemarin waktu belajar coding disini enak banget, kita di kelas bener-bener dibimbing dari nol (0) sama mentor dan pembelajarannya juga gampang di pahami.'
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
        Cerita Sukses Peserta
      </h2>
      <p
        class="mb-4 lg:mb-8 text-sm font-light tracking-tight leading-tight text-center text-gray-900 dark:text-white md:text-lg"
      >
        Cari berbagai macam event teknologi terbaik yang diadakan oleh komunitas dan di dukung oleh
        banyak perusahaan besar lainnya
      </p>
      <div class="mb-4 flex flex-wrap justify-around gap-4">
        <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
          <StoryCard v-for="(story, index) in stories" :key="index" :story="story" />
        </div>
      </div>
    </div>
  </section>
</template>
