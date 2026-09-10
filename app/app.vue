<template>
  <div class="min-h-screen bg-[#080B14] text-white">
    <!-- Navbar -->
    <header
      class="fixed left-0 right-0 top-0 z-50 border-b border-white/5 bg-[#080B14]/90 backdrop-blur-xl">
      <nav
        class="mx-auto flex max-w-7xl items-center justify-between px-6 py-3.5 lg:px-8">
        <!-- Logo -->
        <a href="#" class="text-2xl font-bold tracking-tight">
          Portfolio<span class="text-[#8B5CF6]">.</span>
        </a>

        <!-- Navigation -->
        <div class="hidden items-center gap-8 md:flex">
          <a
            href="#home"
            class="text-sm text-slate-300 transition hover:text-white">
            Home
          </a>

          <a
            href="#about"
            class="text-sm text-slate-300 transition hover:text-white">
            About
          </a>

          <a
            href="#skills"
            class="text-sm text-slate-300 transition hover:text-white">
            Skills
          </a>

          <a
            href="#projects"
            class="text-sm text-slate-300 transition hover:text-white">
            Projects
          </a>

          <a
            href="#contact"
            class="text-sm text-slate-300 transition hover:text-white">
            Contact
          </a>
        </div>

        <!-- CTA -->
        <a
          href="#contact"
          class="hidden rounded-full bg-linear-to-r from-[#8B5CF6] to-[#06B6D4] px-5 py-2 text-sm font-semibold transition duration-300 hover:scale-105 md:block">
          Let's Talk
        </a>
      </nav>
    </header>

    <!-- Main -->
    <main>
      <!-- Hero -->
      <section
        id="home"
        class="relative flex min-h-screen items-center overflow-hidden pt-16">
        <!-- Background Glow -->
        <div
          class="absolute left-1/4 top-1/4 h-72 w-72 rounded-full bg-[#8B5CF6]/20 blur-[120px]" />

        <div
          class="absolute right-1/4 top-1/3 h-72 w-72 rounded-full bg-[#06B6D4]/15 blur-[120px]" />

        <!-- Hero Container -->
        <div
          class="relative mx-auto grid w-full max-w-7xl items-center gap-10 px-6 py-10 lg:grid-cols-2 lg:px-8">
          <!-- Left Content -->
          <div>
            <p class="mb-3 text-lg font-medium text-[#06B6D4]">
              Hello, It's Me 👋
            </p>

            <h1
              class="text-5xl font-bold leading-tight tracking-tight sm:text-6xl lg:text-7xl">
              Wajiha Faisal
            </h1>

            <p
              class="mt-4 max-w-2xl text-xl font-medium leading-relaxed text-[#06B6D4] sm:text-xl">
              Hi, I'm Wajiha 👋 I'm a passionate
              <span class="text-[#8B5CF6]">
                Front-End Web Developer & Full-Stack Web Developer
              </span>
            </p>

            <p
              class="mt-4 max-w-2xl text-lg leading-8 text-slate-400">
              I build modern, responsive and user-friendly websites
              and web applications using Nuxt, Vue.js, JavaScript and
              Tailwind CSS. I focus on clean design, smooth user
              experiences and quality code.
            </p>

            <!-- Buttons -->
            <div class="mt-6 flex flex-wrap gap-4">
              <a
                href="#projects"
                class="rounded-full bg-linear-to-r from-[#8B5CF6] to-[#06B6D4] px-7 py-3.5 font-semibold transition duration-300 hover:scale-105 hover:shadow-lg hover:shadow-[#8B5CF6]/25">
                View My Work
              </a>

              <a
                href="#contact"
                class="rounded-full border border-white/10 px-7 py-3.5 font-semibold text-slate-200 transition duration-300 hover:border-[#8B5CF6] hover:bg-white/5">
                Let's Talk
              </a>
            </div>
          </div>

          <!-- Right Profile -->
          <div
            class="relative flex justify-center lg:justify-end">
            <!-- Glow -->
            <div
              class="absolute h-72 w-72 rounded-full bg-linear-to-r from-[#06B6D4] via-[#8B5CF6] to-pink-500 opacity-30 blur-3xl" />

            <!-- Gradient Ring -->
            <div
              class="relative h-72 w-72 rounded-full bg-linear-to-r from-[#06B6D4] via-[#8B5CF6] to-pink-500 p-1 shadow-2xl shadow-[#06B6D4]/20 sm:h-80 sm:w-80">
              <div
                class="flex h-full w-full items-center justify-center rounded-full bg-[#111827]">
                <span
                  class="text-7xl font-bold text-white/90">
                  WF
                </span>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>
