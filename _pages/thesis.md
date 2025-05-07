---
layout: page
title: Ph.D. Thesis
permalink: /Ph.D.-thesis/
description: 
nav: true
nav_order: 5
---

<style>
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
  width: 100%;
  max-width: 300px;
  height: auto;
  border-radius: 0.5rem;
}

.thesis-text {
  flex: 2;
  min-width: 0;
  text-align: left;
}

.thesis-title {
  font-size: 1.5rem;
  font-weight: bold;
  margin-bottom: 1rem;
  line-height: 1.4;
}

.thesis-text h5 {
  margin-top: 1.2rem;
  font-size: 1.1rem;
  font-weight: 600;
}

.thesis-text ul {
  padding-left: 1.25rem;
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
}

@media (max-width: 768px) {
  .thesis-header {
    flex-direction: column;
  }
  .thesis-left, .thesis-text {
    width: 100%;
  }
  .thesis-text {
    padding-top: 1rem;
  }
}

/* Global font settings */
body {
  font-family: "Inter", "Helvetica Neue", "Segoe UI", "Roboto", sans-serif;
  font-size: 16px;
  line-height: 1.6;
  color: #222;
  background-color: #fff;
  margin: 0;
  padding: 0;
}

h1, h2, h3, h4 {
  font-family: "Inter", "Helvetica Neue", sans-serif;
  font-weight: 600;
  color: #111;
  margin-top: 1.2rem;
  margin-bottom: 0.6rem;
}

a {
  color: var(--primary-color);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

</style>

<!-- Thesis Summary Section -->
<div class="thesis-header">
  <div class="thesis-left">
    <div class="thesis-image">
      <img src="/assets/img/cover.jpg" class="img-fluid rounded" alt="Thesis Cover">
    </div>
    <p style="margin-top: 1rem;">
      <a href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots" class="btn btn-primary">Full Thesis</a>
    </p>
  </div>

  <div class="thesis-text">
    <div class="thesis-title">
      Motion Control for Nonholonomic Unicycle Robots
    </div>
    <p>This doctoral research focuses on developing algorithms for nonholonomic robots in unknown cluttered environments, relying solely on limited onboard sensory measurements for exploration.</p>

    <h5>Part I: Perception-Control Integration</h5>
    <ul>
      <li>Projected gradient-ascent source-seeking control</li>
      <li>Safety guarantees for single robots in obstacle fields</li>
      <li>CBF design with uniform relative degree</li>
    </ul>

    <h5>Part II: Multi-Agent Systems</h5>
    <ul>
      <li>Distributed CBF-QP framework</li>
      <li>Collision avoidance and connectivity preservation</li>
      <li>Adaptive spacing policy for flexible coordination</li>
    </ul>
  </div>
</div>


<hr>

<style>
.acknowledgment-section {
  margin-top: 3rem;
  line-height: 1.8;
  font-size: 1rem;
}
.acknowledgment-section h2 {
  font-size: 1.75rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  text-align: center;
}
.acknowledgment-section p {
  margin-bottom: 1rem;
}
.acknowledgment-section strong {
  font-weight: 600;
}
.acknowledgment-section a {
  color: #0056b3;
  text-decoration: underline;
}
</style>

<!-- Acknowledgments Section -->
<style>
.acknowledgment-section {
  margin-top: 3rem;
  padding: 2rem 1.5rem;
  background-color: #f9f9f9;
  border-radius: 1rem;
  box-shadow: 0 0.5rem 1.2rem rgba(0, 0, 0, 0.05);
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}

.acknowledgment-section.visible {
  opacity: 1;
  transform: translateY(0);
}

.acknowledgment-section h2 {
  font-size: 1.75rem;
  margin-bottom: 1.5rem;
  text-align: center;
}

.acknowledgment-section p {
  font-size: 1rem;
  line-height: 1.7;
  margin-bottom: 1rem;
}

.acknowledgment-section strong {
  font-weight: 600;
}

.acknowledgment-section a {
  display: inline-block;
  margin-top: 1rem;
  color: #007bff;
  text-decoration: underline;
}

@media (max-width: 768px) {
  .acknowledgment-section {
    padding: 1.5rem 1rem;
  }
}
</style>

<div class="acknowledgment-section" id="acknowledgments">
  <h2>Acknowledgments</h2>
  <p>I would like to sincerely thank my dearest supervisors <strong>Prof. Bayu Jayawardhana</strong> and <strong>Prof. Ming Cao</strong> for their constant support and guidance throughout my Ph.D. journey.</p>

  <p>I’m deeply grateful to my paranymphs <strong>Simon Busman</strong> and <strong>Wouter Baar</strong> for their invaluable help and friendship. Thanks to all my lovely colleagues and friends in the <strong>DTPA group</strong> for making this journey memorable.</p>

  <p>Heartfelt appreciation to the defense committee members for their insightful discussions and valuable feedback: <strong>Prof. Claudio De Persis, Prof. Dimos Dimarogonas, Prof. Tamas Keviczky, Prof. Raffaella Carloni, Prof. Maryam Ghandchi Tehrani, Prof. Sami Haddadin, Dr. Bahar Haghighat, and Dr. Ashish Cherukuri</strong>.</p>

  <a href="/assets/pdf/acknowledge.pdf" target="_blank">Read the full acknowledgment here →</a>
</div>

<!-- Intersection Observer Script for Scroll Animation -->
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add("visible");
        }
      });
    }, {
      threshold: 0.2
    });

    const section = document.getElementById("acknowledgments");
    if (section) observer.observe(section);
  });
</script>



<hr>

<style>
.gallery-section {
  margin-top: 3rem;
}

.gallery-section h2 {
  font-size: 1.75rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  text-align: center;
}

.gallery-row {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
}

.gallery-row img {
  border-radius: 0.75rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
  object-fit: cover;
  height: 100%;
  width: 100%;
}

.gallery-col {
  flex: 1 1 30%;
  max-width: 320px;
}

.gallery-video {
  margin-top: 2rem;
  text-align: center;
}

.gallery-video video {
  max-width: 800px;
  width: 100%;
  border-radius: 0.75rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
}
</style>

<!-- Defense Gallery Section -->
<div class="gallery-section">
  <h2>Defense Gallery</h2>

  <div class="gallery-row">
    <div class="gallery-col">
      <img src="/assets/img/news/phd_1.jpg" alt="Defense Photo 1">
    </div>
    <div class="gallery-col">
      <img src="/assets/img/news/phd.jpg" alt="Defense Photo 2">
    </div>
    <div class="gallery-col">
      <img src="/assets/img/news/phd_3.jpg" alt="Defense Photo 3">
    </div>
  </div>

  <div class="gallery-video">
    <video controls>
      <source src="/assets/video/defence.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>
