<template>
  <div class="min-h-screen bg-[#080B14] text-white">
    <!-- Background Glows -->
    <div
      class="pointer-events-none fixed left-0 top-40 -z-10 h-80 w-80 rounded-full bg-[#8B5CF6]/10 blur-[120px]" />

    <div
      class="pointer-events-none fixed right-0 top-72 -z-10 h-80 w-80 rounded-full bg-[#22D3EE]/10 blur-[120px]" />

    <!-- Hero -->
    <section class="px-6 pb-12 pt-32 lg:px-8">
      <div class="mx-auto max-w-7xl text-center">
        <p
          class="mb-3 text-sm font-semibold uppercase tracking-[0.25em] text-[#22D3EE]">
          Get In Touch
        </p>

        <h1
          class="bg-linear-to-r from-white via-[#8B5CF6] to-[#22D3EE] bg-clip-text text-4xl font-bold text-transparent sm:text-5xl lg:text-6xl">
          Let's Work Together
        </h1>

        <p class="mx-auto mt-5 max-w-2xl text-base leading-7 text-gray-400 sm:text-lg">
          Have a project in mind or want to discuss a website?
          Send me a message and I'll get back to you.
        </p>
      </div>
    </section>

    <!-- Contact Section -->
    <section class="px-6 pb-24 lg:px-8">
      <div
        class="mx-auto grid max-w-7xl gap-8 lg:grid-cols-[0.8fr_1.2fr]">
        <!-- Contact Information -->
        <div
          class="relative overflow-hidden rounded-3xl border border-white/10 bg-[#0B1220] p-8">
          <!-- Glow -->
          <div
            class="absolute -right-20 -top-20 h-52 w-52 rounded-full bg-[#8B5CF6]/10 blur-[80px]" />

          <div class="relative">
            <p
              class="text-sm font-semibold uppercase tracking-wider text-[#8B5CF6]">
              Contact Me
            </p>

            <h2 class="mt-3 text-3xl font-bold text-white">
              Let's talk about your idea.
            </h2>

            <p class="mt-4 leading-7 text-gray-400">
              Whether you need a modern website, dashboard, or
              e-commerce experience, I'd love to hear about your project.
            </p>

            <!-- Email -->
            <div
              class="mt-8 flex items-center gap-4 rounded-2xl border border-white/10 bg-white/3 p-4 transition duration-300 hover:border-[#22D3EE]/40 hover:bg-white/5">
              <div
                class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-[#22D3EE]/10 text-xl text-[#22D3EE]">
                ✉
              </div>

              <div>
                <p class="text-sm text-gray-500">
                  Email
                </p>

                <a
                  href="mailto:your-email@example.com"
                  class="break-all text-sm font-medium text-white transition hover:text-[#22D3EE]">
                  your-email@example.com
                </a>
              </div>
            </div>

            <!-- Availability -->
            <div
              class="mt-4 flex items-center gap-4 rounded-2xl border border-white/10 bg-white/3 p-4 transition duration-300 hover:border-[#8B5CF6]/40 hover:bg-white/5">
              <div
                class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-[#8B5CF6]/10 text-xl text-[#8B5CF6]">
                ✓
              </div>

              <div>
                <p class="text-sm text-gray-500">
                  Availability
                </p>

                <p class="text-sm font-medium text-white">
                  Available for new projects
                </p>
              </div>
            </div>

            <!-- Response -->
            <div
              class="mt-4 flex items-center gap-4 rounded-2xl border border-white/10 bg-white/3 p-4">
              <div
                class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-[#8B5CF6]/10 text-xl">
                ⚡
              </div>

              <div>
                <p class="text-sm text-gray-500">
                  Response
                </p>

                <p class="text-sm font-medium text-white">
                  I'll get back to you soon
                </p>
              </div>
            </div>

            <!-- Social Links -->
            <div class="mt-8">
              <p class="mb-4 text-sm font-semibold text-gray-300">
                Connect with me
              </p>

              <div class="flex gap-3">
                <a
                  href="#"
                  aria-label="LinkedIn"
                  class="flex h-11 w-11 items-center justify-center rounded-xl border border-white/10 bg-white/3 font-bold text-gray-400 transition duration-300 hover:-translate-y-1 hover:border-[#8B5CF6]/50 hover:text-[#8B5CF6]">
                  in
                </a>

                <a
                  href="#"
                  aria-label="Fiverr"
                  class="flex h-11 w-11 items-center justify-center rounded-xl border border-white/10 bg-white/3 font-bold text-gray-400 transition duration-300 hover:-translate-y-1 hover:border-[#22D3EE]/50 hover:text-[#22D3EE]">
                  F
                </a>

                <a
                  href="#"
                  aria-label="GitHub"
                  class="flex h-11 w-11 items-center justify-center rounded-xl border border-white/10 bg-white/3 font-bold text-gray-400 transition duration-300 hover:-translate-y-1 hover:border-[#8B5CF6]/50 hover:text-white">
                  G
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Contact Form -->
        <div
          class="rounded-3xl border border-white/10 bg-[#0B1220] p-6 sm:p-8">
          <div class="mb-7">
            <p
              class="text-sm font-semibold uppercase tracking-wider text-[#22D3EE]">
              Send a Message
            </p>

            <h2 class="mt-2 text-3xl font-bold text-white">
              Tell me about your project
            </h2>

            <p class="mt-2 text-sm leading-6 text-gray-400">
              Fill out the form below and I'll receive your message.
            </p>
          </div>

          <!-- Netlify Contact Form -->
          <form
            name="contact"
            method="POST"
            data-netlify="true"
            data-netlify-honeypot="bot-field"
            action="/contact"
            class="space-y-5">
            <!-- Required by Netlify -->
            <input
              type="hidden"
              name="form-name"
              value="contact">

            <!-- Honeypot -->
            <p class="hidden">
              <label>
                Don't fill this out:
                <input name="bot-field">
              </label>
            </p>

            <!-- Name -->
            <div>
              <label
                for="name"
                class="mb-2 block text-sm font-medium text-gray-300">
                Your Name
              </label>

              <input
                id="name"
                type="text"
                name="name"
                placeholder="Enter your name"
                required
                class="w-full rounded-xl border border-white/10 bg-[#080B14] px-4 py-3.5 text-white outline-none transition placeholder:text-gray-600 focus:border-[#8B5CF6] focus:ring-2 focus:ring-[#8B5CF6]/20">
            </div>

            <!-- Email -->
            <div>
              <label
                for="email"
                class="mb-2 block text-sm font-medium text-gray-300">
                Email Address
              </label>

              <input
                id="email"
                type="email"
                name="email"
                placeholder="your@email.com"
                required
                class="w-full rounded-xl border border-white/10 bg-[#080B14] px-4 py-3.5 text-white outline-none transition placeholder:text-gray-600 focus:border-[#22D3EE] focus:ring-2 focus:ring-[#22D3EE]/20">
            </div>

            <!-- Subject -->
            <div>
              <label
                for="subject"
                class="mb-2 block text-sm font-medium text-gray-300">
                Subject
              </label>

              <input
                id="subject"
                type="text"
                name="subject"
                placeholder="What would you like to discuss?"
                required
                class="w-full rounded-xl border border-white/10 bg-[#080B14] px-4 py-3.5 text-white outline-none transition placeholder:text-gray-600 focus:border-[#8B5CF6] focus:ring-2 focus:ring-[#8B5CF6]/20">
            </div>

            <!-- Message -->
            <div>
              <label
                for="message"
                class="mb-2 block text-sm font-medium text-gray-300">
                Your Message
              </label>

              <textarea
                id="message"
                name="message"
                rows="6"
                placeholder="Tell me a little about your project..."
                required
                class="w-full resize-none rounded-xl border border-white/10 bg-[#080B14] px-4 py-3.5 text-white outline-none transition placeholder:text-gray-600 focus:border-[#22D3EE] focus:ring-2 focus:ring-[#22D3EE]/20" />
            </div>

            <!-- Submit -->
            <button
              type="submit"
              class="group flex w-full items-center justify-center gap-2 rounded-xl bg-linear-to-r from-[#8B5CF6] to-[#22D3EE] px-6 py-3.5 font-semibold text-white transition duration-300 hover:scale-[1.02] hover:shadow-[0_0_30px_rgba(139,92,246,0.35)]">
              Send Message

              <span
                class="transition-transform duration-300 group-hover:translate-x-1">
                →
              </span>
            </button>
          </form>
        </div>
      </div>
    </section>

    <!-- Bottom CTA -->
    <section class="px-6 pb-24 lg:px-8">
      <div
        class="mx-auto max-w-7xl rounded-3xl border border-white/10 bg-linear-to-r from-[#111C45] to-[#21174A] px-6 py-10 text-center">
        <h2 class="text-2xl font-bold text-white sm:text-3xl">
          Have a project ready to start?
        </h2>

        <p class="mt-3 text-gray-400">
          Let's turn your idea into a modern web experience.
        </p>
      </div>
    </section>
  </div>
</template>
