---
layout: page
title: Research
permalink: /research/
description:
nav: true
nav_order: 2
---

<style>
/* =========================
   Research Page
   ========================= */

.research-container {
  max-width: 960px;
  margin: 0 auto;
}

/* -------------------------
   Introduction
   ------------------------- */

.research-intro {
  max-width: 800px;
  margin: 0 0 3.5rem;

  font-size: 1.02rem;
  line-height: 1.75;
  color: var(--global-text-color);
}

/* -------------------------
   Project
   ------------------------- */

.project-container {
  display: grid;
  grid-template-columns: minmax(260px, 40%) minmax(0, 1fr);
  gap: 32px;
  align-items: start;

  width: 100%;
  padding: 0 0 2.75rem;
  margin-bottom: 2.75rem;

  border-bottom: 1px solid var(--global-divider-color);
}

/* Remove separator after last project */
.project-container:last-child {
  border-bottom: none;
  margin-bottom: 0;
}

/* -------------------------
   Project media
   ------------------------- */

.project-video {
  min-width: 0;
}

.project-video video {
  display: block;
  width: 100%;
  height: auto;

  border-radius: 6px;
  border: 1px solid var(--global-divider-color);
}

/* -------------------------
   Project text
   ------------------------- */

.project-text {
  min-width: 0;
  color: var(--global-text-color);
}

/* Title */

.project-text h3 {
  margin: 0 0 0.7rem;

  font-size: 1.3rem;
  font-weight: 600;
  line-height: 1.35;
}

.project-text h3 a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.project-text h3 a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}

/* Summary */

.project-summary {
  margin: 0 0 1rem;

  font-size: 0.97rem;
  line-height: 1.65;
  color: var(--global-text-color);
}

/* -------------------------
   Tags
   ------------------------- */

.project-tags {
  display: flex;
  flex-wrap: wrap;
  align-items: center;

  gap: 5px 10px;
  margin: 0 0 1.1rem;
}

.project-tags span {
  display: inline-flex;
  align-items: center;

  padding: 3px 8px;

  font-size: 0.76rem;
  font-weight: 500;
  line-height: 1.4;

  color: var(--global-text-color-light);
  background: transparent;

  border: 1px solid var(--global-divider-color);
  border-radius: 999px;
}

/* -------------------------
   Publication
   ------------------------- */

.paper-cite {
  margin: 0;
  padding: 0;

  font-size: 0.85rem;
  line-height: 1.6;

  color: var(--global-text-color-light);
}

.paper-cite strong {
  color: var(--global-text-color);
  font-weight: 600;
}

.paper-cite em {
  font-style: italic;
}

/* DOI links */

.paper-cite a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.paper-cite a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}

/* -------------------------
   Dark mode
   ------------------------- */

html[data-theme="dark"] .project-video video {
  border-color: var(--global-divider-color);
}

html[data-theme="dark"] .project-tags span {
  background: rgba(255, 255, 255, 0.02);
}

/* -------------------------
   Tablet / Mobile
   ------------------------- */

@media (max-width: 768px) {
  .research-intro {
    margin-bottom: 2.5rem;

    font-size: 1rem;
    line-height: 1.7;
  }

  .project-container {
    grid-template-columns: 1fr;
    gap: 18px;

    padding-bottom: 2.25rem;
    margin-bottom: 2.25rem;
  }

  .project-text h3 {
    font-size: 1.18rem;
    margin-bottom: 0.6rem;
  }

  .project-summary {
    font-size: 0.95rem;
  }

  .paper-cite {
    font-size: 0.83rem;
  }
}

/* -------------------------
   Small mobile
   ------------------------- */

@media (max-width: 480px) {
  .project-container {
    gap: 16px;
  }

  .project-tags {
    gap: 5px 7px;
  }

  .project-tags span {
    font-size: 0.73rem;
    padding: 3px 7px;
  }
}
</style>


<div class="research-container">

  <!-- =====================
       Research Introduction
       ===================== -->

  <p class="research-intro">
    My research focuses on safe and intelligent autonomous robotic systems
    operating in unknown and cluttered environments. My PhD research
    investigated safety-critical motion control for wheeled mobile robots,
    while my current postdoctoral work extends this line of research to aerial
    robotics by developing safety-critical control methods for autonomous and
    safe flight.
  </p>


  <!-- =====================
       Project 1
       ===================== -->

  <div class="project-container">

    <div class="project-video">
      {% include video.liquid
        path="/assets/video/SS.mp4"
        class="img-fluid rounded z-depth-1"
        controls=true
      %}
    </div>

    <div class="project-text">

      <h3>
        <a
          href="https://ieeexplore.ieee.org/abstract/document/9458274"
          target="_blank"
          rel="noopener noreferrer"
        >
          Source-Seeking Robot
        </a>
      </h3>

      <p class="project-summary">
        Source-seeking control for a unicycle robot using flexible airflow
        sensors and local measurements to locate an unknown signal source.
      </p>

      <div class="project-tags">
        <span>Source Seeking</span>
        <span>Unicycle Robots</span>
        <span>Flexible Sensors</span>
      </div>

      <p class="paper-cite">
        <strong>T. Li*</strong>,
        B. Jayawardhana,
        A. M. Kamat,
        and A. G. P. Kottapalli,
        “Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible
        Piezoresistive Sensors,”
        <em>IEEE Transactions on Robotics</em>,
        vol. 38,
        no. 1,
        pp. 448–462,
        Feb. 2022.
        <a
          href="https://doi.org/10.1109/TRO.2021.3076964"
          target="_blank"
          rel="noopener noreferrer"
        >
          DOI
        </a>
      </p>

    </div>

  </div>


  <!-- =====================
       Project 2
       ===================== -->

  <div class="project-container">

    <div class="project-video">
      {% include video.liquid
        path="/assets/video/CO.mp4"
        class="img-fluid rounded z-depth-1"
        controls=true
      %}
    </div>

    <div class="project-text">

      <h3>
        <a
          href="https://ieeexplore.ieee.org/document/10735338"
          target="_blank"
          rel="noopener noreferrer"
        >
          Collision-Free Source-Seeking Robot
        </a>
      </h3>

      <p class="project-summary">
        Safety-critical source-seeking control that enables a mobile robot to
        locate an unknown source while avoiding obstacles in cluttered and
        previously unknown environments.
      </p>

      <div class="project-tags">
        <span>Safety-Critical Control</span>
        <span>Control Barrier Functions</span>
        <span>Obstacle Avoidance</span>
      </div>

      <p class="paper-cite">
        <strong>T. Li*</strong>
        and B. Jayawardhana,
        “Collision-free Source Seeking Control Methods for Unicycle Robots,”
        <em>IEEE Transactions on Automatic Control</em>,
        vol. 70,
        no. 3,
        pp. 2020–2027,
        March 2025.
        <a
          href="https://doi.org/10.1109/TAC.2024.3486654"
          target="_blank"
          rel="noopener noreferrer"
        >
          DOI
        </a>
      </p>

    </div>

  </div>


  <!-- =====================
       Project 3
       ===================== -->

  <div class="project-container">

    <div class="project-video">
      {% include video.liquid
        path="/assets/video/connectivity.mp4"
        class="img-fluid rounded z-depth-1"
        controls=true
      %}
    </div>

    <div class="project-text">

      <h3>
        <a
          href="https://ieeexplore.ieee.org/document/11311473"
          target="_blank"
          rel="noopener noreferrer"
        >
          Flocking Control with Connectivity Preservation
        </a>
      </h3>

      <p class="project-summary">
        Distributed source-seeking and flocking control for multi-agent
        systems with collision avoidance, connectivity preservation, and
        coordinated motion using onboard sensing.
      </p>

      <div class="project-tags">
        <span>Multi-Agent Systems</span>
        <span>Distributed CBFs</span>
        <span>Connectivity Preservation</span>
      </div>

      <p class="paper-cite">
        <strong>T. Li*</strong>
        and B. Jayawardhana,
        “Collision-free Source Seeking and Flocking Control of Multi-agents
        with Connectivity Preservation,”
        <em>IEEE Transactions on Automatic Control</em>,
        vol. 71,
        no. 6,
        pp. 3696–3711,
        June 2026.
        <a
          href="https://doi.org/10.1109/TAC.2025.3647313"
          target="_blank"
          rel="noopener noreferrer"
        >
          DOI
        </a>
      </p>

    </div>

  </div>

</div>