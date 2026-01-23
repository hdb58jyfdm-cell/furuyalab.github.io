---
title: Research
---

<nav class="topnav" aria-label="Primary">
  <a href="/">Home</a>
  <a href="/research" aria-current="page">Research</a>
  <a href="/team">Team</a>
  <a href="/publications">Publications</a>
  <a href="/opportunities">Opportunities</a>
  <a href="/contact">Contact</a>
</nav>

<style>
  /* Page container */
  .wrap { max-width: 980px; margin: 0 auto; padding: 0 14px; }

  /* Top nav */
  .topnav{
    display:flex;
    justify-content:center;
    gap: 26px;
    flex-wrap: wrap;
    margin: 14px 0 18px;
    font-weight: 600;
  }
  .topnav a{
    text-decoration: none;
    padding: 6px 10px;
    border-radius: 999px;
  }
  .topnav a:hover{
    background: rgba(0,0,0,.04);
  }

  /* Cards */
  .card{
    border: 1px solid rgba(0,0,0,.08);
    border-radius: 14px;
    padding: 18px;
    background: rgba(0,0,0,.01);
    margin: 16px 0;
  }
  h1{ margin: 10px 0 6px; font-size: 2.0rem; }
  h2{ margin: 0 0 10px; font-size: 1.25rem; }
  h3{ margin: 0 0 10px; font-size: 1.05rem; }
  p, li{ line-height: 1.65; }
  .lead{ font-size: 1.05rem; margin-top: 6px; }

  /* Project layout (text + image) */
  .proj{
    display:grid;
    grid-template-columns: 0.95fr 1.05fr; /* give images more space */
    gap: 22px;
    align-items: start;
  }

  /* Image styles */
  .fig img{
    width: 100%;
    height: auto;
    display: block;
    border-radius: 12px;
    border: 1px solid rgba(0,0,0,.08);
    background: white;
  }
  .cap{
    margin-top: 10px;
    font-size: .95rem;
    opacity: .85;
  }

  /* Project 2 stacked images (vertical) */
  .imggrid2{
    display:grid;
    grid-template-columns: 1fr; /* vertical stack */
    gap: 14px;
  }

  /* Small muted text */
  .muted{ opacity: .85; }
  .pillrow{ display:flex; flex-wrap:wrap; gap: 8px; margin-top: 10px; }
  .pill{
    padding: 6px 10px;
    border-radius: 999px;
    border: 1px solid rgba(0,0,0,.12);
    font-size: .88rem;
    background: white;
  }

  /* Responsive */
  @media (max-width: 860px){
    .proj{ grid-template-columns: 1fr; }
    .topnav{ gap: 10px; }
  }

  /* Footer */
  .site-footer{
    margin: 28px 0 10px;
    text-align: center;
    font-size: .9rem;
    opacity: .75;
  }
</style>

<div class="wrap">

# Research

<p class="lead">
Our lab develops biomarker-driven strategies to enable <strong>early detection, risk stratification, and precision prevention</strong>.
We combine mechanistic insight with clinically grounded assay development, integrating multi-omics and spatial biology to connect tissue-level
states with non-invasive signals.
</p>

<div class="pillrow">
  <span class="pill">Urine biomarkers</span>
  <span class="pill">Multiplex assays</span>
  <span class="pill">Analytical validation</span>
  <span class="pill">Radiogenomics</span>
  <span class="pill">Spatial biology</span>
</div>

<!-- ===================== PROJECT 1 ===================== -->
<div class="card">
  <div class="proj">
    <div>
      <h2>Project 1: Precision prevention and early detection</h2>
      <p>
        We aim to identify measurable biological signals that precede clinically evident cancer and enable non-invasive detection and surveillance.
      </p>
      <p><strong>Approach:</strong> curated cohorts, PRoBE-style principles when feasible, and clinically practical assay designs.</p>
      <ul>
        <li>Prospective and retrospective cohort studies</li>
        <li>Risk stratification and performance benchmarking</li>
        <li>Translation toward scalable clinical workflows</li>
      </ul>
    </div>

    <div class="fig">
      <img src="/assets/img/Project_1.jpg" alt="Project 1 figure">
      <div class="cap">Project 1 overview.</div>
    </div>
  </div>
</div>

<!-- ===================== PROJECT 2 ===================== -->
<div class="card">
  <div class="proj">
    <div>
      <h2>Project 2: Biomarker panels and assay development</h2>
      <p>
        We focus on translation: building assays that are robust, scalable, and compatible with real clinical workflows.
      </p>

      <h3>Examples of translation priorities</h3>
      <ul>
        <li>Multiplex protein panels (urine-based)</li>
        <li>Reproducible QC frameworks and analytical validation thinking</li>
        <li>Bridging discovery platforms → targeted assays</li>
      </ul>

      <p class="muted">
        (You can refine these bullets later to match your Word figure captions.)
      </p>
    </div>

    <div class="fig">
      <div class="imggrid2">
        <img src="/assets/img/Project_2_1.jpg" alt="Project 2 image 1">
        <img src="/assets/img/Project_2_2.jpg" alt="Project 2 image 2">
      </div>
      <div class="cap">Project 2 schematic (assay development and analytical validation).</div>
    </div>
  </div>
</div>

<!-- ===================== PROJECT 3 ===================== -->
<div class="card">
  <div class="proj">
    <div>
      <h2>Project 3: Spatial and multi-omics biology</h2>
      <p>
        We connect tissue-level biology to urine/tissue biomarkers and outcomes to better understand early tumor-associated states and their clinical implications.
      </p>

      <h3>Methods (examples)</h3>
      <ul>
        <li>Spatial transcriptomics / spatial proteomics</li>
        <li>Bulk profiling + targeted validation</li>
        <li>Integrative analysis across datasets and models</li>
      </ul>
    </div>

    <div class="fig">
      <img src="/assets/img/Project_3.jpg" alt="Project 3 figure">
      <div class="cap">Project 3 overview.</div>
    </div>
  </div>
</div>

<!-- ===================== PROJECT 4 ===================== -->
<div class="card">
  <div class="proj">
    <div>
      <h2>Project 4: Experimental models supporting temporal biology</h2>
      <p>
        We leverage experimental models to understand how early tumor-associated biological states evolve over time and how these changes shape detectable biomarker signals.
      </p>

      <ul>
        <li>Model development for disease initiation and progression</li>
        <li>Temporal profiling and cross-modal comparisons</li>
        <li>Mechanistic studies to connect biology to biomarkers</li>
      </ul>

      <p>
        If you’d like to collaborate, please reach out via <a href="/contact"><strong>Contact</strong></a>.
      </p>
    </div>

    <div class="fig">
      <img src="/assets/img/Project_4.jpg" alt="Project 4 figure">
      <div class="cap">Project 4 overview.</div>
    </div>
  </div>
</div>

<p class="site-footer"><small>© Furuya Lab. All rights reserved.</small></p>

</div>
