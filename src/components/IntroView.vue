<script setup lang="ts">
import NavBar from './NavBar.vue';
</script>
    
<template>
    <div class="intro-container min-h-screen">
        <NavBar />
        <div class="intro px-20">
            <div class="flex justify-center flex-col p-2 gap-11 ">
                <div class="flex flex-col ">
                    <h1 class="text-7xl font-black text-teal-500">Renzo</h1>
                    <h1 class="text-7xl font-black text-teal-500">Cabarios</h1>
                </div>
                <h1 class="text-teal-500 text-3xl font-light">
                    I am a developer
                    who might not be the best,
                    but I am capable enough to finish a job.
                </h1>
                <button
                    class="text-white text-4xl bg-teal-500 w-3/6 px-3 py-2 rounded shadow-lg hover:shadow-2xl transition-all">Let's
                    Connect</button>

            </div>
            <div class="intro-img flex justify-center flex-col">
                <img src="./assets/img.png" alt="" srcset="">
            </div>
        </div>
    </div>
</template>
    
<style scoped>
.intro-container {
    width: 100%;
    display: grid;
    grid-template-rows: 9% auto;
    gap: 2rem;

}

.intro {
    width: 100%;
    display: grid;
    gap: 1rem;
}

.intro-img {
    display: none;
}

@media only screen and (min-width: 600px) {
    .intro {
        grid-template-columns: 40% 60%;
    }

    .intro-img {
        display: inline;
    }
}
</style>
    