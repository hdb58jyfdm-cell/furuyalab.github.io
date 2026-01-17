---
title: Home
---

<nav>
  <a href="/">Home</a> |
  <a href="/research">Research</a> |
  <a href="/publications">Publications</a> |
  <a href="/team">Team</a> |
  <a href="/opportunities">Opportunities</a> |
  <a href="/contact">Contact</a>
</nav>

<style>
  .wrap { max-width: 980px; margin: 0 auto; padding: 0 14px; }
  .hero { margin: 14px 0 18px; border-radius: 14px; overflow: hidden; border: 1px solid rgba(0,0,0,.08); }
  .hero img { width: 100%; height: auto; display: block; }
  .hero-cap { padding: 14px 16px; background: rgba(0,0,0,.02); }
  .kicker { letter-spacing: .08em; text-transform: uppercase; font-size: .78rem; opacity: .85; margin: 0; }
  .title { font-size: 2.0rem; margin: 8px 0 6px; }
  .lead { font-size: 1.05rem; line-height: 1.65; margin: 0; }
  .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 18px; margin-top: 18px; }
  .card { border: 1px solid rgba(0,0,0,.08); border-radius: 14px; padding: 16px; background: rgba(0,0,0,.01); }
  .card h2 { margin-top: 0; font-size: 1.2rem; }
  .profile { display: grid; grid-template-columns: 96px 1fr; gap: 14px; align-items: start; }
  .avatar { width: 96px; height: 96px; border-radius: 14px; object-fit: cover; border: 1px solid rgba(0,0,0,.08); }
  .pillrow { display:flex; flex-wrap: wrap; gap: 8px; margin-top: 10px; }
  .pill { padding: 6px 10px; border-radius: 999px; border: 1px solid rgba(0,0,0,.12); font-size: .88rem; background: white; }
  .small { font-size: .96rem; line-height: 1.65; }
  .muted { opacity: .85; }
  .feature img { width: 100%; border-radius: 12px; border: 1px solid rgba(0,0,0,.08); margin-top: 10px; }
  @media (max-width: 820px){
    .grid { grid-template-columns: 1fr; }
  }
</style>

<div class="wrap">

  <!-- HERO (optional but recommended) -->
  <div class="hero">
    <img src="/assets/img/hero.jpg" alt="Furuya Lab banner image">
    <div class="hero-cap">
      <p class="kicker">Furuya Laboratory</p>
      <div class="title">Precision cancer prevention & biomarker-driven early detection</div>

      <!-- 1) LAB SHORT FOCUS STATEMENT (keep this as your current one) -->
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

  <!-- 2) PI PERSONAL STATEMENT (new section) -->
  <div class="card">
    <h2>PI personal statement</h2>

    <div class="profile">
      <img class="avatar" src="/assets/img/hideki.jpg" alt="Hideki Furuya">
      <div class="small">
        <strong>Hideki Furuya, PhD</strong><br>
        <span class="muted">Current: Cedars-Sinai Medical Center (Los Angeles, CA) · Future: Houston Methodist (Houston, TX)</span>
      </div>
    </div>

    <p class="small" style="margin-top:12px;">
      <!-- Replace this paragraph with your actual statement -->
      My lab’s goal is to enable precision cancer prevention and earlier, more accurate detection by translating robust biomarker
      discoveries into clinically scalable assays. We focus on building practical diagnostic tools—grounded in human cohorts and
      validated with rigorous analytical and clinical study design—while using multi-omics and spatial biology to connect tissue-level
      mechanisms to measurable, non-invasive signals in urine and blood.
    </p>

    <p class="small">
      <!-- Optional 2nd paragraph -->
      We are especially interested in bridging early tumor-associated biology with deployable diagnostics that can reduce reliance on
      invasive procedures, improve risk stratification, and guide personalized surveillance and treatment.
    </p>
  </div>

  <!-- 3) RESEARCH FOCUS (your existing section; now comes after PI statement) -->
  <div class="grid">

    <div class="card feature">
      <h2>Research focus</h2>
      <ul class="small">
        <li>Urine-based biomarkers for early detection, prognosis, and prediction of treatment response</li>
        <li>Multiplex assay development and analytical validation (clinically scalable platforms)</li>
        <li>Radiogenomics and integrative modeling for precision risk stratification</li>
        <li>Spatial and multi-omics profiling to connect tissue biology to liquid biomarkers</li>
      </ul>
      <img src="/assets/img/feature1.jpg" alt="Biomarker assay / urine biomarkers image">
      <p class="small muted" style="margin:10px 0 0;">
        (Optional caption) Multiplex biomarker assay development and validation.
      </p>
    </div>

    <div class="card feature">
      <h2>At a glance</h2>
      <ul class="small">
        <li><a href="/research">Research overview</a></li>
        <li><a href="/publications">Recent publications</a></li>
        <li><a href="/team">Team</a></li>
        <li><a href="/opportunities">Opportunities</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>

      <h2 style="margin-top:14px;">External profiles</h2>
      <ul class="small">
        <li><a href="https://scholar.google.com/citations?user=yriwzHAAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a></li>
        <li><a href="https://www.ncbi.nlm.nih.gov/myncbi/hideki.furuya.1/bibliography/public/" target="_blank" rel="noopener">PubMed bibliography</a></li>
      </ul>

      <img src="/assets/img/feature2.jpg" alt="Spatial biology / imaging / radiogenomics image">
      <p class="small muted" style="margin:10px 0 0;">
        (Optional caption) Integrating imaging, spatial biology, and multi-omics.
      </p>
    </div>

  </div>

</div>
