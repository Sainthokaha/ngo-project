<template>
  <div id="slider">
    <ImageSlides :image="images[0]"/>
  </div>
</template>

<script>
import ImageSlides from './ImageSlides.vue'

export default {
  components: {
    ImageSlides
  },
  data() {
    return {
      images: [
        {
          id: 0,
          url: "../assets/image2.jpg",
          title: "Lightiing"
        },
        {
          id: 1,
          url: "../assets/image1.jpg",
          title: "Thunder"
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>