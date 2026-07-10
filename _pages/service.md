---
layout: page
permalink: /service/
title: Service
description: 
nav: true
nav_order: 4
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

.service-section {
  margin-bottom: 3rem;
}

.service-section h4 {
  margin-bottom: 0.8rem;
  font-size: 1.25rem;
  border-left: 4px solid #00539C;
  padding-left: 0.6rem;
  font-weight: 600;
  color: #00539C;
}

.service-section ul {
  margin-top: 0;
  padding-left: 1.2rem;
}

.service-section li {
  margin-bottom: 0.35rem;
}

.service-section li::marker {
  color: #00539C;
  font-size: 0.85em;
}

.service-section li.indent {
  margin-left: 1.5rem;
}
</style>

<div class="fade-in-section service-section">
  <h4>Journal Reviewer</h4>
  <ul>
    <li>IEEE Transactions on Robotics (T-RO)</li>
    <li>IEEE Robotics and Automation Letters (RA-L)</li>
    <li>IEEE Robotics & Automation Magazine (RA-M)</li>
    <li>Nonlinear Dynamics</li>
    <li>Journal of the Franklin Institute</li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Conference Reviewer</h4>
  <ul>
    <li>IEEE Conference on Decision and Control (CDC 2025)</li>
    <li>European Control Conference (ECC 2023, 2024, 2026)</li>
    <li>American Control Conference (ACC 2021)</li>
    <li>Third IFAC Conference on Modelling, Identification and Control of Nonlinear Systems (MICNON 2021)</li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Guest Lecturer</h4>
  <ul>
    <li><strong>Nonlinear and Adaptive Flight Control (Master course)</strong></li>
    <li class="indent">
      Delft University of Technology, Faculty of Aerospace Engineering, Spring 2025
    </li>
    <li class="indent">
      Working with
      <a href="https://www.tudelft.nl/staff/c.c.devisser/">Prof. Coen de Visser</a>
    </li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Teaching Assistance</h4>
  <ul>
    <li><strong>Robotics (Master course)</strong></li>
    <li class="indent">
      <a href="https://ocasys.rug.nl/2022-2023/catalog/course/WMIE005-05">Course Link</a>
    </li>
    <li class="indent">
      University of Groningen, Faculty of Science and Engineering, Fall 2020–2022
    </li>
    <li class="indent">
      Working with
      <a href="https://www.rug.nl/staff/m.cao/?lang=en">Prof. Ming Cao</a>,
      <a href="https://www.rug.nl/staff/bahar.haghighat/?lang=en">Dr. Bahar Haghighat</a>,
      Dr. Rodolfo Reyes-Báez
    </li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Memberships</h4>
  <ul>
    <li><a href="https://disc.tudelft.nl/">Dutch Institute of Systems and Control (DISC)</a></li>
    <li><a href="https://jcwcenter.web.rug.nl/members/">Jan C. Willems Center for Systems and Control</a></li>
  </ul>
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