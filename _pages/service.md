---
layout: page
permalink: /service/
title: Service
description: 
nav: true
nav_order: 3
---

<style>
.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}
.service-card {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.8s ease-out, transform 0.8s ease-out;
  border-left: 4px solid #a78bfa;
  padding-left: 1rem;
}
.service-card.visible {
  opacity: 1;
  transform: translateY(0);
}
.service-card h4 {
  font-size: 1.2rem;
  margin-bottom: 0.6rem;
}
.service-card ul {
  margin-top: 0;
  padding-left: 1.2rem;
}
</style>

<div class="service-grid">

  <div class="service-card">
    <h4>Journal Reviewer</h4>
    <ul>
      <li>IEEE Transactions on Robotics (T-RO)</li>
      <li>IEEE Robotics & Automation Magazine (RAM)</li>
      <li>Nonlinear Dynamics</li>
      <li>Journal of the Franklin Institute</li>
    </ul>
  </div>

  <div class="service-card">
    <h4>Conference Reviewer</h4>
    <ul>
      <li>European Control Conference (ECC 2023, 2024)</li>
      <li>American Control Conference (ACC 2021)</li>
      <li>IFAC MICNON 2021</li>
    </ul>
  </div>

  <div class="service-card">
    <h4>Teaching Assistance</h4>
    <ul>
      <li>Master course: Robotics  
          (University of Groningen, FSE, Fall 2020–2022)</li>
    </ul>
  </div>

  <div class="service-card">
    <h4>Professional Memberships</h4>
    <ul>
      <li>Dutch Institute of Systems and Control (DISC)</li>
      <li>Jan C. Willems Center for Systems and Control</li>
    </ul>
  </div>

</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target
