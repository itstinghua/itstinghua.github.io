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
  #e9f5ff;
  padding-left: 0.6rem;
  font-weight: 600;
  color: #4b5563;
}
.service-section ul {
  margin-top: 0;
  padding-left: 1.2rem;
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
    <li>IEEE Conference on Decision and Control (CDC 2025)</li>
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
