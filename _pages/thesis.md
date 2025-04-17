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
    max-width: 300px;
    height: auto;
    border-radius: 0.5rem;
    margin-bottom: 1rem;
  }
  .thesis-title {
    text-align: center;
    font-size: 1.25rem;
    font-weight: bold;
    margin-bottom: 1.5rem;
  }
  .thesis-text {
    flex: 2;
    min-width: 0;
  }
  @media (max-width: 768px) {
    .thesis-header {
      flex-direction: column;
      gap: 20px;
    }
    .thesis-left {
      align-items: center;
    }
  }
  .gallery-row {
    margin-bottom: 1rem;
  }
</style>

<!-- Thesis Summary Section -->
<div class="thesis-header">
  <div class="thesis-left">
    <div class="thesis-image">
      <img src="/assets/img/cover.jpg" class="img-fluid rounded" alt="Thesis Cover">
    </div>
    <p class="text-center">
      <a href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots" class="btn btn-primary">Full Thesis PDF</a>
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

<div class="row">
  <div class="col-md-6">
    <h5>Ph.D. Supervisors:</h5>
    <ul>
      <li>Prof. Bayu Jayawardhana</li>
      <li>Prof. Ming Cao</li>
    </ul>
  </div>
  <div class="col-md-6">
    <h5>Committee Members:</h5>
    <ul>
      <li>Prof. Claudio De Persis</li>
      <li>Prof. Dimos Dimarogonas</li>
      <li>Prof. Tamas Keviczky</li>
      <li>Prof. Raffaella Carloni</li>
      <li>Prof. Sami Haddadin</li>
      <li>Prof. Maryam Ghandchi Tehrani</li>
      <li>Dr. Bahar Haghighat</li>
      <li>Dr. Ashish Cherukuri</li>
    </ul>
  </div>
</div>

<p><strong>Paranymphs:</strong> Simon Busman, Wouter Baar</p>
<p>All my lovely colleagues, friends and family</p>

<p><a href="/assets/pdf/acknowledge.pdf" class="btn btn-outline-primary">Full Acknowledgments</a></p>

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