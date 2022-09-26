<script lang="ts">
import NavBar from './utility/NavBar.vue';
import Hero from './utility/Hero.vue';
import MyProject from './utility/MyProject.vue';

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
    components: { NavBar, Hero, MyProject }

};
</script>

<template>
    <NavBar />
    <Hero />
    <MyProject />
    <div class="bg-slate-400 w-full p-12 mt-12"></div>
</template>


<style scoped>

</style>