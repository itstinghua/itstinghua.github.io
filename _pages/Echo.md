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


  <!-- ======================================
       Alicia Keys
  ======================================= -->

  <article class="project-card">

    <div class="project-media">
      <iframe
        src="https://www.youtube.com/embed/izyZLKIWGiA"
        title="Alicia Keys - Underdog"
        loading="lazy"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>
    </div>

    <div class="project-content">
      <h2>
        <a
          href="https://www.bilibili.com/video/BV1XJ411n7VC?t=2.2"
          target="_blank"
          rel="noopener noreferrer">
          Alicia Keys — Underdog
        </a>
      </h2>

      <p>
        <strong>For those who have been underestimated, yet continue to follow
        their own dreams.</strong>
      </p>

      <p class="echo-quote">
        <em>One conversation, a single moment</em><br>
        <em>The things that change us if we notice</em><br>
        <em>When we look up, sometimes</em><br>
        <em>They said I would never make it</em><br>
        <em>But I was built to break the mold</em><br>
        <em>The only dream that I've been chasing is my own</em>
      </p>
    </div>

  </article>


  <!-- ======================================
       Forever Young
  ======================================= -->

  <article class="project-card">

    <div class="project-media">
      <video
        controls
        preload="metadata"
        playsinline>

        <source
          src="{{ '/assets/video/echo/Forever Young.mp4' | relative_url }}"
          type="video/mp4">

        Your browser does not support HTML5 video.
      </video>
    </div>

    <div class="project-content">
      <h2>Forever Young</h2>

      <p>
        <strong><em>May you remember how precious you are.</em></strong>
      </p>

      <p class="echo-quote">
        <span class="zh-kaiti"><strong>愿你在被打击时，记起你的珍贵，抵抗恶意。</strong></span><br>
        <span class="zh-kaiti"><strong>愿你在迷茫时，坚信你的珍贵。</strong></span><br>
        <span class="zh-kaiti"><strong>爱你所爱，行你所行，听从你心，无问西东。</strong></span>
      </p>
    </div>

  </article>


  <!-- ======================================
       Forever Young-1
  ======================================= -->

  <article class="project-card">

    <div class="project-media">
      <video
        controls
        preload="metadata"
        playsinline>

        <source
          src="{{ '/assets/video/echo/Forever Young-1.mp4' | relative_url }}"
          type="video/mp4">

        Your browser does not support HTML5 video.
      </video>
    </div>

    <div class="project-content">
      <h2>Forever Young</h2>

      <p>
        <em>
          <span class="zh-kaiti"><strong>人把自己置身于忙碌当中，有一种麻木的踏实，但丧失了真实。
          你的青春也不过只有这些日子。</strong></span>
        </em>
      </p>
      
      <p class="echo-quote">
          <span class="zh-kaiti"><strong>什么是真实：你看到什么，听到什么，做什么，和谁在一起，
          要有一种从心灵深处漫溢出的、不懊悔也不羞耻的平和与喜悦。</strong></span>
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
      <h2>Don't let this spring pass you by.</h2>
      
      <p class="echo-quote">
          <strong>Cherry blossoms in Delft, 2026 </strong>
      </p>
    </div>

  </article>


  <!-- ======================================
       Back in Groningen
  ======================================= -->

  <article class="project-card">

    <div class="project-media">
      <video
        controls
        preload="metadata"
        playsinline>

        <source
          src="{{ '/assets/video/echo/groningen.mp4' | relative_url }}"
          type="video/mp4">

        Your browser does not support HTML5 video.
      </video>
    </div>

    <div class="project-content">
      <h2>Home. Sweet Home.</h2>

      <p class="echo-quote">
        <strong>Groningen Vibe, Spring 2026</strong>
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
        alt="Tulips in Lelystad, the Netherlands"
        loading="lazy">
    </div>

    <div class="project-content">
      <h2>Friends</h2>

      <p class="echo-quote">
        <strong>Defence Day, 2024</strong>
      </p>
    </div>

  </article> 


   <!--======================================
       Green Day
  ======================================= -->
   <article class="project-card">

    <div class="project-media">
      <video
        controls
        preload="metadata"
        playsinline>

        <source
          src="{{ '/assets/video/echo/greenday.mp4' | relative_url }}"
          type="video/mp4">

        Your browser does not support HTML5 video.
      </video>
    </div>

    <div class="project-content">
      <h2>Green Day - Wake Me Up When September Ends</h2>

      <p>
        <strong>Green Day in Groningen, 2022</strong><br>
      </p>

      <p class="echo-quote">
        <strong>Ring out the bells again</strong><br>
        <strong>Like we did when spring began</strong><br>
        <strong>Wake me up when September ends</strong>
      </p>
    </div>

  </article>


  <!-- ======================================
       Groningen image
  ======================================= -->

 <!--  <article class="project-card">

    <div class="project-media">
      <img
        src="{{ '/assets/img/echo/rock.jpg' | relative_url }}"
        alt=" "
        loading="lazy">
    </div>

    <div class="project-content">
      <h2>Home, Sweet Home at Groningen, 2023</h2>

      <p class="echo-quote">
        <strong>You Rock!</strong>
      </p>
    </div>

  </article> -->


  <!-- ======================================
       Dutch spring image
  ======================================= -->

  <!-- <article class="project-card">

    <div class="project-media">
      <img
        src="{{ '/assets/img/echo/spring.jpeg' | relative_url }}"
        alt="Tulips in Lelystad, the Netherlands"
        loading="lazy">
    </div>

    <div class="project-content">
      <h2>Dutch Spring Vibes, 2021</h2>

      <p class="echo-quote">
        <strong><span class="zh-kaiti">人生荒芜，所以春天周而复始。</span></strong>
      </p>
    </div>

  </article> -->




</div>
```
