<template>
    <main>
        <div class="introduction-container">
            <div class="overlay">
                <div class="logo">
                    <h1>DeinDev</h1>
                    <h3>a freelancing fullstack web developer</h3>
                </div>
                <div class="introduction-text">
                    <h2>Hi, I'm Philip</h2>
                    <h1>Let's make your idea see the light of day!</h1>
                </div>
            </div>

        </div>
    </main>
</template>

<style lang="scss">

    body {
        font-family: Lato;
        color: white;
        margin: 0;
    }

    .introduction-container {
        display: flex;
        background-image: linear-gradient(150deg, rgba(10, 36, 99, 0.65), rgba(57, 100, 201, 0.4) 80%), url(~assets/face.png);
        background-size: cover;
        height: 100vh;
        padding: 0;
    }

    .introduction-text {
        display: flex;
        align-self: center;
        flex-direction: column;

        h1 {
            margin: 5px;
            font-size: 3em;
        }

        h2 {
            margin: 5px;
        }
    }

    .logo {
        margin: 20px;

        h1 {
            margin: 5px;
            font-weight: 300;
        }

        h3 {
            font-weight: 200;
            margin: 5px;
        }
    }

    .overlay {
        display: flex;
        width: 100vw;
        z-index: 2;
    }

</style>