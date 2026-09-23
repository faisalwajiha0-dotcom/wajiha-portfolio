<template>
  <div class="min-h-screen bg-[#080B14] text-white">
    <!-- Navbar -->
    <header
      class="fixed left-0 right-0 top-0 z-50 border-b border-white/5 bg-[#080B14]/90 backdrop-blur-xl">
      <nav
        class="mx-auto flex max-w-7xl items-center justify-between px-6 py-3.5 lg:px-8">
        <!-- Logo -->
        <NuxtLink to="/" class="text-2xl font-bold tracking-tight">
          Wajiha<span class="text-[#8B5CF6]">.</span>
        </NuxtLink>

        <!-- Navigation -->
        <div class="hidden items-center gap-8 md:flex">
          <NuxtLink
            to="/"
            class="text-sm text-slate-300 transition hover:text-white">
            Home
          </NuxtLink>

          <NuxtLink
            to="/about"
            class="text-sm text-slate-300 transition hover:text-white">
            About
          </NuxtLink>

          <NuxtLink
            to="/services"
            class="text-sm text-slate-300 transition hover:text-white">
            Services
          </NuxtLink>

          <NuxtLink
            to="/skills"
            class="text-sm text-slate-300 transition hover:text-white">
            Skills
          </NuxtLink>

          <NuxtLink
            to="/projects"
            class="text-sm text-slate-300 transition hover:text-white">
            Projects
          </NuxtLink>

          <NuxtLink
            to="/contact"
            class="text-sm text-slate-300 transition hover:text-white">
            Contact
          </NuxtLink>
        </div>

        <!-- CTA -->
        <NuxtLink
          to="/contact"
          class="hidden rounded-full bg-linear-to-r from-[#8B5CF6] to-[#06B6D4] px-5 py-2 text-sm font-semibold transition duration-300 hover:scale-105 md:block">
          Let's Talk
        </NuxtLink>
      </nav>
    </header>

    <!-- Page Content -->
    <main>
      <NuxtPage />
    </main>
  </div>
</template>
