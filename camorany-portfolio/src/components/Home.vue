<script setup> 
import { GithubIcon, LinkedinIcon } from 'lucide-vue-next'
</script>

<template>
  <section
    id="home" class="min-h-screen bg-gray-900 text-white flex items-center justify-center px-10 pt-30 md:pt-10 py-20 md:py-0"
  >
    <div
      class="max-w-7xl w-full flex flex-col md:flex-row items-center gap-8 p-2"
    >
      
      <!-- LEFT SIDE -->
      <div class="flex justify-center md:justify-start md:w-1/2 w-full">

            <!--DESKTOP ICONS -->
            <div class="w-30 hidden md:flex justify-center items-center">
                <div class="hidden md:flex flex-col gap-6 left-6 items-center">
                  <a href="https://github.com/Camorany">
                  <GithubIcon class="w-6 h-6 text-white transition-all duration-300 hover:-translate-y-1 hover:text-green-600" />
                  </a>

                  <a href="https://www.linkedin.com/in/cameron-lane-a69842255">
                  <LinkedinIcon class="w-6 h-6 text-white transition-all duration-300 hover:-translate-y-1 hover:text-green-600"/>
                  </a>
                </div>
            </div>

            <div class="w-72 h-72 md:w-96 md:h-96 rounded-full border-4 border-green-500 overflow-hidden shadow-[0_0_15px_#3deb71]">
            <img
                src="../assets/home/portfolio-hero-pic.jpg"
                alt="Profile"
                class="w-full h-full object-cover"
            />
            </div>
      </div>

      <!-- RIGHT SIDE -->
      <div class="md:w-1/2 w-full text-center md:text-left">
        <p class="text-lg mb-5">
          Hi, I'm a
          <span class="text-green-600">Software Engineer</span>
        </p>

        <h1 class=" text-5xl font-bold text-green-600 mb-5">
          Cameron Lane
        </h1>

        <!-- MOBILE ICONS -->
        <div class="mb-5 flex flex-row md:hidden justify-center items-center">
                <div
                class="flex gap-6 items-center"
                >
                <a href="https://github.com/Camorany">
                <GithubIcon class="w-6 h-6 text-white transition-all duration-300 hover:-translate-y-1 hover:text-green-600" />
                </a>

                <a href="https://www.linkedin.com/in/cameron-lane-a69842255/">
                <LinkedinIcon class="w-6 h-6 text-white transition-all duration-300 hover:-translate-y-1 hover:text-green-600" />
                </a>
                </div>

            </div>

        <p class="text-gray-300 leading-relaxed mb-8">
          Software Engineering from Bournemouth University.
          Passionate about building innovative solutions, with hands-on industry experience and a strong foundation in software development. 
          Eager to contribute to impactful projects while continuing to grow in the tech industry.
        </p>

        <!-- BUTTONS -->
        <div class="flex gap-4 justify-center md:justify-start">
          <button
            class="cursor-pointer bg-green-600 text-black px-6 py-3 rounded-xl font-semibold hover:scale-105 hover:shadow-[0_3px_10px__rgba(255,255,255,0.3)] transition"
          >
            Download CV
          </button>

          <button
            class="cursor-pointer border border-green-600 px-6 py-3 rounded-xl hover:scale-105 hover:shadow-[0_3px_10px__rgba(255,255,255,0.3)] transition"
          >
            Projects
          </button>
        </div>
      </div>
    </div>
  </section>
</template>