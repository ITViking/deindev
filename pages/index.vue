<template>
    <main>
        <div class="introduction-container">
            <navigation></navigation>
            <div class="introduction-text">
                <h2>Hi, I'm Philip</h2>
                <h1>Let's make your idea see the light of day!</h1>
            </div>
        </div>
    </main>
</template>

<script>
import Navigation from '~/components/navigation';

export default {
    components: { Navigation }
}
</script>

<style lang="scss">

    body {
        font-family: Lato;
        color: white;
        margin: 0;
    }

    .introduction-container {
        display: flex;
        background-image: linear-gradient(120deg, rgba(10, 36, 99, 0.5), rgba(57, 100, 201, 0.5) 50%), url(~assets/gimpFace.jpg);
        background-size: cover;
        height: 100vh;
        padding: 0;
    }

    .introduction-text {
        display: flex;
        align-self: center;
        flex-direction: column;
        width: 100vw;

        h1 {
            margin: 5px;
            font-size: 3em;
        }

        h2 {
            margin: 5px;
        }
    }
</style>