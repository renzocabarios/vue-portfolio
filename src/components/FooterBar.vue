<script setup lang="ts">
</script>

<template>
        <div class="bg-gray-800 container">
            <h1 class="font-black text-2xl col-span-2 text-center">All Rights Reserved @2022</h1>
            <div class="text-center flex flex-col justify-evenly">
                <h1>Twitter</h1>
                <h1>Facebook</h1>
                <h1>Instagram</h1>
            </div>
            <div class="text-center flex flex-col justify-evenly">
                <h1>Github</h1>
                <h1>Google</h1>
            </div>
        </div>
</template>

<style scoped>
    .container{
        padding: 1rem;
        display: grid;
        gap: 0.2rem;
        grid-template-rows: 3rem auto;
        grid-template-columns: repeat(2, minmax(0, 1fr));;
    }
</style>
