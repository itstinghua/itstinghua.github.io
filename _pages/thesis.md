---
layout: page
title: Ph.D. Thesis
permalink: /Ph.D.-thesis/
description:
nav: true
nav_order: 6
---

<style>
/* ========================================
   Main page container
======================================== */

.thesis-page {
  width: 100%;
  max-width: 920px;
  margin: 0 auto;
  color: var(--global-text-color);
}


/* ========================================
   Thesis overview
======================================== */

.thesis-header {
  display: grid;
  grid-template-columns: 240px minmax(0, 1fr);
  gap: 3rem;
  align-items: start;

  margin: 1.5rem 0 3rem;
}


/* Thesis cover */

.thesis-cover {
  width: 100%;
}

.thesis-cover img {
  display: block;
  width: 100%;
  height: auto;

  border-radius: 6px;
  border: 1px solid var(--global-divider-color);
}


/* Thesis information */

.thesis-info {
  min-width: 0;
}

.thesis-title {
  margin: 0 0 0.75rem;

  font-size: clamp(1.55rem, 2.5vw, 1.9rem);
  font-weight: 600;
  line-height: 1.35;

  color: var(--global-text-color);
}

.thesis-meta {
  margin-bottom: 1.25rem;

  font-size: 0.9rem;
  line-height: 1.6;

  color: var(--global-text-color);
  opacity: 0.62;
}

.thesis-summary {
  margin: 0 0 1.5rem;

  font-size: 1rem;
  line-height: 1.8;

  color: var(--global-text-color);
}


/* ========================================
   Full thesis button
======================================== */

.thesis-link {
  display: inline-block;

  padding: 0.55rem 1rem;

  border: 1px solid var(--global-theme-color);
  border-radius: 6px;

  color: var(--global-theme-color);
  background: transparent;

  font-size: 0.92rem;
  font-weight: 500;

  text-decoration: none;

  transition:
    background-color 0.2s ease,
    color 0.2s ease;
}

.thesis-link:hover {
  color: #fff;
  background: var(--global-theme-color);
  text-decoration: none;
}


/* ========================================
   Large thesis summary figure
======================================== */

.thesis-summary-figure {
  width: 100%;
  margin: 0 0 4rem;
}

.thesis-summary-figure figure {
  margin: 0;
}

.thesis-summary-figure img {
  display: block;
  width: 100%;
  height: auto;

  border-radius: 8px;
  border: 1px solid var(--global-divider-color);
}

.thesis-summary-caption {
  margin: 0.8rem auto 0;
  max-width: 760px;

  font-size: 0.86rem;
  line-height: 1.6;
  text-align: center;

  color: var(--global-text-color);
  opacity: 0.6;
}


/* ========================================
   Section divider
======================================== */

.section-divider {
  margin: 4rem 0 0;

  border: 0;
  border-top: 1px solid var(--global-divider-color);
}


/* ========================================
   Shared section
======================================== */

.thesis-section {
  margin-top: 3.5rem;
}

.thesis-section h2 {
  margin: 0 0 1.6rem;

  font-size: 1.4rem;
  font-weight: 600;
  line-height: 1.4;

  color: var(--global-text-color);
}


/* ========================================
   Research highlights
======================================== */

.highlight-list {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 2.5rem;
}

.highlight-item {
  min-width: 0;
}

.highlight-item h3 {
  margin: 0 0 0.65rem;

  font-size: 1.08rem;
  font-weight: 600;
  line-height: 1.4;

  color: var(--global-text-color);
}

.highlight-item p {
  margin: 0;

  font-size: 0.96rem;
  line-height: 1.75;

  color: var(--global-text-color);
  opacity: 0.88;
}


/* ========================================
   Defence gallery
======================================== */

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));

  gap: 12px;
}

.gallery-grid img {
  display: block;

  width: 100%;
  aspect-ratio: 4 / 3;

  object-fit: cover;

  border-radius: 6px;
  border: 1px solid var(--global-divider-color);
}


/* ========================================
   Defence video
======================================== */

.gallery-video {
  margin-top: 16px;
}

.gallery-video video {
  display: block;

  width: 100%;
  height: auto;

  border-radius: 6px;
  border: 1px solid var(--global-divider-color);

  background: #000;
}


/* ========================================
   Acknowledgments
======================================== */

.acknowledgments {
  max-width: 820px;
}

.acknowledgments p {
  margin: 0 0 1rem;

  font-size: 0.98rem;
  line-height: 1.8;

  color: var(--global-text-color);
}

.acknowledgments strong {
  font-weight: 600;
}

.acknowledgments a {
  display: inline-block;
  margin-top: 0.3rem;

  color: var(--global-theme-color);
  text-decoration: none;
}

.acknowledgments a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}


/* ========================================
   Dark mode
======================================== */

html[data-theme="dark"] .thesis-cover img,
html[data-theme="dark"] .thesis-summary-figure img,
html[data-theme="dark"] .gallery-grid img,
html[data-theme="dark"] .gallery-video video {
  border-color: var(--global-divider-color);
}


/* ========================================
   Tablet / mobile
======================================== */

@media (max-width: 768px) {

  .thesis-page {
    max-width: 100%;
  }

  .thesis-header {
    grid-template-columns: 1fr;

    gap: 1.8rem;

    margin-top: 1rem;
    margin-bottom: 2.5rem;
  }

  .thesis-cover {
    width: 100%;
    max-width: 280px;

    margin: 0 auto;
  }

  .thesis-info {
    width: 100%;
  }

  .thesis-summary-figure {
    margin-bottom: 3rem;
  }

  .highlight-list {
    grid-template-columns: 1fr;
    gap: 1.7rem;
  }

  .gallery-grid {
    grid-template-columns: 1fr;
    gap: 14px;
  }

  .gallery-grid img {
    aspect-ratio: 4 / 3;
  }

  .section-divider {
    margin-top: 3rem;
  }

  .thesis-section {
    margin-top: 2.8rem;
  }
}


/* ========================================
   Small phones
======================================== */

@media (max-width: 480px) {

  .thesis-cover {
    max-width: 230px;
  }

  .thesis-title {
    font-size: 1.4rem;
  }

  .thesis-summary {
    font-size: 0.94rem;
  }

  .thesis-section h2 {
    font-size: 1.25rem;
  }

  .highlight-item p,
  .acknowledgments p {
    font-size: 0.94rem;
  }

  .thesis-summary-caption {
    font-size: 0.8rem;
  }
}
</style>


<div class="thesis-page">


  <!-- ======================================
       Thesis overview
  ======================================= -->

  <section class="thesis-header">


    <!-- Thesis cover -->

    <div class="thesis-cover">

      <img
        src="{{ '/assets/img/thesis/cover.jpg' | relative_url }}"
        alt="Cover of the thesis Motion Control for Nonholonomic Unicycle Robots"
      >

    </div>


    <!-- Thesis description -->

    <div class="thesis-info">

      <h1 class="thesis-title">
        Motion Control for Nonholonomic Unicycle Robots
      </h1>

      <div class="thesis-meta">
        Ph.D. Thesis · University of Groningen
      </div>

      <p class="thesis-summary">
        This doctoral research focuses on developing motion-control methods
        for nonholonomic robots operating in unknown and cluttered environments.
        The proposed algorithms rely only on limited onboard sensory measurements
        and address autonomous exploration, source seeking, obstacle avoidance,
        multi-agent coordination, and connectivity preservation.
      </p>

      <a
        href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots"
        class="thesis-link"
        target="_blank"
        rel="noopener noreferrer">
        Full Thesis →
      </a>

    </div>

  </section>



  <!-- ======================================
       Thesis summary figure
  ======================================= -->

  <section class="thesis-summary-figure">

    <figure>

      <img
        src="{{ '/assets/img/thesis/summary.png' | relative_url }}"
        alt="Research overview of the PhD thesis on motion control for nonholonomic robots"
      >

      <figcaption class="thesis-summary-caption">
        Overview of the research topics and control methods developed in this thesis.
      </figcaption>

    </figure>

  </section>



  <!-- ======================================
       Research Highlights
  ======================================= -->

  <hr class="section-divider">


  <section class="thesis-section">

    <h2>
      Research Highlights
    </h2>


    <div class="highlight-list">


      <!-- Highlight 1 -->

      <div class="highlight-item">

        <h3>
          Safe Source Seeking
        </h3>

        <p>
          Source-seeking control methods for single nonholonomic robots,
          combining gradient-based exploration with safety guarantees
          for navigation in unknown and obstacle-filled environments.
        </p>

      </div>


      <!-- Highlight 2 -->

      <div class="highlight-item">

        <h3>
          Distributed Safe Motion Control
        </h3>

        <p>
          Distributed control-barrier-function frameworks for multi-agent
          systems, addressing collision avoidance, connectivity preservation,
          coordinated motion, and adaptive inter-agent spacing.
        </p>

      </div>


    </div>

  </section>



  <!-- ======================================
       PhD Defence
  ======================================= -->

  <hr class="section-divider">


  <section class="thesis-section">

    <h2>
      PhD Defence
    </h2>


    <!-- Photos -->

    <div class="gallery-grid">

      <img
        src="{{ '/assets/img/news/phd_1.jpg' | relative_url }}"
        alt="PhD defence photo 1"
        loading="lazy"
      >

      <img
        src="{{ '/assets/img/news/phd.jpg' | relative_url }}"
        alt="PhD defence photo 2"
        loading="lazy"
      >

      <img
        src="{{ '/assets/img/news/phd_3.jpg' | relative_url }}"
        alt="PhD defence photo 3"
        loading="lazy"
      >

    </div>


    <!-- Defence video -->

    <div class="gallery-video">

      <video
        controls
        preload="metadata"
        playsinline>

        <source
          src="{{ '/assets/video/defence.mp4' | relative_url }}"
          type="video/mp4">

        Your browser does not support the video tag.

      </video>

    </div>

  </section>



  <!-- ======================================
       Acknowledgments
  ======================================= -->

  <hr class="section-divider">


  <section class="thesis-section acknowledgments">

    <h2>
      Acknowledgments
    </h2>


    <p>
      I would like to sincerely thank my dearest supervisors,
      <strong>Prof. Bayu Jayawardhana</strong> and
      <strong>Prof. Ming Cao</strong>,
      for their constant support and guidance throughout my Ph.D. journey.
    </p>


    <p>
      I am deeply grateful to my paranymphs,
      <strong>Simon Busman</strong> and
      <strong>Wouter Baar</strong>,
      for their invaluable help and friendship.
      I also thank all my lovely colleagues and friends in the
      <strong>DTPA group</strong>
      for making this journey memorable.
    </p>


    <p>
      Heartfelt appreciation goes to the members of my defense committee
      for their insightful discussions and valuable feedback:
      <strong>
        Prof. Claudio De Persis,
        Prof. Dimos Dimarogonas,
        Prof. Tamas Keviczky,
        Prof. Raffaella Carloni,
        Prof. Maryam Ghandchi Tehrani,
        Prof. Sami Haddadin,
        Dr. Bahar Haghighat,
        and Dr. Ashish Cherukuri.
      </strong>
    </p>


    <a
      href="{{ '/assets/pdf/acknowledge.pdf' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer">
      Read the full acknowledgment →
    </a>

  </section>


</div>