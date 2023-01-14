<template>
    <div>
        <iframe id="base-map" src="https://www.google.com/maps/d/embed?mid=1niZsQNF8dmvC_7r6ai4cDFe3529UclU&ehbc=2E312F"></iframe>
        <div id="btn-scroll-up">
            <nav>
                <a href="/#navbar-about" id="scroll-up">
                    <i class="material-symbols-outlined">expand_less</i>
                </a>
            </nav> 
        </div>
        <div id="map-rect">
            <h1 id="location">Locations</h1>
            <h2 id="loc-descrip">September-May: Columbia University, NY <br>Remaining: Boston, MA (primary) | Toronto, Canada (secondary)</h2>
        </div>

    </div>
</template>

<style>

    body {
        margin: 0;
        padding: 0;
    }

    html {
        scroll-behavior: smooth;
    }


    #scroll-up .material-symbols-outlined {
        background-color: rgb(245, 124, 0);
        border-radius: 50%;
        font-size: 100px;
        color: white;
        transform: translate(160vh, -15vh);
        cursor: pointer;
        position: relative;
    }

    #base-map {
        height: 100vh;
        width: 99.7%;
        position: relative;
        align-self: center;
    }

    #map-rect {
        height: 75%;
        width: 50%;
        position: relative;
        transform: translate(5%, -175%);
        background-color: rgba(255, 255, 255, 0.75);
        border: 3px solid white;
        font-family: "Poppins", sans-serif;
        color: rgb(40, 40, 40);
        padding-left: 2vh;
        padding-right: 2vh;
        padding-bottom: 2vh;
    }
    
    #location {
        font-size: 3vw;
        text-align: center;
        text-decoration: underline;
        text-decoration-color: orange;
        text-decoration-thickness: 0.5vw;
    }

    #loc-descrip {
        text-align: justify;
    }

    
</style>