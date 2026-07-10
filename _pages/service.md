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
  padding-left: 0;
  list-style: none;
}

.service-section li {
  position: relative;
  padding-left: 1rem;
  margin-bottom: 0.45rem;
}

.service-section li::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.7em;
  width: 0.4rem;
  height: 2px;
  background-color: #00539C;
}

.service-section li.dated-item {
  display: grid;
  grid-template-columns: 8.5rem 1fr;
  column-gap: 1rem;
  padding-left: 0;
  margin-bottom: 0.8rem;
}

.service-section li.dated-item::before {
  display: none;
}

.service-time {
  color: #555;
  font-weight: 500;
  white-space: nowrap;
}

.service-content {
  position: relative;
  padding-left: 1rem;
}

.service-content::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.7em;
  width: 0.4rem;
  height: 2px;
  background-color: #00539C;
}

/* Global font settings */
/*
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
*/
</style>

<div class="fade-in-section service-section">
  <h4>Invited Talk</h4>
  <ul>
    <li class="dated-item">
      <span class="service-time">June 2024</span>
      <span class="service-content">
        <strong>Motion Control for Nonholonomic Wheeled Mobile Robots</strong><br>
         Keynote Speaker for the 6th AI QianTang Forum<br>
         Hangzhou Dianzi University, China 🇨🇳
      </span>
    </li>
  </ul>
  <ul>
    <li class="dated-item">
      <span class="service-time">June 2023</span>
      <span class="service-content">
        <strong>Motion Control for Nonholonomic Multi-agent System</strong><br>
          <a href="https://people.kth.se/~kallej/group.html">Research group of Prof. Karl Henrik Johansson</a><br>
         <a href="https://www.kth.se/dcs/department-of-decision-and-control-systems-1.788078">Department of Decision and Control Systems</a><br>
         KTH Royal Institute of Technology, Swedem 🇸🇪
      </span>
    </li>
  </ul>
</div>


<div class="fade-in-section service-section">
  <h4>Guest Lecturer</h4>
  <ul>
    <li class="dated-item">
      <span class="service-time">Spring 2025</span>
      <span class="service-content">
        <strong>Nonlinear Control (Master course)</strong><br>
        Delft University of Technology, Faculty of Aerospace Engineering<br>
        Working with
        <a href="https://www.tudelft.nl/staff/c.c.devisser/">Prof. Coen de Visser</a>
      </span>
    </li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Teaching Assistance</h4>
  <ul>
    <li class="dated-item">
      <span class="service-time">Fall 2020, 2021, 2022</span>
      <span class="service-content">
        <strong>Robotics(Master course)</strong><br>
        <a href="https://ocasys.rug.nl/2022-2023/catalog/course/WMIE005-05">Course Link</a><br>
        University of Groningen, Faculty of Science and Engineering<br>
        Working with
        <a href="https://www.rug.nl/staff/m.cao/?lang=en">Prof. Ming Cao</a>,
        <a href="https://www.rug.nl/staff/bahar.haghighat/?lang=en">Dr. Bahar Haghighat</a>,
        Dr. Rodolfo Reyes-Báez
      </span>
    </li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>Memberships</h4>
  <ul>
    <li><a href="https://disc.tudelft.nl/">Dutch Institute of Systems and Control (DISC) </a></li>
    <li><a href="https://jcwcenter.web.rug.nl/members/">Jan C. Willems Center for Systems and Control </a></li>
  </ul>
</div>


<div class="fade-in-section service-section">
  <h4>Journal Reviewer</h4>
  <ul>
    <li>IEEE Transactions on Robotics (T-RO)</li>
    <li>IEEE Robotics and Automation Letters (RA-L)</li>
    <li>IEEE Robotics & Automation Magazine (RA-M)</li>
   <!--  <li>Nonlinear Dynamics</li>
    <li>Journal of the Franklin Institute</li> -->
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