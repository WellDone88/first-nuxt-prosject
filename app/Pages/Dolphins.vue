<template>
  <div class="max-w-3xl mx-auto px-6 py-16 fade-in">
    <!-- Hero Section -->
    <div class="text-center mb-16 slide-up">
      <div class="hero-emoji mb-6">🐬</div>
      <h1 class="text-5xl md:text-6xl font-black tracking-tight leading-[1.1] mb-4" style="font-family: 'Playfair Display', serif;">
        <span class="text-gradient-blue">The Dark Side of</span>
        <br />
        <span class="text-white/90">Dolphin Smiles</span>
      </h1>
      <div class="divider max-w-xs mx-auto" />
      <p class="text-white/40 text-sm tracking-widest uppercase">Cute face, chaotic mind</p>
    </div>

    <!-- Content Card -->
    <article class="glass-card glow-blue p-8 md:p-12 space-y-8">
      <p class="text-lg leading-relaxed text-white/75">
        Dolphins have the best PR team in the animal kingdom. We see that permanent,
        adorable grin and think, "Look at that majestic ocean angel! It just wants to
        swim with me and heal my soul."
      </p>

      <div class="glass-card bg-[#00B4D8]/5 border-[#00B4D8]/20 p-6 slide-up">
        <p class="text-[#00B4D8] font-semibold text-sm tracking-wider uppercase mb-2">The Reality</p>
        <p class="text-white/90 text-lg leading-relaxed">
          Dolphins are the frat boys of the ocean.
        </p>
      </div>

      <p class="text-lg leading-relaxed text-white/75">
        That "smile" isn't happiness; it's just how their skulls are shaped.
        Underneath that cute exterior lies a creature of pure, chaotic intelligence.
        Dolphins don't just swim — they boredom-shop for entertainment.
      </p>

      <div class="divider" />

      <p class="text-white/50 text-sm tracking-wider uppercase">Here's what dolphin behavior actually looks like:</p>

      <div class="space-y-4">
        <div class="glass-card bg-[#0077B6]/5 border-[#00B4D8]/10 p-6 flex gap-4 slide-up">
          <span class="text-3xl">🐡</span>
          <div>
            <p class="text-[#00B4D8] font-bold mb-1">Pufferfish Passing</p>
            <p class="text-white/60 leading-relaxed">
              Dolphins gently bite a toxic pufferfish and pass it around to friends.
              Why? In small doses, the toxin gets them high. They're literally
              puff-puff-passing in the reef.
            </p>
          </div>
        </div>

        <div class="glass-card bg-[#0077B6]/5 border-[#00B4D8]/10 p-6 flex gap-4 slide-up">
          <span class="text-3xl">🐦</span>
          <div>
            <p class="text-[#00B4D8] font-bold mb-1">The Seabird Slap</p>
            <p class="text-white/60 leading-relaxed">
              Caught on camera using their tails to launch unsuspecting seagulls
              into orbit. No food motivation — just pure comedic value.
            </p>
          </div>
        </div>
      </div>

      <div class="divider" />

      <div class="text-center">
        <p class="text-lg text-white/60 leading-relaxed">
          Sharks are terrifying because they want to eat you.
          <br />
          <span class="text-[#00B4D8] font-semibold">Dolphins are terrifying because they might prank you,</span>
          <br />
          laugh about it, and then go get high on a spiky fish.
        </p>
      </div>
    </article>

    <!-- Navigation Button -->
    <div class="flex justify-center mt-12 slide-up">
      <NuxtLink to="/"
        class="btn-primary px-8 py-4 bg-[#D4A843]/10 border border-[#D4A843]/30 text-[#D4A843] rounded-xl
               hover:bg-[#D4A843]/20 hover:border-[#D4A843]/50 transition-all duration-300 font-medium
               flex items-center gap-2"
      >
        <span>←</span> Back to Home
      </NuxtLink>
    </div>
  </div>
</template>