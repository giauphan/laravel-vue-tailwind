<script setup>
import { Link } from "@inertiajs/vue3";
</script>
<template>
    <header
        class="bg-black sticky top-0 flex items-center justify-between gap-4 border-b border-gray-700 px-2 py-4 sm:px-6 md:px-8 lg:px-20 z-[99999]"
    >
        <div>
            <a href="/">
                <img
                    alt="Logo"
                    src=""
                    class="ms-0 md:ms-5 h-auto lg:h-24 w-auto aspect-video"
                />
            </a>
        </div>
        <div class="flex items-center justify-center gap-5">
            <Link href="/" class="text-white">Home</Link>
            <Link href="/" class="text-white">About</Link>
            <Link href="/" class="text-white">Contact</Link>
        </div>
        <div class="flex gap-3">
            <button
                class="border text-white whitespace-nowrap p-2 rounded bg-blue-600 text-lg font-semibold font-['Inter']"
            >
                <a :href="route('login')"> Login </a>
            </button>
            <button
                class="text-white bg-[#DEAD47] whitespace-nowrap p-2 rounded hover:opacity-95 text-lg font-semibold font-['Inter']"
            >
                <a :href="route('register')"> Register </a>
            </button>
        </div>
    </header>
    <main className="min-h-[calc(100vh-89px)]">
        <slot></slot>
    </main>
</template>
