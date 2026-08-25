---
layout: page
title: Echo
permalink: /Echo/
description: Songs, memories, and moments that echo through life.
nav: true
nav_order: 7
---

<style>
/* ========================================
   Page container
======================================== */

.echo-container {
  width: 100%;
  max-width: 980px;
  margin: 0 auto;
}


/* ========================================
   Hero quote
======================================== */

.echo-hero {
  max-width: 720px;
  margin: 2rem auto 4rem;
  padding: 0;
  text-align: center;
}

.echo-hero blockquote {
  margin: 0;
  padding: 0;
  border: none;

  font-size: clamp(1.5rem, 3vw, 2rem);
  font-style: italic;
  font-weight: 400;
  line-height: 1.55;
  letter-spacing: -0.01em;

  color: var(--global-text-color);
}

.echo-hero p {
  margin: 0.8rem 0 0;

  font-size: 0.92rem;
  line-height: 1.5;

  color: var(--global-text-color);
  opacity: 0.6;
}


/* ========================================
   Project / memory cards
======================================== */

.project-card {
  display: grid;
  grid-template-columns:
    minmax(0, 1.15fr)
    minmax(0, 0.85fr);

  gap: 2.4rem;
  align-items: center;

  width: 100%;
  margin-bottom: 2.5rem;
  padding: 1.4rem;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 16px;

  overflow: hidden;

  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.project-card:hover {
  transform: translateY(-3px);
  border-color: var(--global-theme-color);
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.08);
}


/* ========================================
   Alternating layout
======================================== */

.project-card:nth-of-type(even) {
  grid-template-columns:
    minmax(0, 0.85fr)
    minmax(0, 1.15fr);
}

.project-card:nth-of-type(even) .project-media {
  order: 2;
}

.project-card:nth-of-type(even) .project-content {
  order: 1;
}


/* ========================================
   Media area
======================================== */

.project-media {
  width: 100%;
  min-width: 0;

  overflow: hidden;
  border-radius: 12px;

  background: rgba(0, 0, 0, 0.03);
}

.project-media iframe,
.project-media video,
.project-media img {
  display: block;
  width: 100%;

  border: none;
  border-radius: 12px;
}


/* YouTube */
.project-media iframe {
  aspect-ratio: 16 / 9;
}


/* Video */
.project-media video {
  width: 100%;
  height: auto;
  max-height: 460px;

  object-fit: contain;
  background: #000;
}


/* Image */
.project-media img {
  width: 100%;
  height: auto;
  max-height: 460px;

  object-fit: cover;
}


/* ========================================
   Content area
======================================== */

.project-content {
  min-width: 0;
  color: var(--global-text-color);
}

.project-content h2 {
  margin: 0 0 1rem;

  font-size: clamp(1.35rem, 2vw, 1.65rem);
  font-weight: 600;
  line-height: 1.3;
  letter-spacing: -0.01em;
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
  margin: 0.8rem 0;
  line-height: 1.8;
}


/* ========================================
   Small metadata / place / date
======================================== */

.echo-meta {
  margin-bottom: 0.8rem;

  font-size: 0.82rem;
  line-height: 1.5;

  color: var(--global-text-color);
  opacity: 0.55;

  text-transform: uppercase;
  letter-spacing: 0.06em;
}


/* ========================================
   Quote area
======================================== */

.echo-quote {
  margin-top: 1rem;
  padding: 0.9rem 0 0.9rem 1.2rem;

  border: none;
  border-left: 3px solid var(--global-theme-color);

  background: transparent;

  font-size: 0.96rem;
  line-height: 1.85;

  color: var(--global-text-color);
}

.echo-quote em {
  opacity: 0.88;
}


/* ========================================
   Chinese text
======================================== */

.zh-kaiti {
  font-family:
    "KaiTi",
    "STKaiti",
    "Kaiti SC",
    "DFKai-SB",
    serif;
}


/* ========================================
   Dark mode
======================================== */

html[data-theme="dark"] .project-card {
  box-shadow: none;
}

html[data-theme="dark"] .project-card:hover {
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.25);
}

html[data-theme="dark"] .project-media {
  background: rgba(255, 255, 255, 0.03);
}


/* ========================================
   Mobile
======================================== */

@media (max-width: 768px) {

  .echo-hero {
    margin: 1.5rem auto 2.8rem;
  }

  .project-card,
  .project-card:nth-of-type(even) {
    grid-template-columns: 1fr;

    gap: 1.3rem;

    padding: 1rem;
    margin-bottom: 1.8rem;

    border-radius: 14px;
  }

  .project-card .project-media,
  .project-card:nth-of-type(even) .project-media {
    order: 1;
  }

  .project-card .project-content,
  .project-card:nth-of-type(even) .project-content {
    order: 2;
  }

  .project-content h2 {
    font-size: 1.25rem;
  }
}


/* ========================================
   Small phones
======================================== */

@media (max-width: 480px) {

  .echo-hero {
    margin-top: 1rem;
    margin-bottom: 2.2rem;
  }

  .echo-hero blockquote {
    font-size: 1.3rem;
  }

  .echo-hero p {
    font-size: 0.85rem;
  }

  .project-card {
    padding: 0.85rem;
    border-radius: 12px;
  }

  .project-media,
  .project-media iframe,
  .project-media video,
  .project-media img {
    border-radius: 9px;
  }

  .project-content h2 {
    margin-bottom: 0.7rem;
    font-size: 1.18rem;
  }

  .echo-quote {
    padding-left: 0.9rem;
    font-size: 0.92rem;
  }

  .echo-meta {
    font-size: 0.76rem;
  }
}
</style>


<!-- ======================================
     Hero
======================================= -->

<div class="echo-hero">

  <blockquote>
    “This is not a song for the broken-hearted”
  </blockquote>

  <p>
    — Bon Jovi, <em>It's My Life</em>
  </p>

</div>


<!-- ======================================
     Echo content
======================================= -->

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

      <div class="echo-meta">
        Music · Bon Jovi
      </div>

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



  <!-- ======================================
       Defence Day
  ======================================= -->

  <article class="project-card">

    <div class="project-media">

      <img
        src="{{ '/assets/img/echo/defence.jpeg' | relative_url }}"
        alt="Friends on Defence Day in Groningen"
        loading="lazy">

    </div>


    <div class="project-content">

      <div class="echo-meta">
        Groningen · 2024
      </div>

      <h2>
        Friends
      </h2>

      <p class="echo-quote">
        <strong>Defence Day, Groningen, 2024</strong>
      </p>

    </div>

  </article>



  <!-- ======================================
       Delft — Cherry Blossoms
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

      <div class="echo-meta">
        Delft · Spring 2026
      </div>

      <h2>
        Don’t Let This Spring Pass By
      </h2>

      <p class="echo-quote">
        <strong>Cherry Blossoms in Spring, Delft, 2026</strong>
      </p>

    </div>

  </article>


</div>