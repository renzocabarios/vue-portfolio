<script lang="ts">
import NavBar from './utility/NavBar.vue';
import Hero from './utility/Hero.vue';
import MyProject from './utility/MyProject.vue';
import BaseFooter from './utility/BaseFooter.vue';

export default {
    setup() {
        function qr_code() {
            window.location.href = "https://github.com/renzocabarios/vanilla-web/tree/master/qr-code-component-main";
        }

        function preview() {
            window.location.href = "https://github.com/renzocabarios/vanilla-web/tree/master/preview-card-component";
        }

        function order_summary() {
            window.location.href = "https://github.com/renzocabarios/vanilla-web/tree/master/order-summary-component-main";
        }

        return { qr_code, preview, order_summary }
    },
    components: { NavBar, Hero, MyProject, BaseFooter }

};
</script>

<template>
    <NavBar />
    <Hero />
    <MyProject />
    <BaseFooter />
</template>


<style scoped>

</style>