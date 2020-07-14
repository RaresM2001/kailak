<template lang="html">
  <nav>
     <!-- <img id="left-corner" src="../assets/images/corner.jpg" alt="Image not found">
     <img id="right-corner" src="../assets/images/corner.jpg" alt="Image not found"> -->
     <div id="logo-container">
        <h1 id="logo">Kaliak</h1>
        <img id="separator" src="../assets/images/decorative-separator.png" alt="image not found">
     </div>
     <ul id="nav-list">
        <li class="nav-li"><a href="#">Home</a></li>
        <li class="nav-li"><a href="#">Shop</a></li>
        <li class="nav-li"><a href="#">Contact</a></li>
     </ul>
  </nav>
</template>

<script>
export default {}
</script>

<style lang="css" scoped>
   nav {
      width: 100%;
      height: auto;
      padding-bottom: 10px;
      background-color: white;
      /* border-bottom: 1px solid black; */
      position: relative;
   }

   #left-corner {
      position: absolute;
      top: 10px;
      left: 10px;;
      height: 130px;
   }

   #right-corner {
      position: absolute;
      right: 10px;
      top: 10px;
      height: 130px;
      transform: rotate(90deg);
   }

   /*******************************
      LOGO & LOGO CONTAINER
   ******************************/

   #logo-container {
      height: 120px;
      width: auto;
      line-height: 120px;
      vertical-align: center;
      display: inline-block;
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      text-align: center;
   }

   #separator {
      width: 250px;
      height: auto;
      margin-top: 40px;
   }

   #logo {
      font-family: 'Great Vibes';
      font-size: 3em;
      display: inline-block;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translateX(-50%) translateY(-50%);
   }

   /*******************************
      NAVIGATION LIST
   ******************************/

   #nav-list {
      float: right;
      width: 450px;
      height: 100%;
      display: inline-block;
      list-style-type: none;
      margin-right: 50px;
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
   }

   .nav-li {
      width: 33.33%;
      float: left;
      text-align: center;
      font-family: 'Barlow', sans-serif;
      font-size: 1em;
   }

   a {
      transition: all .4s;
     text-transform: uppercase;
     text-decoration: none;
     letter-spacing: 0.15em;
     display: inline-block;
     padding: 15px 20px;
     padding-bottom: 5px;
     position: relative;
     color: black;
     margin-top: 110px;
   }

   a:hover {
      color: #b30000;
   }

   a:after {
     background: none repeat scroll 0 0 transparent;
     bottom: 0;
     content: "";
     display: block;
     height: 2px;
     left: 50%;
     position: absolute;
     background: black;
     transition: width 0.3s ease 0s, left 0.3s ease 0s;
     width: 0;
   }

   a:hover:after {
     width: 100%;
     left: 0;
   }

</style>
