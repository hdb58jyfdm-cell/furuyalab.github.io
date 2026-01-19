---
title: Home
---

<style>
  body { margin: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; }

  /* Layout */
  .wrap { max-width: 1100px; margin: 0 auto; padding: 0 16px; }

  /* HERO */
  .hero {
    margin: 0 auto 32px;
    border-radius: 18px;
    overflow: hidden;
    border: 1px solid rgba(0,0,0,.08);
  }
  .hero img {
    width: 100%;
    height: auto;
    display: block;
  }
  .hero-cap {
    padding: 28px;
    background: #fff;
  }

  .kicker {
    letter-spacing: .14em;
    text-transform: uppercase;
    font-size: .9rem;
    opacity: .85;
    margin-bottom: 10px;
  }
  .title {
    font-size: 2.2rem;
    margin: 0 0 10px;
  }
  .lead {
    font-size: 1.05rem;
    line-height: 1.7;
    max-width: 900px;
  }

  /* Pills */
  .pillrow {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 18px;
  }
  .pill {
    padding: 7px 14px;
    border-radius: 999px;
    border: 1px solid rgba(0,0,0,.15);
    font-size: .9rem;
    background: #fff;
  }

  /* NAV — placed BELOW hero content */
  .nav {
    text-align: center;
    margin: 22px 0 0;
  }
  .nav a {
    margin: 0 14px;
    text-decoration: none;
    font-weight: 500;
    color: #0b5ed7;
  }
  .nav a:hover {
    text-decoration: underline;
  }

  /* Cards */
  .card {
    border: 1px solid rgba(0,0,0,.08);
    border-radius: 16px;
    padding: 22px;
    margin: 28px 0;
    background: rgba(0,0,0,.015);
  }

  /* Profile */
  .profile {
    display: grid;
    grid-template-columns: 140px 1fr;
    gap: 18px;
    align-items: start;
  }
  .avatar {
    width: 140px;
    height: 140px;
    border-radius: 16px;
    object-fit: cover;
    border: 1px solid rgba(0,0,0,.1);
  }

  /* Footer */
  footer {
    text-align: center;
    margin: 40px 0 20px;
    font-size: .85rem;
    opacity: .75;
  }
</style>

<div class="wrap">

  <!-- HERO -->
  <div class="hero">
    <img src="/assets/img/hero.jpg" alt="Furuya Lab research illustration">

    <div class="hero-cap">
      <div class="kicker">FURUYA LABORATORY</div>

      <h1 class="title">
        Precision cancer prevention & biomarker-driven early detection
      </h1>

      <p class="lead">
        We develop and validate non-invasive biomarkers and integrative multi-omics
        strategies to enable earlier detection, risk stratification, and precision
        treatment of cancer—with a major focus on bladder cancer and upper-tract
        urothelial carcinoma.
      </p>

      <div class="pillrow">
        <span class="pill">Urine biomarkers</span>
        <span class="pill">Multiplex protein assays</span>
        <span class="pill">Radiogenomics</span>
        <span class="pill">Spatial biology</span>
        <span class="pill">Clinical translation</span>
      </div>

      <!-- NAVIGATION MOVED HERE -->
      <div class="nav">
        <a href="/">Home</a>
        <a href="/research">Research</a>
        <a href="/team">Team</a>
        <a href="/publications">Publications</a>
        <a href="/opportunities">Opportunities</a>
        <a href="/contact">Contact</a>
      </div>

    </div>
  </div>

  <!-- PI STATEMENT -->
  <div class="card">
    <h2>PI personal statement</h2>

    <div class="profile">
      <img src="/assets/img/hideki.jpg" alt="Hideki Furuya" class="avatar">
      <div>
        <strong>Hideki Furuya, PhD</strong><br>
        Translational cancer researcher focused on biomarker-driven precision prevention,
        early detection, and clinically scalable assay development.
      </div>
    </div>

    <p style="margin-top:16px;">
      My lab’s goal is to enable precision cancer prevention and earlier, more accurate
      detection by translating robust biomarker discoveries into practical diagnostic
      tools. We integrate human cohorts, rigorous analytical validation, and multi-omics
      biology to connect tissue-level mechanisms with non-invasive biomarkers.
    </p>
  </div>

  <!-- RESEARCH FOCUS -->
  <div class="card">
    <h2>Research focus</h2>
    <ul>
      <li>Urine-based biomarkers for early detection and prognosis</li>
      <li>Multiplex assay development and analytical validation</li>
      <li>Radiogenomics and integrative modeling</li>
      <li>Spatial and multi-omics profiling</li>
    </ul>
  </div>

</div>

<footer>
  © Furuya Lab. All rights reserved.
</footer>
