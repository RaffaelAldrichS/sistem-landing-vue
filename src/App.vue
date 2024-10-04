<script setup>
import { RouterView } from 'vue-router'
import NavigationBar from './components/Navbar.vue'
import FooterMenu from './components/Footer.vue'
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
  initFlowbite()
})
</script>

<template>
  <header>
    <NavigationBar />
  </header>

  <RouterView />
  <FooterMenu />
</template>
