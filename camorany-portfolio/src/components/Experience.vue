<script setup> 
import { GraduationCap, BriefcaseBusiness } from 'lucide-vue-next'

</script>

<template>
  <section
    id="experience" class="min-h-screen bg-gray-900 text-slate-300 flex items-center justify-center px-30 py-30"
  >

    <div
      class="max-w-7xl w-full flex flex-col gap-8 justify-center p-2"
    >

        <h1 class="text-center text-5xl font-bold text-emerald-600 mb-10">
            Experience
        </h1>

        <div class="flex flex-col lg:flex-row w-full gap-15">
            <!-- EXPERIENCE SIDE -->
            <div class="lg:w-1/2 w-full">
  
            <!-- SECTION TITLE -->
            <div class="flex gap-2 items-center mb-6">
                <h3 class="text-2xl font-semibold text-emerald-600">
                Industry Experience
                </h3>

                <BriefcaseBusiness
                class="w-5 h-5 text-emerald-600 transition-all duration-300 hover:-translate-y-1"
                />
            </div>

            <!-- EXPERIENCE CARD -->
            <div
                class="rounded-2xl border border-slate-700/60 bg-slate-900/40 backdrop-blur-sm p-7 transition-all duration-300 hover:border-emerald-500/40 hover:shadow-lg hover:shadow-emerald-500/10"
            >

                <!-- ROLE -->
                <div class="mb-5">
                <h3 class="text-2xl font-semibold text-white mb-2">
                    Software Engineer
                </h3>

                <div
                    class="inline-flex items-center gap-5 rounded-full border border-emerald-500/20 bg-emerald-500/10 px-3 py-1 text-sm text-emerald-400"
                >
                    <span class="font-bold">
                        Time and Data Systems International
                    </span>

                    <span>
                        2023 — Present
                    </span> 
                </div>
                </div>

                <!-- DESCRIPTION -->
                <div class="space-y-4 text-slate-300 leading-8">
                <p>
                    I worked for a year as a junior software developer at TDSi during my
                    Bournemouth University internship year. I developed across numerous
                    projects utilising .NET Framework, .NET Core, Node.js, and AngularJS
                    technologies to implement and maintain software solutions.
                </p>

                <p>
                    I contributed to third-party API integrations, full-stack feature
                    development, and functional unit testing for various services.
                </p>

                <p>
                    Collaborating within an agile team, I participated in sprint planning,
                    code reviews, and feature delivery to ensure efficient and high-quality
                    software development.
                </p>
                </div>
            </div>
            </div>

            <!-- EDUCATION SIDE -->
            <div class="lg:w-1/2 w-full">
  
            <!-- SECTION TITLE -->
            <div class="flex gap-2 items-center mb-6">
                <h3 class="text-2xl font-semibold text-emerald-600">
                Education
                </h3>

                <GraduationCap
                class="w-5 h-5 text-emerald-600 transition-all duration-300 hover:-translate-y-1"
                />
            </div>

            <!-- EXPERIENCE CARD -->
            <div
                class="rounded-2xl border border-slate-700/60 bg-slate-900/40 backdrop-blur-sm p-7 transition-all duration-300 hover:border-emerald-500/40 hover:shadow-lg hover:shadow-emerald-500/10"
            >

                <!-- ROLE -->
                <div class="mb-5">
                    <h3 class="text-2xl font-semibold text-white mb-2">
                        BSc Hons in Software Engineering
                    </h3>

                    <div
                        class="inline-flex gap-5 items-center rounded-full border border-emerald-500/20 bg-emerald-500/10 px-3 py-1 text-sm text-emerald-400"
                    >
                        <span class="font-bold">
                            Bournemouth University
                        </span>

                        <span>
                            2021 — 2025
                        </span>
                    </div>
                </div>

                <!-- DESCRIPTION -->
                <div class="space-y-4 text-slate-300 leading-8">
                <p>
                    I worked for a year as a junior software developer at TDSi during my
                    Bournemouth University internship year. I developed across numerous
                    projects utilising .NET Framework, .NET Core, Node.js, and AngularJS
                    technologies to implement and maintain software solutions.
                </p>

                <p>
                    I contributed to third-party API integrations, full-stack feature
                    development, and functional unit testing for various services.
                </p>

                <p>
                    Collaborating within an agile team, I participated in sprint planning,
                    code reviews, and feature delivery to ensure efficient and high-quality
                    software development.
                </p>
                </div>
            </div>
            </div>

        </div>


    </div>
  </section>
</template>