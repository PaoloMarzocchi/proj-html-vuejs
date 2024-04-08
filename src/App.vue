<script>
import AppHeader from './components/AppHeader.vue';

export default {
    name: 'App',
    components: {
        AppHeader,
    },
}
</script>

<template>
    <AppHeader></AppHeader>

    <div id="site-main">

        <section class="jumbo">
            <div class="container d-flex">
                <h6>CINEMATO STUDIO</h6>
                <h1>ACTION AND <br> INSPIRE PEOPLE</h1>
                <button>READ MORE</button>
            </div>

        </section>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
        <section></section>

    </div>
    <div id="site-footer">
        <div class="top">
            <ul>
                <li></li>
            </ul>
            <ul>
                <li></li>
            </ul>
            <ul>
                <li></li>
            </ul>
            <ul>
                <li></li>
            </ul>
        </div>
        <div class="bottom"></div>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Reem+Kufi+Fun:wght@400..700&display=swap');

:root {
    --cine--light: #f2f2f2;
    --cine--lightest: #ffffff;
    --cine--dark: #666666;
    --cine--darkest: #111111;
}

/* #region Common */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: "Reem Kufi Fun", sans-serif;
}

img {
    max-width: 100%;
}

ul {
    list-style: none;
}

a {
    text-decoration: none;
    color: inherit;
}

/* #endregion Common */

/* #region Utilities */
.d-flex {
    display: flex;
}

.container {
    width: 80%;
    margin: 0 auto;
}

/* #endregion Utilities */

.jumbo {
    height: 30rem;
    position: relative;

    &::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url(/img/jumbotron.webp);
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
        filter: brightness(50%);


    }

    &>div {
        position: relative;
        z-index: 100;
        flex-direction: column;
        color: var(--cine--lightest);
        justify-content: center;
        height: 100%;


        & h1 {

            font-size: 3rem;
            word-spacing: 5px;
            letter-spacing: 2px;
            line-height: 60px;
        }

        & h6 {
            letter-spacing: 2px;
            word-spacing: 5px;

        }


        & button {
            background-color: var(--cine--lightest);
            border: none;
            padding: 0.5rem 1rem;
            font-size: 10px;
            font-weight: bold;
            width: fit-content;
            margin-top: 1rem;

        }
    }


}
</style>
