<template>
  <div class="min-h-screen flex flex-col relative">
    <!-- Ambient background effects -->
    <div class="fixed inset-0 pointer-events-none">
      <div class="absolute top-0 left-1/4 w-96 h-96 bg-[#D4A843] rounded-full mix-blend-multiply filter blur-[128px] opacity-[0.04]" />
      <div class="absolute top-1/3 right-1/4 w-96 h-96 bg-[#00B4D8] rounded-full mix-blend-multiply filter blur-[128px] opacity-[0.03]" />
      <div class="absolute bottom-1/4 left-1/3 w-96 h-96 bg-[#FF6B6B] rounded-full mix-blend-multiply filter blur-[128px] opacity-[0.02]" />
    </div>

    <!-- Header -->
    <header class="relative z-50 border-b border-white/[0.06]">
      <nav class="max-w-5xl mx-auto px-6 py-5 flex items-center justify-between">
        <NuxtLink to="/" class="flex items-center gap-2 group">
          <span class="text-2xl">🐾</span>
          <span class="text-xl font-bold tracking-tight">
            <span class="text-gradient-gold">Animal</span>
            <span class="text-white/50"> Secrets</span>
          </span>
        </NuxtLink>
        <div class="flex items-center gap-1">
          <NuxtLink to="/" class="px-4 py-2 text-sm text-white/50 hover:text-[#D4A843] transition-colors duration-200 rounded-lg hover:bg-white/[0.03]">
            Home
          </NuxtLink>
          <NuxtLink to="/Dolphins" class="px-4 py-2 text-sm text-white/50 hover:text-[#00B4D8] transition-colors duration-200 rounded-lg hover:bg-white/[0.03]">
            Dolphins
          </NuxtLink>
          <NuxtLink to="/Assholes" class="px-4 py-2 text-sm text-white/50 hover:text-[#FF6B6B] transition-colors duration-200 rounded-lg hover:bg-white/[0.03]">
            Ocean
          </NuxtLink>
        </div>
      </nav>
    </header>

    <!-- Main Content -->
    <main class="flex-1 relative z-10">
      <NuxtPage />
    </main>

    <!-- Footer -->
    <footer class="relative z-10 border-t border-white/[0.04] py-8 text-center">
      <p class="text-white/20 text-xs tracking-widest uppercase">
        Made with 🐴 intelligence, 🐬 chaos & 🥒 sea cucumbers — 2026
      </p>
    </footer>
  </div>
</template>