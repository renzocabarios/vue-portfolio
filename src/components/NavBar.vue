<script setup lang="ts">
</script>

<template>
    <div class="nav bg-teal-400 text-white px-10">
        <div class="flex justify-center items-center w-full h-full">
            <h1 class="text-6xl font-black">Portolio</h1>
        </div>
        <div></div>
        <div class="flex flex-col justify-around w-full h-full p-2">
            <div class="h-1/6 w-full bg-white rounded"></div>
            <div class="h-1/6 w-full bg-white rounded"></div>
            <div class="h-1/6 w-full bg-white rounded"></div>
        </div>
    </div>
</template>

<style scoped>
.nav {
    width: 100%;
    height: 100%;
    display: grid;
    grid-template-columns: max-content auto 5rem;
}
</style>
