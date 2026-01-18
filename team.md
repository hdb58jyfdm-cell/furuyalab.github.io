---
title: Team
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
  .card { border: 1px solid rgba(0,0,0,.08); border-radius: 14px; padding: 18px; background: rgba(0,0,0,.01); margin-top: 18px; }
  h1, h2 { margin-top: 0; }
  .small { font-size: .96rem; line-height: 1.65; }
  .muted { opacity: .85; }

  /* PI profile */
  .pi-profile {
    display: grid;
    grid-template-columns: 180px 1fr;
    gap: 20px;
    align-items: start;
  }
  .pi-photo {
    width: 180px;
    height: 220px;
    object-fit: cover;
    border-radius: 14px;
    border: 1px solid rgba(0,0,0,.1);
  }

  /* Team grid */
  .team-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 18px;
    margin-top: 12px;
  }
  .member {
    border: 1px dashed rgba(0,0,0,.15);
    border-radius: 14px;
    padding: 16px;
    background: rgba(0,0,0,.02);
    text-align: center;
  }

  @media (max-width: 820px){
    .pi-profile { grid-template-columns: 1fr; }
    .team-grid { grid-template-columns: 1fr; }
    .pi-photo { margin: 0 auto; }
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
        I received my PhD from <strong>Meiji University (Tokyo, Japan)</strong> and completed postdoctoral
        training at the <strong>Medical University of South Carolina</strong> and the
        <strong>University of Hawaiʻi Cancer Center</strong>. I later joined UHCC as an Assistant Professor
        before moving to <strong>Cedars-Sinai Medical Center</strong>, where I opened my independent laboratory.
      </p>

      <p class="small">
        My research integrates human cohorts, multi-omics, spatial biology, and rigorous analytical
        validation to develop non-invasive diagnostic strategies that can improve risk stratification
        and patient care.
      </p>
    </div>
  </div>
</div>

<!-- LAB MEMBERS -->
<div class="card">
  <h2>Lab Members</h2>

  <div class="team-grid">
    <div class="member">
      <p class="muted"><strong>Position open</strong></p>
      <p class="small">Postdoctoral Fellow</p>
    </div>

    <div class="member">
      <p class="muted"><strong>Position open</strong></p>
      <p class="small">Graduate Student / Research Associate</p>
    </div>
  </div>

  <p class="small muted" style="margin-top:14px;">
    Motivated trainees and collaborators are welcome.
    See <a href="/opportunities">Opportunities</a> for more information.
  </p>
</div>

<p style="margin:28px 0 10px;">
  <small>© Furuya Lab. All rights reserved.</small>
</p>

</div>
