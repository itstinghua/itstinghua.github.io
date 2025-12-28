---
layout: page
title: Research
permalink: /research/
description:
nav: true
nav_order: 2
---

<style>
/* 注意：不要重写全站 .container（会影响别的页面）
   用本页专属容器类更安全 */
.research-container {
  max-width: 1000px;
  margin: 0 auto;
}

/* 单个项目卡片 */
.project-container {
  display: flex;
  gap: 20px;              /* 你原来写成了 20xp（拼写错误），这里修正 */
  align-items: center;
  margin-bottom: 2rem;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 12px;

  padding: 20px;
  width: 100%;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-container:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

/* 视频区 */
.project-video {
  flex: 1;
  min-width: 0;
  max-width: 50%;
}
.project-video video {
  width: 95%;
  border-radius: 8px;
}

/* 文本区 */
.project-text {
  flex: 1;
  min-width: 0;
  color: var(--global-text-color);
}

.project-text h3 {
  margin-top: 0;
  font-size: 1.25rem;
  font-weight: 600;
  color: var(--global-theme-color);
}

/* 标题链接 */
.project-text h3 a {
  color: var(--global-theme-color);
  text-decoration: none;
}
.project-text h3 a:hover {
  text-decoration: underline;
  color: var(--global-hover-color);
}

/* 引用信息块：浅色模式淡蓝，深色模式变暗一点 */
.paper-cite {
  margin-top: 0.5rem;
  padding: 10px;
  border-radius: 10px;
  border: 1px solid var(--global-divider-color);
  background-color: rgba(0, 83, 156, 0.08); /* 适配浅色背景 */
  color: var(--global-text-color);
}

/* 深色模式下引用块更“暗”、但文字更亮 */
html[data-theme="dark"] .paper-cite {
  background-color: rgba(230, 237, 243, 0.06);
}

/* 移动端 */
@media (max-width: 768px) {
  .project-container {
    flex-direction: column;
    gap: 20px;
  }
  .project-video {
    max-width: 100%;
  }
}
</style>

<div class="container">

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
    <p class="paper-cite">
      • <strong>T. Li*</strong>, B. Jayawardhana, A. M. Kamat and A. G. P. Kottapalli, “Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors”, in
      <strong>IEEE Transactions on Robotics (TRO)</strong>, vol. 38, no. 1, pp. 448–462, Feb. 2022,
      doi: 10.1109/TRO.2021.3076964
    </p>
  </div>
</div>

<div class="project-container">
  <div class="project-video">
    {% include video.liquid path="/assets/video/CO.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
  <div class="project-text">
    <h3>
      <a href="https://ieeexplore.ieee.org/document/10735338">Collision-free Source-seeking Robot</a>
    </h3>
    <p>
      Collision-free source-seeking framework integrating control barrier functions (CBFs) in quadratic programming. Includes analysis of three CBF designs with experimental validation.
    </p>
    <p class="paper-cite">
      •  <strong>T. Li*</strong> and B. Jayawardhana, “Collision-free Source Seeking Control Methods for Unicycle Robots”, in
      <strong>IEEE Transactions on Automatic Control (TAC)</strong>, vol. 70, no. 3, pp. 2020–2027, March 2025,
      doi: 10.1109/TAC.2024.3486654
    </p>
  </div>
</div>

<div class="project-container">
  <div class="project-video">
    {% include video.liquid path="/assets/video/connectivity.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
  <div class="project-text">
    <h3><a href = "https://ieeexplore.ieee.org/document/11311473">Flocking Control with Connectivity Preservation</a></h3>
    <p>
      Distributed control method for networked multi-agent systems with non-holonomic constraints. Maintains flocking cohesion while ensuring connectivity preservation and collision avoidance.
    </p>
   <p class="paper-cite">
      •  <strong>T. Li*</strong> and B. Jayawardhana, “Collision-free Source Seeking and Flocking Control of Multi-agents with Connectivity Preservation", in <strong>IEEE Transactions on Automatic Control (T-AC)</strong>, doi: 10.1109/TAC.2025.3647313
    </p>
  </div>
</div>

</div>
