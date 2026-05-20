<template>
  <div class="page-container py-32">
    <div class="featured-box">
      <span class="section-tag">Arkiv v3.0 / Hovedoversikt</span>
      <h1 class="hero-title">Eselets <br> Hemmelighet.</h1>
      
      <div class="featured-row border-top-thin">
        <p class="lead-text body-italic">
          Hvorfor kaller vi dem sta? Egentlig er de kanskje de mest fornuftige skapningene vi kjenner til.
        </p>
        <NuxtLink to="/Dolphins" class="cta-link">
          Neste rapport →
        </NuxtLink>
      </div>
    </div>

    <div class="grid-trio">
      <div class="info-card">
        <span class="section-tag section-label-muted">Rapport 01</span>
        <h3 class="stat-value">Frossen Intelligens</h3>
        <p class="body-small">Eselet blir ikke "sta". Den fryser fordi den vurderer risikoen. Hvis den føler at situasjonen er utrygg, nekter den å gå – en ren overlevelsesmekanisme.</p>
      </div>
      <div class="info-card">
        <span class="section-tag section-label-muted">Rapport 02</span>
        <h3 class="stat-value">Bedre enn hester</h3>
        <p class="body-small">I motsetning til hester som panikker og flykter blindt (ofte rett inn i farer), stopper esler opp og tenker selvstendig.</p>
      </div>
      <div class="info-card">
        <span class="section-tag section-label-muted">Rapport 03</span>
        <h3 class="stat-value">Beskytteren</h3>
        <p class="body-small">Esler er fryktløse og brukes ofte som "livvakter" for sauer. De nøler ikke med å angripe ulv eller coyoter for å beskytte flokken sin.</p>
      </div>
    </div>
  </div>
</template>

<script setup>
const features = [
  { title: 'Intelligence', desc: 'Nye funn om hvordan maritime pattedyr kommuniserer på tvers av arter.' },
  { title: 'The Abyss', desc: 'Hva skjuler seg i dypet der lyset aldri når? Vi tar deg med helt ned.' },
  { title: 'Survival', desc: 'Naturens mest brutale og geniale strategier for overlevelse i det skjulte.' }
]
</script>
