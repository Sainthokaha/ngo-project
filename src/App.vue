<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import TopContact from './components/TopContact.vue'
  import CharityHeader from './components/CharityHeader.vue'
  import NavBar from './components/NavBar.vue'
  import TopImageSlider from './components/TopImageSlider.vue'
  import HomeBottom from './components/HomeBottom.vue'
  import About from './components/About.vue'
  import Causes from './components/Causes.vue'
  // import Volunteer from './components/Volunteer.vue'
  import Gallery from './components/Gallery.vue'
  import GalleryBottom from './components/GalleryBottom.vue'
</script>

<template>
  <TopContact />
  <CharityHeader />
  <NavBar />
  <TopImageSlider />
  <HomeBottom />
  <About />
  <Causes />
  <!-- <Volunteer /> -->
  <Gallery />
  <GalleryBottom />
</template>

<style scoped>
  
</style>
