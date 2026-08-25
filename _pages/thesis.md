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
   Thesis Header
======================================== */

.thesis-header {
  display: flex;
  gap: 40px;
  align-items: flex-start;
  margin-bottom: 2.5rem;
}

.thesis-left {
  flex: 1;
  min-width: 0;

  display: flex;
  flex-direction: column;
  align-items: center;
}

.thesis-image img {
  display: block;

  width: 100%;
  max-width: 300px;
  height: auto;

  border-radius: 0.5rem;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
}

.thesis-text {
  flex: 2;
  min-width: 0;

  text-align: left;
  color: var(--global-text-color);
}

.thesis-title {
  margin-bottom: 1rem;

  font-size: 1.5rem;
  font-weight: 700;
  line-height: 1.4;

  color: var(--global-text-color);
}

.thesis-text p {
  margin-bottom: 1rem;

  line-height: 1.75;
  color: var(--global-text-color);
}

.thesis-text h5 {
  margin-top: 1.4rem;
  margin-bottom: 0.5rem;

  font-size: 1.05rem;
  font-weight: 600;
  line-height: 1.5;

  color: var(--global-text-color);
}

.thesis-text ul {
  margin-top: 0.4rem;
  margin-bottom: 0.8rem;
  padding-left: 1.25rem;
}

.thesis-text li {
  margin-bottom: 0.3rem;
  line-height: 1.65;
}


/* ========================================
   Full Thesis Button
======================================== */

.thesis-link {
  margin-top: 1rem;
  margin-bottom: 0;

  text-align: center;
}

.thesis-link a {
  display: inline-block;

  padding: 0.5rem 1rem;

  color: #fff;
  background: var(--global-theme-color);

  border-radius: 0.35rem;

  font-size: 0.9rem;
  font-weight: 500;
  text-decoration: none;

  transition:
    opacity 0.2s ease,
    transform 0.2s ease;
}

.thesis-link a:hover {
  opacity: 0.9;
  transform: translateY(-1px);

  color: #fff;
  text-decoration: none;
}


/* ========================================
   Thesis Summary Figure
======================================== */

.thesis-summary-figure {
  width: 100%;
  max-width: 1000px;

  margin: 2.8rem auto 0;

  text-align: center;
}

.thesis-summary-figure img {
  display: block;

  width: 100%;
  height: auto;

  margin: 0 auto;

  border-radius: 0.65rem;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.10);
}


/* ========================================
   Section Divider
======================================== */

.section-divider {
  margin: 3.5rem 0;

  border: 0;
  border-top: 1px solid var(--global-divider-color);
}


/* ========================================
   Ph.D. Defence Gallery
======================================== */

.gallery-section {
  width: 100%;

  margin: 0 auto;

  color: var(--global-text-color);
}

.gallery-section h2 {
  margin: 0 0 1.8rem;

  font-size: 1.75rem;
  font-weight: 600;
  line-height: 1.4;
  text-align: center;

  color: var(--global-text-color);
}


/* Gallery grid */

.gallery-row {
  display: grid;

  grid-template-columns: repeat(3, minmax(0, 1fr));

  gap: 16px;

  width: 100%;
  max-width: 1000px;

  margin: 0 auto;
}


/* Gallery item */

.gallery-col {
  min-width: 0;

  overflow: hidden;

  border-radius: 0.6rem;
}


/* Equal-sized images */

.gallery-row img {
  display: block;

  width: 100%;
  aspect-ratio: 4 / 3;

  object-fit: cover;
  object-position: center center;

  border-radius: 0.6rem;

  box-shadow: 0 2px 7px rgba(0, 0, 0, 0.12);

  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease;
}

.gallery-row img:hover {
  transform: scale(1.015);

  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.16);
}


/* ----------------------------------------
   Individual crop adjustment

   如果某一张人物被裁掉，可以只修改这里，
   不会影响三张图片尺寸。
---------------------------------------- */

.gallery-col:nth-child(1) img {
  object-position: center center;
}

.gallery-col:nth-child(2) img {
  object-position: center center;
}

.gallery-col:nth-child(3) img {
  object-position: center center;
}


/* ========================================
   Defence Video
======================================== */

.gallery-video {
  width: 100%;
  max-width: 1000px;

  margin: 2.5rem auto 0;

  text-align: center;
}

.gallery-video video {
  display: block;

  width: 100%;
  height: auto;

  margin: 0 auto;

  border-radius: 0.6rem;

  box-shadow: 0 2px 7px rgba(0, 0, 0, 0.12);
}


/* ========================================
   Acknowledgements
======================================== */

.acknowledgment-section {
  width: 100%;
  max-width: 760px;

  margin: 0 auto 2rem;
  padding: 0 1rem;

  color: var(--global-text-color);

  opacity: 0;
  transform: translateY(20px);

  transition:
    opacity 0.8s ease-out,
    transform 0.8s ease-out;
}

.acknowledgment-section.visible {
  opacity: 1;
  transform: translateY(0);
}

.acknowledgment-section h2 {
  margin: 0 0 2rem;

  font-size: 1.75rem;
  font-weight: 600;
  line-height: 1.4;
  text-align: center;

  color: var(--global-text-color);
}

.acknowledgment-section p {
  margin: 0 0 1.4rem;

  font-size: 1rem;
  line-height: 1.85;
  text-align: left;

  color: var(--global-text-color);
}

.acknowledgment-section strong {
  font-weight: 600;
}


/* ========================================
   Acknowledgement Link
======================================== */

.acknowledgment-link {
  margin-top: 2.2rem;

  text-align: center;
}

.acknowledgment-link a {
  color: var(--global-theme-color);

  font-size: 0.95rem;
  text-decoration: none;
}

.acknowledgment-link a:hover {
  color: var(--global-hover-color);

  text-decoration: underline;
}


/* ========================================
   Dark Mode
======================================== */

html[data-theme="dark"] .thesis-image img,
html[data-theme="dark"] .thesis-summary-figure img,
html[data-theme="dark"] .gallery-row img,
html[data-theme="dark"] .gallery-video video {
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.30);
}


/* ========================================
   Tablet / Mobile
======================================== */

@media (max-width: 768px) {

  .thesis-header {
    flex-direction: column;

    gap: 1.5rem;
  }

  .thesis-left,
  .thesis-text {
    width: 100%;
  }

  .thesis-left {
    align-items: center;
  }

  .thesis-text {
    padding-top: 0.5rem;
  }

  .thesis-title {
    font-size: 1.35rem;
  }

  .thesis-summary-figure {
    margin-top: 2rem;
  }


  /* Gallery */

  .gallery-section h2,
  .acknowledgment-section h2 {
    font-size: 1.5rem;
  }

  .gallery-row {
    grid-template-columns: 1fr;

    gap: 14px;
  }

  .gallery-row img {
    aspect-ratio: 4 / 3;
  }

  .gallery-video {
    margin-top: 2rem;
  }


  /* Acknowledgements */

  .acknowledgment-section {
    padding: 0 0.5rem;
  }

  .acknowledgment-section p {
    font-size: 0.96rem;
    line-height: 1.8;
  }

  .section-divider {
    margin: 3rem 0;
  }
}


/* ========================================
   Small Phones
======================================== */

@media (max-width: 480px) {

  .thesis-image img {
    max-width: 250px;
  }

  .thesis-title {
    font-size: 1.25rem;
  }

  .thesis-text h5 {
    font-size: 1rem;
  }

  .thesis-summary-figure img,
  .gallery-row img,
  .gallery-video video {
    border-radius: 0.5rem;
  }

  .gallery-row {
    gap: 12px;
  }

  .acknowledgment-section h2 {
    margin-bottom: 1.5rem;
  }
}


/* ========================================
   Reduced Motion
======================================== */

@media (prefers-reduced-motion: reduce) {

  .gallery-row img,
  .acknowledgment-section {
    transition: none;
  }

  .acknowledgment-section {
    opacity: 1;
    transform: none;
  }
}

</style>


<!-- ======================================
     Thesis Overview
======================================= -->

<div class="thesis-header">

  <div class="thesis-left">

    <div class="thesis-image">

      <img
        src="{{ '/assets/img/thesis/cover.jpg' | relative_url }}"
        alt="Cover of the thesis Motion Control for Nonholonomic Unicycle Robots"
      >

    </div>


    <p class="thesis-link">

      <a
        href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots"
        target="_blank"
        rel="noopener noreferrer"
      >
        Full Thesis
      </a>

    </p>

  </div>


  <div class="thesis-text">

    <div class="thesis-title">
      Motion Control for Nonholonomic Unicycle Robots
    </div>


    <p>
      This doctoral research focuses on developing algorithms for
      nonholonomic robots in unknown cluttered environments, relying solely
      on limited onboard sensory measurements for exploration.
    </p>


    <h5>
      Part I: Safe Source Seeking for a Single Unicycle Robot
    </h5>

    <ul>
      <li>Projected gradient-ascent source-seeking control</li>
      <li>Safety guarantees for single robots in obstacle fields</li>
      <li>CBF design with uniform relative degree</li>
    </ul>


    <h5>
      Part II: Distributed Safe Motion Control for Multi-Agent Systems
    </h5>

    <ul>
      <li>Distributed CBF-QP framework</li>
      <li>Collision avoidance and connectivity preservation</li>
      <li>Adaptive spacing policy for flexible coordination</li>
    </ul>

  </div>

</div>


<!-- ======================================
     Thesis Summary Figure
======================================= -->

<div class="thesis-summary-figure">

  <img
    src="{{ '/assets/img/thesis/summary.png' | relative_url }}"
    alt="Summary of the Ph.D. research on motion control for nonholonomic unicycle robots"
    loading="lazy"
  >

</div>


<hr class="section-divider">


<!-- ======================================
     Ph.D. Defence Gallery
======================================= -->

<div class="gallery-section">

  <h2>Ph.D. Defence Gallery</h2>


  <div class="gallery-row">

    <div class="gallery-col">

      <img
        src="{{ '/assets/img/news/phd_1.jpg' | relative_url }}"
        alt="Ph.D. defence photo 1"
        loading="lazy"
      >

    </div>


    <div class="gallery-col">

      <img
        src="{{ '/assets/img/news/phd.jpg' | relative_url }}"
        alt="Ph.D. defence photo 2"
        loading="lazy"
      >

    </div>


    <div class="gallery-col">

      <img
        src="{{ '/assets/img/news/phd_3.jpg' | relative_url }}"
        alt="Ph.D. defence photo 3"
        loading="lazy"
      >

    </div>

  </div>


  <!-- Defence Video -->

  <div class="gallery-video">

    <video
      controls
      preload="metadata"
      playsinline
    >

      <source
        src="{{ '/assets/video/defence.mp4' | relative_url }}"
        type="video/mp4"
      >

      Your browser does not support the video tag.

    </video>

  </div>

</div>


<hr class="section-divider">


<!-- ======================================
     Acknowledgements
======================================= -->

<div
  class="acknowledgment-section"
  id="acknowledgments"
>

  <h2>Acknowledgements</h2>


  <p>
    I would like to sincerely thank my dearest supervisors,
    <strong>Prof. Bayu Jayawardhana</strong> and
    <strong>Prof. Ming Cao</strong>, for their constant support and guidance
    throughout my Ph.D. journey.
  </p>


  <p>
    I’m deeply grateful to my paranymphs,
    <strong>Simon Busman</strong> and
    <strong>Wouter Baar</strong>, for their invaluable help and friendship.
    Thanks to all my lovely colleagues and friends in the
    <strong>DTPA group</strong> for making this journey memorable.
  </p>


  <p>
    Heartfelt appreciation to the defense committee members for their
    insightful discussions and valuable feedback:
    Prof. Claudio De Persis,
    Prof. Dimos Dimarogonas,
    Prof. Tamas Keviczky,
    Prof. Raffaella Carloni,
    Prof. Maryam Ghandchi Tehrani,
    Prof. Sami Haddadin,
    Dr. Bahar Haghighat,
    and Dr. Ashish Cherukuri.
  </p>


  <div class="acknowledgment-link">

    <a
      href="{{ '/assets/pdf/acknowledge.pdf' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
    >
      Read the full acknowledgements →
    </a>

  </div>

</div>


<!-- ======================================
     Scroll Animation
======================================= -->

<script>
document.addEventListener("DOMContentLoaded", function () {

  const animatedSections = [
    document.getElementById("acknowledgments")
  ].filter(Boolean);


  const prefersReducedMotion = window.matchMedia(
    "(prefers-reduced-motion: reduce)"
  ).matches;


  if (
    prefersReducedMotion ||
    !("IntersectionObserver" in window)
  ) {

    animatedSections.forEach(function (section) {
      section.classList.add("visible");
    });

    return;
  }


  const observer = new IntersectionObserver(
    function (entries, currentObserver) {

      entries.forEach(function (entry) {

        if (entry.isIntersecting) {

          entry.target.classList.add("visible");

          currentObserver.unobserve(entry.target);

        }

      });

    },
    {
      threshold: 0.2
    }
  );


  animatedSections.forEach(function (section) {
    observer.observe(section);
  });

});
</script>