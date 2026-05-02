<script setup> 
import { ref } from 'vue'
const navOpen = ref(false)
</script>

<template> 
    <div>

        <div>

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

            <nav v-bind:class="navOpen ? '' : 'hidden' ">
                <a href="#" class="block">About Me</a>
                <a href="#" class="block">Projects</a>
                <a href="#" class="block">Experience</a>
                <a href="#" class="block">Contact</a>

            </nav>

        </div>

        {{ navOpen }}

    </div>
</template>