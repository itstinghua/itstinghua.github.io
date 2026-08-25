---
layout: page
title: Echo
permalink: /Echo/
description: Songs, memories, and moments that echo through life.
nav: true
nav_order: 6
---

<style>
/* ========================================
   Container
======================================== */

.echo-container {
  width: 100%;
  max-width: 680px;
  margin: 0 auto;
}


/* ========================================
   Hero
======================================== */

.echo-hero {
  max-width: 620px;
  margin: 1.5rem auto 3.5rem;
  text-align: center;
}

.echo-hero blockquote {
  margin: 0;
  padding: 0;
  border: none;

  font-size: clamp(1.25rem, 2.4vw, 1.7rem);
  font-style: italic;
  font-weight: 400;
  line-height: 1.55;

  color: var(--global-text-color);
}

.echo-hero p {
  margin-top: 0.6rem;

  font-size: 0.82rem;

  color: var(--global-text-color);
  opacity: 0.48;
}


/* ========================================
   Echo Item
======================================== */

.echo-item {
  width: 100%;
  max-width: 620px;

  margin: 0 auto 4rem;
}


/* ========================================
   Media
======================================== */

.echo-media {
  width: 100%;
  overflow: hidden;

  border-radius: 8px;

  background: rgba(0, 0, 0, 0.025);
}

.echo-media iframe,
.echo-media video,
.echo-media img {
  display: block;

  width: 100%;

  border: 0;
  border-radius: 8px;
}


/* YouTube */

.echo-media iframe {
  aspect-ratio: 16 / 9;
}


/* Local Video */

.echo-media video {
  height: auto;
  max-height: 430px;

  object-fit: contain;

  background: #000;
}


/* Image */

.echo-media img {
  height: auto;
}


/* ========================================
   Content
======================================== */

.echo-content {
  margin-top: 1rem;
}

.echo-meta {
  margin-bottom: 0.3rem;

  font-size: 0.7rem;
  font-weight: 500;

  text-transform: uppercase;
  letter-spacing: 0.1em;

  color: var(--global-text-color);
  opacity: 0.42;
}

.echo-title {
  margin: 0;

  font-size: clamp(1.15rem, 2vw, 1.35rem);
  font-weight: 600;
  line-height: 1.35;
}

.echo-title a {
  color: var(--global-text-color);
  text-decoration: none;
}

.echo-title a:hover {
  color: var(--global-theme-color);
}


/* ========================================
   Short Note
======================================== */

.echo-note {
  max-width: 560px;

  margin-top: 0.5rem;
  margin-bottom: 0;

  font-size: 0.92rem;
  line-height: 1.7;

  color: var(--global-text-color);
  opacity: 0.68;
}


/* ========================================
   Longer Story
======================================== */

.echo-story {
  max-width: 580px;

  margin-top: 0.8rem;

  color: var(--global-text-color);
}

.echo-story p {
  margin: 0 0 1rem;

  font-size: 0.92rem;
  line-height: 1.75;

  color: var(--global-text-color);
  opacity: 0.72;
}

.echo-story strong {
  font-weight: 600;
}


/* ========================================
   Link
======================================== */

.echo-link {
  margin-top: 1.1rem;
}

.echo-link a {
  font-size: 0.88rem;
  font-weight: 500;

  color: var(--global-theme-color);

  text-decoration: none;
}

.echo-link a:hover {
  color: var(--global-hover-color);

  text-decoration: underline;
}


/* ========================================
   Divider
======================================== */

.echo-divider {
  width: 28px;
  height: 1px;

  margin: 3.2rem auto;

  background: var(--global-divider-color);

  opacity: 0.7;
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
   Dark Mode
======================================== */

html[data-theme="dark"] .echo-media {
  background: rgba(255, 255, 255, 0.025);
}


/* ========================================
   Tablet / Mobile
======================================== */

@media (max-width: 768px) {

  .echo-container {
    max-width: 100%;
  }

  .echo-hero {
    margin: 1.25rem auto 2.75rem;
  }

  .echo-item {
    max-width: 100%;
    margin-bottom: 3rem;
  }

  .echo-divider {
    margin: 2.5rem auto;
  }
}


/* ========================================
   Small Mobile
======================================== */

@media (max-width: 480px) {

  .echo-hero blockquote {
    font-size: 1.2rem;
  }

  .echo-media,
  .echo-media iframe,
  .echo-media video,
  .echo-media img {
    border-radius: 7px;
  }

  .echo-title {
    font-size: 1.1rem;
  }

  .echo-note,
  .echo-story p {
    font-size: 0.88rem;
    line-height: 1.65;
  }

  .echo-meta {
    font-size: 0.68rem;
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


  <!-- ====================================
       1. Bon Jovi
  ===================================== -->

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
          rel="noopener noreferrer"
        >
          It's My Life
        </a>

      </h2>

      <p class="echo-note">
        A song that has stayed with me through different stages of life.
      </p>

    </div>

  </article>


  <div class="echo-divider"></div>


  <!-- ====================================
       2. Defence Day
  ===================================== -->

  <article class="echo-item">

    <div class="echo-media">

      <video
        controls
        preload="metadata"
        playsinline
      >

        <source
          src="{{ '/assets/video/echo/defence.mp4' | relative_url }}"
          type="video/mp4"
        >

        Your browser does not support HTML5 video.

      </video>

    </div>


    <div class="echo-content">

      <div class="echo-meta">
        Groningen · 2024
      </div>

      <h2 class="echo-title">
        Defence Day
      </h2>

      <p class="echo-note">
        The closing moment of my Ph.D. journey. Thanks to everyone who shared
        this moment with me.
      </p>


      <div class="echo-link">

        <a
          href="{{ '/assets/pdf/acknowledge.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          Full acknowledgements →
        </a>

      </div>

    </div>

  </article>


  <div class="echo-divider"></div>


  <!-- ====================================
       3. Say Goodbye
  ===================================== -->

  <article class="echo-item">

    <div class="echo-media">

      <img
        src="{{ '/assets/img/echo/defence.jpeg' | relative_url }}"
        alt="Friends on Defence Day in Groningen"
        loading="lazy"
      >

    </div>


    <div class="echo-content">

      <div class="echo-meta">
        Groningen · 2024
      </div>

      <h2 class="echo-title">
        Say Goodbye
      </h2>

      <p class="echo-note">
        Friends, memories, and the closing of an unforgettable chapter in Groningen.
      </p>

    </div>

  </article>


  <div class="echo-divider"></div>


  <!-- ====================================
       4. Delft
  ===================================== -->

  <article class="echo-item">

    <div class="echo-media">

      <video
        controls
        preload="metadata"
        playsinline
      >

        <source
          src="{{ '/assets/video/echo/delft.mp4' | relative_url }}"
          type="video/mp4"
        >

        Your browser does not support HTML5 video.

      </video>

    </div>


    <div class="echo-content">

      <div class="echo-meta">
        Delft · Spring 2026
      </div>

      <h2 class="echo-title">
        Don’t Let Spring Pass By
      </h2>

      <p class="echo-note">
        Cherry blossoms in Delft.
      </p>

    </div>

  </article>


</div>