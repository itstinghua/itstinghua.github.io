---
layout: page
permalink: /news/
title: News
description:
nav: true
nav_order: 5
---

<style>
/* =========================
   Fade-in animation
   ========================= */
.fade-in-section {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity .8s ease-out, transform .8s ease-out;
}

.fade-in-section.visible {
  opacity: 1;
  transform: translateY(0);
}


/* =========================
   News sections
   ========================= */
.news-section {
  margin-bottom: 3rem;
}

.news-section h4 {
  margin-bottom: .8rem;
  font-size: 1.25rem;
  border-left: 4px solid;
  padding-left: .6rem;
  font-weight: 600;
  color: #00539C;
}

.news-section ul {
  margin-top: 0;
  padding-left: 1.2rem;
}


/* =========================
   News rows
   ========================= */
.news-row {
  display: flex;
  align-items: flex-start;
  gap: .5rem;
  margin-bottom: .75rem;
  line-height: 1.7;
}

.news-date {
  flex: 0 0 5.4rem;
  font-weight: 600;
  white-space: nowrap;
}

.news-text {
  flex: 1;
  min-width: 0;
}


/* =========================
   Images
   ========================= */
.news-gallery,
.large-img {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: .75rem;
  margin-top: .75rem;
}

.news-gallery img {
  width: 100%;
  max-width: 400px;
  height: auto;
  border-radius: .5rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, .1);
  object-fit: cover;
}

.large-img img {
  width: 100%;
  max-width: 500px;
  height: auto;
  border-radius: .5rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, .1);
  object-fit: cover;
}


/* =========================
   Videos
   ========================= */
.gallery-video {
  display: flex;
  justify-content: center;
  margin-top: .75rem;
}

.gallery-video video {
  width: 100%;
  max-width: 500px;
  height: auto;
  border-radius: .5rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, .1);
}


/* =========================
   Links
   ========================= */
.news-section a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.news-section a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}


/* =========================
   Mobile
   ========================= */
@media (max-width: 576px) {
  .news-row {
    display: block;
    margin-bottom: 1rem;
  }

  .news-date {
    display: block;
    margin-bottom: .1rem;
  }

  .news-text {
    display: block;
  }
}
</style>


<!-- =========================================================
     2026
     ========================================================= -->

<div class="fade-in-section news-section">
  <h4>2026</h4>

  <ul>

    <li class="news-row">
      <span class="news-date">2026.06 —</span>
      <span class="news-text">
        Our paper, “Collision-Free Source Seeking and Flocking Control of Multiagents With Connectivity Preservation,”
        was published in <em>IEEE Transactions on Automatic Control (TAC)</em>.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2026.05 —</span>
      <span class="news-text">
        Attended the
        <a href="https://eurognc.ceas.org/" target="_blank" rel="noopener noreferrer">
          2026 CEAS Conference on Guidance, Navigation and Control (EuroGNC)
        </a>
        and participated in the workshop
        <a href="https://safeflighteurognc.github.io/" target="_blank" rel="noopener noreferrer">
          “Control Barrier Functions in Aerospace: From Foundations to Real-World Applications”
        </a>
        in Madrid, Spain.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2026.04 —</span>
      <span class="news-text">
        Co-organized the workshop
        <a href="https://sites.google.com/view/bayujayawardhanainaugural/home?authuser=0"
           target="_blank"
           rel="noopener noreferrer">
          “Opto-Mechatronics and Control of Nonlinear Systems”
        </a>
        with colleagues at the University of Groningen, celebrating the inaugural lecture of
        Prof. Bayu Jayawardhana. Fijn om weer terug te zijn in Groningen!
      </span>
    </li>

  </ul>
</div>


<!-- =========================================================
     2025
     ========================================================= -->

<div class="fade-in-section news-section">
  <h4>2025</h4>

  <ul>

    <li class="news-row">
      <span class="news-date">2025.12 —</span>
      <span class="news-text">
        Our paper, “Collision-Free Source Seeking and Flocking Control of Multiagents With Connectivity Preservation,”
        was accepted for publication as a full paper in
        <em>IEEE Transactions on Automatic Control (TAC)</em>.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2025.08 —</span>
      <span class="news-text">
        Visited the Robotics and Autonomous Systems group at the
        Hong Kong University of Science and Technology (Guangzhou).
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2025.06 —</span>
      <span class="news-text">
        Delivered my first guest lecture for the Master’s course
        “Nonlinear Control” at the Faculty of Aerospace Engineering, TU Delft.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2025.03 —</span>
      <span class="news-text">
        Our paper, “Collision-Free Source Seeking Control Methods for Unicycle Robots,”
        was published online in
        <em>IEEE Transactions on Automatic Control (TAC)</em>.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2025.02 —</span>
      <span class="news-text">
        Started my postdoctoral journey at Delft University of Technology (TU Delft),
        expanding my research from ground mobile robotics to aerospace.
      </span>
    </li>

  </ul>
</div>


<!-- =========================================================
     2024
     ========================================================= -->

<div class="fade-in-section news-section">
  <h4>2024</h4>

  <ul>

    <li class="news-row">
      <span class="news-date">2024.10 —</span>
      <span class="news-text">
        Our paper, “Collision-Free Source Seeking Control Methods for Unicycle Robots,”
        was accepted for publication in
        <em>IEEE Transactions on Automatic Control (TAC)</em>.
        This work forms a key part of my Ph.D. thesis.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2024.06 —</span>
      <span class="news-text">
        Gave a keynote talk at the 6th AI QianTang Forum,
        School of Automation (School of AI),
        Hangzhou Dianzi University, China.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2024.01 —</span>
      <span class="news-text">
        🎓 Successfully defended my Ph.D. thesis,
        “Motion Control for Nonholonomic Unicycle Robots,”
        at the University of Groningen, the Netherlands.
      </span>
    </li>

  </ul>
</div>


<!-- =========================================================
     2023
     ========================================================= -->

<div class="fade-in-section news-section">
  <h4>2023</h4>

  <ul>

    <li class="news-row">
      <span class="news-date">2023.06 —</span>
      <span class="news-text">
        Visited Prof. Karl Henrik Johansson’s research group at KTH Royal Institute of Technology, Sweden.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2023.03 —</span>
      <span class="news-text">
        Presented our work,
        “Multi-Agent Source Seeking and Flocking Control with Connectivity Preservation and Collision Avoidance,”
        at the <em>42nd Benelux Meeting on Systems and Control</em>
        in Elspeet, the Netherlands.
      </span>
    </li>

  </ul>
</div>


<!-- =========================================================
     2022
     ========================================================= -->

<div class="fade-in-section news-section">
  <h4>2022</h4>

  <ul>

    <li class="news-row">
      <span class="news-date">2022.07 —</span>
      <span class="news-text">
        Presented our work,
        “Collision-Free Source Seeking Control of Unicycle Robots under Uncertain Environments,”
        at the <em>41st Benelux Meeting on Systems and Control</em>
        in Brussels, Belgium.
      </span>
    </li>

  </ul>
</div>


<!-- =========================================================
     2021
     ========================================================= -->

<div class="fade-in-section news-section">
  <h4>2021</h4>

  <ul>

    <li class="news-row">
      <span class="news-date">2021.10 —</span>
      <span class="news-text">
        Presented our source-seeking work at
        <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2021)</em>
        (virtual).
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2021.07 —</span>
      <span class="news-text">
        Presented our work,
        “Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors,”
        at the <em>40th Benelux Meeting on Systems and Control</em>
        in Rotterdam, the Netherlands.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2021.06 —</span>
      <span class="news-text">
        Attended the DISC Summer School
        “Planning, Learning and Control for Multi-Robot and Multi-Agent Systems”
        in Rotterdam, the Netherlands.
      </span>
    </li>

    <li class="news-row">
      <span class="news-date">2021.04 —</span>
      <span class="news-text">
        My first Ph.D. paper,
        “Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors,”
        was accepted for publication in
        <em>IEEE Transactions on Robotics (T-RO)</em>.
      </span>
    </li>

  </ul>
</div>


<!-- =========================================================
     Fade-in animation
     ========================================================= -->

<script>
document.addEventListener("DOMContentLoaded", function () {
  const observer = new IntersectionObserver(
    function (entries) {
      entries.forEach(function (entry) {
        if (entry.isIntersecting) {
          entry.target.classList.add("visible");
        }
      });
    },
    {
      threshold: 0.15
    }
  );

  document.querySelectorAll(".fade-in-section").forEach(function (section) {
    observer.observe(section);
  });
});
</script>