---
layout: page
title: Research
permalink: /research/
description:
nav: true
nav_order: 2
---

<style>
.research-container {
  max-width: 1000px;
  margin: 0 auto;
}

.research-intro {
  margin: 1.5rem 0 2.5rem;
  max-width: 850px;
  line-height: 1.7;
  color: var(--global-text-color);
}

.project-container {
  display: flex;
  gap: 24px;
  align-items: flex-start;
  margin-bottom: 2rem;
  padding: 24px;
  width: 100%;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 8px;

  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.project-container:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
}

.project-video {
  flex: 0 0 46%;
  min-width: 0;
}

.project-video video {
  width: 100%;
  border-radius: 8px;
}

.project-text {
  flex: 1;
  min-width: 0;
  color: var(--global-text-color);
}

.project-text h3 {
  margin-top: 0;
  margin-bottom: 0.65rem;
  font-size: 1.25rem;
  font-weight: 600;
  line-height: 1.35;
}

.project-text h3 a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.project-text h3 a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}

.project-summary {
  margin-bottom: 0.8rem;
  line-height: 1.6;
  font-size: 0.98rem;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0.8rem 0 1rem;
}

.project-tags span {
  display: inline-block;
  padding: 4px 9px;
  font-size: 0.78rem;
  line-height: 1.3;
  border-radius: 999px;
  border: 1px solid var(--global-divider-color);
  color: var(--global-text-color);
  background-color: rgba(0, 83, 156, 0.06);
}

.paper-cite {
  margin-top: 0.9rem;
  padding: 12px 14px;
  border-radius: 8px;
  border: 1px solid var(--global-divider-color);
  background-color: rgba(0, 83, 156, 0.08);
  color: var(--global-text-color);
  font-size: 0.9rem;
  line-height: 1.55;
}

.paper-cite em {
  font-style: italic;
}

html[data-theme="dark"] .project-tags span {
  background-color: rgba(230, 237, 243, 0.05);
}

html[data-theme="dark"] .paper-cite {
  background-color: rgba(230, 237, 243, 0.06);
}

@media (max-width: 768px) {
  .research-intro {
    margin-top: 1rem;
  }

  .project-container {
    flex-direction: column;
    gap: 18px;
    padding: 18px;
  }

  .project-video {
    flex: none;
    width: 100%;
  }

  .project-text h3 {
    font-size: 1.15rem;
  }
}
</style>

<div class="research-container">

  <p class="research-intro">
    My research focuses on source-seeking control, safety-critical control, and multi-agent robotic systems. I am particularly interested in enabling robots to navigate uncertain and cluttered environments using local sensing, optimization-based control, and control barrier functions.
  </p>

  <div class="project-container">
    <div class="project-video">
      {% include video.liquid path="/assets/video/SS.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>

    <div class="project-text">
      <h3>
        <a href="https://ieeexplore.ieee.org/abstract/document/9458274">
          Source-Seeking Robot
        </a>
      </h3>

      <p class="project-summary">
        A unicycle robot uses flexible airflow sensors and gradient-based control to locate an unknown source using only local measurements.
      </p>

      <div class="project-tags">
        <span>Source seeking</span>
        <span>Mobile robots</span>
        <span>Flexible sensors</span>
        <span>Gradient-based control</span>
      </div>

      <p class="paper-cite">
        <strong>T. Li*</strong>, B. Jayawardhana, A. M. Kamat, and A. G. P. Kottapalli,
        “Source-Seeking Control of Unicycle Robots With 3-D-Printed Flexible Piezoresistive Sensors,”
        <em>IEEE Transactions on Robotics</em>, vol. 38, no. 1, pp. 448–462, Feb. 2022,
        doi: 10.1109/TRO.2021.3076964.
      </p>
    </div>
  </div>

  <div class="project-container">
    <div class="project-video">
      {% include video.liquid path="/assets/video/CO.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>

    <div class="project-text">
      <h3>
        <a href="https://ieeexplore.ieee.org/document/10735338">
          Collision-Free Source-Seeking Robot
        </a>
      </h3>

      <p class="project-summary">
        A safety-critical source-seeking framework that allows a unicycle robot to search for a signal source while avoiding obstacles in unknown cluttered environments.
      </p>

      <div class="project-tags">
        <span>Control barrier functions</span>
        <span>Obstacle avoidance</span>
        <span>Safety-critical control</span>
        <span>Unicycle robots</span>
      </div>

      <p class="paper-cite">
        <strong>T. Li*</strong> and B. Jayawardhana,
        “Collision-free Source Seeking Control Methods for Unicycle Robots,”
        <em>IEEE Transactions on Automatic Control</em>, vol. 70, no. 3, pp. 2020–2027, March 2025,
        doi: 10.1109/TAC.2024.3486654.
      </p>
    </div>
  </div>

  <div class="project-container">
    <div class="project-video">
      {% include video.liquid path="/assets/video/connectivity.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>

    <div class="project-text">
      <h3>
        <a href="https://ieeexplore.ieee.org/document/11311473">
          Flocking Control with Connectivity Preservation
        </a>
      </h3>

      <p class="project-summary">
        A distributed source-seeking and flocking-control method for networked multi-agent systems, where agents maintain safety, connectivity, and coordinated motion using onboard sensing.
      </p>

      <div class="project-tags">
        <span>Multi-agent systems</span>
        <span>Flocking control</span>
        <span>Connectivity preservation</span>
        <span>Distributed control</span>
      </div>

      <p class="paper-cite">
        <strong>T. Li*</strong> and B. Jayawardhana,
        “Collision-free Source Seeking and Flocking Control of Multi-agents with Connectivity Preservation,”
        <em>IEEE Transactions on Automatic Control</em>, vol. 71, no. 6, pp. 3696–3711, June 2026,
        doi: 10.1109/TAC.2025.3647313.
      </p>
    </div>
  </div>

</div>