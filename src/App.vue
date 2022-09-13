<script setup lang="ts">
import NavBar from './components/NavBar.vue';
import Card from './components/Card.vue';
import IntroView from './components/IntroView.vue';
import FooterBar from './components/FooterBar.vue';


</script>

<script  lang="ts">
export default {
    data() {
        return {
            name: 'Vue.js'
        }
    },
    methods: {
        student() {
            window.location.href = "https://github.com/renzocabarios/laravue-student-crud";
        },
        pet_clinic() {
            window.location.href = "https://github.com/renzocabarios/pet-clinic-mern";
        },
        user() {
            window.location.href = "https://github.com/renzocabarios/mern-crud";
        },
    }
};
</script>

<template>
    <IntroView />
    <div class="project min-h-screen px-10">
        <div class="col-span-2 justify-self-center">
            <h1 class="text-6xl font-black text-teal-500">My Projects</h1>
        </div>
        <div @click="user" class="bg-teal-500 rounded-lg shadow-lg hover:shadow-2xl transition-all">
            <div class="w-full h-full flex justify-center items-center text-center">
                <h1 class="text-5xl font-black text-white">User Management System</h1>
            </div>
        </div>
        <div @click="student" class="bg-teal-500 rounded-lg shadow-lg hover:shadow-2xl transition-all">
            <div class="w-full h-full flex justify-center items-center text-center">
                <h1 class="text-5xl font-black text-white">Student Management System</h1>
            </div>
        </div>
        <div @click="pet_clinic" class="bg-teal-500 rounded-lg shadow-lg hover:shadow-2xl transition-all">
            <div class="w-full h-full flex justify-center items-center text-center">
                <h1 class="text-5xl font-black text-white">Pet Clinic System</h1>
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

    .project {
        display: grid;
        grid-template-rows: max-content auto;
        gap: 3rem;
        margin: 1rem 0;
    }
}
</style>
