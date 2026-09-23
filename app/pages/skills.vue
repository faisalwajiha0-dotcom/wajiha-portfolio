<template>
  <div class="min-h-screen bg-[#080B14] text-white">
    <section class="relative overflow-hidden px-6 pb-24 pt-28 lg:px-8">
      <!-- Background Glows -->
      <div
        class="pointer-events-none absolute left-10 top-32 h-72 w-72 rounded-full bg-purple-500/10 blur-3xl" />

      <div
        class="pointer-events-none absolute right-10 top-52 h-72 w-72 rounded-full bg-cyan-400/10 blur-3xl" />

      <!-- Heading -->
      <div class="relative mx-auto max-w-7xl text-center">
        <h1 class="text-4xl font-bold sm:text-5xl">
          My
          <span
            class="bg-linear-to-r from-purple-500 to-cyan-400 bg-clip-text text-transparent">
            Skills
          </span>
        </h1>

        <p class="mx-auto mt-5 max-w-2xl text-gray-400">
          The technologies and professional skills I use to create
          modern and user-friendly web experiences.
        </p>
      </div>

      <!-- Main Skills Area -->
      <div
        class="relative mx-auto mt-16 grid max-w-7xl gap-16 lg:grid-cols-2">
        <!-- Technical Skills -->
        <div>
          <h2 class="mb-10 text-xl font-semibold">
            Technical
            <span
              class="bg-linear-to-r from-purple-500 to-cyan-400 bg-clip-text text-transparent">
              Skills
            </span>
          </h2>

          <!-- HTML -->
          <div class="mb-7">
            <div class="mb-1 flex items-center justify-between">
              <span class="text-lg font-medium">HTML</span>
              <span class="font-medium text-cyan-400">90%</span>
            </div>

            <div class="h-2 overflow-hidden rounded-full bg-black/70">
              <div
                class="h-full rounded-full bg-linear-to-r from-purple-500 to-cyan-400"
                style="width: 90%" />
            </div>
          </div>

          <!-- CSS -->
          <div class="mb-7">
            <div class="mb-1 flex items-center justify-between">
              <span class="text-lg font-medium">CSS</span>
              <span class="font-medium text-cyan-400">85%</span>
            </div>

            <div class="h-2 overflow-hidden rounded-full bg-black/70">
              <div
                class="h-full rounded-full bg-linear-to-r from-purple-500 to-cyan-400"
                style="width: 85%" />
            </div>
          </div>

          <!-- JavaScript -->
          <div class="mb-7">
            <div class="mb-1 flex items-center justify-between">
              <span class="text-lg font-medium">JavaScript</span>
              <span class="font-medium text-cyan-400">80%</span>
            </div>

            <div class="h-2 overflow-hidden rounded-full bg-black/70">
              <div
                class="h-full rounded-full bg-linear-to-r from-purple-500 to-cyan-400"
                style="width: 80%" />
            </div>
          </div>

          <!-- Tailwind CSS -->
          <div class="mb-7">
            <div class="mb-1 flex items-center justify-between">
              <span class="text-lg font-medium">Tailwind CSS</span>
              <span class="font-medium text-cyan-400">85%</span>
            </div>

            <div class="h-2 overflow-hidden rounded-full bg-black/70">
              <div
                class="h-full rounded-full bg-linear-to-r from-purple-500 to-cyan-400"
                style="width: 85%" />
            </div>
          </div>

          <!-- Vue / Nuxt -->
          <div>
            <div class="mb-3 flex items-center justify-between">
              <span class="text-lg font-medium">Vue / Nuxt</span>
              <span class="font-medium text-cyan-400">75%</span>
            </div>

            <div class="h-2 overflow-hidden rounded-full bg-black/70">
              <div
                class="h-full rounded-full bg-linear-to-r from-purple-500 to-cyan-400"
                style="width: 75%" />
            </div>
          </div>
        </div>

        <!-- Professional Skills -->
        <div>
          <h2 class="mb-10 text-xl font-semibold">
            Professional
            <span
              class="bg-linear-to-r from-purple-500 to-cyan-400 bg-clip-text text-transparent">
              Skills
            </span>
          </h2>

          <div class="grid grid-cols-2 gap-x-8 gap-y-12">
            <!-- Creativity -->
            <div class="group text-center">
              <div
                class="mx-auto flex h-32 w-32 items-center justify-center rounded-full transition duration-300 group-hover:scale-105"
                style="background: conic-gradient(#8B5CF6 0% 90%, #111827 90% 100%)">
                <div
                  class="flex h-24 w-24 items-center justify-center rounded-full bg-[#080B14]">
                  <span class="text-xl font-semibold">90%</span>
                </div>
              </div>

              <p class="mt-5 text-lg font-medium">
                Creativity
              </p>
            </div>

            <!-- Communication -->
            <div class="group text-center">
              <div
                class="mx-auto flex h-32 w-32 items-center justify-center rounded-full transition duration-300 group-hover:scale-105"
                style="background: conic-gradient(#22D3EE 0% 65%, #111827 65% 100%)">
                <div
                  class="flex h-24 w-24 items-center justify-center rounded-full bg-[#080B14]">
                  <span class="text-xl font-semibold">65%</span>
                </div>
              </div>

              <p class="mt-5 text-lg font-medium">
                Communication
              </p>
            </div>

            <!-- Problem Solving -->
            <div class="group text-center">
              <div
                class="mx-auto flex h-32 w-32 items-center justify-center rounded-full transition duration-300 group-hover:scale-105"
                style="background: conic-gradient(#8B5CF6 0% 75%, #111827 75% 100%)">
                <div
                  class="flex h-24 w-24 items-center justify-center rounded-full bg-[#080B14]">
                  <span class="text-xl font-semibold">75%</span>
                </div>
              </div>

              <p class="mt-5 text-lg font-medium">
                Problem Solving
              </p>
            </div>

            <!-- Teamwork -->
            <div class="group text-center">
              <div
                class="mx-auto flex h-32 w-32 items-center justify-center rounded-full transition duration-300 group-hover:scale-105"
                style="background: conic-gradient(#22D3EE 0% 85%, #111827 85% 100%)">
                <div
                  class="flex h-24 w-24 items-center justify-center rounded-full bg-[#080B14]">
                  <span class="text-xl font-semibold">85%</span>
                </div>
              </div>

              <p class="mt-5 text-lg font-medium">
                Teamwork
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
