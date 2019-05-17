<template>
    <div class="navigation">
         <div class="logo">
            <h1>DeinDev</h1>
            <h3>a freelancing fullstack web developer</h3>
        </div>
        <div class="nav-options">
            <button>about me</button>
            <button>skills</button>
        </div>
    </div>
</template>

<style lang="scss">
    .navigation {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        width: 100vw;
        height: 140px;
        flex-grow: 1;
        z-index: 10;
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

    .nav-options {
        display: flex;
        margin-right: 150px;

        button {
            background: none;
            color: inherit;
            border: none;
            padding: 0;
            font-family: inherit;
            border-bottom:1px solid white;
            cursor: pointer;
            margin: 50px 30px;
            font-size: 1.2em;
        }

        button:focus {
            outline: none;
        }
    }
</style>
