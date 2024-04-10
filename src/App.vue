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
            navBarEl: {
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
            footerEl: {
                contacts: {
                    title: 'CONTACT INFO',
                    list: [
                        {
                            info: '2/45 Tower Street, New York USA',
                            icon: 'footer-location-dot-solid.svg',
                        },
                        {
                            info: 'Call Us On 0800 840 1010',
                            icon: 'footer-phone-solid.svg',
                        },
                        {
                            info: 'Demo@Example.Com',
                            icon: 'footer-envelope-soli.svg',
                        }
                    ]
                },
                infos: {
                    title: 'INFORMATION',
                    list: ['Product Support', 'Checkout', 'Report Abuse', 'Redeem Voucher', 'Order Status']
                },
                links: {
                    title: 'USEFUL LINKS',
                    list: ['Policies & Rules', 'Privacy Policy', 'License Policy', 'My Account', 'Locality']
                },
                newsletter: {
                    title: 'NEWSLETTER',
                    message: 'Subscribe To Receive Inspiration, Ideas & News In Your Inbox',
                    inputEmail: ''
                },
                copyright: '2024 All Rights Reserved. Developed By Paolo Marzocchi'
            }
        }
    },
}
</script>

<template>
    <AppHeader :logo="navBarEl.logo" :menu="navBarEl.menu" :icons="navBarEl.icons"></AppHeader>

    <AppMain></AppMain>
    <AppFooter :footerEl="footerEl"></AppFooter>

</template>

<style></style>
