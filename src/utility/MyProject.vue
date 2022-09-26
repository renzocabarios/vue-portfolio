<script lang="ts">
export default {
    setup() { }
};
</script>

<template>
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
</template>


<style scoped>
span {
    font-size: 3rem;
}
</style>