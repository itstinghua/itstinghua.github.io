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

<!-- Acknowledgments Section -->
<h2>Acknowledgments</h2>
- I would like to thank my dearest supervisor **Prof. Bayu Jayawardhana** and **Prof. Ming Cao** for their warm support in the past four-year study, thank  **Simon Busman** and **Wouter Baar** for being my best paranymphs, thank my lovely colleagues and friends in DTPA group. Thank you for all defense committee members for the great discussion during the defense: **Prof. Claudio De Persis, Prof. Dimos Dimarogonas, Prof. Tamas Keviczky, Prof. Raffaella Carloni, Prof. Maryam Ghandchi Tehrani, Prof. Sami Haddadin, Dr. Bahar Haghighat, Dr. Ashish Cherukuri**. 
- <a href="/assets/pdf/acknowledge.pdf"  target = "_blank"> My full acknowledgment is here. </a>

<hr>

<!-- Defense Gallery Section -->
<h2>Defense Gallery</h2>

<div class="row gallery-row">
  <div class="col-sm-4 mb-3">
    <img src="/assets/img/news/phd_1.jpg" class="img-fluid rounded" alt="Defense Photo 1">
  </div>
  <div class="col-sm-4 mb-3">
    <img src="/assets/img/news/phd.jpg" class="img-fluid rounded" alt="Defense Photo 2">
  </div>
  <div class="col-sm-4 mb-3">
    <img src="/assets/img/news/phd_3.jpg" class="img-fluid rounded" alt="Defense Photo 3">
  </div>
</div>

<div class="mt-3">
  <video controls class="img-fluid rounded w-100">
    <source src="/assets/video/defence.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>