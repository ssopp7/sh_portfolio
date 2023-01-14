<template>
    <div id="birds">
        <video id="birds-video" controls>
            <source src="../static/birds.mp4" type="video/mp4">
            <source src="../static/birds.ogv" type="video/ogg">
        </video>
    </div>
</template>

<style>
    #birds {
        background-color: black;
    }
    #birds-video {
        position: relative;
        height: 94vh;
        width: 100%;
    }
</style>