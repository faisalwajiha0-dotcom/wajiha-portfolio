<template>
  <div class="min-h-screen bg-[#080B14] text-white">
    <!-- Projects Hero -->
    <section class="relative overflow-hidden px-6 pb-16 pt-32 lg:px-8">
      <!-- Background Glow -->
      <div
        class="absolute left-1/2 top-10 -z-10 h-72 w-72 -translate-x-1/2 rounded-full bg-[#8B5CF6]/20 blur-[120px]" />

      <div
        class="absolute right-10 top-40 -z-10 h-64 w-64 rounded-full bg-[#22D3EE]/10 blur-[120px]" />

      <div class="mx-auto max-w-7xl text-center">
        <h1
          class="bg-linear-to-r from-white via-[#8B5CF6] to-[#22D3EE] bg-clip-text text-4xl font-bold text-transparent sm:text-5xl lg:text-6xl">
          My Projects
        </h1>

        <p class="mx-auto mt-5 max-w-2xl text-base leading-7 text-gray-400 sm:text-lg">
          Here are some of the projects I have built while learning and
          improving my web development skills.
        </p>
      </div>
    </section>

    <!-- Projects -->
    <section class="px-6 pb-24 lg:px-8">
      <div class="mx-auto grid max-w-7xl grid-cols-1 gap-7 md:grid-cols-2 lg:grid-cols-3">
        <!-- ================= Smart Shop ================= -->
        <article
          class="group overflow-hidden rounded-2xl border border-white/10 bg-[#0B1220] transition-all duration-500 hover:-translate-y-2 hover:border-[#22D3EE]/40 hover:shadow-[0_0_45px_rgba(34,211,238,0.25)]">
          <!-- Project Image -->
          <div class="relative overflow-hidden">
            <img
              src="/images/smart-shop.png"
              alt="Smart Shop project"
              class="h-48 w-full object-cover object-top transition duration-700 group-hover:scale-105">

            <!-- Image Overlay -->
            <div
              class="absolute inset-0 bg-gradient-to-t from-[#0B1220] via-transparent to-transparent opacity-70" />
          </div>

          <!-- Content -->
          <div class="p-5">
            <p
              class="mb-2 text-xs font-semibold uppercase tracking-wider text-[#22D3EE]">
              E-Commerce
            </p>

            <h2 class="text-xl font-bold text-white">
              Smart Shop
            </h2>

            <p class="mt-3 min-h-[72px] text-sm leading-6 text-gray-400">
              A modern and responsive e-commerce website with product
              browsing, categories, cart and checkout features.
            </p>

            <a
              href="https://smart-shop-store.netlify.app/"
              target="_blank"
              rel="noopener noreferrer"
              class="mt-5 inline-flex items-center gap-2 rounded-lg bg-linear-to-r from-[#8B5CF6] to-[#22D3EE] px-4 py-2.5 text-sm font-semibold text-white transition-all duration-300 hover:scale-105 hover:shadow-[0_0_20px_rgba(139,92,246,0.45)]">
              Live Demo
              <span>→</span>
            </a>
          </div>
        </article>

        <!-- ================= BizFlow ================= -->
        <article
          class="group overflow-hidden rounded-2xl border border-white/10 bg-[#0B1220] transition-all duration-500 hover:-translate-y-2 hover:border-[#8B5CF6]/50 hover:shadow-[0_0_45px_rgba(139,92,246,0.25)]">
          <!-- Project Image -->
          <div class="relative overflow-hidden">
            <img
              src="/images/bizflow.png"
              alt="BizFlow Dashboard project"
              class="h-48 w-full object-cover object-top transition duration-700 group-hover:scale-105">

            <!-- Image Overlay -->
            <div
              class="absolute inset-0 bg-gradient-to-t from-[#0B1220] via-transparent to-transparent opacity-70" />
          </div>

          <!-- Content -->
          <div class="p-5">
            <p
              class="mb-2 text-xs font-semibold uppercase tracking-wider text-[#8B5CF6]">
              Business Dashboard
            </p>

            <h2 class="text-xl font-bold text-white">
              BizFlow Dashboard
            </h2>

            <p class="mt-3 min-h-[72px] text-sm leading-6 text-gray-400">
              A modern business dashboard for managing products, orders,
              customers, analytics and overall business performance.
            </p>

            <a
              href="https://bizflow-dashboard.netlify.app/"
              target="_blank"
              rel="noopener noreferrer"
              class="mt-5 inline-flex items-center gap-2 rounded-lg bg-linear-to-r from-[#8B5CF6] to-[#22D3EE] px-4 py-2.5 text-sm font-semibold text-white transition-all duration-300 hover:scale-105 hover:shadow-[0_0_20px_rgba(139,92,246,0.45)]">
              Live Demo
              <span>→</span>
            </a>
          </div>
        </article>

        <!-- ================= Portfolio ================= -->
        <article
          class="group overflow-hidden rounded-2xl border border-white/10 bg-[#0B1220] transition-all duration-500 hover:-translate-y-2 hover:border-[#22D3EE]/40 hover:shadow-[0_0_45px_rgba(34,211,238,0.25)]">
          <!-- Project Image -->
          <div class="relative overflow-hidden">
            <img
              src="/images/portfolio.png"
              alt="Personal portfolio project"
              class="h-48 w-full object-cover object-top transition duration-700 group-hover:scale-105">

            <!-- Image Overlay -->
            <div
              class="absolute inset-0 bg-gradient-to-t from-[#0B1220] via-transparent to-transparent opacity-70" />
          </div>

          <!-- Content -->
          <div class="p-5">
            <p
              class="mb-2 text-xs font-semibold uppercase tracking-wider text-[#22D3EE]">
              Web Development
            </p>

            <h2 class="text-xl font-bold text-white">
              Personal Portfolio
            </h2>

            <p class="mt-3 min-h-[72px] text-sm leading-6 text-gray-400">
              A modern personal portfolio website showcasing my skills,
              services, projects and web development experience.
            </p>

            <a
              href="#"
              class="mt-5 inline-flex items-center gap-2 rounded-lg bg-linear-to-r from-[#8B5CF6] to-[#22D3EE] px-4 py-2.5 text-sm font-semibold text-white transition-all duration-300 hover:scale-105 hover:shadow-[0_0_20px_rgba(139,92,246,0.45)]">
              View Portfolio
              <span>→</span>
            </a>
          </div>
        </article>
      </div>
    </section>
  </div>
</template>
