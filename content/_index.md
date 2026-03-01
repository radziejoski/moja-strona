---
title: "Strona główna"
date: 2026-03-01T00:00:00+01:00
---

<style>
  .hero-full { position:relative; width:100%; overflow:hidden; }
  .hero-full .bg { width:100%; height:60vh; background-size:cover; background-position:center; }
  .hero-full .overlay { position:absolute; inset:0; display:flex; align-items:center; justify-content:center; }
  .hero-full h1{ color:white; font-size:clamp(2rem,4vw,3.5rem); margin:0; text-shadow:0 6px 18px rgba(0,0,0,0.5)}
  .hero-full p{ color:rgba(255,255,255,0.95); font-size:1.05rem; text-align:center; margin-top:10px; text-shadow:0 4px 12px rgba(0,0,0,0.45)}
  @media (max-width:640px){ .hero-full .bg{height:45vh} }
</style>

<section class="hero-full">
  <div class="bg" style="background-image:url('/images/oferta/zdj5.jpeg')"></div>
  <div class="overlay">
    <div style="max-width:1000px;padding:1rem;text-align:center">
      <h1>Witamy</h1>
      <p>Zapraszam do zapoznania się z naszą ofertą i realizacjami.</p>
    </div>
  </div>
</section>
