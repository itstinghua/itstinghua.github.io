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
<meta charset="UTF-8">
<style>
:root {
  --primary-color: var(--global-theme-color);
  --light-bg: var(--global-card-bg-color);  
  --border-color: var(--global-divider-color);
}

/* Profile header */
.profile-header {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}

.profile-photo {
  width: 200px;
  object-fit: cover;
  border: none;
  flex-shrink: 0;
}

.profile-info { flex: 1; }

.name-heading {
  font-size: 1.8rem;
  margin-bottom: 0.5rem;
  font-weight: bold;
}

.profile-section p {
  margin: 0;
  line-height: 1.6;
  color: var(--global-text-color); /* ✅ */
}

.profile-section a {
  color: var(--primary-color);
  text-decoration: none;
}

.profile-section a:hover { text-decoration: underline; }

.contact-badges span {
  display: inline-block;
  margin-top: 6px;
  font-size: 0.95rem;
  color: var(--global-text-color-light); 
}

/* 手机端优化 */
@media (max-width: 600px) {
  .profile-header {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .profile-photo { width: 140px; }
  .profile-info { align-items: center; }
}

/* Compact sections */
.compact-section { margin-bottom: 2.5rem; }
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
  margin-top: 1.2rem;
}

.research-group h3 {
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
  color: var(--global-text-color); 
}

.research-group ul {
  list-style-type: disc;
  padding-left: 1.2rem;
  margin: 0;
}

.research-group li {
  margin-bottom: 0.3rem;
  font-size: 0.95rem;
  color: var(--global-text-color); 
}

/* Responsive */
@media (max-width: 768px) {
  .research-grid { grid-template-columns: 1fr; }
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
  border-bottom: 1px solid var(--border-color);
}

.skills-table td {
  padding: 0.8rem 1rem;
  border-bottom: 1px solid var(--border-color);
  color: var(--global-text-color);        
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
  color: var(--global-text-color);        
}
.skills-list li:before {
  content: "•";
  color: var(--primary-color);
  position: absolute;
  left: 0;
}

/* Publications */
.publication-item { margin-bottom: 1.5rem; }
.publication-title {
  font-weight: 600;
  margin-bottom: 0.3rem;
  color: var(--global-text-color);        
}
.publication-authors {
  font-style: italic;
  margin-bottom: 0.3rem;
  color: var(--global-text-color);        
}
.publication-venue {
  color: var(--global-text-color-light);  
}

/* Global font settings */
body {
  font-family: "Inter", "Helvetica Neue", "Segoe UI", "Roboto", sans-serif;
  font-size: 16px;
  line-height: 1.6;
  color: var(--global-text-color);
  background-color: var(--global-bg-color);
  margin: 0;
  padding: 0;
}

h1, h2, h3, h4 {
  font-family: "Inter", "Helvetica Neue", sans-serif;
  font-weight: 600;
  color: var(--global-text-color); 
  margin-bottom: 0.6rem;
  font-size: 23px;
}

a {
  color: var(--primary-color);
  text-decoration: none;
}
a:hover { text-decoration: underline; }

.chinese-name {
  font-family: 'KaiTi', 'STKaiti', '楷体', serif;
  font-size: 1.4rem;
  margin-left: 10px;
  color: var(--global-text-color); 
}
</style>


<!-- Profile Header with Photo -->
<div class="profile-header"> <img src="/assets/img/Tinghua_li.jpg" class="profile-photo">

  <div class="profile-info">
     <h2>
      <span class="chinese-name">厉庭华 (/ˈtɪŋ-hwɑː li:/)</span>
    </h2>
    <div class="profile-section">
      <p>
        <strong>Postdoctoral Researcher (2025–)</strong><br>
        <a href="https://www.tudelft.nl/lr/organisatie/afdelingen/control-and-operations/control-and-simulation">Control & Simulation, Delft University of Technology </a><br>
        <span>📍🇳🇱 Delft, Netherlands</span><br>
      </p>
    </div>
    <br>
    <div class="profile-section">
      <p>
        <strong>PhD in Robotics & Control Engineering (2024)</strong><br>
        <a href="https://www.rug.nl/research/discrete-technology-production-automation/?lang=en">
          DTPA Group, University of Groningen 
        </a><br>
        Advisors:
        <a href="https://www.rug.nl/staff/b.jayawardhana">Prof. Bayu Jayawardhana</a> and
        <a href="https://www.rug.nl/staff/m.cao/">Prof. Ming Cao</a><br>
        <span>📍🇳🇱 Groningen, Netherlands</span>  
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
        <li>Aerial Robots</li>
      </ul>
    </div>
    <div class="research-group">
      <h3>Motion Control</h3>
      <ul>
        <li>Source seeking</li>
        <li>Flexible Flocking</li>
        <li>Collision/Obstacle Avoidance</li>
        <li>Safe Flight Control</li>
      </ul>
    </div>
  <!--   <div class="research-group">
      <h3>Applications</h3>
      <ul>
        <li>3D-Printed Flexible Sensors</li>
        <li>Navigation in Cluttered Environments</li>
         <li>Aerial Robots</li>
      </ul>
    </div> -->
  </div>
</section>


<!-- Selected Publications -->
<section class="compact-section">
  <h2>Selected Publications</h2>
   <div class="publication-item">
    <div class="publication-title">Collision-free Source Seeking and Flocking Control of Multi-agents with Connectivity Preservation</div>
    <div class="publication-authors"><strong>Tinghua Li*</strong>, Bayu Jayawardhana</div>
    <div class="publication-venue">IEEE Transactions on Automatic Control (TAC), To appear in June, 2026</div>
  </div>
  <div class="publication-item">
    <div class="publication-title"><a href="https://ieeexplore.ieee.org/document/10735338">Collision-free Source Seeking Control Methods for Unicycle Robots</a></div>
    <div class="publication-authors"><strong>Tinghua Li*</strong>, Bayu Jayawardhana</div>
    <div class="publication-venue">IEEE Transactions on Automatic Control (TAC), 2025 </div>
  <!-- vol. 70, no. 3, pp. 2020-2027, March 2025, doi: 10.1109/TAC.2024.3486654. </div> -->
  </div>
  <div class="publication-item">
    <div class="publication-title"><a href="https://ieeexplore.ieee.org/document/9458274">Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors</a> </div>
    <div class="publication-authors"><strong>Tinghua Li*</strong>, Bayu Jayawardhana, Amar M. Kamat, Ajay Giri Prakash Kottapalli</div>
    <div class="publication-venue">IEEE Transactions on Robotics (TRO), 2022</div>
    <!-- vol. 38, no. 1, pp. 448-462, Feb. 2022, doi: 10.1109/TRO.2021.3076964.</div> -->
  </div>
</section>



<!-- Technical Skills -->
<!-- <section class="compact-section">
  <h2>Technical Skills</h2>
  <table class="skills-table">
    <tr>
      <th>Software</th>
      <td>
        <ul class="skills-list">
          <li>C/C++/Python/MATLAB</li>
          <li>ROS/Gazebo/OpenCV</li>
          <li>SLAM</li>
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
</section> -->

<!-- Contact -->
<!-- <section class="compact-section">
  <h2>Contact</h2>
  <p>Open to collaborations and discussions. Please reach out via email or social media links :)</p>
</section> -->