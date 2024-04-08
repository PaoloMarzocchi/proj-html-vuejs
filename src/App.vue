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
        <section></section>
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

/* #endregion Utilities */
</style>
