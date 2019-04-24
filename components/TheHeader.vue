<template>
    <header class="header-container d-flex  align-items-center justify-content-between px-5"> 
        <!--links container-->
        <ul class="links-container d-flex align-items-center mb-0 pl-0">
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Review</a></li>
            <li><a href="">Gallery</a></li>
            <li><a href="">Make Payment </a></li>
        </ul>
        <!--Make a Book-->
        <a href="" class="make-a-book hotdog ff-oswald">Make a Booking</a>
    </header>
    
</template>



<style lang="scss" scoped>
    header.header-container{
        height:80px;
        background:#4f5051;
        border-bottom: 1px solid darkgray;
    }

    ul.links-container{
        list-style: none;

        li{
            display: inline-block;
            margin: 0 1rem;

            a{
                transition: all 0.15s ease-in-out;
                font-family: 'Oswald', 'Arial', sans-serif;
                text-transform: uppercase;
                letter-spacing: 0.45px;
                color: white;
            }
        }
    }

    .make-a-book{
        letter-spacing: 0.45px;
        transition: all 0.15s ease-in-out;
    }
</style>
