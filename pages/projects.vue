<template>
    <div>
        <NavBar/>
        <div>
            <h1 id="lhs">Virtual Tour of High School</h1>
            <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
            <iframe id="lhs-tour" src="https://storymaps.arcgis.com/stories/d2529974571f4b1d8e9985dafd29c7ce" width="100%" height="100%" frameborder="0" allowfullscreen allow="geolocation"></iframe>
        </div>
    </div>
</template>

<style>

    a{
        scroll-behavior: smooth;
    }

    #down .material-symbols-outlined{
        font-size: 100px;
        color: rgb(0, 0, 0);
        transform: translate(55vh, -10vh);
        cursor: pointer;
    }

    #lhs {
        font-family: "Poppins", sans-serif;
        position: relative;
        text-align: center;
    }
</style>