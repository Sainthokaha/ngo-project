<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import TopContact from './components/TopContact.vue'
  import CharityHeader from './components/CharityHeader.vue'
  import NavBar from './components/NavBar.vue'
  import HomeBottom from './components/HomeBottom.vue'
</script>

<template>
  <TopContact />
  <CharityHeader />
  <NavBar />
  <TopImageSlider />
  <HomeBottom />
</template>

<style scoped>
  
</style>
