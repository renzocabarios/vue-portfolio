<script setup lang="ts">
import NavBar from './components/NavBar.vue';
import Card from './components/Card.vue';
import FooterBar from './components/FooterBar.vue';
</script>

<template>
    <div class="container bg-gray-500  text-white">
        <NavBar/>
        <div class="w-full h-full flex flex-col justify-center gap-10 items-center bg-gray-800 p-5">
            <div class="h-56 w-56 rounded-full bg-white"></div>
            <div class="text-center">
                <h1 class="text-center font-black text-2xl">Hello There!</h1>
                <h1 class="font-light text-xl">I am aspiring software engineer who has a passion for making real world solutions to real world problems</h1>
            </div>
        </div>
        <div class="bg-gray-800 py-10 px-5">
            <Card/>
        </div>
        <FooterBar />
    </div>
</template>

<style scoped>
    .container{
        display: grid;
        gap: 0.2rem;
        grid-template-rows: 8vh 92vh auto 30vh;
    }


</style>
