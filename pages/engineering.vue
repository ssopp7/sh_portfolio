<template>
    <div>
        <NavBar/>
        <div class="making-text">
            <h1 id="aoe-heading">The Art of Engineering</h1>
            <h2 id="aoe-course">ENGI 1102</h2>
            <video id="aoe-video" controls>
                <source src="../static/battleship.mp4" type="video/mp4">
                <source src="../static/battleship.ogv" type="video/ogg">
            </video>
        </div>

        <div class="making-text">
            <h1 id="FTC-heading">FIRST Tech Challenge</h1>
            <h2 id="FTC-team">Team #14079 Attic Fanatics</h2>
            <video id="ftc-video" controls>
                <source src="../static/ftc.mp4" type="video/mp4">
                <source src="../static/ftc.ogv" type="video/ogg">
            </video>
        </div>
    </div>
</template>

<style>
    #aoe-video {
        height: 60vh;
        width: auto;
    }

    .making-text {
        font-family: "Poppins", sans-serif;
        position: relative;
        margin: 5%;
    }
    #ftc-video {
        height: 60vh;
        width: auto;
        position: relative;
        transform: translate(55vh, -84vh)
    }
    #FTC-heading, #FTC-team {
        position: relative;
        transform: translate(55vh, -84vh)
    }

</style>