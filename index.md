---
layout: default
title: SOS Gemini
class: home
---

<div class="post-container">
  <div class="intro">
    <h1 class="main-title-centered">SOS Gemini – La tua guida per una vita sostenibile</h1>
    <h2 class="small-title">
      Benvenuto su SOS Gemini: qui trovi consigli pratici per vivere in armonia con l'ambiente, migliorando la tua salute e quella dei tuoi amici a quattro zampe.
    </h2>
  </div>
<div class="post-container">
  <div class="intro">
    <h1 class="main-title-centered">SOS Gemini – La tua guida per una vita sostenibile</h1>
    <h2 class="small-title">
      Benvenuto su SOS Gemini: qui trovi consigli pratici per vivere in armonia con l'ambiente, migliorando la tua salute e quella dei tuoi amici a quattro zampe.
    </h2>
  </div>

  <section class="square-grid">
    <a href="/alimentazione/" class="content-square">
      <img src="/assets/img/ICO-alimenti-cibo.webp" alt="Alimentazione">
      <p>Alimentazione</p>
      <div class="description">Mangiare sano e sostenibile</div>
    </a>

    <a href="/animali/" class="content-square">
      <img src="/assets/img/ICO-amici.webp" alt="Animali">
      <p>Animali</p>
      <div class="description">Cura e rispetto per i nostri amici</div>
    </a>

    <a href="/salute/" class="content-square">
      <img src="/assets/img/ICO-medicina-salute.webp" alt="Salute">
      <p>Salute</p>
      <div class="description">Benessere naturale e prevenzione</div>
    </a>

    <a href="/lavoro/" class="content-square">
      <img src="/assets/img/ICO-lavoro-attivita.webp" alt="Lavoro">
      <p>Lavoro</p>
      <div class="description">Etica, smart working e futuro</div>
    </a>

    <a href="/fai-da-te/" class="content-square">
      <img src="/assets/img/ICO-oggettistica-faidate.webp" alt="Fai da te">
      <p>Fai da te</p>
      <div class="description">Soluzioni pratiche e creative</div>
    </a>
  </section>
</div>

<section class="square-grid">
  {% for square in site.data.squares %}
    <a href="{{ square.url | relative_url }}" class="content-square">
      <img src="{{ '/assets/img/' | append: square.img | relative_url }}" alt="{{ square.alt }}">
      <p>{{ square.label }}</p>
      <div class="description">{{ square.desc }}</div>
    </a>
  {% endfor %}
</section>
