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
/* 页面动画和排版样式 */
.fade-in-section {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}
.fade-in-section.visible {
  opacity: 1;
  transform: translateY(0);
}
section.about-section {
  margin-bottom: 3rem;
  padding-right: 1rem;
}
ul {
  margin-top: 0.3rem;
  margin-bottom: 1rem;
  padding-left: 1.2rem;
}
.flex-columns {
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
}
.flex-column {
  flex: 1;
  min-width: 200px;
}

/* 表格样式 */
.skills-table {
  width: 100%;
  border-collapse: collapse;
  margin: 1rem 0;
  font-size: 0.95rem;
}

.skills-table th, .skills-table td {
  padding: 12px 15px;
  text-align: left;
  border-bottom: 1px solid #e0e0e0;
}

.skills-table th {
  background-color: #f8f9fa;
  font-weight: 600;
}

.skills-table tr:hover {
  background-color: #f5f5f5;
}

/* 技能列表样式 */
.skills-list {
  margin: 0;
  padding-left: 0;
  list-style-type: none;
}

.skills-list li {
  margin-bottom: 5px;
  position: relative;
  padding-left: 1.2em;
}

.skills-list li:before {
  content: "•";
  color: #6f42c1; /* 紫色圆点 */
  position: absolute;
  left: 0;
}
.skills-table {
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}
@media (max-width: 768px) {
  .skills-table {
    font-size: 0.9rem;
  }
}
.skills-table td {
  padding: 8px 12px;
}
</style>

<!-- 🔹 个人简介模块 -->
<section id="about" class="fade-in-section about-section">
  <header>
    <strong>厉庭华</strong><br>
    Postdoctoral Researcher<br>
    <a href="https://www.tudelft.nl/lr/organisatie/afdelingen/control-and-operations/control-and-simulation">
      C&S, Delft University of Technology (2025--)
    </a>
  </header>

  <div style="height: 1rem;"></div>

  <p>
    PhD in Robotics & Control Engineering (2024)<br>
    <a href="https://www.rug.nl/research/discrete-technology-production-automation/?lang=en">
      DTPA, University of Groningen
    </a><br>
    Advisor:
    <a href="https://www.rug.nl/staff/b.jayawardhana">Prof. Bayu Jayawardhana</a> and
    <a href="https://www.rug.nl/staff/m.cao/">Prof. Ming Cao</a>
  </p>
</section>

<!-- 🔹 研究方向模块 -->
<section id="research" class="fade-in-section about-section">
  <h2>Research Interests</h2>

  <p><strong>Robotics</strong></p>
  <ul>
    <li>Nonholonomic Systems</li>
    <li>Multi-agent Systems</li>
    <li>Wheeled Mobile Robots</li>
    <li>Quadcopters</li>
  </ul>

  <p><strong>Motion Control</strong></p>
  <ul>
    <li>Source seeking</li>
    <li>Flexible Flocking</li>
    <li>Safety Control (Collision/Obstacle avoidance)</li>
    <li>Loss-of-Control</li>
  </ul>

  <p><strong>Practical Applications</strong></p>
  <ul>
    <li>3D-Printed Flexible Piezoresistive Sensors</li>
    <li>Navigation in the cluttered environment</li>
  </ul>

  <p><em>Bridging theoretical control methods with practical robotic implementations</em></p>
</section>


<!-- 🔹 技术技能模块 -->
<section id="skills" class="fade-in-section about-section">
  <h2>Technical Skills</h2>

  <table class="skills-table">
    <tr>
      <th>Category</th>
      <th>Skills</th>
    </tr>
    <tr>
      <td><strong>Software</strong></td>
      <td>
        <ul class="skills-list">
          <li>C/C++</li>
          <li>Python</li>
          <li>MATLAB</li>
          <li>ROS</li>
          <li>Gazebo</li>
          <li>OpenCV</li>
          <li>SLAM</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Hardware</strong></td>
      <td>
        <ul class="skills-list">
          <li>STM32 / Arduino</li>
          <li>Sensor Integration (LiDAR, RealSense)</li>
          <li>Mecanum-wheel Robotics Platforms</li>
        </ul>
      </td>
    </tr>
  </table>
</section>

<!-- 🔹 联系方式模块 -->
<section id="contact" class="fade-in-section about-section">
  <h2>Contact</h2>
  <p>Open to collaborations and discussions ↓</p>
</section>

<!-- 🔹 页面动画脚本 -->
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add("visible");
        }
      });
    }, {
      threshold: 0.15
    });

    document.querySelectorAll(".fade-in-section").forEach(el => {
      observer.observe(el);
    });
  });
</script>
