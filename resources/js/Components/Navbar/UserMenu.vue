<template>
    <div class="relative">
        <div class="flex flex-row items-center gap-3">
            <div
            class="hidden md:block text-sm font-semibold py-3 px-4 rounded-full hover:bg-neutral-100 transition cursor-pointer "
            >
            Airbnb your home
        </div>
        <div
            onClick={toggleOpen}
            class="p-4 md:py-1 md:px-2 border-[1px] border-neutral-200 flex flex-row items-center gap-3 rounded-full cursor-pointer hover:shadow-md transition"
        >
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
            </svg>

            <div class="hidden md:block">
                <Avatar />
            </div>
        </div>
    </div>
    <div class="absolute rounded-xl shadow-md w-[40vw] md:w-3/4 bg-white overflow-hidden right-0 top-12 text-sm">
        <div class="flex flex-col cursor-pointer">

        </div>
    </div>
    </div>
</template>
<script setup>
import Avatar from "@/Components/Avatar.vue";
</script>
