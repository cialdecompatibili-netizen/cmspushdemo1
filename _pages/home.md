ï»¿---
layout: home
title: "Home"
permalink: /home-page/
---

<!-- SLIDER -->
<div class="lx-slider" id="lx-slider">

  <div class="lx-slide active">
    <div class="lx-slide-bg" style="background-color:#f0ede8;"></div>
    <div class="lx-slide-overlay"></div>
    <div class="lx-slide-content">
      <p class="lx-slide-eyebrow">Benvenuto nel caos</p>
      <h1 class="lx-slide-title">Idee, guide<br>e <em>riflessioni</em></h1>
      <p class="lx-slide-sub">Apri la bocca. Giuro che non morde (quasi).</p>
    </div>
  </div>

  <div class="lx-slide">
    <div class="lx-slide-bg" style="background-color:#e8edf0;"></div>
    <div class="lx-slide-overlay"></div>
    <div class="lx-slide-content">
      <p class="lx-slide-eyebrow">Le nostre cure</p>
      <h1 class="lx-slide-title">Articoli<br><em>pratici</em> e diretti</h1>
      <p class="lx-slide-sub">Otturazioni, pulizie e barzellette dal 2003.</p>
    </div>
  </div>

  <div class="lx-slide">
    <div class="lx-slide-bg" style="background-color:#ede8f0;"></div>
    <div class="lx-slide-overlay"></div>
    <div class="lx-slide-content">
      <p class="lx-slide-eyebrow">Chi siamo</p>
      <h1 class="lx-slide-title">Netizen<br><em>cialdecompatibile</em></h1>
      <p class="lx-slide-sub">Uno studio dentistico. O forse un circo. Ancora non lo sappiamo.</p>
    </div>
  </div>

  <div class="lx-arrows">
    <button class="lx-arrow" onclick="lxSlide(-1)">&#8592;</button>
    <button class="lx-arrow" onclick="lxSlide(1)">&#8594;</button>
  </div>
  <div class="lx-dots">
    <button class="lx-dot active" onclick="lxGo(0)"></button>
    <button class="lx-dot" onclick="lxGo(1)"></button>
    <button class="lx-dot" onclick="lxGo(2)"></button>
  </div>
</div>

<!-- DESCRIPTION -->
<div class="lx-desc">
  <div class="lx-desc-inner">
    <p class="lx-desc-label">Lo studio</p>
    <h2 class="lx-desc-title">Un posto dove mettere ordine<br>ai pensieri sul digitale</h2>
    <p class="lx-desc-text">Vieni per i denti, resti per le barzellette. Studio dentistico serio (abbastanza) nel cuore di Roma.</p>
    <a href="{{ '/blog/' | relative_url }}" class="lx-desc-cta">Prenota e vedi tu stesso →</a>
  </div>
</div>

<!-- 3 STEPS -->
<div class="lx-steps">

  <div class="lx-step">
    <p class="lx-step-num">01</p>
    <div class="lx-step-icon">
      <svg viewBox="0 0 24 24"><path d="M12 20h9M16.5 3.5a2.121 2.121 0 013 3L7 19l-4 1 1-4L16.5 3.5z"/></svg>
    </div>
    <h3 class="lx-step-title">Prenota</h3>
    <p class="lx-step-desc">Chiama, scrivi, urla dal balcone. Ti rispondiamo comunque.</p>
  </div>

  <div class="lx-step">
    <p class="lx-step-num">02</p>
    <div class="lx-step-icon">
      <svg viewBox="0 0 24 24"><path d="M4 6h16M4 12h16M4 18h7"/></svg>
    </div>
    <h3 class="lx-step-title">Vieni (senza fuggire)</h3>
    <p class="lx-step-desc">Ambiente accogliente, musica assurda, dottore leggermente fuori di testa.</p>
  </div>

  <div class="lx-step">
    <p class="lx-step-num">03</p>
    <div class="lx-step-icon">
      <svg viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 9.8 19.79 19.79 0 01.1 1.2 2 2 0 012.11 0h3a2 2 0 012 1.72 12.84 12.84 0 00.7 2.81 2 2 0 01-.45 2.11L6.59 7.91a16 16 0 006.29 6.29l.77-.77a2 2 0 012.11-.45 12.84 12.84 0 002.81.7A2 2 0 0122 16.92z"/></svg>
    </div>
    <h3 class="lx-step-title">Esci sorridendo</h3>
    <p class="lx-step-desc">Denti sistemati. Dignità intatta. Probabilmente.</p>
  </div>

</div>
