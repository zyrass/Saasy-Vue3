<script setup lang="ts">
import MyHeader from './components/MyHeader.vue';
import MyNavbar from './components/MyNavbar.vue';
import Status from './components/Status.vue';
import Activity from './components/Activity.vue';
</script>

<template>
    <div class="container">
        <article class="bg-white min-h-screen rounded-2xl">
            <MyHeader />
            <MyNavbar />
            <Status />
            <Activity />
        </article>
    </div>
</template>

<style scoped></style>
