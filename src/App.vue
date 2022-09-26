<script lang="ts">
import NavBar from './utility/NavBar.vue';

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
    components: { NavBar }

};
</script>

<template>
    <NavBar />
    <div class="min-h-screen px-10 grid grid-cols-2 text-black">
        <div class="flex flex-col justify-evenly gap-1 px-24">
            <div class="text-slate-400 font-black">
                <p class="text-9xl">Renzo</p>
                <p class="text-9xl">Cabarios</p>
            </div>
            <p class="text-6xl text-slate-400">
                I am a developer
                who might not be the best, but I am capable enough to finish a job.
            </p>
            <button class="bg-slate-400 font-black text-white p-6 rounded shadow text-3xl">Let's Connect</button>
        </div>
        <div class="image"></div>
    </div>
    <div class="px-10 flex flex-col gap-10 ">
        <p class="text-7xl text-slate-400 font-black text-center">My Projects</p>
        <div class="flex flex-wrap justify-center w-full gap-10">
            <div class="relative bg-slate-400 w-1/4 h-56 rounded shadow">
                <span class="material-symbols-outlined text-white cursor-pointer" @click="preview">
                    open_in_new
                </span>
                <h1 class="text-2xl absolute bottom-3 left-3 text-white">Preview Card Component</h1>
            </div>
            <div class="relative bg-slate-400 w-1/4 h-56 rounded shadow">
                <span class="material-symbols-outlined text-white cursor-pointer" @click="qr_code">
                    open_in_new
                </span>
                <h1 class="text-2xl absolute bottom-3 left-3 text-white">QR Code Component</h1>
            </div>
            <div class="relative bg-slate-400 w-1/4 h-56 rounded shadow">
                <span class="material-symbols-outlined text-white cursor-pointer" @click="order_summary">
                    open_in_new
                </span>
                <h1 class="text-2xl absolute bottom-3 left-3 text-white">Order Summary Component</h1>
            </div>
        </div>
    </div>

    <div class="bg-slate-400 w-full p-12 mt-12"></div>
</template>


<style scoped>
.image {
    background-image: url("./assets/img.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-size: 100% 100%;
}

span {
    font-size: 3rem;
}

@media only screen and (min-width: 600px) {
    body {
        background-color: lightblue;
    }
}
</style>