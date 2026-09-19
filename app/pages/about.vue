<template>
  <div class="min-h-screen bg-[#080B14] text-white">
    <!-- About Hero -->
    <section class="relative overflow-hidden px-6 pb-20 pt-32 lg:px-8">
      <!-- Background Glows -->
      <div
        class="absolute left-10 top-20 h-72 w-72 rounded-full bg-[#8B5CF6]/10 blur-[120px]" />

      <div
        class="absolute right-10 top-40 h-72 w-72 rounded-full bg-[#06B6D4]/10 blur-[120px]" />

      <div class="relative mx-auto max-w-7xl">
        <!-- Small Heading -->
        <div class="mb-12 text-center">
          <h1 class="text-4xl font-bold sm:text-5xl">
            About
            <span
              class="bg-linear-to-r from-[#8B5CF6] to-[#06B6D4] bg-clip-text text-transparent">
              Me
            </span>
          </h1>

          <p class="mx-auto mt-4 max-w-2xl text-slate-400">
            A little about my journey, skills and passion for creating
            modern web experiences.
          </p>
        </div>

        <!-- Main About -->
        <div class="grid items-center gap-14 lg:grid-cols-2">
          <!-- LEFT : Certificate -->
          <div class="relative">
            <!-- Glow -->
            <div
              class="absolute -inset-4 rounded-3xl bg-linear-to-r from-[#8B5CF6]/20 to-[#06B6D4]/20 blur-2xl" />

            <!-- Image Card -->
            <div
              class="relative overflow-hidden rounded-3xl border border-white/10 bg-[#111827] p-3 shadow-2xl shadow-black/30">
              <img
                src="/certificate.jpg"
                alt="Web Development Certificate"
                class="h-80 w-full rounded-2xl object-cover transition duration-500 hover:scale-[1.02] sm:h-100">
            </div>
          </div>

          <!-- RIGHT : About Me -->
          <div>
            <p
              class="mb-3 text-sm font-semibold uppercase tracking-[0.2em] text-[#8B5CF6]">
              Who I Am👀
            </p>

            <h2 class="text-3xl font-bold leading-tight sm:text-4xl">
              Building websites with
              <span
                class="bg-linear-to-r from-[#8B5CF6] to-[#06B6D4] bg-clip-text text-transparent">
                purpose & creativity.
              </span>
            </h2>

            <p class="mt-6 leading-8 text-slate-400">
              I'm Wajiha, a passionate web developer who enjoys turning
              ideas into modern, responsive and user-friendly websites.
              I love creating interfaces that are not only visually
              attractive but also simple and enjoyable to use.
            </p>

            <p class="mt-4 leading-8 text-slate-400">
              My main focus is modern frontend development using Vue.js,
              Nuxt.js, JavaScript and Tailwind CSS. I'm continuously
              learning new technologies and improving my development
              skills by building real-world projects.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Who I Am -->
    <section class="border-t border-white/5 px-6 py-24 lg:px-8">
      <div class="mx-auto max-w-7xl">
        <div class="grid gap-12 lg:grid-cols-2">
          <!-- Text -->
          <div>
            <h2 class="text-3xl font-bold sm:text-4xl">
              Who I Am 👀
            </h2>

            <p class="mt-6 leading-8 text-slate-400">
              I started my web development journey by learning the
              fundamentals of HTML, CSS and JavaScript. With time,
              I moved toward modern tools like Tailwind CSS, Vue.js
              and Nuxt.js.
            </p>

            <p class="mt-4 leading-8 text-slate-400">
              Building projects has helped me understand how real
              websites are structured, how users interact with them,
              and how design and functionality work together.
            </p>

            <p class="mt-4 leading-8 text-slate-400">
              My goal is to keep improving as a developer and create
              websites that help businesses, individuals and brands
              build a strong online presence.
            </p>
          </div>

          <!-- What I Can Do -->
          <div>
            <p class="mb-6 text-lg font-semibold text-white">
              What I Can Help You With
            </p>

            <div class="space-y-4">
              <!-- Business -->
              <div
                class="group flex items-center gap-5 rounded-2xl border border-white/10 bg-[#101522] p-5 transition duration-300 hover:-translate-y-1 hover:border-[#8B5CF6]/40">
                <div
                  class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-[#8B5CF6]/10 text-xl">
                  💻
                </div>

                <div>
                  <h3 class="font-semibold">
                    Business Websites
                  </h3>

                  <p class="mt-1 text-sm text-slate-500">
                    Modern websites for businesses and brands.
                  </p>
                </div>
              </div>

              <!-- Landing Pages -->
              <div
                class="group flex items-center gap-5 rounded-2xl border border-white/10 bg-[#101522] p-5 transition duration-300 hover:-translate-y-1 hover:border-[#06B6D4]/40">
                <div
                  class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-[#06B6D4]/10 text-xl">
                  🎨
                </div>

                <div>
                  <h3 class="font-semibold">
                    Landing Pages
                  </h3>

                  <p class="mt-1 text-sm text-slate-500">
                    Attractive and responsive landing pages.
                  </p>
                </div>
              </div>

              <!-- Responsive -->
              <div
                class="group flex items-center gap-5 rounded-2xl border border-white/10 bg-[#101522] p-5 transition duration-300 hover:-translate-y-1 hover:border-pink-500/40">
                <div
                  class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-pink-500/10 text-xl">
                  📱
                </div>

                <div>
                  <h3 class="font-semibold">
                    Responsive Web Design
                  </h3>

                  <p class="mt-1 text-sm text-slate-500">
                    Websites that work smoothly on every screen.
                  </p>
                </div>
              </div>

              <!-- E-commerce -->
              <div
                class="group flex items-center gap-5 rounded-2xl border border-white/10 bg-[#101522] p-5 transition duration-300 hover:-translate-y-1 hover:border-[#8B5CF6]/40">
                <div
                  class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-[#8B5CF6]/10 text-xl">
                  🛒
                </div>

                <div>
                  <h3 class="font-semibold">
                    E-commerce Interfaces
                  </h3>

                  <p class="mt-1 text-sm text-slate-500">
                    Clean and user-friendly online store interfaces.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.skill-badge {
  border-radius: 9999px;
  border: 1px solid rgba(255, 255, 255, 0.1);
  background-color: rgba(255, 255, 255, 0.03);
  padding: 0.75rem 1.5rem;
  font-size: 0.875rem;
  font-weight: 500;
  color: rgb(148, 163, 184);
  transition-duration: 300ms;
}

.skill-badge:hover {
  border-color: rgba(139, 92, 246, 0.5);
  background-color: rgba(139, 92, 246, 0.1);
  color: white;
}
</style>
