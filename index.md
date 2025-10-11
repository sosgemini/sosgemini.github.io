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

<section class="square-grid">
  {% for square in site.data.squares %}
    <a href="{{ square.url | relative_url }}" class="content-square">
      <img src="{{ '/assets/img/' | append: square.img | relative_url }}" alt="{{ square.alt }}">
      <p>{{ square.label }}</p>
      <div class="description">{{ square.desc }}</div>
    </a>
  {% endfor %}
</section>
