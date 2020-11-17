<template>
  <body>
        <aside>
            <a href="#" class="special">Explore</a>
            <ul>
                <li><a href="#" class="snips">Home</a></li>
                <li><a href="#" class="snips">Places</a></li>
                <li><a href="#" class="snips">Landmarks</a></li>
                <li><a href="#" class="snips">Locations</a></li>
                <li><a href="#" class="snips">About</a></li>
                <li><a href="#" class="snips">Book</a></li>
                <li><a href="#" class="snips">Photos</a></li>
            </ul>
            <a href="#" class="special">Contact Us</a>
        </aside>
        <main>
            <div class="logo">
                <i class="fas fa-city"></i>
            </div>
            <h1>Visit Lagos</h1>
            <h3>Explore The Legendary Lasgidi</h3>
        </main>
    </body>
</template>


<style>
@import url("https://fonts.googleapis.com/css2?family=Prata&display=swap");

* {
    box-sizing: border-box;
}

.snips:hover{
background-color: white;
color:  rgb(150, 146, 146);
box-shadow: 2x 3px 4px -4px rgba(0,0,0,0.75);
transition: 100ms ease-in;
cursor: pointer;
transform: scale(1.08);
}

body {
    background-image: url(./bg.png);
    background-size: cover;
    background-repeat: no-repeat;
    /* background-position: center center; */
    display: flex;
    font-family: "Prata", sans-serif;
    margin: 0;
    min-height: 100vh;
}

aside {
    background-color: rgb(150, 146, 146);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 2rem;
    width: 300px;
    height: 100vh;
}

aside ul {
    padding: 0;
    list-style-type: none;
}

aside a {
    color: white;
    display: inline-block;
    font-size: 2rem;
    text-decoration: none;
    margin: 0.5rem;
}

.special {
    background-color: #feab51;
    color: black;
    display: block;
    padding: 1rem;
    text-align: center;
}

main {
    color: #fff;
    font-size: 2.5rem;
    padding: 3rem;
}

main h1 {
    margin: 0;
}

main h3 {
    color: #feab51;
    margin: 0;
}

@media screen and (max-width: 768px) {
    body {
        flex-direction: column-reverse;
        justify-content: space-between;
    }

    main {
        min-height: 60vh;
    }

    aside {
        height: auto;
        width: 100%;
    }

    aside ul {
        display: flex;
        flex-wrap: wrap;
    }

    .special {
        display: none;
    }
}

</style>
