---
title: Furuya Lab
---

<nav>
  <a href="/">Home</a> |
  <a href="/research">Research</a> |
  <a href="/team">Team</a> |
  <a href="/publications">Publications</a> |
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
  .grid { display: grid; grid-template-columns: 1fr; gap: 18px; margin-top: 18px; }
  .card { border: 1px solid rgba(0,0,0,.08); border-radius: 14px; padding: 16px; background: rgba(0,0,0,.01); }
  .card h2 { margin-top: 0; font-size: 1.2rem; }
  .profile {
  display: grid;
  grid-template-columns: 180px 1fr; /* was 96px */
  gap: 16px;
  align-items: start;
}

.avatar {
  width: 180px;        /* was 96px */
  height: 180px;       /* was 96px */
  border-radius: 16px; /* slightly rounder looks nicer at larger size */
  object-fit: cover;
  border: 1px solid rgba(0,0,0,.08);
}
  .pillrow { display:flex; flex-wrap: wrap; gap: 8px; margin-top: 10px; }
  .pill { padding: 6px 10px; border-radius: 999px; border: 1px solid rgba(0,0,0,.12); font-size: .88rem; background: white; }
  .small { font-size: .96rem; line-height: 1.65; }
  .muted { opacity: .85; }
  .feature img { width: 100%; border-radius: 12px; border: 1px solid rgba(0,0,0,.08); margin-top: 10px; }

  /* NEW: two images side-by-side */
  .image-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
    margin-top: 12px;
  }
  .image-row img {
    width: 100%;
    border-radius: 12px;
    border: 1px solid rgba(0,0,0,.08);
    margin-top: 0; /* override .feature img margin-top */
    display: block;
  }
  @media (max-width: 700px) {
    .image-row { grid-template-columns: 1fr; }
  }
</style>

<div class="wrap">

  <!-- HERO -->
  <div class="hero">
    <img src="/assets/img/hero.jpg" alt="Furuya Lab banner image">
    <div class="hero-cap">
      <p class="kicker">Furuya Laboratory</p>
      <div class="title">Precision cancer prevention & biomarker-driven early detection</div>

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

  <!-- PI PERSONAL STATEMENT -->
  <div class="card">
    <h2>PI personal statement</h2>

    <div class="profile">
      <img class="avatar" src="/assets/img/hideki.jpg" alt="Hideki Furuya">
      <div class="small">
        <strong>Hideki Furuya, PhD</strong><br>
        <span class="muted">
          Institution: Cedars-Sinai Medical Center (Los Angeles, CA) ·
        </span>
      </div>
    </div>

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

  <!-- RESEARCH FOCUS -->
  <div class="card feature">
    <h2>Research focus</h2>
    <ul class="small">
      <li>Urine-based biomarkers for early detection, prognosis, and prediction of treatment response</li>
      <li>Multiplex assay development and analytical validation (clinically scalable platforms)</li>
      <li>Radiogenomics and integrative modeling for precision risk stratification</li>
      <li>Spatial and multi-omics profiling to connect tissue biology to liquid biomarkers</li>
    </ul>

    <!-- NEW: images on the same row -->
    <div class="image-row">
      <div>
        <img src="/assets/img/feature1.jpg" alt="Multiplex biomarker assay development and validation">
        <p class="small muted" style="margin:10px 0 0;">
          Multiplex biomarker assay development and validation.
        </p>
      </div>

      <div>
        <img src="/assets/img/feature2.jpg" alt="Spatial biology, imaging, and radiogenomics">
        <p class="small muted" style="margin:10px 0 0;">
          Integrating imaging, spatial biology, and multi-omics to connect tissue biology with liquid biomarkers.
        </p>
      </div>
    </div>
  </div>

  <p style="margin:28px 0 10px;">
    <small>© Furuya Lab. All rights reserved.</small>
  </p>

</div>
