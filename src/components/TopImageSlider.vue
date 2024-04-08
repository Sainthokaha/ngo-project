<template>
  <section id="container">
    <div id="slider-wrapper" class="relative mx-auto my-0">
      <div id="slider" class="flex aspect-video overflow-x-hidden snap-x snap-mandatory scroll-smooth">
        <img id="slide-2" class="flex-[1_0_100%] snap-start object-cover" src="../assets/image2.jpg" alt="">
        <img id="slide-1" class="flex-[1_0_100%] snap-start object-cover" src="../assets/image1.jpg" alt="">
      </div>
      <div id="slider-nav" class="flex gap-x-4 absolute bottom-5 left-1/2 -translate-x-[50%] z-10">
        <a class="w-2 h-2 rounded-[50%] bg-[#fff] opacity-75 transition-opacity duration-200 hover:opacity-100" href="#slide-1"></a>
        <a class="w-2 h-2 rounded-[50%] bg-[#fff] opacity-75 transition-opacity duration-200 hover:opacity-100" href="#slide-2"></a>
        
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>

</style>
