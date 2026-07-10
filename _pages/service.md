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

.service-group {
  margin-bottom: 4rem;
}

.service-group > h2 {
  margin-bottom: 1.5rem;
  padding-bottom: 0.45rem;
  font-size: 1.7rem;
  font-weight: 700;
  color: #222;
  border-bottom: 2px solid #00539C;
}

.service-section {
  margin-bottom: 2.5rem;
  padding-left: 2rem;
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
  grid-template-columns: 5rem 1fr;
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

/* Only adjust the spacing of the Teaching Assistant entry */
.service-section li.teaching-assistant-item {
  grid-template-columns: 8rem minmax(0, 1fr);
  column-gap: 2rem;
}

@media (max-width: 700px) {
  .service-section {
    padding-left: 0.75rem;
  }

  .service-section li.dated-item {
    grid-template-columns: 1fr;
    row-gap: 0.25rem;
  }

  .service-content {
    padding-left: 1rem;
  }

  .service-content::before {
    display: none;
  }
}
</style>

<!-- 1. Talk & Presentations -->
<section class="fade-in-section service-group">
  <h2>Talk &amp; Presentations</h2>

  <div class="service-section">
    <h4>Invited Talks</h4>
    <ul>
      <li class="dated-item">
        <span class="service-time">Jun. 2024</span>
        <span class="service-content">
          <strong>Motion Control for Nonholonomic Wheeled Mobile Robots</strong><br>
          Keynote Speaker for the 6th AI QianTang Forum<br>
          <em>Hangzhou Dianzi University,</em> China 🇨🇳
        </span>
      </li>
      <li class="dated-item">
        <span class="service-time">Jun. 2023</span>
        <span class="service-content">
          <strong>Motion Control for Nonholonomic Multi-agent Systems</strong><br>
          <a href="https://people.kth.se/~kallej/group.html">Research group of Prof. Karl Henrik Johansson</a><br>
          <a href="https://www.kth.se/dcs/department-of-decision-and-control-systems-1.788078">Department of Decision and Control Systems</a><br>
          <em>KTH Royal Institute of Technology,</em> Sweden 🇸🇪
        </span>
      </li>
      <li class="dated-item">
        <span class="service-time">Oct. 2021</span>
        <span class="service-content">
          <strong>Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors</strong><br>
          Invited presentation of an T-RO paper<br>
          <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2021)</em><br>
          (Virtual presentation due to Covid. Hosted from Prague, Czech Republic 🇨🇿)
        </span>
      </li>
    </ul>
  </div>


  <div class="service-section">
    <h4>Conference Presentations</h4>
    <ul>
      <li class="dated-item">
        <span class="service-time">Mar. 2023</span>
        <span class="service-content">
          <strong>Multi-agents Source Seeking and Flocking Control with Connectivity Preservation and Collision Avoidance</strong><br>
          <a href="https://beneluxmeeting.nl/2023/"><em>The 42nd Benelux Meeting on Systems and Control</em></a><br>
          Elspeet, The Netherlands 🇳🇱
        </span>
      </li>
      <li class="dated-item">
        <span class="service-time">Jul. 2022</span>
        <span class="service-content">
          <strong>Collision-free source seeking control of unicycle robot under uncertain environment</strong><br>
          <a href="https://www.beneluxmeeting.nl/2022/"><em>The 41st Benelux Meeting on Systems and Control</em></a><br>
          Brussels, Belgium 🇧🇪
        </span>
      </li>
      <li class="dated-item">
        <span class="service-time">Jun. 2021</span>
        <span class="service-content">
          <strong>3D-printed Flexible Piezoresistive Sensors-based Source Seeking Control of Unicycle Robots</strong><br> <a href="https://www.beneluxmeeting.nl/2021/"><em>The 40th Benelux Meeting on Systems and Control</em></a><br>
          Rotterdam, The Netherlands 🇳🇱
        </span>
      </li>
    </ul>
  </div>
 
</section>

<!-- 2. Teaching -->
<section class="fade-in-section service-group">
  <h2>Teaching &amp; Supervision</h2>

  <div class="service-section">
    <h4>Guest Lecturer</h4>
    <ul>
      <li class="dated-item">
        <span class="service-time">Spring 2025</span>
        <span class="service-content">
          <strong>Nonlinear Control (Master's Course)</strong><br>
          Faculty of Aerospace Engineering, <em>Delft University of Technology</em><br>
          In collaboration with <a href="https://www.tudelft.nl/staff/c.c.devisser/">Prof. Coen de Visser</a>
        </span>
      </li>
    </ul>
  </div>

  <div class="service-section">
    <h4>Teaching Assistant</h4>
    <ul>
      <li class="dated-item teaching-assistant-item">
        <span class="service-time">Fall 2020–2022</span>
        <span class="service-content">
          <strong>Robotics (Master's Course)</strong><br>
          <a href="https://ocasys.rug.nl/2022-2023/catalog/course/WMIE005-05">Course Link</a><br>
          Faculty of Science and Engineering, <em>University of Groningen</em><br>
          In collaboration with 
          <a href="https://www.rug.nl/staff/m.cao/?lang=en">Prof. Ming Cao</a>,
          <a href="https://www.rug.nl/staff/bahar.haghighat/?lang=en">Dr. Bahar Haghighat</a>,
          and Dr. Rodolfo Reyes-Báez
        </span>
      </li>
    </ul>
  </div>

  <div class="service-section">
    <h4>Supervision</h4>
    <ul>
      <li class="dated-item">
        <span class="service-time">2021</span>
        <span class="service-content">
          <strong><a href="https://fse.studenttheses.ub.rug.nl/24672/">Mitigating Crosswind Effects on Aerodynamic Drag Reduction in a Platoon Formation through Lateral Offsets</a></strong><br>
          Co-supervised master’s thesis, <em>University of Groningen</em><br>
        </span>
      </li>
      <li class="dated-item">
        <span class="service-time">2020</span>
        <span class="service-content">
          <strong><a href="https://fse.studenttheses.ub.rug.nl/21794/">Source Seeking by a Mobile Robot using Airflow Sensor Measurements</a></strong><br>
          Co-supervised master’s thesis, <em>University of Groningen</em><br>
        </span>
      </li>
    </ul>
  </div>

</section>

<!-- 3. Academic Service -->
<section class="fade-in-section service-group">
  <h2>Academic Service</h2>

  <div class="service-section">
    <h4>Memberships</h4>
    <ul>
      <li><a href="https://disc.tudelft.nl/">Dutch Institute of Systems and Control (DISC)</a></li>
      <li><a href="https://jcwcenter.web.rug.nl/members/">Jan C. Willems Center for Systems and Control</a></li>
    </ul>
  </div>
  

  <div class="service-section">
    <h4>Journal Reviewer</h4>
    <ul>
      <li>IEEE Transactions on Robotics (T-RO)</li>
      <li>IEEE Robotics and Automation Letters (RA-L)</li>
      <li>IEEE Robotics &amp; Automation Magazine (RA-M)</li>
      <!--
      <li>Nonlinear Dynamics</li>
      <li>Journal of the Franklin Institute</li>
      -->
    </ul>
  </div>

  <div class="service-section">
    <h4>Conference Reviewer</h4>
    <ul>
      <li>IEEE Conference on Decision and Control (CDC 2025)</li>
      <li>European Control Conference (ECC 2023, 2024, 2026)</li>
      <li>American Control Conference (ACC 2021)</li>
      <li>Third IFAC Conference on Modelling, Identification and Control of Nonlinear Systems (MICNON 2021)</li>
    </ul>
  </div>

  <div class="service-section">
    <h4>Workshop Organization</h4>
    <ul>
      <li class="dated-item">
        <span class="service-time">May 2026</span>
        <span class="service-content">
          <strong>Workshop on Opto-Mechatronics and Control of Nonlinear Systems</strong><br>
          <a href="https://sites.google.com/view/bayujayawardhanainaugural/home">Workshop Website</a><br>
          <em>University of Groningen</em><br>
        </span>
        </li>
    </ul>
  </div>

</section>



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
