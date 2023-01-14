<template>
    <div>
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
        <div class="hero-image-3">
            <div class="hero-text-3">      
                <h1 id="passions">Passions</h1>
                <h2 id="passions-list">CAD ● Robotics ● Biomimetics ● Birding ● DIY</h2>
                <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
                <nav>
                    <a href="/#base-map" id="btnScrollDown">
                        <i class="material-symbols-outlined" id="orange-arrow">expand_more</i>
                    </a>
                </nav>
            </div>
        </div>
    </div>
</template>

<style>

.hero-text-3 {
        text-align: center;
        position: relative;
        top: 50%;
        left: 50%;
        transform: translate(-50%, 10%);
        color: rgb(40, 40, 40);
        font-family: "Poppins", sans-serif;
    }

    .hero-image-3 {
        background-color: white;
        min-height: 40vh;
        width: 100%;
        position: relative;
        margin: 0;
        padding-top: 10px;
        font-family: "Poppins", sans-serif;
    }

    #passions {
        font-size: 3vw;
        text-decoration: underline;
        text-decoration-color: rgba(255, 162, 0, 0.9);
        text-decoration-thickness: 0.5vw;
        text-align: center;
    }

    #btnScrollDown {
        background-color: transparent;
        border: none;
        padding: 12px 16px;
        cursor: pointer;
    }

    #btnScrollDown .material-symbols-outlined {
        font-size: 100px;
        color: orange;
        transform: translate(0%, 25%)
    }
    
</style>