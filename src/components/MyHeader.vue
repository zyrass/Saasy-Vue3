<template>
    <header class="h-24 grid grid-cols-3 items-center">
        <div
            class="bg-[url('./assets/images/logo.png')] size-8 bg-cover ml-8"
        ></div>
        <nav>
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

<script setup lang="ts"></script>

<styles scoped></styles>
