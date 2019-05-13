<template>
    <main>
        <div class="introduction-container">
            <div class="introduction-text">
                <h1>DeinDev</h1>
                <h3>Let's make your idea come to life!</h3>
                <br>
                <h2>Hi, I'm Philip Dein</h2>
                <h2>and I'm a freelancing fullstack web developer</h2>
            </div>
            <div class="picture">
                <img src="~/assets/philip.png" alt="picture-of-me">
            </div>
        </div>
    </main>
</template>

<style lang="scss">

    body {
        font-family: Lato;
        background-color: #0A2463;
        color: white;
    }

    h1 {
        margin: 5px;
        font-weight: 300;
    }

    h3 {
        font-weight: 200;
        margin: 5px;
    }

    .introduction-container {
        display: flex;
        flex-direction: row;
    }

    .introduction-text {
        width: 50vw;
        flex-grow: 1;
    }

    .picture {
        max-width: 50vw;
    }

    .picture img {
        max-width: 50vw;
    }
</style>