<template>
  <div>
    <carousel :autoplay="true" :loop="true" :paginationEnabled="false">
      <slide>
        <v-img :src="require('@/assets/images/home_1.jpg')" height="500px" aspect-ratio="1"></v-img>
      </slide>
      <slide>
        <v-img :src="require('@/assets/images/home_2.jpg')" height="500px" aspect-ratio="1"></v-img>
      </slide>
      <slide>
        <v-img :src="require('@/assets/images/home_3.jpg')" height="500px" aspect-ratio="1"></v-img>
      </slide>
    </carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel'
export default {
  name: 'Home',
  components: {
    Carousel,
    Slide
  }
}
</script>

<style>
</style>
