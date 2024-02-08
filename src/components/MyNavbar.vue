<template>
    <nav
        class="flex justify-between p-8 border-y border-slate-200 *:transition-all items-center"
    >
        <ul class="flex gap-x-4 hover:*:text-sky-500 font-bold cursor-pointer">
            <li>Cashflow</li>
            <li class="text-sky-500">Last 7 days</li>
            <li>Last 30 days</li>
            <li>All-time</li>
        </ul>
        <button
            class="bg-sky-500 px-4 py-2 text-white capitalize rounded-md shadow-md hover:shadow-sm hover:bg-sky-700"
        >
            + new Invoice
        </button>
    </nav>
</template>
