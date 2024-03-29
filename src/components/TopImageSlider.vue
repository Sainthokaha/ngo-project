<template>
  <!-- <section id="container">
    <div id="slider-wrapper" class="relative mx-auto my-0">
      <div id="slider" class="flex aspect-video overflow-x-hidden snap-x snap-mandatory scroll-smooth">
        <img id="slide-1" class="flex-[1_0_100%] snap-start object-cover" src="../assets/image1.jpg" alt="">
        <img id="slide-2" class="flex-[1_0_100%] snap-start object-cover" src="../assets/image2.jpg" alt="">
      </div>
      <div id="slider-nav" class="flex gap-x-4 absolute bottom-5 left-1/2 -translate-x-[50%] z-10">
        <a class="w-2 h-2 rounded-[50%] bg-[#fff] opacity-75 transition-opacity duration-200 hover:opacity-100" href="#slide-1"></a>
        <a class="w-2 h-2 rounded-[50%] bg-[#fff] opacity-75 transition-opacity duration-200 hover:opacity-100" href="#slide-2"></a>
        
      </div>
    </div>
  </section> -->
  <div class="slider block w-full h-full bg-[#1f1f1f] overflow-hidden absolute">
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.slide {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  background: #1f1f1f;
  animation: slide 12s infinite;
  overflow: hidden;
}

.slide:nth-child(1) {
  left: 0%;
  animation-delay: -1s;
  background-image: url(../assets/image1.jpg);
  background-size: cover;
  background-position: center;
}

.slide:nth-child(2) {
  animation-delay: 2s;
  background-image: url(../assets/image2.jpg);
  background-size: cover;
  background-position: center;
}

.slide:nth-child(3) {
  animation-delay: 5s;
  background-image: url(../assets/image1.jpg);
  background-size: cover;
  background-position: center;
}
.slide:nth-child(4) {
  animation-delay: 8s;
  background-image: url(../assets/image2.jpg);
  background-size: cover;
  background-position: center;
}

@keyframes slide {
  0% {
    left: 100%;
    width: 100%;
  }
  5% {
    left: 0%;
  }
  25% {
    left: 0%;
  }
  30% {
    left: -100%;
    width: 100%;
  }
  30.0001% {
    left: -100%;
    width: 0%;
  }
  100% {
    left: 100%;
    width: 0%;
  }
}
</style>
