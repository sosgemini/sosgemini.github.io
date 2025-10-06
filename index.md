---
layout: default
title: Home
---

<header class="site-header">
  <div class="header-container page-width">
    <!-- Logo + Titolo -->
    <div class="logo-area">
      <a href="{{ '/' | relative_url }}" class="logo-link">
  <img src="{{ '/assets/img/SOS-96x96.png' | relative_url }}" alt="Logo SOS Gemini" class="logo-img">
</a>
<span class="site-title">SOS Gemini</span>

    </div>

    <!-- Utility -->
    <div class="utility-area">
      <select class="lang-switch" aria-label="Lingua">
        <option value="it">Italiano</option>
        <option value="en">English</option>
      </select>
      <a href="{{ '/login.html' | relative_url }}" class="login-link">Accedi</a>
      <input type="search" class="search-box" placeholder="Cerca" aria-label="Cerca nel sito">
    </div>
  </div>

  <!-- Barra nera -->

<!-- Barra nera -->
<div class="indice-bar">
  <nav class="main-nav">
    <ul class="nav-links">
      <li><a href="{{ '/' | relative_url }}">Home</a></li>
      <li><a href="{{ '/Amici/' | relative_url }}">Amici</a></li>
      <li><a href="{{ '/Alimenti/' | relative_url }}">Alimentazione</a></li>
      <li><a href="{{ '/Lavoro - Attivita/' | relative_url }}">Lavoro</a></li>
      <li><a href="{{ '/Medicina - Salute/' | relative_url }}">Medicina</a></li>
      <li><a href="{{ '/Oggettistica - Fai-da-te/' | relative_url }}">Oggettistica</a></li>
      <li><a href="{{ '/Motori - Attrezzi/' | relative_url }}">Motori</a></li>
    </ul>
  </nav>
</div>

</header>

<main class="page-wrapper">
  <div class="larghezza-indicata">
    --- larghezza pagina 1150 ---
  </div>

</main>

<footer class="site-footer">
  <p>&copy; 2005 SOS Gemini. Tutti i diritti riservati.</p>
</footer>
