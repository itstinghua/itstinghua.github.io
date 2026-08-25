---
layout: page
title: Echo
permalink: /Echo/
description: Songs, memories, and moments that echo through life.
nav: true
nav_order: 7
---

<div class="echo-hero">
  <blockquote>
    “This is not a song for the broken-hearted”
  </blockquote>

  <p>
    — Bon Jovi, <em>It's My Life</em>
  </p>
</div>

<style>
/* ========================================
   Main container
======================================== */

.echo-container {
  width: 100%;
  max-width: 1000px;
  margin: 0 auto;
}


/* ========================================
   Top quote — no card, no border
======================================== */

.echo-hero {
  max-width: 760px;
  margin: 1rem auto 3rem;
  padding: 0;
  text-align: center;

  background: none;
  border: none;
  border-radius: 0;
  box-shadow: none;
}

.echo-hero blockquote {
  margin: 0;
  padding: 0;
  border: none;

  font-size: clamp(1.35rem, 2.5vw, 1.7rem);
  font-style: italic;
  line-height: 1.6;
  color: var(--global-text-color);
}

.echo-hero p {
  margin: 0.6rem 0 0;
  font-size: 0.95rem;
  color: var(--global-text-color);
  opacity: 0.7;
}


/* ========================================
   Project cards
======================================== */

.project-card {
  display: grid;
  grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
  gap: 2rem;
  align-items: center;

  width: 100%;
  margin-bottom: 2rem;
  padding: 1.8rem;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 20px;

  overflow: hidden;

  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.project-card:hover {
  transform: translateY(-3px);
  border-color: var(--global-theme-color);
  box-shadow: 0 10px 24px rgba(0, 0, 0, 0.08);
}


/* ========================================
   Media area — always on the left
======================================== */

.project-media {
  width: 100%;
  min-width: 0;
  overflow: hidden;
  border-radius: 12px;
  background: rgba(0, 0, 0, 0.04);
}

.project-media iframe,
.project-media video,
.project-media img {
  display: block;
  width: 100%;
  border: none;
  border-radius: 12px;
}

.project-media iframe {
  aspect-ratio: 16 / 9;
}

.project-media video {
  width: 100%;
  height: auto;
  max-height: 440px;
  object-fit: contain;
  background: #000;
}

.project-media img {
  width: 100%;
  height: auto;
  max-height: 440px;
  object-fit: cover;
}


/* ========================================
   Text area
======================================== */

.project-content {
  min-width: 0;
  color: var(--global-text-color);
}

.project-content h2 {
  margin: 0 0 0.8rem;
  font-size: clamp(1.25rem, 2vw, 1.55rem);
  font-weight: 650;
  line-height: 1.35;
}

.project-content h2 a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.project-content h2 a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}

.project-content p {
  margin: 0.75rem 0;
  line-height: 1.75;
}


/* ========================================
   Chinese text only — KaiTi
======================================== */

.zh-kaiti {
  font-family: "KaiTi", "STKaiti", "Kaiti SC", "DFKai-SB", serif;
}


/* ========================================
   Quote box inside cards
======================================== */

.echo-quote {
  position: relative;

  margin-top: 1rem;
  padding: 1rem 1.1rem 1rem 1.3rem;

  line-height: 1.75;
  color: var(--global-text-color);

  background: rgba(0, 83, 156, 0.07);
  border: 1px solid var(--global-divider-color);
  border-left: 4px solid var(--global-theme-color);
  border-radius: 10px;
}

.echo-quote em {
  opacity: 0.92;
}


/* ========================================
   Dark mode
======================================== */

html[data-theme="dark"] .echo-quote {
  background: rgba(230, 237, 243, 0.05);
}


/* ========================================
   Mobile layout
======================================== */

@media (max-width: 768px) {
  .echo-hero {
    margin-bottom: 2rem;
  }

  .project-card {
    grid-template-columns: 1fr;
    gap: 1.25rem;
    padding: 1rem;
    border-radius: 16px;
  }

  .project-media {
    order: 1;
  }

  .project-content {
    order: 2;
  }

  .project-content h2 {
    font-size: 1.25rem;
  }
}

@media (max-width: 480px) {
  .echo-hero blockquote {
    font-size: 1.25rem;
  }

  .project-card {
    border-radius: 12px;
  }

  .project-media,
  .project-media iframe,
  .project-media video,
  .project-media img {
    border-radius: 8px;
  }

  .echo-quote {
    padding: 0.9rem 0.9rem 0.9rem 1rem;
  }
}
</style>


<div class="echo-container">


  <!-- ======================================
       Bon Jovi
  ======================================= -->

  <article class="project-card">

    <div class="project-media">
      <iframe
        src="https://www.youtube.com/embed/VUxIwnf_wZk"
        title="Bon Jovi - It's My Life"
        loading="lazy"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>
    </div>

    <div class="project-content">
      <h2>
        <a
          href="https://www.bilibili.com/video/BV1Q3411k7Be?t=4.0"
          target="_blank"
          rel="noopener noreferrer">
          Bon Jovi — It's My Life
        </a>
      </h2>

      <p class="echo-quote">
        <em>This is for the ones who stood their ground</em><br>
        <em>It's for Tommy and Gina who never backed down</em><br>
        <em>Tomorrow's getting harder, make no mistake</em><br>
        <em>Luck ain't enough, you've got to make your own breaks</em>
      </p>
    </div>

  </article>



   <!--======================================
       Defence Day
  ======================================= -->

  <article class="project-card">

    <div class="project-media">
      <img
        src="{{ '/assets/img/echo/defence.jpeg' | relative_url }}"
        alt="the Netherlands"
        loading="lazy">
    </div>

    <div class="project-content">
      <h2>Friends</h2>

      <p class="echo-quote">
        <strong>Defence Day, Groningen, 2024</strong>
      </p>
    </div>

  </article> 


 <!-- ======================================
       Delft-Cherry blossoms
  ======================================= -->

  <article class="project-card">

    <div class="project-media">
      <video
        controls
        preload="metadata"
        playsinline>

        <source
          src="{{ '/assets/video/echo/delft.mp4' | relative_url }}"
          type="video/mp4">

        Your browser does not support HTML5 video.
      </video>
    </div>

    <div class="project-content">
      <h2>Don't Let This Spring Pass By.</h2>
      
      <p class="echo-quote">
          <strong>Cherry Blossoms in Spring Delft, 2026 </strong>
      </p>
    </div>

  </article>







</div>

