<script setup> 
import { Code } from 'lucide-vue-next'

</script>

<template>
  <section id="projects" class="min-h-screen bg-gray-900 text-white flex items-center justify-center px-10 py-30 lg:py-30"
  >
    <div
      class="max-w-7xl w-full flex flex-col md:flex-row p-2"
    >

      <div class="flex flex-col items-center w-full">
        
            <h1 class=" text-5xl font-bold text-green-600 mb-15">
            Projects
            </h1>
                
                <div class="grid grid-cols-2 md:grid-cols-2 gap-20">

                    <!--HYPERTROPHY EDU CARD-->
                    <div class="group relative rounded-3xl aspect-[6/4] overflow-hidden shadow-[0_10px_40px_#3deb715d] max-w-md">
                        <img
                            src="../assets/aboutme/about-me-pic.jpg"
                            alt="About Me Picture"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                        />

                        <!-- OVERLAY -->
                         <div class="absolute inset-0 bg-black/70 flex flex-col items-center justify-center text-center p-5
                         opacity-0 group-hover:opacity-100 transition duration-300">

                         <h3 class="text-white font-semibold text-2xl mb-5">
                            Hypertrophy EDU
                         </h3>

                         <p class="text-gray-200 mb-5">
                            A web application utilising generative AI to provide legitimised fitness content and education.
                         </p>

                         <a class="cursor-pointer border border-green-600 px-6 py-3 rounded-xl hover:scale-105 hover:shadow-[0_3px_10px__rgba(255,255,255,0.3)] transition">
                            View Project
                         </a>

                         </div>
                    </div>

                    <!--HTTP/1.1 PROTOCOL REMAKE CARD-->
                    <div class="group relative rounded-3xl aspect-[6/4] overflow-hidden shadow-[0_10px_40px_#3deb715d] max-w-md">
                        <img
                            src="../assets/aboutme/about-me-pic.jpg"
                            alt="About Me Picture"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                        />

                        <!-- OVERLAY -->
                         <div class="absolute inset-0 bg-black/70 flex flex-col items-center justify-center text-center p-5
                         opacity-0 group-hover:opacity-100 transition duration-300">

                         <h3 class="text-white font-semibold text-2xl mb-5">
                            HTTP/1.1 Remake
                         </h3>

                         <p class="text-gray-200 mb-5">
                            A web application utilising generative AI to provide legitimised fitness content and education.
                         </p>

                         <a class="cursor-pointer border border-green-600 px-6 py-3 rounded-xl hover:scale-105 hover:shadow-[0_3px_10px__rgba(255,255,255,0.3)] transition">
                            View Project
                         </a>

                         </div>
                    </div>

                </div>

      </div>
    </div>
  </section>
</template>