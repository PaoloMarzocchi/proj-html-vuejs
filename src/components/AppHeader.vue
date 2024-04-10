<script>
export default {
    name: 'AppHeader',
    props: {
        logo: String,
        menu: Array,
        icons: Object,
    },

}
</script>

<template>

    <nav id="site-header" class="d-flex">
        <div class="logo">

            <img :src="'/img/' + logo" style="width: 10rem;" alt="">

        </div>
        <!-- Navigation menu -->
        <div class="menu">
            <ul class="d-flex">
                <li class="d-flex" v-for="item in menu">
                    <a href="#">{{ item.name }}</a>
                    <template v-if="item.dropDownMenu">
                        <img :src="'/img/' + item.dropDownMenu.arrowDownImg" alt="">
                        <div class="dropdown-menu">
                            <ul>
                                <li v-for="subItem in item.dropDownMenu.dropdown">
                                    <a href="#">{{ subItem }}</a>
                                </li>
                            </ul>
                        </div>
                    </template>

                </li>
            </ul>
        </div>
        <!-- /Navigation menu -->
        <div class="tools d-flex">

            <div class="search">
                <img :src="'/img/' + icons.search" alt="">
            </div>

            <div class="social" v-for="socialIcon in icons.social">
                <img :src="'/img/' + socialIcon" alt="">
            </div>

        </div>
    </nav>

</template>



<style></style>