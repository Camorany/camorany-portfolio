<script setup> 
import { GithubIcon, LinkedinIcon } from 'lucide-vue-next'
</script>

<template>
  <section
    class="min-h-screen bg-gray-900 text-white flex items-center justify-center px-10"
  >
    <div
      class="max-w-7xl w-full flex flex-col md:flex-row items-center gap-16"
    >
      
      <!-- LEFT SIDE -->
      <div class="flex justify-center">

            <div class="w-30 flex justify-center items-center">
                <!-- SOCIAL SIDEBAR -->
                <div
                class="hidden lg:flex flex-col gap-6 left-6 items-center"
                >
                <a href="https://github.com/Camorany">
                <GithubIcon class="w-6 h-6 text-white hover:text-green-600" />
                </a>

                <a href="https://www.linkedin.com/in/cameron-lane-a69842255/">
                <LinkedinIcon class="w-6 h-6 text-white hover:text-green-600" />
                </a>
                </div>

                </div>

            <div
            
            class="w-72 h-72 md:w-96 md:h-96 rounded-full border-4 border-green-500 overflow-hidden shadow-[0_0_40px_#ffffff]"
            >
            <img
                src=""
                alt="Profile"
                class="w-full h-full object-cover"
            />
            </div>
      </div>

      <!-- RIGHT SIDE -->
      <div class="max-w-xl text-center md:text-left">
        <p class="text-lg mb-5">
          Hi, I'm a
          <span class="text-green-600">Software Engineer</span>
        </p>

        <h1 class="text-5xl font-bold text-green-600 mb-6">
          Cameron Lane
        </h1>

        <p class="text-gray-300 leading-relaxed mb-8">
          I'm a Software Engineer
        </p>

        <!-- BUTTONS -->
        <div class="flex gap-4 justify-center md:justify-start">
          <button
            class="cursor-pointer bg-green-600 text-black px-6 py-3 rounded-xl font-semibold hover:scale-105 transition"
          >
            Download CV
          </button>

          <button
            class="cursor-pointer border border-green-600 px-6 py-3 rounded-xl hover:bg-green-600 hover:text-black transition"
          >
            Projects
          </button>
        </div>
      </div>
    </div>
  </section>
</template>