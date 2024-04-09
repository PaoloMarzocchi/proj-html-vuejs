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
        <!-- <div class="container"> -->
        <!-- Jumbotron section -->
        <section class="jumbo">
            <div class="container">
                <div class="text-box d-flex">
                    <h6>CINEMATO STUDIO</h6>
                    <h1>ACTION AND <br> INSPIRE PEOPLE</h1>
                    <button class="btn-light">READ MORE</button>
                </div>
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
        <section class="about ">
            <div class="container d-flex">
                <div class="text-box d-flex">
                    <h6>ABOUT US</h6>
                    <h2>HIGH QUALITY CINEMA</h2>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto, repellendus dolore
                        distinctio cumque neque voluptatibus eius reiciendis sunt non tenetur quasi incidunt deserunt
                        aliquid sed? Reiciendis dolores similique officia aliquid.
                    </p>
                    <button class="btn-light">READ MORE</button>

                </div>
            </div>

        </section>
        <section class="watchlist p-section">

            <div class="section-title">
                <h6>YOUR WATCHLIST</h6>
                <h2>BEST HITS MOVIES</h2>
            </div>
            <div class="container">
                <div class="row d-flex">
                    <div class="col d-flex">
                        <img src="/img/Gallery-01.jpg" alt="">
                        <h4>SEVENTEENTH SUMMER</h4>
                        <span>Commercial, Music Video</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Gallery-02.jpg" alt="">
                        <h4>SEVENTEENTH SUMMER</h4>
                        <span>Commercial, Music Video</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Gallery-03.jpg" alt="">
                        <h4>SEVENTEENTH SUMMER</h4>
                        <span>Commercial, Music Video</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Gallery-04.jpg" alt="">
                        <h4>SEVENTEENTH SUMMER</h4>
                        <span>Commercial, Music Video</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Gallery-05.jpg" alt="">
                        <h4>SEVENTEENTH SUMMER</h4>
                        <span>Commercial, Music Video</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Gallery-01.jpg" alt="">
                        <h4>SEVENTEENTH SUMMER</h4>
                        <span>Commercial, Music Video</span>
                    </div>
                </div>
            </div>
        </section>
        <section class="stats">
            <div class="container">
                <div class="row d-flex">
                    <div class="col d-flex">
                        <h2>158</h2>
                        <h6>SATISFIED CLIENTS</h6>
                    </div>
                    <div class="col d-flex">
                        <h2>3 +</h2>
                        <h6>OUR PROJECTS</h6>
                    </div>
                    <div class="col d-flex">
                        <h2>1.906</h2>
                        <h6>CUP OF COFFEE</h6>
                    </div>
                    <div class="col d-flex">
                        <h2>2</h2>
                        <h6>OUR AWARDS</h6>
                    </div>
                </div>
            </div>
        </section>
        <section class="team p-section">
            <div class="section-title">
                <h6>THE PERICUROS</h6>
                <h2>MEET THE TEAM</h2>
            </div>
            <div class="container">
                <div class="row d-flex">
                    <div class="col d-flex">
                        <img src="/img/Team-01.jpg" alt="">
                        <h4>FABRICIO GUERRA</h4>
                        <span>Main director</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Team-02.jpg" alt="">
                        <h4>UMBERTO PAGODA</h4>
                        <span>Main writer</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Team-03.jpg" alt="">
                        <h4>GLORIA RICCASSO</h4>
                        <span>Main producer</span>
                    </div>
                    <div class="col d-flex">
                        <img src="/img/Team-04.jpg" alt="">
                        <h4>LIO NAPOIN</h4>
                        <span>Cameraman</span>
                    </div>
                </div>
            </div>
        </section>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
        <!-- </div> -->
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
#site-main {

    margin: 0 5px;



}
</style>
