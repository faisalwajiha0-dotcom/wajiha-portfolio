<template>
  <div class="min-h-screen bg-[#080B14] text-white">
    <!-- Services Section -->
    <section class="relative overflow-hidden px-6 pb-24 pt-32 lg:px-8">
      <!-- Background Glow -->
      <div
        class="absolute left-1/4 top-20 h-72 w-72 rounded-full bg-purple-500/10 blur-3xl" />

      <div
        class="absolute right-1/4 top-40 h-72 w-72 rounded-full bg-cyan-400/10 blur-3xl" />

      <!-- Heading -->
      <div class="relative mx-auto max-w-7xl text-center">
        <h1 class="text-4xl font-bold sm:text-5xl">
          My
          <span
            class="bg-linear-to-r from-purple-500 to-cyan-400 bg-clip-text text-transparent">
            Services
          </span>
        </h1>

        <p class="mx-auto mt-5 max-w-2xl text-gray-400">
          I provide modern, responsive and user-friendly web solutions
          designed to help businesses build a strong online presence.
        </p>
      </div>

      <!-- Service Cards -->
      <div
        class="relative mx-auto mt-16 grid max-w-7xl gap-8 md:grid-cols-2 lg:grid-cols-3">
        <!-- UI/UX Design -->
        <div
          class="group rounded-2xl border border-white/5 bg-[#0B1220] px-7 py-10 text-center
        transition-all duration-300
        hover:-translate-y-2
        hover:border-cyan-400/30
        hover:shadow-[0_0_45px_rgba(34,211,238,0.55)]">
          <div
            class="mx-auto mb-6 flex h-16 w-16 items-center justify-center rounded-2xl
          bg-linear-to-br from-purple-500/20 to-cyan-400/20
          text-3xl transition-transform duration-300
          group-hover:scale-110">
            🎨
          </div>

          <h2 class="text-2xl font-semibold">
            UI/UX Design
          </h2>

          <p class="mt-5 leading-7 text-gray-400">
            I create clean and modern UI/UX designs that are
            user-friendly, attractive and easy to navigate.
          </p>
        </div>

        <!-- Web Development -->
        <div
          class="group rounded-2xl border border-white/5 bg-[#0B1220] px-7 py-10 text-center
        transition-all duration-300
        hover:-translate-y-2
        hover:border-purple-400/30
        hover:shadow-[0_0_45px_rgba(139,92,246,0.55)]">
          <div
            class="mx-auto mb-6 flex h-16 w-16 items-center justify-center rounded-2xl
          bg-linear-to-br from-purple-500/20 to-cyan-400/20
          text-3xl transition-transform duration-300
          group-hover:scale-110">
            💻
          </div>

          <h2 class="text-2xl font-semibold">
            Web Development
          </h2>

          <p class="mt-5 leading-7 text-gray-400">
            I build responsive and modern websites using technologies
            like Nuxt.js, Vue.js, JavaScript and Tailwind CSS.
          </p>
        </div>

        <!-- Domain & Deployment -->
        <div
          class="group rounded-2xl border border-white/5 bg-[#0B1220] px-7 py-10 text-center
        transition-all duration-300
        hover:-translate-y-2
        hover:border-cyan-400/30
        hover:shadow-[0_0_45px_rgba(34,211,238,0.55)]">
          <div
            class="mx-auto mb-6 flex h-16 w-16 items-center justify-center rounded-2xl
          bg-linear-to-br from-purple-500/20 to-cyan-400/20
          text-3xl transition-transform duration-300
          group-hover:scale-110">
            🌐
          </div>

          <h2 class="text-2xl font-semibold">
            Domain & Deployment
          </h2>

          <p class="mt-5 leading-7 text-gray-400">
            I help connect domains, configure hosting and deploy
            websites so they can go live smoothly on the internet.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>
