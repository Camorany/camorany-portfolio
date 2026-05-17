<script setup> 
</script>

<template>
  <section
    class="min-h-screen bg-gray-900 text-white flex items-center justify-center px-10"
  >
    <div
      class="outline-1 max-w-7xl w-full flex flex-col md:flex-row gap-8 p-2"
    >
      
      <!-- LEFT SIDE -->
      <div class="flex flex-col outline-1 md:w-1/2 w-full">
        
        <h1 class=" text-5xl font-bold text-green-600 mb-5">
          About Me
        </h1>

        <p class="text-gray-300 leading-relaxed mb-8">
          Software Engineering from Bournemouth University.
          Passionate about building innovative solutions, with hands-on industry experience and a strong foundation in software development. 
          Eager to contribute to impactful projects while continuing to grow in the tech industry.
        </p>

        <!-- BUTTONS -->
        <div class="flex justify-center md:justify-start">
            <button class="cursor-pointer border border-green-600 px-6 py-3 rounded-xl hover:scale-105 hover:shadow-[0_3px_10px__rgba(255,255,255,0.3)] transition">
                Projects
            </button>
        </div>

        <div class="flex flex-col justify-center md:justify-start mt-10">
            <h3 class="text-2xl font-semibold text-green-600 mb-5">
                Skills
            </h3>
            <div class="flex gap-10">
                <button class="bg-green-600 text-black px-6 py-3 rounded-4xl font-semibold hover:scale-105 hover:shadow-[0_3px_10px_rgba(255,255,255,0.3)] transition">
                Contact Me
            </button>
            <button class="bg-green-600 text-black px-6 py-3 rounded-4xl font-semibold hover:scale-105 hover:shadow-[0_3px_10px_rgba(255,255,255,0.3)] transition">
                Contact Me
            </button>
            <button class="bg-green-600 text-black px-6 py-3 rounded-4xl font-semibold hover:scale-105 hover:shadow-[0_3px_10px_rgba(255,255,255,0.3)] transition">
                Contact Me
            </button>

            </div>
        </div>
      </div>

      <!-- RIGHT SIDE -->
      <div class="flex justify-center md:w-1/2 w-full text-center md:text-left">
        <div class="w-100 h-100 rounded overflow-hidden shadow-[0_10px_40px_#3deb715d]">
                <img
                    src="../assets/home/portfolio-hero-pic.jpg"
                    alt="Profile"
                    class="w-full h-full object-cover"
                />
            </div>
      </div>
    </div>
  </section>
</template>