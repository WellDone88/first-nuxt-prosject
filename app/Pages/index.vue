<template>
  <div class="max-w-3xl mx-auto px-6 py-20 flex flex-col items-center fade-in">
    <!-- Hero Section -->
    <div class="text-center mb-20">
      <div class="text-6xl mb-8">🫏</div>
      <h1 class="text-5xl md:text-6xl font-black tracking-tight leading-[1.1] mb-6" style="font-family: 'Playfair Display', serif;">
        <span class="text-gradient-gold">The Myth of</span>
        <br />
        <span class="text-white/90">the "Stubborn"</span>
        <br />
        <span class="text-gradient-gold">Donkey</span>
      </h1>
      <div class="divider max-w-xs mx-auto" />
      <p class="text-white/40 text-sm tracking-widest uppercase">For centuries, misunderstood</p>
    </div>

    <!-- Content Card -->
    <article class="glass-card glow-gold p-8 md:p-12 space-y-8 w-full">
      <p class="text-lg leading-relaxed text-white/75 text-center">
        For centuries, humans have called donkeys stubborn. But here is the truth:
      </p>

      <div class="glass-card bg-[#D4A843]/8 border-[#D4A843]/25 p-6">
        <p class="text-[#D4A843] font-semibold text-sm tracking-wider uppercase mb-2 text-center">The Truth</p>
        <p class="text-white/90 text-lg leading-relaxed text-center">
          Donkeys aren't stubborn — they are just vastly more intelligent than us.
        </p>
      </div>

      <p class="text-lg leading-relaxed text-white/75 text-center">
        When a horse sees a scary plastic bag, it panics and runs away at
        <span class="text-[#FF6B6B] font-bold">Mach 5</span>.
        A donkey, however, operates on a completely different wavelength.
        It plants all four hooves firmly into the dirt and
        <span class="italic text-white/60">engages its brain</span>.
      </p>

      <div class="glass-card bg-[#D4A843]/8 border-[#D4A843]/25 p-6">
        <div class="flex items-start gap-3 justify-center">
          <span class="text-2xl mt-1">🧠</span>
          <div>
            <p class="text-[#D4A843] font-semibold text-sm tracking-wider uppercase mb-2">Donkey Logic</p>
            <p class="text-white/70 italic leading-relaxed">
              "What is that? Is it a trap? Why is the human walking toward it?
              The human is an idiot. I am staying right here until I calculate
              the exact risk percentage."
            </p>
          </div>
        </div>
      </div>

      <p class="text-lg leading-relaxed text-white/75 text-center">
        This is a brilliant survival mechanism called the
        <span class="text-[#D4A843] font-semibold">freeze response</span>.
        Donkeys evolved in rocky deserts where running away blindly meant
        falling off a cliff. Stopping to think was literally the difference
        between life and death.
      </p>

      <div class="divider" />

      <div class="text-center">
        <p class="text-2xl md:text-3xl font-bold text-gradient-gold leading-relaxed" style="font-family: 'Playfair Display', serif;">
          We should all be a little more like the donkey.<br />
          <span class="text-white/60 text-lg">Stop. Think. Ignore the screaming human.</span>
        </p>
      </div>
    </article>

    <!-- Navigation Buttons -->
    <div class="flex justify-center gap-4 mt-12">
      <NuxtLink to="/Dolphins"
        class="btn-primary px-8 py-4 bg-[#0077B6]/15 border border-[#00B4D8]/40 text-[#00B4D8] rounded-xl
               hover:bg-[#0077B6]/25 hover:border-[#00B4D8]/60 transition-all duration-300 font-medium"
      >
        🐬 Dolphins |
      </NuxtLink>
      <NuxtLink to="/Assholes"
        class="btn-primary px-8 py-4 bg-[#FF6B6B]/15 border border-[#FF6B6B]/40 text-[#FF6B6B] rounded-xl
               hover:bg-[#FF6B6B]/25 hover:border-[#FF6B6B]/60 transition-all duration-300 font-medium"
      >
        🥒 Ocean Life
      </NuxtLink>
    </div>
  </div>
</template>
