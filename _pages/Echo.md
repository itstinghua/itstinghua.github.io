---
layout: page
title: Echo
permalink: /Echo/
description:
nav: true
nav_order: 7
---

<div style="
    text-align: center;
    font-style: italic;
    font-size: 1.2rem;
    color: var(--global-text-color);
    margin: 1.5rem auto 2rem auto;
">
  “This is not a song for the broken-hearted”
  <div style="
      margin-top: 0.5rem;
      font-size: 0.95rem;
      opacity: 0.75;
  ">
    — Bon Jovi, <em>"It's My Life"</em>
  </div>
</div>

<style>
.research-container {
  max-width: 1000px;
  margin: 0 auto;
}

.project-container {
  display: flex;
  gap: 20px;
  align-items: center;
  margin-bottom: 2rem;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 12px;

  padding: 20px;
  width: 100%;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-container:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}


.project-media {
  flex: 1;
  min-width: 0;
  max-width: 50%;
}


.project-media video,
.project-media iframe {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  border: none;
  border-radius: 8px;
}


.project-media img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
  object-fit: contain;
}


.project-text {
  flex: 1;
  min-width: 0;
  color: var(--global-text-color);
}

.project-text h3 {
  margin-top: 0;
  margin-bottom: 0.75rem;
  font-size: 1.25rem;
  font-weight: 600;
  color: var(--global-theme-color);
}

.project-text h3 a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.project-text h3 a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}

.paper-cite {
  margin-top: 0.5rem;
  padding: 10px;
  border: 1px solid var(--global-divider-color);
  border-radius: 10px;
  background-color: rgba(0, 83, 156, 0.08);
  color: var(--global-text-color);
}

html[data-theme="dark"] .paper-cite {
  background-color: rgba(230, 237, 243, 0.06);
}


@media (max-width: 768px) {
  .project-container {
    flex-direction: column;
    align-items: stretch;
    gap: 20px;
  }

  .project-media {
    max-width: 100%;
  }

  .project-media video,
  .project-media iframe,
  .project-media img {
    width: 100%;
  }
}
</style>

<div class="research-container">

  <div class="project-container">
    <div class="project-media">
      <iframe
        src="https://www.youtube.com/embed/VUxIwnf_wZk"
        title="Bon Jovi - It's My Life"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>
    </div>
    <div class="project-text">
      <h3>
        <a href="https://www.youtube.com/embed/VUxIwnf_wZk">
         Bon Jovi - It's My Life
        </a>
      </h3>
    <!--   <p>
        Experimental validation of source-seeking control for unicycle robots
        with 3D-printed graphene-based airflow sensors. The algorithm ensures
        convergence to the source even with partial sensor failure.
      </p> -->
      <p class="paper-cite">
        <em>This is for the ones who stood their ground</em><br>
        <em>It's for Tommy and Gina who never backed down</em><br>
        <em>Tomorrow's getting harder, make no mistake</em><br>
        <em>Luck ain't enough, you've got to make your own breaks</em>
      </p>
    </div>

  </div>


  <div class="project-container">
    <div class="project-media">
      <img
        src="/assets/img/echo/rock.jpg"
        alt="Description of the image"
        loading="lazy">
    </div>
    <div class="project-text">
      <h3>Home, Sweet Home at Groningen, 2023</h3>
      <p class="paper-cite">
        You Rock!!!<br>
      </p>
    </div> 



  </div>

</div>
```
