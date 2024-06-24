<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import TopContact from './components/TopContact.vue'
  import CharityHeader from './components/CharityHeader.vue'
  import NavBar from './components/NavBar.vue'
  import TopImageSlider from './components/TopImageSlider.vue'
  import HomeBottom from './components/HomeBottom.vue'
  import About from './components/About.vue'
  import Causes from './components/Causes.vue'
</script>

<template>
  <TopContact />
  <CharityHeader />
  <NavBar />
  <TopImageSlider />
  <HomeBottom />
  <About />
  <Causes />
</template>

<style scoped>
  
</style>
