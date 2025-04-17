layout: page
permalink: /news/
title: News
description: 
nav: true
nav_order: 4
---

<style>
.news-section {
  margin: 2rem 0;
}
.news-year {
  font-size: 1.75rem;
  font-weight: bold;
  margin: 2.5rem 0 1.5rem;
  border-bottom: 2px solid #ddd;
  padding-bottom: 0.5rem;
  color: #a78bfa; /* 紫色 */
}
.news-item {
  margin-bottom: 2rem;
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}
.news-item.visible {
  opacity: 1;
  transform: translateY(0);
}
.news-item h4 {
  font-weight: bold;
  margin-bottom: 0.5rem;
}
.news-item p {
  margin-bottom: 0.5rem;
  line-height: 1.7;
}

/* 优化图片排版 */
.news-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0.75rem;
  margin-top: 1rem;
}

.news-gallery img {
  max-width: 180px;
  height: auto;
  border-radius: 0.5rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}
</style>

<div class="news-section">

  <div class="news-year">2024</div>

  <div class="news-item">
    <h4>October</h4>
    <p>Our work <a href="https://ieeexplore.ieee.org/document/10735338">"Collision-free Source Seeking Control Methods for Unicycle Robots"</a> is officially accepted in <strong>IEEE Transactions on Automatic Control (TAC)</strong>! This is a key part of my PhD thesis and proposes three control barrier function (CBF) designs for solving the mixed relative degree problem in unicycle robot control. Many thanks to my advisor Prof. Bayu Jayawardhana for the insightful discussions and unwavering support! 😊</p>
  </div>

  <div class="news-item">
    <h4>June</h4>
    <p>Honored to be a keynote speaker at the 6th AI QianTang Forum, School of Automation (School of AI), Hangzhou Dianzi University, China. Thanks to Prof. Jiming Chen and Prof. Jiuwen Cao for the warm invitation and welcome!</p>
    <div class="news-gallery">
      <img src="/assets/img/news/hangzhou_1.jpg" alt="Hangzhou Talk 1">
      <img src="/assets/img/news/hangzhou_2.jpg" alt="Hangzhou Talk 2">
    </div>
  </div>

  <div class="news-item">
    <h4>January</h4>
    <p>🎓 I am excited to announce that I have defended my <strong>Ph.D. thesis</strong> <a href="https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots">"Motion control for nonholonomic unicycle robots"</a>. This work addresses source-seeking, collision avoidance (via multi-input CBFs), and flocking cohesion, both from theoretical and experimental perspectives.</p>
  </div>

  <div class="news-year">2023</div>

  <div class="news-item">
    <h4>November</h4>
    <p>Visited Prof. Qinghua Yang's group at Shanghai University and shared my PhD work. Great to be back on campus!</p>
  </div>

  <div class="news-item">
    <h4>October</h4>
    <p>Visited Prof. Wenan Zhang's group at Zhejiang University of Technology. Thanks for the kind invitation!</p>
  </div>

  <div class="news-item">
    <h4>September</h4>
    <p>Participated in the "Five Decades of Systems and Control Theory in Groningen" to celebrate the 50th anniversary of the Systems & Control group at the University of Groningen.</p>
  </div>

  <div class="news-item">
    <h4>June</h4>
    <p>Visited Prof. Karl Henrik Johansson’s group at KTH, Sweden, to present my work on motion control of nonholonomic robots. Many thanks for the invitation and engaging discussions.</p>
  </div>

  <div class="news-item">
    <h4>March</h4>
    <p>Attended the 42nd Benelux Meeting on Systems and Control in Elspeet, Netherlands. Presented our paper <em>"Collision-free Source Seeking and Flocking Control of Multi-agents with Connectivity Preservation"</em> and received my DISC certificates!</p>
    <div class="news-gallery">
      <img src="/assets/img/news/disc_2023_1.jpg" alt="DISC 1">
      <img src="/assets/img/news/disc_2023_2.jpg" alt="DISC 2">
    </div>
  </div>

  <div class="news-year">2022</div>
  <div class="news-item">
    <h4>March</h4>
    <p>Joined the DISC Winter Course on Data Learning & Dynamics at the Intersection of Neuroscience and Control.</p>
  </div>

  <div class="news-year">2021</div>
  <div class="news-item">
    <h4>October</h4>
    <p>Presented our source-seeking work at IROS 2021 (virtual), as an invited <strong>T-RO</strong> paper.</p>
  </div>

  <div class="news-item">
    <h4>July</h4>
    <p>Presented <em>"Source-Seeking Control of Unicycle Robots With 3D-Printed Flexible Sensors"</em> at the 10th Benelux Meeting in Rotterdam.</p>
  </div>

  <div class="news-item">
    <h4>June</h4>
    <p>Joined the DISC Summer School 2021: Planning, Learning and Control for Multi-Robot and Multi-Agent Systems (Rotterdam).</p>
  </div>

  <div class="news-item">
    <h4>April</h4>
    <p>Our paper <a href="https://ieeexplore.ieee.org/document/9458274"><em>"Source Seeking Control of Unicycle Robots with 3D-printed Flexible Piezoresistive Sensors"</em></a> was accepted by <strong>IEEE Transactions on Robotics (TRO)</strong>! Huge thanks to Prof. Bayu Jayawardhana, Prof. Ajay Giri Prakash Kottapalli, and Dr. Amar Kamat for the fruitful collaboration!</p>
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

    document.querySelectorAll(".news-item").forEach(el => {
      observer.observe(el);
    });
  });
</script>
