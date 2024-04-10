<script>
export default {
    name: 'AppFooter',
    props: {
        footerEl: Object,
    }
}
</script>

<template>
    <div id="site-footer">
        <div class="top">
            <div class="container">
                <div class="row d-flex">
                    <template v-for="(elements, key) in footerEl">
                        <div class="col" v-if="key !== 'newsletter' && key !== 'copyright'">
                            <ul>
                                <li>
                                    <h4>{{ elements.title }}</h4>
                                </li>
                                <li :class="key === 'contacts' ? 'd-flex' : ''" v-for="element in elements.list">
                                    <template v-if="key === 'contacts'">
                                        <img :src="'/img/' + element.icon" alt="">
                                        <a href="#">{{ element.info }}</a>
                                    </template>
                                    <template v-else>
                                        <a href="#">{{ element }}</a>
                                    </template>
                                </li>
                            </ul>
                        </div>
                    </template>
                    <div class="col">
                        <ul>
                            <li>
                                <h4>{{ footerEl.newsletter.title }}</h4>
                            </li>
                            <li>
                                {{ footerEl.newsletter.message }}
                            </li>
                            <li>
                                <input type="email" placeholder="Enter Your Email"
                                    v-model="footerEl.newsletter.inputEmail">
                            </li>
                            <li>
                                <button class="btn-light">SUBSCRIBE</button>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="bottom">
            &copy; {{ footerEl.copyright }}
        </div>
    </div>
</template>



<style></style>