---
layout: page
title: Ph.D. Thesis
permalink: /Ph.D.-thesis/
description: 
nav: true
nav_order: 6
---

<style>
/* ---------------------------
   Thesis Header
   --------------------------- */
.thesis-header {
  display: flex;
  gap: 40px;
  align-items: flex-start;
  margin-bottom: 2rem;
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
  font-weight: bold;
  line-height: 1.4;
  color: var(--global-text-color);
}

.thesis-text h5 {
  margin-top: 1.2rem;
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--global-text-color);
}

.thesis-text ul {
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
  padding-left: 1.25rem;
}

@media (max-width: 768px) {
  .thesis-header {
    flex-direction: column;
  }

  .thesis-left,
  .thesis-text {
    width: 100%;
  }

  .thesis-text {
    padding-top: 1rem;
  }
}


/* ---------------------------
   Shared Section Divider
   --------------------------- */
.section-divider {
  margin: 3rem 0;
  border: 0;
  border-top: 1px solid var(--global-divider-color);
}


/* ---------------------------
   Gallery
   --------------------------- */
.gallery-section {
  margin-top: 3rem;
  color: var(--global-text-color);
}

.gallery-section h2 {
  margin-bottom: 1.5rem;
  font-size: 1.75rem;
  font-weight: 600;
  text-align: center;
  color: var(--global-text-color);
}

.gallery-row {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
}

.gallery-col {
  flex: 1 1 30%;
  max-width: 320px;
  overflow: hidden;
  border-radius: 0.75rem;
}

.gallery-row img {
  display: block;
  width: 100%;
  height: 260px;
  object-fit: cover;
  border-radius: 0.75rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
  transition:
    transform 0.3s ease,
    box-shadow 0.3s ease;
}

.gallery-row img:hover {
  transform: scale(1.025);
  box-shadow: 0 8px 18px rgba(0, 0, 0, 0.18);
}

.gallery-video {
  margin-top: 2rem;
  text-align: center;
}

.gallery-video video {
  display: block;
  width: 100%;
  max-width: 1000px;
  margin: 0 auto;
  border-radius: 0.75rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
}

@media (max-width: 768px) {
  .gallery-col {
    flex: 1 1 100%;
    max-width: 100%;
  }

  .gallery-row img {
    height: auto;
    aspect-ratio: 4 / 3;
  }
}


/* ---------------------------
   Vincent van Gogh Image
   --------------------------- */
.artwork-section {
  margin-top: 3rem;
  color: var(--global-text-color);
}

.artwork-section h2 {
  margin-bottom: 1.5rem;
  font-size: 1.75rem;
  font-weight: 600;
  line-height: 1.4;
  text-align: center;
  color: var(--global-text-color);
}

.artwork-card {
  max-width: 1000px;
  margin: 0 auto;
  padding: 1rem;

  background-color: rgba(0, 83, 156, 0.05);
  border: 1px solid var(--global-divider-color);
  border-radius: 1rem;
  box-shadow: 0 0.5rem 1.2rem rgba(0, 0, 0, 0.08);

  opacity: 0;
  transform: translateY(30px);
  transition:
    opacity 0.8s ease-out,
    transform 0.8s ease-out,
    box-shadow 0.3s ease;
}

.artwork-card.visible {
  opacity: 1;
  transform: translateY(0);
}

.artwork-card:hover {
  box-shadow: 0 0.8rem 1.8rem rgba(0, 0, 0, 0.14);
}

.artwork-card figure {
  margin: 0;
}

.artwork-card img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 0.75rem;
}

.artwork-caption {
  margin-top: 1rem;
  margin-bottom: 0;
  padding: 0 0.5rem 0.25rem;

  font-size: 0.95rem;
  line-height: 1.7;
  text-align: center;
  color: var(--global-text-color-light);
}

.artwork-caption strong {
  color: var(--global-text-color);
}

html[data-theme="dark"] .artwork-card {
  background-color: rgba(255, 255, 255, 0.04);
  box-shadow: 0 0.5rem 1.2rem rgba(0, 0, 0, 0.25);
}

@media (max-width: 768px) {
  .artwork-card {
    padding: 0.75rem;
  }

  .artwork-section h2 {
    font-size: 1.5rem;
  }
}


/* ---------------------------
   Acknowledgments Card
   --------------------------- */
.acknowledgment-section {
  margin-top: 3rem;
  padding: 2rem 1.5rem;

  font-size: 1rem;
  line-height: 1.8;

  background-color: rgba(0, 83, 156, 0.08);
  border: 1px solid var(--global-divider-color);
  border-radius: 1rem;
  box-shadow: 0 0.5rem 1.2rem rgba(0, 0, 0, 0.05);

  opacity: 0;
  transform: translateY(30px);
  transition:
    opacity 0.8s ease-out,
    transform 0.8s ease-out;

  color: var(--global-text-color);
}

.acknowledgment-section.visible {
  opacity: 1;
  transform: translateY(0);
}

.acknowledgment-section h2 {
  margin-bottom: 1.5rem;
  font-size: 1.75rem;
  font-weight: 600;
  text-align: center;
  color: var(--global-text-color);
}

.acknowledgment-section p {
  margin-bottom: 1rem;
  color: var(--global-text-color);
}

.acknowledgment-section strong {
  font-weight: 600;
}

.acknowledgment-section a {
  display: inline-block;
  margin-top: 1rem;
  color: var(--global-theme-color);
  text-decoration: underline;
}

.acknowledgment-section a:hover {
  color: var(--global-hover-color);
}

html[data-theme="dark"] .acknowledgment-section {
  background-color: rgba(255, 255, 255, 0.05);
  box-shadow: 0 0.5rem 1.2rem rgba(0, 0, 0, 0.25);
}

@media (max-width: 768px) {
  .acknowledgment-section {
    padding: 1.5rem 1rem;
  }
}


/* ---------------------------
   Reduced Motion
   --------------------------- */
@media (prefers-reduced-motion: reduce) {
  .gallery-row img,
  .artwork-card,
  .acknowledgment-section {
    transition: none;
  }

  .artwork-card,
  .acknowledgment-section {
    opacity: 1;
    transform: none;
  }
}
</style>


<!-- Thesis Summary Section -->
<div class="thesis-header">

  <div class="thesis-left">
    <div class="thesis-image">
      <img
        src="/assets/img/thesis/cover.jpg"
        class="img-fluid rounded"
        alt="Cover of the thesis Motion Control for Nonholonomic Unicycle Robots"
      >
    </div>

    <p style="margin-top: 1rem;">
      <a
        href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots"
        class="btn btn-primary"
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
      Part I: Safe Source Seeking (for Single Unicycle Robot)
    </h5>

    <ul>
      <li>Projected gradient-ascent source-seeking control</li>
      <li>Safety guarantees for single robots in obstacle fields</li>
      <li>CBF design with uniform relative degree</li>
    </ul>

    <h5>
      Part II: Distributed Safe Motion Control (for Multi-Agent System)
    </h5>

    <ul>
      <li>Distributed CBF-QP framework</li>
      <li>Collision avoidance and connectivity preservation</li>
      <li>Adaptive spacing policy for flexible coordination</li>
    </ul>
  </div>

</div>


<hr class="section-divider">


<!-- Defense Gallery Section -->
<div class="gallery-section">

  <h2>PhD Defence Gallery</h2>

  <div class="gallery-row">

    <div class="gallery-col">
      <img
        src="/assets/img/news/phd_1.jpg"
        alt="PhD defence photo 1"
        loading="lazy"
      >
    </div>

    <div class="gallery-col">
      <img
        src="/assets/img/news/phd.jpg"
        alt="PhD defence photo 2"
        loading="lazy"
      >
    </div>

    <div class="gallery-col">
      <img
        src="/assets/img/news/phd_3.jpg"
        alt="PhD defence photo 3"
        loading="lazy"
      >
    </div>

  </div>

  <div class="gallery-video">
    <video controls preload="metadata" playsinline>
      <source
        src="/assets/video/defence.mp4"
        type="video/mp4"
      >
      Your browser does not support the video tag.
    </video>
  </div>

</div>


<hr class="section-divider">



<hr class="section-divider">


<!-- Acknowledgments Section -->
<div
  class="acknowledgment-section"
  id="acknowledgments"
>
  <h2>Acknowledgments</h2>

  <p>
    I would like to sincerely thank my dearest supervisors
    <strong>Prof. Bayu Jayawardhana</strong> and
    <strong>Prof. Ming Cao</strong> for their constant support and guidance
    throughout my Ph.D. journey.
  </p>

  <p>
    I’m deeply grateful to my paranymphs
    <strong>Simon Busman</strong> and
    <strong>Wouter Baar</strong> for their invaluable help and friendship.
    Thanks to all my lovely colleagues and friends in the
    <strong>DTPA group</strong> for making this journey memorable.
  </p>

  <p>
    Heartfelt appreciation to the defense committee members for their
    insightful discussions and valuable feedback:
    <strong>
      Prof. Claudio De Persis, Prof. Dimos Dimarogonas,
      Prof. Tamas Keviczky, Prof. Raffaella Carloni,
      Prof. Maryam Ghandchi Tehrani, Prof. Sami Haddadin,
      Dr. Bahar Haghighat, and Dr. Ashish Cherukuri
    </strong>.
  </p>

  <a
    href="/assets/pdf/acknowledge.pdf"
    target="_blank"
    rel="noopener noreferrer"
  >
    Read the full acknowledgment here →
  </a>
</div>




<!-- Intersection Observer Script for Scroll Animation -->
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const animatedSections = [
      document.getElementById("starry-nights-artwork"),
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
```
