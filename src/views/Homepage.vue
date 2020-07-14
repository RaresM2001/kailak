<template>
   <div class="root">
      <navigation></navigation>
      <div id="hero-section"></div>
      <div id="hookah-list-wrapper">
      <carousel></carousel>
      </div>
   </div>
</template>

<script>

import Navigation from '../components/Navigation.vue'
import Carousel from '../components/Carousel.vue';

export default {
   components: {
      'navigation': Navigation,
      'carousel': Carousel
   }
};

</script>

<style lang="css" scoped>

   /*******************************
            HERO SECTION
   ******************************/

   @keyframes example {
     from {height: 0}
     to {height: 650px}
   }

   @keyframes fadein {
      from {opacity: 0.0}
      to: {opacity: 1.0}
   }

   #hero-section {
      width: 100%;
      height: 650px;
      animation-name: example;
      animation-duration: 1s;
      background-color: red;
      margin-top: 160px;
      background-image: url('../assets/images/herobg.jpg');
      background-position: top;
   }

   /*******************************
            HOOKAH SLIDER
   ******************************/


</style>
