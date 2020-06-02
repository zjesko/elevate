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
    <div id="banner" class="tile is-ancestor">
      <div class="tile is-12">
        <article class="tile is-child notification is-primary is-family-secondary">
      <div class="content">
        <p class="title is-1">Welcome to Elevate Wealth Creation</p>
        <p class="subtitle">A reputed name for comprehensive financial advisory and product distribution services</p>
        <div class="content">
        </div>
      </div>
    </article>
      </div>
      </div>
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
#banner {
  padding-top: 24px;
  padding-bottom: 10px;
  margin-left: 12px;
  margin-right: 12px;
}
</style>
