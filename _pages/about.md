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
.fade-in-section {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}
.fade-in-section.visible {
  opacity: 1;
  transform: translateY(0);
}
.about-section {
  margin-bottom: 3rem;
}
ul {
  margin-top: 0.3rem;
  margin-bottom: 1rem;
}
</style>

<div class="fade-in-section about-section">
  <strong>厉庭华</strong>  
  <br>Postdoctoral Researcher  
  <br><a href="https://www.tudelft.nl/lr/organisatie/afdelingen/control-and-operations/control-and-simulation">C&S, Delft University of Technology</a>

  <p>PhD in Robotics & Control Engineering (2024)  
  <br><a href="https://www.rug.nl/research/discrete-technology-production-automation/?lang=en">DTPA, University of Groningen</a>  
  <br>Advisor: <a href="https://www.rug.nl/staff/b.jayawardhana">Prof. Bayu Jayawardhana</a> and <a href="https://www.rug.nl/staff/m.cao/">Prof. Ming Cao</a></p>
</div>

<div class="fade-in-section about-section">
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
</div>

<div class="fade-in-section about-section">
  <h2>Technical Skills</h2>

  <div style="display: flex; flex-wrap: wrap; gap: 40px;">
    <div style="flex: 1; min-width: 200px;">
      <p><strong>Software</strong></p>
      <ul>
        <li>C/C++</li>
        <li>Python</li>
        <li>MATLAB</li>
        <li>ROS</li>
        <li>Gazebo</li>
        <li>OpenCV</li>
        <li>SLAM</li>
        <li>Point Cloud Processing</li>
      </ul>
    </div>

    <div style="flex: 1; min-width: 200px;">
      <p><strong>Hardware</strong></p>
      <ul>
        <li>STM32 / Arduino</li>
        <li>Sensor Integration (LiDAR, RealSense)</li>
        <li>Mecanum-wheel Robotics Platforms</li>
      </ul>
    </div>
  </div>
</div>

<div class="fade-in-section about-section">
  <h2>Contact</h2>
  <p>Open to collaborations and discussions ↓</p>
</div>

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
