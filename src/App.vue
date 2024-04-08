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

        <!-- Jumbotron section -->
        <section class="jumbo">
            <div class="container d-flex">
                <h6>CINEMATO STUDIO</h6>
                <h1>ACTION AND <br> INSPIRE PEOPLE</h1>
                <button>READ MORE</button>
            </div>

        </section>


        <section class="studio p-section">
            <div class="section-title">
                <h6>PELICULA STUDIO</h6>
                <h2>THIS IS WHAT WE DO</h2>
            </div>
            <div class="container">
                <div class="row d-flex">
                    <div class="col d-flex">
                        <div class="top">
                            <img src="/img/image (14).svg" alt="">
                        </div>

                        <h4>ARRAY OF EQUIPMENT</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor, laboriosam.</p>

                    </div>
                    <div class="col d-flex">
                        <div class="top">
                            <img src="/img/image (16).svg" alt="">
                        </div>
                        <h4>NEW TECHNOLOGIES</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor, laboriosam.</p>

                    </div>
                    <div class="col d-flex">
                        <div class="top">
                            <img src="/img/image (18).svg" alt="">
                        </div>
                        <h4>VERSITILE ACTORS</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor, laboriosam.</p>

                    </div>
                    <div class="col d-flex">
                        <div class="top">
                            <img src="/img/image (15).svg" alt="">
                        </div>
                        <h4>TOP DIRECTORS</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor, laboriosam.</p>

                    </div>
                    <div class="col d-flex">
                        <div class="top">
                            <img src="/img/image (17).svg" alt="">
                        </div>
                        <h4>MINUTE EDITING</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor, laboriosam.</p>

                    </div>
                    <div class="col d-flex">
                        <div class="top">
                            <img src="/img/image (19).svg" alt="">
                        </div>
                        <h4>VERSITILE ACTORS</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor, laboriosam.</p>

                    </div>

                </div>
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

.p-section {
    padding: 3rem;
}

/* #endregion Utilities */

#site-main {

    margin: 0 5px;

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

    .studio {
        background-color: var(--cine--light);

        .section-title {
            text-align: center;

            & h2 {
                margin: 0.5rem 0;
            }
        }

        .row {
            padding: 1rem 0;
            flex-wrap: wrap;
        }

        .col {
            width: calc(100%/12 * 4);
            flex-direction: column;
            align-items: center;
            gap: 1rem;
            justify-content: space-between;
            padding-top: 3rem;

            .top {
                height: 5.5rem;
                width: 5rem;
            }

            & p {
                text-align: center;
            }
        }

    }

}
</style>
