---
layout: page
title: Projects
permalink: /projects/
description:
nav: true
nav_order: 2
---

<style>
/* 全局容器样式 */
.container {
  max-width: 1000px;     /* 设置页面最大宽度 */
  margin: 0 auto;        /* 左右居中 */
/*  padding: 20px 30px;    /* 内边距（可根据需要调整） */*/
/*  box-sizing: border-box;*/
}

/* Flex 容器样式 */
.project-container {
  display: flex;
  align-items: stretch;
  gap: 1rem;
  margin-bottom: 3rem;   /* 每组之间添加间隔 */
}

/* 视频与文本区域 */
.project-video,
.project-text {
  flex: 1;
  min-width: 0;
}

/* 视频样式 */
.project-video video {
  width: 100%;
/*  height: 100%;*/
  object-fit: cover;
/*  border-radius: 2px;*/
}

/* 文本排版 */
.project-text {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.project-text h3 {
  margin-top: 0;
  font-size: 1.25rem;
  font-weight: 600;
  color: #00539C;
}

.project-text p {
  font-size: 1rem;
  line-height: 1.6;
}

/* 参考信息块 */
.reference {
  background-color: #f0f8ff;
  padding: 10px;
  border-radius: 5px;
  margin-top: 0.5rem;
  font-size: 0.95rem;
}

/* 响应式：小屏幕下改为竖排 */
@media (max-width: 768px) {
  .project-container {
    flex-direction: column;
  }

  .project-video video {
    height: auto;
  }

  .container {
    padding: 10px 15px; /* 减小内边距 */
  }
}
</style>

<div class="container">

  <!-- 第一个项目 -->
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
      <p class="reference">
        • <strong>T. Li</strong>, B. Jayawardhana, A. M. Kamat and A. G. P. Kottapalli, “Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors”, in <strong>IEEE Transactions on Robotics (TRO)</strong>, vol. 38, no. 1, pp. 448–462, Feb. 2022, doi: 10.1109/TRO.2021.3076964.
      </p>
    </div>
  </div>

  <!-- 第二个项目 -->
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
      <p class="reference">
        •  <strong>T. Li</strong> and B. Jayawardhana, “Collision-free Source Seeking Control Methods for Unicycle Robots”, in <strong>IEEE Transactions on Automatic Control (TAC)</strong>, vol. 70, no. 3, pp. 2020–2027, March 2025, doi: 10.1109/TAC.2024.3486654.
      </p>
    </div>
  </div>

  <!-- 第三个项目 -->
  <div class="project-container">
    <div class="project-video">
      {% include video.liquid path="/assets/video/connectivity.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="project-text">
      <h3>
        <a href="https://arxiv.org/pdf/2301.04576.pdf">Flocking Control with Connectivity Preservation</a>
      </h3>
      <p>
        Distributed control method for networked multi-agent systems with non-holonomic constraints. Maintains flocking cohesion while ensuring connectivity preservation and collision avoidance.
      </p>
      <p class="reference">
        • <strong>T. Li</strong> and B. Jayawardhana, “Collision-free Source Seeking and Flocking Control of Multi-agents with Connectivity Preservation", arXiv preprint arXiv:2301.04576, 2023. (<strong>conditionally accepted as regular paper in IEEE Transactions on Automatic Control (T-AC)</strong>)
      </p>
    </div>
  </div>

</div>
