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
  height: auto;
  border-radius: 0.5rem;
}
.thesis-title {
  margin-top: 1rem;
  text-align: center;
  font-size: 1.25rem;
  font-weight: bold;
}
.thesis-text {
  flex: 2;
  min-width: 0;
}
@media (max-width: 768px) {
  .thesis-header {
    flex-direction: column;
  }
  .thesis-left, .thesis-text {
    width: 100%;
  }
  .thesis-title {
    text-align: left;
  }
}
</style>

<div class="thesis-header">
  <div class="thesis-left">
    <div class="thesis-image">
      <img src="/assets/img/cover-all.png" class="img-fluid rounded">
    </div>
    <div class="thesis-title">
      Motion Control for Nonholonomic Unicycle Robots
    </div>
  </div>
  <div class="thesis-text">
    <p><a href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots">Full thesis available here</a></p>

    <p>This doctoral research focuses on developing algorithms for nonholonomic robots in an unknown cluttered scenario, where the robot solely relies on the limited onboard sensory measurements for exploration.</p>

    <p><strong>Part I</strong> bridges the gap between perception and control tasks, introducing:
    <ul>
      <li>Projected gradient-ascent source-seeking control</li>
      <li>Safety guarantees for single robots in obstacle fields</li>
      <li>CBF design with uniform relative degree</li>
    </ul>
    </p>

    <p><strong>Part II</strong> extends to multi-agent systems with:
    <ul>
      <li>Distributed CBF-QP framework</li>
      <li>Collision avoidance and connectivity preservation</li>
      <li>Adaptive spacing policy for flexible coordination</li>
    </ul>
    </p>
  </div>
</div>

---
<br>

## Acknowledgments  

**Ph.D. Supervisors:**  
Prof. Bayu Jayawardhana  
Prof. Ming Cao  

**Committee Members:**  
Prof. Claudio De Persis, Prof. Dimos Dimarogonas,  
Prof. Tamas Keviczky, Prof. Raffaella Carloni,  
Prof. Sami Haddadin, Prof. Maryam Ghandchi Tehrani,
Dr. Bahar Haghighat, Dr. Ashish Cherukuri. 

**Paranymphs:**
Simon Busman
Wouter Baar

**All my lovely colleagues, friends and family**

[Full acknowledgments available here](https://yourdomain.com/assets/pdf/acknowledge.pdf)

---
<br>

## Defense Gallery

<div class="row">
  <div class="col-sm-4">
    <img src="/assets/img/news/phd_1.jpg" class="img-fluid rounded">
  </div>
  <div class="col-sm-4">
    <img src="/assets/img/news/phd.jpg" class="img-fluid rounded">
  </div>
  <div class="col-sm-4">
    <img src="/assets/img/news/phd_3.jpg" class="img-fluid rounded">
  </div>
</div>

<div class="mt-3">
  <video controls class="img-fluid rounded">
    <source src="/assets/video/defence.mp4" type="video/mp4">
  </video>
</div>