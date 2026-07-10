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

.service-section li.indent {
  margin-left: 1.5rem;
}

.talk-item {
  display: grid;
  grid-template-columns: 110px 1fr;
  column-gap: 1.2rem;
  margin-bottom: 1.2rem;
}

.talk-date {
  font-weight: 600;
  color: #00539C;
  white-space: nowrap;
}

.talk-content ul {
  margin: 0;
  padding-left: 1.2rem;
}

.talk-content li {
  list-style-type: disc;
}

.talk-content li.indent {
  margin-left: 1.5rem;
}

.talk-content li.talk-title {
  list-style-type: none;
  margin-left: -1.2rem;
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

  <div class="talk-item">
    <div class="talk-date">June 2024</div>
    <div class="talk-content">
      <ul>
        <li class="talk-title">Motion Control For Nonholonomic Wheeled Mobile Robots</li>
        <li class="indent">
          Keynote speaker for the 6th AI QianTang Forum, School of Automation and School of AI
        </li>
        <li class="indent">
          Hangzhou Dianzi University, China
        </li>
      </ul>
    </div>
  </div>

  <div class="talk-item">
    <div class="talk-date">June 2023</div>
    <div class="talk-content">
      <ul>
        <li class="talk-title">Motion Control For Nonholonomic Multi-agent System</li>
        <li class="indent">
          <a href="https://www.kth.se/dcs">Department of Decision and Control Systems</a>
        </li>
        <li class="indent">
          KTH Royal Institute of Technology, Sweden
        </li>
      </ul>
    </div>
  </div>
</div>

<div class="fade-in-section service-section">
  <h4>Guest Lecturer</h4>
  <ul>
    <li><strong>Master course: Nonlinear Control</strong></li>
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
    <li><strong>Master course: Robotics</strong></li>
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