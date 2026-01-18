---
title: Team
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

  .card { border: 1px solid rgba(0,0,0,.08); border-radius: 14px; padding: 16px; background: rgba(0,0,0,.01); }
  .card h1, .card h2 { margin-top: 0; }
  .muted { opacity: .85; }
  .small { font-size: .96rem; line-height: 1.65; }

  /* PI row */
  .pi { display: grid; grid-template-columns: 220px 1fr; gap: 18px; align-items: start; }
  .pi img { width: 100%; aspect-ratio: 1 / 1; object-fit: cover; border-radius: 14px; border: 1px solid rgba(0,0,0,.08); }
  .pi .name { font-size: 1.6rem; margin: 0 0 6px; }
  .pi .role { font-weight: 600; margin: 0 0 10px; }
  .pi .meta { margin: 0 0 10px; }

  /* Member grid */
  .grid2 { display: grid; grid-template-columns: 1fr 1fr; gap: 18px; margin-top: 18px; }
  .member { text-align: center; padding: 18px 16px; }
  .member .mname { font-size: 1.25rem; margin: 0; }
  .member .mrole { margin: 6px 0 10px; font-weight: 600; }
  .member .mbio { margin: 0; }

  /* Placeholder avatar */
  .ph {
    width: 140px; height: 140px; border-radius: 999px;
    margin: 0 auto 12px;
    border: 1px dashed rgba(0,0,0,.18);
    background: rgba(0,0,0,.02);
    display: grid; place-items: center;
    font-size: .9rem; opacity: .75;
  }

  @media (max-width: 820px){
    .pi { grid-template-columns: 1fr; }
    .grid2 { grid-template-columns: 1fr; }
    .pi img { max-width: 320px; }
  }
</style>

<div class="wrap">

  <div class="card">
    <h1>Team</h1>

    <!-- PI -->
    <div class="pi" style="margin-top:10px;">
      <img src="/assets/img/hideki.jpg" alt="Hideki Furuya">
      <div>
        <p class="name"><strong>Hideki Furuya, PhD</strong></p>
        <p class="role">Principal Investigator</p>

        <p class="small muted meta">
          Translational cancer researcher focused on biomarker-driven precision prevention, early detection,
          and assay development. The lab integrates multi-omics and spatial biology with clinically practical
          diagnostic strategies.
        </p>

        <p class="small">
          Our program develops and validates non-invasive biomarkers—particularly urine-based assays—and
          integrative multi-omics approaches to enable earlier detection, improved risk stratification,
          and clinically deployable decision-support tools, with a major focus on bladder cancer and
          upper-tract urothelial carcinoma.
        </p>

        <p class="small muted" style="margin-top:10px;">
          Cedars-Sinai Medical Center (Los Angeles, CA)
        </p>

        <p class="small" style="margin-top:10px;">
          Interested in joining? Please see <a href="/opportunities">Opportunities</a> or
          <a href="/contact">Contact</a>.
        </p>
      </div>
    </div>
  </div>

  <!-- LAB MEMBERS -->
  <div class="grid2">

    <div class="card member">
      <div class="ph">Photo</div>
      <p class="mname"><strong>We’re recruiting</strong></p>
      <p class="mrole">Postdoctoral fellows</p>
      <p class="small mbio">
        Biomarkers, assay development and validation, multi-omics integration,
        spatial biology, and radiogenomics.
      </p>
      <p class="small" style="margin-top:12px;">
        <a href="/opportunities">See openings</a>
      </p>
    </div>

    <div class="card member">
      <div class="ph">Photo</div>
      <p class="mname"><strong>We’re recruiting</strong></p>
      <p class="mrole">Research staff & trainees</p>
      <p class="small mbio">
        Research associates/technicians, graduate and undergraduate trainees,
        and computational collaborators.
      </p>
      <p class="small" style="margin-top:12px;">
        <a href="/contact">Get in touch</a>
      </p>
    </div>

  </div>

  <p style="margin:28px 0 10px;">
    <small>© Furuya Lab. All rights reserved.</small>
  </p>

</div>
