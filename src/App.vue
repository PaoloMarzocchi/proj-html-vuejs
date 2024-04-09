<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
    name: 'App',
    components: {
        AppHeader,
        AppMain,
    },
}
</script>

<template>
    <AppHeader></AppHeader>

    <AppMain></AppMain>
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

<style></style>
