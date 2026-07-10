---
layout: page
title: Echo
permalink: /Echo/
description:
nav: true
nav_order: 7
---

<div style="
    text-align:center;
    font-style:italic;
    font-size:1.2rem;
    color:var(--global-text-color);
    margin:1.5rem auto 2rem auto;
">
  “This ain't a song for the broken-hearted”
  <div style="margin-top:0.5rem;font-size:0.95rem;opacity:0.75;">
    — Bon Jovi, <em>It's My Life</em>
  </div>
</div>

<style>
.research-container {
  max-width: 1000px;
  margin: 0 auto;
}

.project-container {
  display: flex;
  gap: 20px;
  align-items: center;
  margin-bottom: 2rem;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 12px;

  padding: 20px;
  width: 100%;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-container:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

.project-video {
  flex: 1;
  min-width: 0;
  max-width: 50%;
}

.project-video video,
.project-video iframe {
  width: 95%;
  aspect-ratio: 16 / 9;
  border-radius: 8px;
  border: none;
}

.project-text {
  flex: 1;
  min-width: 0;
  color: var(--global-text-color);
}

.project-text h3 {
  margin-top: 0;
  font-size: 1.25rem;
  font-weight: 600;
  color: var(--global-theme-color);
}

.project-text h3 a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.project-text h3 a:hover {
  text-decoration: underline;
  color: var(--global-hover-color);
}

.paper-cite {
  margin-top: 0.5rem;
  padding: 10px;
  border-radius: 10px;
  border: 1px solid var(--global-divider-color);
  background-color: rgba(0,83,156,0.08);
  color: var(--global-text-color);
}

html[data-theme="dark"] .paper-cite {
  background-color: rgba(230,237,243,0.06);
}

@media (max-width:768px) {
  .project-container {
    flex-direction: column;
    gap: 20px;
  }

  .project-video {
    max-width: 100%;
  }

  .project-video video,
  .project-video iframe {
    width: 100%;
  }
}
</style>

<div class="container">

<br>

<div class="project-container">

  <div class="project-video">
  <iframe
      width="100%"
      height="315"
      src="https://www.youtube.com/embed/VUxIwnf_wZk"
      title="Bon Jovi - It's My Life"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen>
  </iframe>
</div>
      

  <div class="project-text">
    <h3>
      <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458274&tag=1">
        Source-Seeking Robot
      </a>
    </h3>
    <p>
      Experimental validation of source seeking control for unicycle robots with
      3D-printed graphene-based airflow sensors. The algorithm ensures convergence
      to the source even with partial sensor failure.
    </p>
    <p class="paper-cite">
      • <strong>T. Li*</strong>, B. Jayawardhana, A. M. Kamat and A. G. P.
      Kottapalli, "Source-Seeking Control of Unicycle Robots With 3-D-Printed
      Flexible Piezoresistive Sensors", <strong>IEEE Transactions on Robotics</strong>,
      vol. 38, no. 1, pp. 448–462, Feb. 2022,
      doi:10.1109/TRO.2021.3076964
    </p>

  </div>

</div>

</div>