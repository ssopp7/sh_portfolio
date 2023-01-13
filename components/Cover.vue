<template>
    <div>
        <div class="hero-image">
            <div class="hero-text">
                <h1 class="text-underline" id="temp" style="font-size: 75px">Hi! I'm Sophia Hann.</h1>
                <h3 class="text-underline" style="font-size: 25px">she/her/hers</h3>
                <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
                <nav>
                    <a href="/#navbar-about" id="btnScrollDown">
                        <i class="material-symbols-outlined">expand_more</i>
                    </a>
                </nav>          
            </div>
        </div>
        <div id="sticky">
            <nav class="navbar" id="navbar-about">
                <NuxtLink to="/">About</NuxtLink>
                <NuxtLink to="/engineering">Engineering</NuxtLink>
                <NuxtLink to="/photography">Photography</NuxtLink>
                <n-link to="/résumé">Résumé</n-link>        
                <NuxtLink to="/contact">Contact</NuxtLink>        
            </nav>
        </div>
    </div>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Lora&family=Poppins&display=swap');
    body{
        margin: 0;
    }

    a{
        scroll-behavior: smooth;
    }

    .navbar{
       background-color: rgb(255, 255, 255);
       max-width: 100%;
       padding: 14px;
       font-family: 'Poppins', sans-serif;
       text-align: center;
       position: fixed;
       top: 100;
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

    .text-underline {
        text-decoration: underline;
        text-decoration-color: rgba(255, 162, 0, 0.9);
    }

    #btnScrollDown {
        background-color: transparent;
        border: none;
        padding: 12px 16px;
        cursor: pointer;
    }

    #btnScrollDown .material-symbols-outlined {
        font-size: 100px;
        color: white;
        transform: translate(0%, 100%)
    }

    .hero-image {
        /*rgba(42, 88, 236, 0.80)*/
        /*rgba(255, 255, 255, 0.50)*/

        background-image: linear-gradient(to top, rgba(0, 0, 0, 0.9), rgba(0, 0, 0, 0.6)), url(../static/linepattern.png);
        background-color: #cccccc;
        height: 100vh;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
        margin: 0;
        padding: 0;
    }
    .hero-text {
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: white;
        font-family: "Poppins", sans-serif;
    }

</style>

<script>
</script>