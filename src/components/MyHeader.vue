<template>
    <header class="h-24 grid grid-cols-3 items-center relative">
        <div
            class="flex sm:hidden ml-8 h-8 w-10 rounded-md shadow text-xl border items-center hover:bg-gray-200 active:bg-gray-300 justify-center cursor-pointer"
            @click="updateState"
        >
            <i v-if="!state.openMenu" class="fa-solid fa-bars"></i>
            <i v-if="state.openMenu" class="fa-solid fa-xmark"></i>

            <!-- Menu exclusivement sur mobile -->
            <div
                v-if="state.openMenu"
                class="absolute sm:hidden top-24 left-0 h-64 w-full bg-slate-100 border-b-2 border-t-1 border-gray-200 shadow-md transition-all"
            >
                <ul
                    class="flex flex-col py-8 gap-y-4 items-center hover:*:text-sky-500 cursor-pointer transition-all *:py-1 font-bold"
                >
                    <li>Home</li>
                    <li>Invoices</li>
                    <li>Clients</li>
                    <li>Expenses</li>
                </ul>
            </div>
        </div>
        <div
            class="bg-[url('./assets/images/logo.png')] size-8 bg-cover ml-8"
        ></div>
        <nav class="hidden sm:block">
            <ul
                class="flex justify-center hover:*:text-sky-500 cursor-pointer transition-all *:px-2 font-bold"
            >
                <li>Home</li>
                <li>Invoices</li>
                <li>Clients</li>
                <li>Expenses</li>
            </ul>
        </nav>
        <ul class="flex justify-end mr-8 items-center gap-x-4">
            <li><i class="fa-regular fa-bell text-xl text-slate-400"></i></li>
            <li>
                <div
                    class="bg-[url('https://randomuser.me/api/portraits/women/22.jpg')] size-9 bg-cover rounded-full"
                ></div>
            </li>
        </ul>
    </header>
</template>

<script setup lang="ts">
import { reactive, watch } from 'vue';

const state = reactive({
    openMenu: false,
});
const updateState = () => {
    state.openMenu = !state.openMenu;
};

// Ajout d'un watcher pour rafraîchir automatiquement lorsque state.openMenu change
watch(
    () => state.openMenu,
    () => {
        console.log('La valeur de openMenu a changé :', state.openMenu);
    },
);
</script>

<styles scoped></styles>
