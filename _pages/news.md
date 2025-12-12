---
layout: page
permalink: /news/
title: News
description:
nav: true
nav_order: 5
---

<style>
.fade-in-section{opacity:0;transform:translateY(30px);transition:opacity .8s ease-out,transform .8s ease-out}
.fade-in-section.visible{opacity:1;transform:translateY(0)}
.service-section{margin-bottom:3rem}
.service-section h4{margin-bottom:.8rem;font-size:1.25rem;border-left:4px solid;padding-left:.6rem;font-weight:600;color:#00539C}
.service-section ul{margin-top:0;padding-left:1.2rem}
.service-section li{margin-bottom:.75rem;line-height:1.7}
.news-date{font-weight:600}
.news-gallery,.large-img{display:flex;flex-wrap:wrap;justify-content:center;gap:.75rem;margin-top:.75rem}
.news-gallery img{width:100%;max-width:400px;height:auto;border-radius:.5rem;box-shadow:0 2px 6px rgba(0,0,0,.1);object-fit:cover}
.large-img img{width:100%;max-width:500px;height:auto;border-radius:.5rem;box-shadow:0 2px 6px rgba(0,0,0,.1);object-fit:cover}
.service-section a{color:var(--global-theme-color);text-decoration:none}
.service-section a:hover{color:var(--global-hover-color);text-decoration:underline}
</style>

<div class="fade-in-section service-section">
  <h4>2025</h4>
  <ul>
    <li><span class="news-date">2025.12</span> — I am pleased to share that our paper <strong>"Collision-free Source Seeking and Flocking Control of Multi-agents with Connectivity Preservation"</strong> has been offically accepted for publication as full paper in <strong><em>IEEE Transactions on Automatic Control (TAC)</em></strong>. It is expected to appear in June, 2026. Stay Tuned!</li>
    <li><span class="news-date">2025.08</span> — I am super happy to visit the Hong Kong University of Science and Technology (Guangzhou) and give a presentation in Robotics and Autonomous Systems, System Hub.</li>
    <li>
      <span class="news-date">2025.06</span> — I had the pleasure of delivering my first guest lecture in the Master’s course “Nonlinear Control” at the Faculty of Aerospace Engineering, TU Delft.
      <!-- <div class="large-img"><img src="/assets/img/news/guest_lecture_TUD.png"></div> -->
    </li>
    <li><span class="news-date">2025.03</span> — Our paper <strong><a href="https://ieeexplore.ieee.org/document/10735338">"Collision-free Source Seeking Control Methods for Unicycle Robots"</a></strong> is now online in <strong><em>IEEE Transactions on Automatic Control (TAC)</em></strong>, please feel free to check out the details :)</li>
    <li><span class="news-date">2025.02</span> — I have started my postdoc journey at Control and Simulation (C&amp;S), Delft University of Technology (TU Delft). Excited to explore the challenges from ground mobile robots to aerospace!</li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>2024</h4>
  <ul>
    <li><span class="news-date">2024.10</span> — Our work <strong>"Collision-free Source Seeking Control Methods for Unicycle Robots"</strong> is officially accepted in <strong><em>IEEE Transactions on Automatic Control (TAC)</em></strong>. This is a key part of my PhD thesis and proposes three control barrier function (CBF) designs for solving the mixed relative degree problem in unicycle robot control.</li>
    <li><span class="news-date">2024.06</span> — Honored to be a keynote speaker at the 6th AI QianTang Forum, School of Automation (School of AI), Hangzhou Dianzi University, China.</li>
    <li><span class="news-date">2024.01</span> — 🎓 I am excited to announce that I have defended my <strong><em>Ph.D. thesis</em> <a href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots">"Motion control for nonholonomic unicycle robots".</a></strong></li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>2023</h4>
  <ul>
    <li><span class="news-date">2023.11</span> — Visited Prof. Qinghua Yang's group at Shanghai University and shared my PhD work.</li>
    <li><span class="news-date">2023.10</span> — Visited Prof. Wenan Zhang's group at Zhejiang University of Technology.</li>
    <li><span class="news-date">2023.09</span> — Participated in the "Five Decades of Systems and Control Theory in Groningen".</li>
    <li><span class="news-date">2023.06</span> — Visited Prof. Karl Henrik Johansson’s group at KTH, Sweden.</li>
    <li>
      <span class="news-date">2023.03</span> — Attended the 42nd Benelux Meeting on Systems and Control in Elspeet, Netherlands.
      <div class="news-gallery"><img src="/assets/img/news/disc_2023_1.jpg"><img src="/assets/img/news/disc_2023_2.jpg"></div>
    </li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>2022</h4>
  <ul>
    <li><span class="news-date">2022.03</span> — Joined the DISC Winter Course on Data Learning &amp; Dynamics at the Intersection of Neuroscience and Control.</li>
  </ul>
</div>

<div class="fade-in-section service-section">
  <h4>2021</h4>
  <ul>
    <li><span class="news-date">2021.10</span> — Presented our source-seeking work at IROS 2021 (virtual).</li>
    <li><span class="news-date">2021.07</span> — Presented "Source-Seeking Control of Unicycle Robots With 3D-Printed Flexible Sensors" at the 10th Benelux Meeting.</li>
    <li><span class="news-date">2021.06</span> — Joined the DISC Summer School 2021.</li>
    <li><span class="news-date">2021.04</span> — Our paper on source-seeking control was accepted by <strong><em>IEEE Transactions on Robotics (TRO)</em></strong>.</li>
  </ul>
</div>

<script>
document.addEventListener("DOMContentLoaded",function(){const o=new IntersectionObserver(e=>{e.forEach(t=>{t.isIntersecting&&t.target.classList.add("visible")})},{threshold:.15});document.querySelectorAll(".fade-in-section").forEach(e=>{o.observe(e)})});
</script>
