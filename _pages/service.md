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
  margin-bottom: 1.2rem;
  font-size: 1.25rem;
  border-left: 4px solid #00539C;
  padding-left: 0.6rem;
  font-weight: 600;
  color: #00539C;
}

/* ===== CV style ===== */

.service-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 1.6rem;
}

.service-time {
  width: 95px;
  flex-shrink: 0;
  color: #666;
  font-weight: 600;
}

.service-content {
  flex: 1;
}

.service-content .title {
  font-weight: 600;
  margin-bottom: 0.3rem;
}

.service-content .detail {
  margin-left: 1rem;
  color: #444;
  line-height: 1.6;
}
</style>

<div class="fade-in-section service-section">
<h4>Invited Talk</h4>

<div class="service-item">
<div class="service-time">Jun 2024</div>

<div class="service-content">
<div class="title">
Motion Control For Nonholonomic Wheeled Mobile Robots
</div>

<div class="detail">
Keynote speaker for the 6th AI QianTang Forum, School of Automation and School of AI
</div>

<div class="detail">
Hangzhou Dianzi University, China
</div>
</div>
</div>

<div class="service-item">
<div class="service-time">Jun 2023</div>

<div class="service-content">
<div class="title">
Motion Control For Nonholonomic Multi-agent System
</div>

<div class="detail">
<a href="https://www.kth.se/dcs">Department of Decision and Control Systems</a>
</div>

<div class="detail">
KTH Royal Institute of Technology, Sweden
</div>
</div>
</div>

</div>

<div class="fade-in-section service-section">
<h4>Guest Lecturer</h4>

<div class="service-item">
<div class="service-time">Spring 2025</div>

<div class="service-content">
<div class="title">
Master course: Nonlinear Control
</div>

<div class="detail">
Delft University of Technology, Faculty of Aerospace Engineering
</div>

<div class="detail">
Working with
<a href="https://www.tudelft.nl/staff/c.c.devisser/">
Prof. Coen de Visser
</a>
</div>
</div>
</div>

</div>

<div class="fade-in-section service-section">
<h4>Teaching Assistance</h4>

<div class="service-item">
<div class="service-time">2020–2022</div>

<div class="service-content">
<div class="title">
Master course: Robotics
</div>

<div class="detail">
<a href="https://ocasys.rug.nl/2022-2023/catalog/course/WMIE005-05">
Course Link
</a>
</div>

<div class="detail">
University of Groningen, Faculty of Science and Engineering
</div>

<div class="detail">
Working with
<a href="https://www.rug.nl/staff/m.cao/?lang=en">Prof. Ming Cao</a>,
<a href="https://www.rug.nl/staff/bahar.haghighat/?lang=en">Dr. Bahar Haghighat</a>,
Dr. Rodolfo Reyes-Báez
</div>
</div>
</div>

</div>

<div class="fade-in-section service-section">
<h4>Memberships</h4>

<div class="service-item">
<div class="service-time"></div>

<div class="service-content">
<div class="detail">
<a href="https://disc.tudelft.nl/">
Dutch Institute of Systems and Control (DISC)
</a>
</div>

<div class="detail">
<a href="https://jcwcenter.web.rug.nl/members/">
Jan C. Willems Center for Systems and Control
</a>
</div>
</div>
</div>

</div>

<div class="fade-in-section service-section">
<h4>Journal Reviewer</h4>

<div class="service-item">
<div class="service-time"></div>

<div class="service-content">
<div class="detail">IEEE Transactions on Robotics (T-RO)</div>
<div class="detail">IEEE Robotics and Automation Letters (RA-L)</div>
<div class="detail">IEEE Robotics & Automation Magazine (RA-M)</div>
<div class="detail">Nonlinear Dynamics</div>
<div class="detail">Journal of the Franklin Institute</div>
</div>
</div>

</div>

<div class="fade-in-section service-section">
<h4>Conference Reviewer</h4>

<div class="service-item">
<div class="service-time"></div>

<div class="service-content">
<div class="detail">IEEE Conference on Decision and Control (CDC 2025)</div>
<div class="detail">European Control Conference (ECC 2023, 2024, 2026)</div>
<div class="detail">American Control Conference (ACC 2021)</div>
<div class="detail">
Third IFAC Conference on Modelling, Identification and Control of Nonlinear Systems (MICNON 2021)
</div>
</div>
</div>

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