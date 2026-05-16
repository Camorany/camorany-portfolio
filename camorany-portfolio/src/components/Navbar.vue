<script setup> 
import { ref } from 'vue'
const navOpen = ref(false)
</script>

<template> 
    <div class="navbar">
        
        <!-- Mobile Navbar -->
        <div class="sm:hidden bg-gray-900 px-8 py-4 text-white shadow-[0_10px_15px_rgba(0,0,0,0.5)]">
            <div>
                <button @click="navOpen = !navOpen">

                    <svg v-bind:class="navOpen ? 'hidden' : '' " xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                    </svg>

                    <svg v-bind:class="navOpen ? '' : 'hidden' " xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m9.75 9.75 4.5 4.5m0-4.5-4.5 4.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                    </svg>
                </button>
            </div>

            <nav
                class="overflow-hidden transition-all duration-600 ease-in-out"
                :class="navOpen ? 'max-h-60 opacity-100 mt-1' : 'max-h-0 opacity-0'"
                >

                <a href="#" class="block py-1">About Me</a>
                <a href="#" class="block py-1">Projects</a>
                <a href="#" class="block py-1">Experience</a>
                <a href="#" class="block py-1">Contact</a>

            </nav>
        </div>

        <!-- Desktop Navbar -->
        <div class="px-4 py-8 bg-gray-900 text-white hidden sm:block shadow-[0_10px_15px_rgba(0,0,0,0.5)]">
            <div class="flex items-center">
                <div class="pl-3">
                    <h2>Cameron Lane</h2>
                </div>
                <div class="flex ml-auto lg:gap-x-35 md:gap-x-18 sm:gap-x-9 pr-15">
                    <a href="#">About Me</a>
                    <a href="#">Projects</a>
                    <a href="#">Experience</a>
                    <a href="#">Contact</a>
                </div>
            </div>
        </div>

    </div>
</template>