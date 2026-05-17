<script setup> 
import { GraduationCap, BriefcaseBusiness } from 'lucide-vue-next'

</script>

<template>
  <section
    id="experience" class="min-h-screen bg-gray-900 text-white flex items-center justify-center px-30"
  >

    <div
      class="outline max-w-7xl w-full flex flex-col gap-8 justify-center p-2"
    >

        <h1 class="text-center text-5xl font-bold text-green-600 mb-15">
            Experience
        </h1>

        <div class="flex flex-col lg:flex-row w-full gap-50">
                <!-- EXPERIENCE SIDE -->
            <div class="lg:w-1/2 w-full">
                <!-- TITLE -->
                <div class="flex gap-2 items-center md:justify-start mb-5">
                    <h3 class="text-2xl font-semibold text-green-600">
                    Industry Experience
                    </h3>
                    <BriefcaseBusiness class="w-5 h-5 transition-all duration-300 hover:-translate-y-1 text-green-600"/>
                </div>

                <div class="flex flex-col justify-center">
                    <h3 class="mb-3 font-xl">
                        Software Engineer
                    </h3>
                    <p class="mb-3">
                        Time and Data Systems International Ltd. (TDSi) 2023-Present
                    </p>

                    <p class="mb-3">
                        Doing lots of coding mate.
                    </p>
                </div>
            </div>

            <!-- Education SIDE -->
            <div class="lg:w-1/2 w-full">
                <!-- TITLE -->
                <div class="flex gap-2 items-center md:justify-start mb-5">
                    <h3 class="text-2xl font-semibold text-green-600">
                    Education
                    </h3>
                    <GraduationCap class="w-5 h-5 transition-all duration-300 hover:-translate-y-1 text-green-600"/>
                </div>

                <div class="flex flex-col justify-center">
                    <h3 class="mb-3 font-xl">
                        BSc Hons Software Engineering
                    </h3>
                    <p class="mb-3">
                        Bournemouth University  2021-2025
                    </p>

                    <p class="mb-3">
                        Also Doing lots of coding mate.
                    </p>
                </div>
            </div>

        </div>


    </div>
  </section>
</template>