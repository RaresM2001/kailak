<template>
  <div id="app">
   <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: "App",
};
</script>

<style lang="css">
/* importing global fonts */
@import url('https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Barlow&family=Great+Vibes&display=swap');

/* some global styles */
* {
   box-sizing: border-box;
   padding: 0;
   margin: 0;
}

.m-btn {
   border: none;
   background-color: black;
   height: 60px;
   width: 200px;
   color: white;
   font-weight: bold;
   font-family: 'Barlow', sans-serif;
   cursor: pointer;
   transition: all .4s;
   margin-left: calc(50% - 100px);
   font-size: 1.1em;
   border: 3px solid black;
}

.m-btn:hover {
   width: 180px;
   margin-left: calc(50% - 90px);
}


</style>
