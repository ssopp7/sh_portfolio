<template>
    <div>
        <div id="circle">
            <nav>
                <a href="/#navbar-about" id="toTop">
                    <i class="material-symbols-outlined">expand_less</i>
                </a>
            </nav> 
        </div>
    </div>
</template>

<style>
    body{
        margin: 0;
    }

    a{
        scroll-behavior: smooth;
    }

    #circle {
        background-color: orange;
        border: none;
        border-radius: 50%;
        height: 10px;
        width: 10px;
        padding: 12px 16px;
        cursor: pointer;
        position: fixed;
    }

    #toTop .material-symbols-outlined {
        font-size: 100px;
        color: white;
    }

</style>