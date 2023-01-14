<template>
    <div>
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
        <div class="hero-image-2">
            <div class="rect">      
                <h1 id="columbia">I am currently a freshman at Columbia University's School of Engineering and Applied Sciences.
                    <a href="/#passions" id="ScrollDown">
                        <i class="material-symbols-outlined">expand_more</i>
                    </a>
                </h1>
            </div>
        </div>
    </div>
</template>

<style>
    html {
        scroll-behavior: smooth;
    }

    body {
        margin: 0;
        padding: 0;
    }
    .hero-image-2 {
        /*background-color: rgb(185, 217, 235);*/
        background-image: linear-gradient(to top, rgba(108, 172, 228, 0.7), rgba(108, 172, 228, 0.7)), url(../static/lowlib.jpg);
        background-color: #cccccc;
        height: 75vh;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
        margin: 0;
        padding: 0;
    }

    .rect {
        height: 75%;
        width: 90%;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background-color: rgba(0, 51, 160, 0.5);
        border: 3px solid white;
    }

    #columbia {
        font-family: "Poppins", sans-serif;
        font-size: 3vw;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -75%);
        color: white;
    }

    #ScrollDown {
        background-color: transparent;
        border: none;
        padding: 12px 16px;
        cursor: pointer;
        position: absolute;
        transform: translate(50%, 50%);
    }

    #ScrollDown .material-symbols-outlined {
        font-size: 100px;
        color: white;
    }

    .page-enter-active, .page-leave-active {
      transition: all 0.4s;
    }

    .page-enter-from, .page-leave-to {
      opacity: 0;
      filter: blur(1rem);
    }

</style>

<script>
    export default {
        app: {
            pageTransition: {name: "page", mode: "out-in"}
        }
    }
</script>