<template>
   <div class="root">
      <navigation></navigation>
      <div id="hero-section"></div>
   </div>
</template>

<script>

import Navigation from '../components/Navigation.vue'

export default {
   components: {
      'navigation': Navigation
   }
};

</script>

<style lang="css" scoped>
   /*******************************
            HERO SECTION
   ******************************/

   #hero-section {
      width: 100%;
      height: 700px;
      background-color: red;
      margin-top: 160px;
      background-image: url('../assets/images/herobg.jpg');
      background-position: top;
   }

</style>
