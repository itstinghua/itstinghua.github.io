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


/* =========================
   Introduction
========================= */

.research-intro {
  width: 100%;

  margin: 0 0 3.5rem;

  font-size: 1.02rem;
  line-height: 1.75;

  color: var(--global-text-color);
}


/* =========================
   Section Titles
========================= */

.research-section-title {
  margin: 0 0 1.8rem;

  font-size: 1.55rem;
  font-weight: 600;
  line-height: 1.4;

  color: var(--global-text-color);
}


/* =========================
   Ph.D. Research
========================= */

.phd-research {
  width: 100%;

  margin-bottom: 4rem;
  padding-bottom: 3.5rem;

  border-bottom: 1px solid var(--global-divider-color);
}


/* -------------------------
   Ph.D. Overview
------------------------- */

.phd-overview {
  display: grid;

  grid-template-columns: 210px minmax(0, 1fr);

  gap: 32px;
  align-items: start;
}


/* Thesis cover */

.phd-cover {
  min-width: 0;
}

.phd-cover img {
  display: block;

  width: 100%;
  height: auto;

  border-radius: 6px;

  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.10);
}


/* Thesis text */

.phd-content {
  min-width: 0;

  color: var(--global-text-color);
}

.phd-content h3 {
  margin: 0 0 0.8rem;

  font-size: 1.3rem;
  font-weight: 600;
  line-height: 1.4;

  color: var(--global-text-color);
}

.phd-description {
  margin: 0 0 1.3rem;

  font-size: 0.97rem;
  line-height: 1.7;

  color: var(--global-text-color);
}


/* -------------------------
   Ph.D. Research Parts
------------------------- */

.phd-part {
  margin-bottom: 1rem;
}

.phd-part strong {
  display: block;

  margin-bottom: 0.25rem;

  font-size: 0.93rem;
  font-weight: 600;
  line-height: 1.5;

  color: var(--global-text-color);
}

.phd-part span {
  display: block;

  font-size: 0.9rem;
  line-height: 1.6;

  color: var(--global-text-color-light);
}


/* -------------------------
   Thesis Link
------------------------- */

.phd-link {
  display: inline-block;

  margin-top: 0.4rem;

  font-size: 0.9rem;
  font-weight: 500;

  color: var(--global-theme-color);

  text-decoration: none;
}

.phd-link:hover {
  color: var(--global-hover-color);

  text-decoration: underline;
}


/* -------------------------
   Thesis Summary Figure
------------------------- */

.phd-summary {
  width: 100%;

  margin-top: 2.3rem;
}

.phd-summary img {
  display: block;

  width: 100%;
  height: auto;

  border-radius: 8px;

  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.10);
}


/* =========================
   Selected Projects
========================= */

.projects-section {
  width: 100%;
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
   Project Media
------------------------- */

.project-video {
  min-width: 0;
}

.project-video video {
  display: block;

  width: 100%;
  height: auto;

  border: 1px solid var(--global-divider-color);
  border-radius: 6px;
}


/* -------------------------
   Project Text
------------------------- */

.project-text {
  min-width: 0;

  color: var(--global-text-color);
}


/* Project title */

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


/* -------------------------
   Project Summary
------------------------- */

.project-summary {
  margin: 0 0 1rem;

  font-size: 0.97rem;
  line-height: 1.65;

  color: var(--global-text-color);
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


/* =========================
   Dark Mode
========================= */

html[data-theme="dark"] .project-video video {
  border-color: var(--global-divider-color);
}

html[data-theme="dark"] .phd-cover img,
html[data-theme="dark"] .phd-summary img {
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.30);
}


/* =========================
   Tablet / Mobile
========================= */

@media (max-width: 768px) {

  .research-intro {
    margin-bottom: 3rem;

    font-size: 1rem;
    line-height: 1.7;
  }


  /* Section title */

  .research-section-title {
    font-size: 1.4rem;
    margin-bottom: 1.5rem;
  }


  /* Ph.D. Research */

  .phd-research {
    margin-bottom: 3rem;
    padding-bottom: 3rem;
  }

  .phd-overview {
    grid-template-columns: 1fr;

    gap: 20px;
  }

  .phd-cover {
    width: 100%;
    max-width: 220px;

    margin: 0 auto;
  }

  .phd-content h3 {
    font-size: 1.18rem;
  }

  .phd-description {
    font-size: 0.95rem;
  }

  .phd-summary {
    margin-top: 2rem;
  }


  /* Projects */

  .project-container {
    grid-template-columns: 1fr;

    gap: 18px;

    padding-bottom: 2.25rem;
    margin-bottom: 2.25rem;
  }

  .project-text h3 {
    margin-bottom: 0.6rem;

    font-size: 1.18rem;
  }

  .project-summary {
    font-size: 0.95rem;
  }

  .paper-cite {
    font-size: 0.83rem;
  }
}


/* =========================
   Small Mobile
========================= */

@media (max-width: 480px) {

  .project-container {
    gap: 16px;
  }

  .phd-cover {
    max-width: 200px;
  }

}

</style>


<div class="research-container">


  <!-- =====================
       Research Introduction
  ====================== -->

  <p class="research-intro">
    My research focuses on safe and intelligent autonomous robotic systems
    operating in unknown and cluttered environments. My PhD research
    investigated safety-critical motion control for wheeled mobile robots,
    while my current postdoctoral work extends this line of research to aerial
    robotics by developing safety-critical control methods for autonomous and
    safe flight.
  </p>



  <!-- =====================
       Ph.D. Research
  ====================== -->

  <section class="phd-research">

    <h2 class="research-section-title">
      Ph.D. Research
    </h2>


    <div class="phd-overview">


      <!-- Thesis Cover -->

      <div class="phd-cover">

        <img
          src="{{ '/assets/img/thesis/cover.jpg' | relative_url }}"
          alt="Cover of the thesis Motion Control for Nonholonomic Unicycle Robots"
        >

      </div>


      <!-- Thesis Information -->

      <div class="phd-content">

        <h3>
          Motion Control for Nonholonomic Unicycle Robots
        </h3>


        <p class="phd-description">
          My doctoral research focused on safety-critical motion control for
          nonholonomic mobile robots operating in unknown and cluttered
          environments using limited onboard sensing.
        </p>


        <div class="phd-part">

          <strong>
            Part I — Safe Source Seeking for a Single Unicycle Robot
          </strong>

          <span>
            Source-seeking control, obstacle avoidance, and control barrier
            function design for autonomous exploration using local sensory
            measurements.
          </span>

        </div>


        <div class="phd-part">

          <strong>
            Part II — Distributed Safe Motion Control for Multi-Agent Systems
          </strong>

          <span>
            Distributed safety-critical control for multi-agent systems with
            collision avoidance, connectivity preservation, and coordinated
            motion.
          </span>

        </div>


        <a
          class="phd-link"
          href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots"
          target="_blank"
          rel="noopener noreferrer"
        >
          View Full Thesis →
        </a>

      </div>

    </div>


    <!-- Thesis Summary Figure -->

    <div class="phd-summary">

      <img
        src="{{ '/assets/img/thesis/summary.png' | relative_url }}"
        alt="Summary of the Ph.D. research on motion control for nonholonomic unicycle robots"
        loading="lazy"
      >

    </div>

  </section>



  <!-- =====================
       Selected Research Projects
  ====================== -->

  <section class="projects-section">

    <h2 class="research-section-title">
      Selected Research Projects
    </h2>



    <!-- =====================
         Project 1
    ====================== -->

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

        </p>

      </div>

    </div>



    <!-- =====================
         Project 2
    ====================== -->

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


        <p class="paper-cite">

          <strong>T. Li*</strong>
          and B. Jayawardhana,

          “Collision-free Source Seeking Control Methods for Unicycle Robots,”

          <em>IEEE Transactions on Automatic Control</em>,

          vol. 70,
          no. 3,
          pp. 2020–2027,
          March 2025.

        </p>

      </div>

    </div>



    <!-- =====================
         Project 3
    ====================== -->

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

        </p>

      </div>

    </div>


  </section>


</div>