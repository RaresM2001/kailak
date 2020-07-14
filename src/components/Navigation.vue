<template lang="html">
  <nav>
     <div id="logo-container">
        <h1 id="logo">Kailak</h1>
     </div>
     <ul id="nav-list">
        <li class="nav-li"><a href="#">About</a></li>
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
      background-color: white;
      border-bottom: 1px solid black;
      position: relative;
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

   #logo {
      font-family: 'Great Vibes';
      font-size: 3.5em;
      display: inline-block;
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
     text-transform: uppercase;
     text-decoration: none;
     letter-spacing: 0.15em;
     display: inline-block;
     padding: 15px 20px;
     position: relative;
     color: black;
     margin-top: 100px;
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
