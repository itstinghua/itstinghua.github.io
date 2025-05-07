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

</style>


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
