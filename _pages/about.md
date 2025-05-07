---
layout: about
title: About Me
permalink: /
profile:
  align: right
  image: Tinghua_li.jpg
  image_circular: false
social: true
---

<style>
/* ===== 全局紧凑排版 ===== */
:root {
  --theme-color: #6f42c1;
  --text-color: #333;
  --light-bg: #f8f9fa;
}

body {
  line-height: 1.5;
}

/* ===== 模块通用样式 ===== */
.about-section {
  margin-bottom: 2rem;
  padding: 1.2rem;
  background: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

/* ===== 紧凑型表格技能展示 ===== */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-top: 1rem;
}

.skill-category {
  background: var(--light-bg);
  padding: 1rem;
  border-radius: 6px;
  border-left: 3px solid var(--theme-color);
}

.skill-category h3 {
  margin-top: 0;
  color: var(--theme-color);
  font-size: 1.1rem;
}

.skill-list {
  margin: 0;
  padding-left: 1.2rem;
  columns: 2;
  column-gap: 1.5rem;
}

.skill-list li {
  font-size: 0.9rem;
  margin-bottom: 0.4rem;
  break-inside: avoid;
}

/* ===== 研究方向多列布局 ===== */
.research-columns {
  columns: 2;
  column-gap: 2rem;
}

.research-group {
  break-inside: avoid;
  margin-bottom: 1.2rem;
}

/* ===== 响应式调整 ===== */
@media (max-width: 768px) {
  .skills-grid {
    grid-template-columns: 1fr;
  }
  .research-columns {
    columns: 1;
  }
  .skill-list {
    columns: 1;
  }
}
</style>

<!-- 个人信息模块 -->
<section class="about-section">
  <h1>厉庭华</h1>
  <p class="subtitle">Postdoctoral Researcher @ <a href="https://www.tudelft.nl/lr">TU Delft</a></p>
  
  <div class="contact-badges">
    <span>✉️ tinghua.li@tudelft.nl</span>
    <span>📍 Delft, Netherlands</span>
  </div>

  <p class="education">
    <strong>PhD in Robotics & Control</strong><br>
    University of Groningen, 2024<br>
    Advisors: <a href="#">Prof. Bayu Jayawardhana</a>, <a href="#">Prof. Ming Cao</a>
  </p>
</section>

<!-- 研究方向模块 -->
<section class="about-section">
  <h2>Research Interests</h2>
  <div class="research-columns">
    <div class="research-group">
      <h3>Robotics</h3>
      <ul>
        <li>Nonholonomic Systems</li>
        <li>Multi-agent Systems</li>
        <li>Wheeled Mobile Robots</li>
        <li>Quadcopters</li>
      </ul>
    </div>

    <div class="research-group">
      <h3>Motion Control</h3>
      <ul>
        <li>Source seeking</li>
        <li>Flexible Flocking</li>
        <li>Safety Control</li>
      </ul>
    </div>
  </div>
</section>

<!-- 技术技能模块 -->
<section class="about-section">
  <h2>Technical Skills</h2>
  <div class="skills-grid">
    <div class="skill-category">
      <h3>Software</h3>
      <ul class="skill-list">
        <li>C/C++/Python/MATLAB</li>
        <li>ROS/Gazebo</li>
        <li>SLAM</li>
      </ul>
    </div>

    <div class="skill-category">
      <h3>Hardware</h3>
      <ul class="skill-list">
        <li>STM32/Arduino</li>
        <li>Sensor Integration</li>
        <li>Robotics Platforms</li>
        <li>3D Printing</li>
      </ul>
    </div>
  </div>
</section>