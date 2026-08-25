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
   Container
======================================== */

.echo-container {
  width: 100%;
  max-width: 760px;
  margin: 0 auto;
}


/* ========================================
   Hero
======================================== */

.echo-hero {
  max-width: 680px;
  margin: 2rem auto 4.5rem;
  text-align: center;
}

.echo-hero blockquote {
  margin: 0;
  padding: 0;
  border: none;

  font-size: clamp(1.35rem, 2.8vw, 1.85rem);
  font-style: italic;
  font-weight: 400;
  line-height: 1.6;

  color: var(--global-text-color);
}

.echo-hero p {
  margin-top: 0.7rem;
  font-size: 0.88rem;

  color: var(--global-text-color);
  opacity: 0.55;
}


/* ========================================
   Echo item
======================================== */

.echo-item {
  margin-bottom: 4.5rem;
}


/* ========================================
   Media
======================================== */

.echo-media {
  width: 100%;
  overflow: hidden;

  border-radius: 10px;
  background: rgba(0, 0, 0, 0.025);
}

.echo-media iframe,
.echo-media video,
.echo-media img {
  display: block;
  width: 100%;

  border: 0;
  border-radius: 10px;
}

.echo-media iframe {
  aspect-ratio: 16 / 9;
}

.echo-media video {
  height: auto;
  max-height: 520px;

  object-fit: contain;
  background: #000;
}

.echo-media img {
  height: auto;
  max-height: 520px;

  object-fit: cover;
}


/* ========================================
   Text
======================================== */

.echo-content {
  margin-top: 1.25rem;
}

.echo-meta {
  margin-bottom: 0.35rem;

  font-size: 0.75rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;

  color: var(--global-text-color);
  opacity: 0.45;
}

.echo-title {
  margin: 0;

  font-size: clamp(1.2rem, 2vw, 1.45rem);
  font-weight: 600;
  line-height: 1.4;
}

.echo-title a {
  color: var(--global-text-color);
  text-decoration: none;
}

.echo-title a:hover {
  color: var(--global-theme-color);
}

.echo-note {
  margin-top: 0.65rem;

  font-size: 0.95rem;
  line-height: 1.75;

  color: var(--global-text-color);
  opacity: 0.75;
}


/* ========================================
   Small divider
======================================== */

.echo-divider {
  width: 36px;
  height: 1px;

  margin: 4rem auto;

  background: var(--global-divider-color);
}


/* ========================================
   Chinese
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

html[data-theme="dark"] .echo-media {
  background: rgba(255, 255, 255, 0.025);
}


/* ========================================
   Mobile
======================================== */

@media (max-width: 768px) {

  .echo-container {
    max-width: 100%;
  }

  .echo-hero {
    margin: 1.5rem auto 3rem;
  }

  .echo-item {
    margin-bottom: 3rem;
  }

  .echo-content {
    margin-top: 1rem;
  }
}


@media (max-width: 480px) {

  .echo-hero blockquote {
    font-size: 1.25rem;
  }

  .echo-media,
  .echo-media iframe,
  .echo-media video,
  .echo-media img {
    border-radius: 8px;
  }

  .echo-title {
    font-size: 1.15rem;
  }

  .echo-note {
    font-size: 0.9rem;
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
     Echo
======================================= -->

<div class="echo-container">


  <!-- 1. Bon Jovi -->

  <article class="echo-item">

    <div class="echo-media">

      <iframe
        src="https://www.youtube.com/embed/VUxIwnf_wZk"
        title="Bon Jovi - It's My Life"
        loading="lazy"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>

    </div>

    <div class="echo-content">

      <div class="echo-meta">
        Music · Bon Jovi
      </div>

      <h2 class="echo-title">
        <a
          href="https://www.bilibili.com/video/BV1Q3411k7Be?t=4.0"
          target="_blank"
          rel="noopener noreferrer">
          It's My Life
        </a>
      </h2>

      <p class="echo-note">
        A song that has stayed with me through different stages of life.
      </p>

    </div>

  </article>


  <div class="echo-divider"></div>


  <!-- 2. Defence Day -->

  <article class="echo-item">

    <div class="echo-media">

      <img
        src="{{ '/assets/img/echo/defence.jpeg' | relative_url }}"
        alt="Friends on Defence Day in Groningen"
        loading="lazy">

    </div>

    <div class="echo-content">

      <div class="echo-meta">
        Groningen · 2024
      </div>

      <h2 class="echo-title">
        Defence Day
      </h2>

      <p class="echo-note">
        Friends, memories, and the closing of an unforgettable chapter in Groningen.
      </p>

    </div>

  </article>


  <div class="echo-divider"></div>


  <!-- 3. Delft -->

  <article class="echo-item">

    <div class="echo-media">

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

    <div class="echo-content">

      <div class="echo-meta">
        Delft · Spring 2026
      </div>

      <h2 class="echo-title">
        Don’t Let This Spring Pass By
      </h2>

      <p class="echo-note">
        Cherry blossoms in Delft.
      </p>

    </div>

  </article>


</div>