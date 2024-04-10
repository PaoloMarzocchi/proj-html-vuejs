<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
    name: 'App',
    components: {
        AppHeader,
        AppMain,
        AppFooter,
    },
    data() {
        return {
            navBar: {
                logo: 'logo.svg',
                menu: [
                    {
                        name: 'HOME',
                        dropDownMenu: null,
                    },
                    {
                        name: 'BLOG',
                        dropDownMenu: null,
                    },
                    {
                        name: 'PAGES',
                        dropDownMenu: {
                            arrowDownImg: 'image (7).svg',
                            dropdown: ['SERVICES', 'OUR WORK FLOW', 'VIDEO THUMBNAIL TYPE']
                        },
                    },
                    {
                        name: 'ABOUT',
                        dropDownMenu: null,
                    },
                    {
                        name: 'CONTACTS',
                        dropDownMenu: null,
                    },
                    {
                        name: 'GALLERY',
                        dropDownMenu: null,
                    },
                    {
                        name: 'SHOP',
                        dropDownMenu: {
                            arrowDownImg: 'image (7).svg',
                            dropdown: ['SERVICES', 'OUR WORK FLOW', 'VIDEO THUMBNAIL TYPE']
                        },
                    },
                ],
                icons: {
                    search: 'image (8).svg',
                    social: {
                        facebook: 'image (9).svg',
                        twitter: 'image (10).svg',
                        youtube: 'image (11).svg',
                        instagram: 'image (12).svg',
                    }

                }
            },
        }
    },
}
</script>

<template>
    <AppHeader :logo="navBar.logo" :menu="navBar.menu" :icons="navBar.icons"></AppHeader>

    <AppMain></AppMain>

    <AppFooter></AppFooter>
</template>

<style></style>
