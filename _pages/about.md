---
layout: about
title: About Me
permalink: /
profile:
  align: right
  # image: Tinghua_li.jpg
  # image_circular: false
social: true
---

<style>
:root {
  --primary-color:#00539C;
  --light-bg: #f8f9fa;
  --border-color: #e0e0e0;
}

/* Profile header */
.profile-header {
  display: flex;
  align-items: flex-start;
  gap: 30px;
  flex-wrap: wrap; /* 保证移动端换行 */
  margin-bottom: 2rem;
}

.profile-photo {
  width: 180px;      /* 更大尺寸 */
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  flex-shrink: 0;    /* 防止在小屏压缩照片 */
}

.profile-info {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
  flex: 1;           /* 占据剩余宽度 */
}

.position-info, .education-info {
  font-size: 1rem;
  line-height: 1.5;
}

.contact-badges span {
  display: inline-block;
  margin-top: 6px;
  font-size: 0.95rem;
  color: #555;
}

/* 手机端优化 */
@media (max-width: 600px) {
  .profile-header {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .profile-photo {
    width: 140px;
  }

  .profile-info {
    align-items: center;
  }
}


/* Compact sections */
.compact-section {
  margin-bottom: 2.5rem;
}
.compact-section h2 {
  border-bottom: 2px solid var(--primary-color);
  padding-bottom: 0.3rem;
  margin-bottom: 1.2rem;
}

/* Research grid */
.research-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
  margin-top: 1rem;
}

.research-group h3 {
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
  color: #333;
}

.research-group ul {
  list-style-type: disc;
  padding-left: 1.2rem;
  margin: 0;
}

.research-group li {
  margin-bottom: 0.3rem;
  font-size: 0.95rem;
}

/* Responsive for smaller screens */
@media (max-width: 768px) {
  .research-grid {
    grid-template-columns: 1fr;
  }
}

/* Skills table */
.skills-table {
  width: 100%;
  border-collapse: collapse;
  margin: 1rem 0;
}
.skills-table th {
  text-align: left;
  padding: 0.8rem 1rem;
  background-color: var(--light-bg);
  color: var(--primary-color);
  width: 25%;
}
.skills-table td {
  padding: 0.8rem 1rem;
  border-bottom: 1px solid var(--border-color);
}
.skills-list {
  margin: 0;
  padding-left: 0;
  list-style: none;
}
.skills-list li {
  margin-bottom: 0.5rem;
  position: relative;
  padding-left: 1.2rem;
}
.skills-list li:before {
  content: "•";
  color: var(--primary-color);
  position: absolute;
  left: 0;
}

/* Publications */
.publication-item {
  margin-bottom: 1.5rem;
}
.publication-title {
  font-weight: 600;
  margin-bottom: 0.3rem;
}
.publication-authors {
  font-style: italic;
  margin-bottom: 0.3rem;
}
.publication-venue {
  color: #555;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .profile-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
  }
  .research-grid {
    grid-template-columns: 1fr;
  }
  .skills-table th {
    width: 30%;
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

<!-- Profile Header with Photo -->
<div class="profile-header">
  <img src="/assets/img/Tinghua_li.jpg" alt="Tinghua Li (厉庭华)" class="profile-photo">

  <div class="profile-info">
    <div class="position-info">
      <p><strong>Postdoctoral Researcher</strong></p>
      <p>
        <a href="https://www.tudelft.nl/lr/organisatie/afdelingen/control-and-operations/control-and-simulation">
          Control & Simulation, Delft University of Technology (2025–)
        </a>
      </p>
      <div class="contact-badges">
        <span>📍 Delft, Netherlands</span>
      </div>
    </div>

    <div class="education-info">
      <p>
        <strong>PhD in Robotics & Control Engineering</strong>, 2024<br>
        <a href="https://www.rug.nl/research/discrete-technology-production-automation/?lang=en">
          DTPA, University of Groningen
        </a><br>
        Advisors:
        <a href="https://www.rug.nl/staff/b.jayawardhana">Prof. Bayu Jayawardhana</a> and
        <a href="https://www.rug.nl/staff/m.cao/">Prof. Ming Cao</a>
      </p>
    </div>
  </div>
</div>


<!-- Research Interests -->
<section class="compact-section">
  <h2>Research Interests</h2>
  <div class="research-grid">
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
        <li>Collision/Obstacle Avoidance</li>
        <li>Sensor Integration</li>
      </ul>
    </div>
    <div class="research-group">
      <h3>Applications</h3>
      <ul>
        <li>3D-Printed Flexible Sensors</li>
        <li>Navigation in Cluttered Environments</li>
      </ul>
    </div>
  </div>
</section>


<!-- Technical Skills -->
<section class="compact-section">
  <h2>Technical Skills</h2>
  <table class="skills-table">
    <tr>
      <th>Software</th>
      <td>
        <ul class="skills-list">
          <li>C/C++/Python/MATLAB</li>
          <li>ROS/Gazebo/OpenCV</li>
          <li>SLAM/Point Cloud Processing</li>
        </ul>
      </td>
    </tr>
    <tr>
      <th>Hardware</th>
      <td>
        <ul class="skills-list">
          <li>STM32/Arduino</li>
          <li>LiDAR/RealSense Integration</li>
          <li>Mecanum-wheel Platforms</li>
        </ul>
      </td>
    </tr>
  </table>
</section>

<!-- Selected Publications -->
<section class="compact-section">
  <h2>Selected Publications</h2>
  <div class="publication-item">
    <div class="publication-title">Collision-free Source Seeking Control Methods for Unicycle Robots</div>
    <div class="publication-authors"><strong>Tinghua Li</strong>, Bayu Jayawardhana</div>
    <div class="publication-venue">IEEE Transactions on Automatic Control, 2024</div>
  </div>
  <div class="publication-item">
    <div class="publication-title">Source-seeking control with 3D-printed flexible sensors</div>
    <div class="publication-authors"><strong>Tinghua Li</strong>, B. Jayawardhana, A.M. Kamat</div>
    <div class="publication-venue">IEEE Transactions on Robotics, 2022</div>
  </div>
</section>

<!-- Contact -->
<section class="compact-section">
  <h2>Contact</h2>
  <p>Open to collaborations and discussions. Please reach out via email or social media links :)</p>
</section>