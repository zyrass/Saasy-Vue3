<template>
    <nav
        class="flex sm:flex-row flex-col justify-between py-8 sm:p-8 border-y border-slate-200 *:transition-all items-center"
    >
        <div
            class="flex flex-col items-center pt-8 sm:pt-0 sm:flex-row gap-y-4 sm:order-1 order-2 sm:gap-x-4 hover:*:text-sky-500 font-bold cursor-pointer sm:divide-x-2"
        >
            <span>Cashflow</span>
            <ul class="flex flex-col sm:flex-row sm:gap-x-4 gap-4 items-center">
                <li class="text-sky-500 sm:ml-4">Last 7 days</li>
                <li>Last 30 days</li>
                <li>All-time</li>
            </ul>
        </div>
        <button
            class="bg-sky-500 px-4 py-2 text-white capitalize sm:order-2 order-1 rounded-md shadow-md hover:shadow-sm hover:bg-sky-700"
        >
            + new Invoice
        </button>
    </nav>
</template>
