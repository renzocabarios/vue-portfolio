<script  lang="ts">
export default {
    setup() { },
};

</script>

<template>
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
</template>


<style scoped>
.image {
    background-image: url("../assets/img.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-size: 100% 100%;
}
</style>