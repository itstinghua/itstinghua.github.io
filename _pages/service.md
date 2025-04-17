---
layout: page
permalink: /service/
title: Service
description: 
nav: true
nav_order: 3
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
  border-left: 4px solid;
/*   #a78bfa;*/
  padding-left: 0.6rem;
}
.service-section ul {
  margin-top: 0;
  padding-left: 1.2rem;
}
</style>

<div class="fade-in-section service-section">
  <h4>Journal Reviewer</h4>
  <ul>
    <li>IEEE Transactions on Robotics (T-RO)</li>
    <li>IEEE Robotics & Automation Magazine (RAM)</li>
    <li>Nonlinear Dynamics</li>
    <li>Journal of the Franklin Institute</li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Conference Reviewer</h4>
  <ul>
    <li>European Control Conference (ECC 2023, 2024)</li>
    <li>American Control Conference (ACC 2021)</li>
    <li>Third IFAC Conference on Modelling, Identification and Control of Nonlinear Systems (MICNON 2021)</li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Teaching Assistance</h4>
  <ul>
    <li>Master course: Robotics (University of Groningen, Faculty of Science and Engineering, Fall 2020–2022)</li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Professional Memberships</h4>
  <ul>
    <li>Dutch Institute of Systems and Control (DISC)</li>
    <li>Jan C. Willems Center for Systems and Control</li>
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
