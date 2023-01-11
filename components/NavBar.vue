<template>
    <div>
       <!--navigation bar-->
       <nav class="navbar">
          <span id = "test">
             <NuxtLink to="/">About</NuxtLink>
          </span>
          <NuxtLink to="/engineering">Engineering</NuxtLink>
          <NuxtLink to="/photography">Photography</NuxtLink>
          <NuxtLink to="/contact">Contact</NuxtLink>
          <n-link to="/résumé">Résumé</n-link>
       </nav>
  
       <!--dropdowns-->
    </div>
  </template>
  
  <style>
    .material-symbols-outlined {
    font-variation-settings:
    'FILL' 0,
    'wght' 400,
    'GRAD' 0,
    'opsz' 48
    }
  
    .navbar{
       background-color: rgb(201, 214, 223);
       position: fixed;
       top: 0;
       left: -3px;
       width: 100%;
       
    }
  
    a:link, a:visited{
      float: left;
      text-align: center;
      padding: 14px 16px;
      color: rgb(30, 32, 34);
      text-decoration: none;
      font-size: 18px;
    }
    a:hover, a:active{
       background-color: rgb(240, 245, 249);
    }
  
    .navbar a.nuxt-link-exact-active{
      float: left;
      text-align: center;
      padding: 14px 16px;
      font-size: 18px;
      color: rgb(30, 32, 34);
      background-color: rgb(240, 245, 249);
    }
  </style>