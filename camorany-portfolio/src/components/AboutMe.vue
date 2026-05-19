<script setup> 
import { Code } from 'lucide-vue-next'

</script>

<template>
  <section
    id="aboutme" class="min-h-screen bg-gray-900 text-slate-300 flex items-center justify-center px-30 py-35 lg:py-30"
  >
    <div
      class="max-w-7xl w-full flex flex-col lg:flex-row gap-8 p-2"
    >
      
      <!-- LEFT SIDE -->
      <div class="lg:w-[55%] w-full order-2 lg:order-1">
        
        <h1 class=" text-5xl font-bold text-emerald-600 mb-5">
          About Me
        </h1>

        <p class="text-gray-300 leading-relaxed mb-8">
          Software Engineering from Bournemouth University.
          Passionate about building innovative solutions, with hands-on industry experience and a strong foundation in software development. 
          Eager to contribute to impactful projects while continuing to grow in the tech industry.
        </p>

        <!-- BUTTONS -->
        <div class="mb-10">
            <button class="cursor-pointer border border-emerald-600 px-6 py-3 rounded-xl hover:scale-105 hover:shadow-[0_3px_10px__rgba(255,255,255,0.3)] transition" href="#">
                Contact Me
            </button>
        </div>

        <div class="flex flex-col justify-center md:justify-start">
            <div class="flex gap-2 items-center md:justify-start mb-5">
                <h3 class="text-2xl font-semibold text-emerald-600">
                Skills
                </h3>
                <Code class="w-5 h-5 transition-all duration-300 hover:-translate-y-1 text-emerald-600"/>
            </div>
            
            <div class="flex flex-wrap gap-5 justify-center md:justify-start">
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                C# / .NET
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                Python
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                Golang
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                Angular / AngularJS
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                React.js
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                Vue.Js
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                SQL Server
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                MySQL
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                MongoDB
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                GitHub Actions
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                AWS
                </button>
                <button class="bg-emerald-500 text-black px-6 py-3 rounded-4xl font-semibold hover:text-emerald-600 hover:bg-gray-900 border hover:border-emerald-600 transition">
                Docker
                </button>
            </div>
        </div>
      </div>

      <!-- RIGHT SIDE -->
      <div class="flex justify-center items-center lg:w-[45%] w-full md:text-left order-1 lg:order-2">
        <div class="w-full max-w-[500px] aspect-[6/5] rounded-3xl overflow-hidden shadow-[0_10px_40px_#0596695d]">
                <img
                    src="../assets/aboutme/about-me-pic.jpg"
                    alt="About Me Picture"
                    class="w-full h-full object-cover"
                />
        </div>
      </div>
    </div>
  </section>
</template>