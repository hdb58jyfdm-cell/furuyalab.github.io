---
title: Home
---

<style>
  body {
    margin: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  }

  .wrap {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 16px;
  }

  /* HERO */
  .hero {
    margin-top: 24px;
    border-radius: 18px;
    overflow: hidden;
    border: 1px solid rgba(0,0,0,.08);
  }

  .hero img {
    width: 100%;
    display: block;
  }

  .hero-text {
    padding: 28px 32px;
    background: white;
  }

  .labname {
    font-size: 0.95rem;
    letter-spacing: 0.14em;
    font-weight: 600;
    color: #555;
    margin-bottom: 6px;
  }

  .title {
    font-size: 2.3rem;
    line-height: 1.25;
    margin: 6px 0 14px;
  }

  .lead {
    font-size: 1.05rem;
    line-height: 1.7;
    max-width: 820px;
  }

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

  /* NAV */
  .nav {
    text-align: center;
    margin: 26px 0 40px;
    font-size: 1.05rem;
  }

  .nav a {
    margin: 0 14px;
    text-decoration: none;
    color: #0b5ed7;
    font-weight: 500;
  }

  .nav a:hover {
    text-decoration: underline;
  }

  /* SECTIONS */
  .card {
    border: 1px solid rgba(0,0,0,.08);
    border-radius: 16px;
    padding: 22px 24px;
    margin-bottom: 28px;
    background: #fafafa;
  }

  .card h2 {
    margin-top: 0;
    font-size: 1.35rem;
  }

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

  .small {
    font-size: 0.97rem;
    line-height: 1.7;
  }

  .muted {
    color: #666;
  }

  .feature-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 18px;
    margin-top: 16px;
  }

  .feature-grid img {
    width: 100%;
    border-radius: 14px;
    border: 1px solid rgba(0,0,0,.1);
  }

  @media (max-width: 900px) {
    .feature-grid {
      grid-template-columns: 1fr;
    }

    .profile {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="wrap">

  <!-- HERO -->
  <div class="hero">
    <img src="/assets/img/hero.jpg" alt="Precision cancer biomarkers">
    <div class="hero-text">
      <div class="labname">FURUYA LABORATORY</div>
      <div class="title">Precision cancer prevention & biomarker-driven early detection</div>
      <p class="lead">
        We develop and validate non-invasive biomarkers and integrative multi-omics strategies
        to enable earlier detection, risk stratification, and precision treatment of cancer —
        with a major focus on bladder cancer and upper-tract urothelial carcinoma.
      </p>

      <div class="pillrow">
        <span class="pill">Urine biomarkers</span>
        <span class="pill">Multiplex protein assays</span>
        <span class="pill">Radiogenomics</span>
        <span class="pill">Spatial biology</span>
        <span class="pill">Clinical translation</span>
      </div>
    </div>
  </div>

  <!-- NAVIGATION -->
  <div class="nav">
    <a href="/">Home</a>
    <a href="/research">Research</a>
    <a href="/team">Team</a>
    <a href="/publications">Publications</a>
    <a href="/opportunities">Opportunities</a>
    <a href="/contact">Contact</a>
  </div>

  <!-- PI STATEMENT -->
  <div class="card">
    <h2>PI personal statement</h2>

    <div class="profile">
      <img class="avatar" src="/assets/img/hideki.jpg" alt="Hideki Furuya">
      <div class="small">
        <strong>Hideki Furuya, PhD</strong><br>
        <span class="muted">Cedars-Sinai Medical Center, Los Angeles, CA</span>
      </div>
    </div>

    <p class="small" style="margin-top:16px;">
      My lab’s goal is to enable precision cancer prevention and earlier, more accurate detection
      by translating robust biomarker discoveries into clinically scalable assays.
      We focus on practical diagnostic tools grounded in human cohorts and rigorous analytical
      validation, while using multi-omics and spatial biology to connect tissue-level mechanisms
      to measurable, non-invasive signals.
    </p>
  </div>

  <!-- RESEARCH FOCUS -->
  <div class="card">
    <h2>Research focus</h2>

    <ul class="small">
      <li>Urine-based biomarkers for early detection, prognosis, and prediction of treatment response</li>
      <li>Multiplex assay development and analytical validation</li>
      <li>Radiogenomics and integrative modeling</li>
      <li>Spatial and multi-omics profiling</li>
    </ul>

    <div class="feature-grid">
      <img src="/assets/img/feature1.jpg" alt="Multiplex biomarker assays">
      <img src="/assets/img/feature2.jpg" alt="Spatial biology and imaging">
    </div>

    <p class="small muted" style="margin-top:12px;">
      Multiplex biomarker assay development and integrative imaging / spatial biology.
    </p>
  </div>

  <p style="margin:36px 0 18px; text-align:center;">
    <small>© Furuya Lab. All rights reserved.</small>
  </p>

</div>
