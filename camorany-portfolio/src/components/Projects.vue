<script setup> 
import { Code } from 'lucide-vue-next'

</script>

<template>
  <section id="projects" class="min-h-screen bg-gray-900 text-white flex items-center justify-center px-10 py-20 md:py-0"
  >
    <div
      class="max-w-7xl w-full flex flex-col md:flex-row p-2"
    >
      
      <!-- LEFT SIDE -->
      <div class="flex flex-col items-center w-full">
        
            <h1 class=" text-5xl font-bold text-green-600 mb-15">
            Projects
            </h1>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-20">
                    <div class="rounded-3xl aspect-[6/4] overflow-hidden shadow-[0_10px_40px_#3deb715d]">
                        <img
                            src="../assets/aboutme/about-me-pic.jpg"
                            alt="About Me Picture"
                            class="w-full h-auto object-cover"
                        />
                    </div>
                    <div class="rounded-3xl aspect-[6/4] overflow-hidden shadow-[0_10px_40px_#3deb715d]">
                        <img
                            src="../assets/aboutme/about-me-pic.jpg"
                            alt="About Me Picture"
                            class="w-full h-auto object-cover"
                        />
                    </div>
                    <div class="rounded-3xl aspect-[6/4] overflow-hidden shadow-[0_10px_40px_#3deb715d]">
                        <img
                            src="../assets/aboutme/about-me-pic.jpg"
                            alt="About Me Picture"
                            class="w-full h-auto object-cover"
                        />
                    </div>
                    <div class=" rounded-3xl aspect-[6/4] overflow-hidden shadow-[0_10px_40px_#3deb715d]">
                        <img
                            src="../assets/aboutme/about-me-pic.jpg"
                            alt="About Me Picture"
                            class="w-full h-auto object-cover"
                        />
                    </div>
                </div>

      </div>
    </div>
  </section>
</template>