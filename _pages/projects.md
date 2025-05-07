---
layout: page
title: Projects
permalink: /projects/
description:
nav: true
nav_order: 2
---

<style>
/*.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 20px;
}*/
.reference {
  background-color: #f0f8ff;  
  padding: 10px;
  border-radius: 5px;
  margin: 0.5rem 0;
}
.project-container {
  display: flex;
  gap: 40px;
  align-items: center;
  margin-bottom: 3rem;
}
.project-video {
  flex: 1;
  min-width: 0;
  max-width: 50%; /* 新增：限制视频最大宽度 */
}
.project-video video {
  width: 100%;
  max-height: 300px; /* 新增：限制视频最大高度 */
}
.project-text {
  flex: 1;
  min-width: 0;
}
.project-text h3 {
  margin-top: 0;
  font-size: 1.25rem;
  font-weight: 600;
  color: #00539C;
}
@media (max-width: 768px) {
  .project-container {
    flex-direction: column;
    gap: 20px;
  }
  .project-video {
    max-width: 100%; /* 移动端恢复全宽 */
  }
}

/* Global font settings */


</style>

<div class="container">

<!-- Visit my <a href="https://www.youtube.com/channel/UCAduhzSeh_5dEN9CteFiM9w" target="_blank">YouTube channel</a> for more videos. -->


<br>

<div class="project-container">
  <div class="project-video">
    {% include video.liquid path="/assets/video/SS.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
  <div class="project-text">
    <h3>
      <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458274&tag=1">Source-seeking Robot</a>
    </h3>
    <p>
      Experimental validation of source seeking control for unicycle robots with 3D-printed graphene-based airflow sensors. The algorithm ensures convergence to the source even with partial sensor failure.
    </p>
    <p style="margin-top: 0.5rem;">
      <p class="reference">
      • <strong>T. Li</strong>, B. Jayawardhana, A. M. Kamat and A. G. P. Kottapalli, “Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors”, in <strong>IEEE Transactions on Robotics (TRO)</strong>, vol. 38, no. 1, pp. 448–462, Feb. 2022, doi: 10.1109/TRO.2021.3076964.
      </p>
    </p>
  </div>
</div>



<div class="project-container">
  <div class="project-video">
    {% include video.liquid path="/assets/video/CO.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
  <div class="project-text">
    <h3>
      <a href="https://ieeexplore.ieee.org/document/10735338">Collision-free Source-seeking</a>
    </h3>
    <p>
      Collision-free source-seeking framework integrating control barrier functions (CBFs) in quadratic programming. Includes analysis of three CBF designs with experimental validation.
    </p>
    <p style="margin-top: 0.5rem;">
      <p class="reference">
      •  <strong>T. Li</strong> and B. Jayawardhana, “Collision-free Source Seeking Control Methods for Unicycle Robots”, in
      <strong>IEEE Transactions on Automatic Control (TAC)</strong>, vol. 70, no. 3, pp. 2020–2027, March 2025, doi: 10.1109/TAC.2024.3486654.
       </p>
    </p>
  </div>
</div>




<div class="project-container">
  <div class="project-video">
    {% include video.liquid path="/assets/video/connectivity.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
  <div class="project-text">
    <h3><a href="https://arxiv.org/pdf/2301.04576.pdf">Flocking Control with Connectivity Preservation</a></h3>
    <p>Distributed control method for networked multi-agent systems with non-holonomic constraints. Maintains flocking cohesion while ensuring connectivity preservation and collision avoidance.</p>
    <p style="margin-top: 0.5rem;">
     <p class="reference">
      • <strong>T. Li</strong> and B. Jayawardhana, “Collision-free Source Seeking and Flocking Control of Multi-agents with Connectivity Preservation", arXiv preprint arXiv:2301.04576, 2023. (<strong>conditionally accepted as regular paper in IEEE Transactions on Automatic Control (T-AC)</strong>)
       </p>
    </p>
  </div>
</div>

</div>