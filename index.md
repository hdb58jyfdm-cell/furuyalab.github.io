---
title: Home
---

<style>
  .wrap { max-width: 980px; margin: 0 auto; padding: 0 14px; }

  /* NAV (centered, clean) */
  .nav {
    display: flex;
    justify-content: center;
    gap: 28px;
    flex-wrap: wrap;
    margin: 14px 0 18px;
    font-size: 1.05rem;
  }
  .nav a {
    text-decoration: none;
    color: #0b57d0;
    font-weight: 600;
  }
  .nav a:hover { text-decoration: underline; }

  /* HERO */
  .hero { margin: 14px 0 10px; border-radius: 14px; overflow: hidden; border: 1px solid rgba(0,0,0,.08); }
  .hero img { width: 100%; height: auto; display: block; }
  .hero-cap { padding: 14px 16px; background: rgba(0,0,0,.02); }
  .kicker { letter-spacing: .08em; text-transform: uppercase; font-size: .95rem; font-weight: 800; margin: 0; }
  .title { font-size: 2.0rem; margin: 10px 0 8px; }
  .lead { font-size: 1.05rem; line-height: 1.65; margin: 0; }

  /* CARDS */
  .card { border: 1px solid rgba(0,0,0,.08); border-radius: 14px; padding: 16px; background: rgba(0,0,0,.01); }
  .card h2 { margin-top: 0; font-size: 1.2rem; }
  .small { font-size: .96rem; line-height: 1.65; }
  .muted { opacity: .85; }

  /* PROFILE */
  .profile { display: grid; grid-template-columns: 220px 1fr; gap: 16px; align-items: start; }
  .avatar { width: 220px; height: 220px; border-radius: 16px; object-fit: cover; border: 1px solid rgba(0,0,0,.08); }

  /* PILLS */
  .pillrow { display:flex; flex-wrap: wrap; gap: 8px; margin-top: 12px; }
  .pill { padding: 6px 10px; border-radius: 999px; border: 1px solid rgba(0,0,0,.12); font-size: .88rem; background: white; }

  /* FEATURE IMAGES (two images side-by-side) */
  .imgrow { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-top: 12px; }
  .imgrow img { width: 100%; border-radius: 12px; border: 1px solid rgba(0,0,0,.08); display: block; }

  @media (max-width: 820px){
    .profile { grid-template-columns: 1fr; }
    .avatar { width: 180px; height: 180px; }
    .imgrow { grid-template-columns: 1fr; }
    .nav { gap: 18px; }
  }
</style>

<div class="wrap">

  <!-- HERO -->
  <div class="hero">
    <img src="/assets/img/hero.jpg" alt="Furuya Lab banner image">
    <div class="hero-cap">
      <p class="kicker">FURUYA LABORATORY</p>
      <div class="title">Precision cancer prevention &amp; biomarker-driven early detection</div>

      <p class="lead">
        We develop and validate non-invasive biomarkers and integrative multi-omics strategies to enable earlier detection,
        risk stratification, and precision treatment of cancer—with a major focus on bladder cancer and upper-tract urothelial carcinoma.
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

  <!-- NAV (moved BELOW hero) -->
  <nav class="nav" aria-label="Primary navigation">
    <a href="/">Home</a>
    <a href="/research">Research</a>
    <a href="/team">Team</a>
    <a href="/publications">Publications</a>
    <a href="/opportunities">Opportunities</a>
    <a href="/contact">Contact</a>
  </nav>

  <!-- PI PERSONAL STATEMENT -->
  <div class="card">
    <h2>PI personal statement</h2>

    <div class="profile">
      <img class="avatar" src="/assets/img/hideki.jpg" alt="Hideki Furuya">
      <div class="small">
        <strong>Hideki Furuya, PhD</strong><br>
        <span class="muted">Institution: Cedars-Sinai Medical Center (Los Angeles, CA)</span>

        <p class="small" style="margin-top:12px;">
          My lab’s goal is to enable precision cancer prevention and earlier, more accurate detection by translating robust biomarker
          discoveries into clinically scalable assays. We focus on building practical diagnostic tools—grounded in human cohorts and
          validated with rigorous analytical and clinical study design—while using multi-omics and spatial biology to connect tissue-level
          mechanisms to measurable, non-invasive signals in urine and blood.
        </p>

        <p class="small">
          We are especially interested in bridging early tumor-associated biology with deployable diagnostics that can reduce reliance on
          invasive procedures, improve risk stratification, and guide personalized surveillance and treatment.
        </p>
      </div>
    </div>
  </div>

  <!-- RESEARCH FOCUS -->
  <div class="card" style="margin-top:18px;">
    <h2>Research focus</h2>
    <ul class="small">
      <li>Urine-based biomarkers for early detection, prognosis, and prediction of treatment response</li>
      <li>Multiplex assay development and analytical validation (clinically scalable platforms)</li>
      <li>Radiogenomics and integrative modeling for precision risk stratification</li>
      <li>Spatial and multi-omics profiling to connect tissue biology to liquid biomarkers</li>
    </ul>

    <!-- Two images in the same row -->
    <div class="imgrow">
      <img src="/assets/img/feature1.jpg" alt="Multiplex biomarker assay and urine biomarker analysis">
      <img src="/assets/img/feature2.jpg" alt="Spatial biology, imaging, and radiogenomics">
    </div>

    <p class="small muted" style="margin:10px 0 0;">
      Multiplex biomarker assay development, and integrative imaging/spatial biology to connect tissue biology with liquid biomarkers.
    </p>
  </div>

  <p style="margin:28px 0 10px;">
    <small>© Furuya Lab. All rights reserved.</small>
  </p>

</div>
