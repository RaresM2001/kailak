<template lang="html">
   <div id="carousel">
      <div id="inner">
         <div class="card">
            <img src="../assets/images/aladin-hookah-red.jpg" alt="Image not found">
            <p class="hookah-title">ALADIN ROCK RED</p>
         </div>
         <div class="card">
            <img src="../assets/images/aladin-hookah-red.jpg" alt="Image not found">
            <p class="hookah-title">ALADIN ROCK RED</p>
         </div>
         <div class="card">
            <img src="../assets/images/aladin-hookah-red.jpg" alt="Image not found">
            <p class="hookah-title">ALADIN ROCK RED</p>
         </div>
         <div class="card">
            <img src="../assets/images/aladin-hookah-red.jpg" alt="Image not found">
            <p class="hookah-title">ALADIN ROCK RED</p>
         </div>
         <div class="clearfix"></div>
         <button class="m-btn" style="margin-top: 50px;">
         COMANDA ACUM
         </button>

      </div>
   </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

@keyframes fadein {
      from {opacity: 0.0}
      to {opacity: 1.0}
}

#carousel {
   animation-name: fadein;
   animation-duration: 4s;
   /* animation-delay: 2s; */
   margin-top: 25px;
   margin-bottom: 100px;
   /* overflow: hidden; */
}

#inner {
   width: 1360px;
   padding: 10px 0 10px 0;
   height: 450px;
   margin-left: calc(50% - 680px);
}

.card {
   width: 300px;
   height: 400px;
   border-radius: 8px;
   transition: all .4s;
   cursor: pointer;
   float: left;
   margin: 0 20px 0 20px;
   /* position: relative; */
}

.card:hover {
   box-shadow: 0px 3px 15px rgba(0,0,0,0.2);
   transform: scale(1.02);
}

.card img {
   width: 100%;
   height: auto;
   margin-top: 15px;
}

.hookah-title {
   font-family: 'Barlow', sans-serif;
   font-weight: bold;
   text-align: center;
   margin-top: 20px;

}

.clearfix {
   clear: both;
   content: "";
}
</style>
