<template>
    <div>
         <!--navigation bar-->
         <nav class="navbar" id="navbar-about">
            <NuxtLink to="/">About</NuxtLink>
            <NuxtLink to="/engineering">Engineering</NuxtLink>
            <NuxtLink to="/photography">Photography</NuxtLink>
            <n-link to="/résumé">Résumé</n-link>        
            <NuxtLink to="/contact">Contact</NuxtLink>  
            
         </nav>
  
       <!--dropdowns-->
    </div>
  </template>
  
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Lora&family=Poppins&display=swap');
    

    body{
      /*rgb(162, 183, 246)*/
      background-color: rgb(185, 217, 235);
      margin: 0;
      padding: 0;
    }

    .navbar{
       background-color: rgb(255, 255, 255);
       position: relative;
       max-width: 100%;
       padding: 14px;
       font-family: 'Poppins', sans-serif;
       text-align: center;
    }
  
    a:link, a:visited{
      text-align: center;
      padding: 14px 16px;
      color: rgb(30, 32, 34);
      text-decoration: none;
      font-size: 16px;
    }
    a:hover, a:active{
       font-weight: bold;
    }
  
    .navbar a.nuxt-link-exact-active{
      text-align: center;
      padding: 14px 16px;
      font-size: 16px;
      color: rgb(30, 32, 34);
      font-weight:bold;
    }

</style>

<script>

</script>