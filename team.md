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

  .card {
    border: 1px solid rgba(0,0,0,.08);
    border-radius: 14px;
    padding: 18px;
    background: rgba(0,0,0,.01);
    margin-top: 18px;
  }

  h1, h2 { margin-top: 0; }

  .small { font-size: .96rem; line-height: 1.65; }
  .muted { opacity: .85; }

  /* PI profile */
  .pi-profile {
    display: grid;
    grid-template-columns: 200px 1fr;
    gap: 22px;
    align-items: start;
  }

  .pi-photo {
    width: 200px;
    height: 240px;
    object-fit: cover;
    border-radius: 14px;
    border: 1px solid rgba(0,0,0,.1);
  }

  /* Recruiting grid */
  .grid2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 18px;
    margin-top: 12px;
  }

  .member {
    text-align: center;
  }

  .ph {
    width: 100%;
    height: 160px;
    border-radius: 12px;
    border: 1px dashed rgba(0,0,0,.2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: .9rem;
    color: rgba(0,0,0,.45);
    margin-bottom: 12px;
    background: rgba(0,0,0,.02);
  }

  .mname { margin: 6px 0 2px; font-size: 1.05rem; }
  .mrole { margin: 0; font-weight: 600; opacity: .9; }
  .mbio { margin-top: 8px; }

  @media (max-width: 820px){
    .pi-profile { grid-template-columns: 1fr; }
    .pi-photo { margin: 0 auto; }
    .grid2 { grid-template-columns: 1fr; }
  }
</style>

<div class="wrap">

<h1>Team</h1>

<!-- PI SECTION -->
<div class="card">
  <div class="pi-profile">
    <img src="/assets/img/hideki.jpg" alt="Hideki Furuya headshot" class="pi-photo">

    <div>
      <h2>Hideki Furuya, PhD</h2>
      <p class="muted">Principal Investigator</p>

      <p class="small">
        Translational cancer researcher focused on biomarker-driven precision prevention,
        early detection, and clinically scalable assay development.
      </p>

      <p class="small">
        I received my PhD from Meiji University (Tokyo, Japan) and completed postdoctoral
        training at the Medical University of South Carolina and the
        University of Hawaiʻi Cancer Center. I later joined UHCC as an Assistant Professor
        before moving to Cedars-Sinai Medical Center, where I opened my independent laboratory.
      </p>

      <p class="small">
        My research integrates human cohorts, multi-omics, spatial biology, and rigorous analytical
        validation to develop non-invasive diagnostic strategies that improve risk stratification
        and patient care.
      </p>
    </div>
  </div>
</div>

<!-- LAB MEMBERS / RECRUITING -->
<div class="card">
  <h2>Lab members</h2>

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
</div>

<p style="margin:28px 0 10px;">
  <small>© Furuya Lab. All rights reserved.</small>
</p>

</div>
