<template>
    <section
        class="grid grid-cols-1 grid-rows-4 sm:grid-cols-2 sm:grid-rows-2 xl:grid-cols-4 xl:grid-rows-1 gap-y-2 sm:gap-y-8 border-b border-slate-300 py-0 px-4 sm:px-8 divide-y-2 sm:divide-y-0 *:xl:py-8 xl:divide-x-2"
    >
        <!-- N°1 -->
        <div class="pt-4 *:mx-4 sm:*:mx-0">
            <div
                class="flex justify-between text-slate-400 font-bold text-sm xl:mr-8 mb-2"
            >
                <span>Revenue</span>
                <span>+4.75%</span>
            </div>
            <p class="text-3xl sm:text-4xl">$405,091.00</p>
        </div>

        <!-- N°2 -->
        <div class="pt-4 *:mx-4 *:lg:mx-8 sm:*:mx-0">
            <div
                class="flex justify-between text-slate-400 font-bold text-sm sm:mx-8 mb-2"
            >
                <span>Overdue invoices</span>
                <span class="text-red-500">+12.61%</span>
            </div>
            <p class="text-3xl sm:text-4xl sm:ml-8">$12,101.00</p>
        </div>

        <!-- N°3 -->
        <div class="pt-4 *:mx-4 sm:*:mx-0 *:lg:ml-8 sm:pt-0">
            <div
                class="flex justify-between text-slate-400 font-bold text-sm xl:mx-8 mb-2"
            >
                <span>Outstanding invoces</span>
                <span>-3.25%</span>
            </div>
            <p class="text-3xl sm:text-4xl xl:ml-8">$205,222.00</p>
        </div>

        <!-- N°4 -->
        <div class="pt-4 *:mx-4 sm:*:mx-0 *:lg:ml-8 sm:pt-0">
            <div
                class="flex justify-between text-slate-400 font-bold text-sm sm:mx-8 mb-2"
            >
                <span>Expensives</span>
                <span class="text-red-500">+5.15%</span>
            </div>
            <p class="text-3xl sm:text-4xl sm:ml-8">$22,250.00</p>
        </div>
    </section>
</template>

<script setup lang="ts"></script>

<styles scoped></styles>
