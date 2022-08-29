<script setup lang="ts">
</script>

<template>
        <div class="container bg-gray-900">
            <div class="flex flex-col justify-evenly items-center px-3 py-1">
                <div class="h-1 w-5/6 bg-white"></div>
                <div class="h-1 w-5/6 bg-white"></div>
                <div class="h-1 w-5/6 bg-white"></div>
            </div>
        </div>
</template>

<style scoped>
    .container{
        display: grid;
        gap: 0.2rem;
        grid-template-columns: 5rem auto 5rem;
    }
</style>
