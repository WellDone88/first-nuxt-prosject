<template>
  <div class="app-shell">
    <div class="app-glow-top" />
    <div class="app-glow-bottom" />

    <Header />
    
    <main class="main-content">
      <NuxtPage />
    </main>

    <footer class="footer-pill">
      <p class="footer-title">Animal Secrets Archive</p>
      <p class="footer-sub">© {{ new Date().getFullYear() }} — Documenting the Unseen</p>
    </footer>
  </div>
</template>
