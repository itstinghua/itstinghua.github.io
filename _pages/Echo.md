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
/* ================================
   Page layout
================================ */

.echo-container {
  width: 100%;
  max-width: 1000px;
  margin: 0 auto;
}


/* ================================
   Hero quote
================================ */

.echo-hero {
  max-width: 760px;
  margin: 1.5rem auto 3rem;
  padding: 1.75rem 2rem;
  text-align: center;

  background:
    linear-gradient(
      135deg,
      rgba(0, 83, 156, 0.08),
      rgba(0, 83, 156, 0.02)
    );

  border: 1px solid var(--global-divider-color);
  border-radius: 16px;
}

.echo-hero blockquote {
  margin: 0;
  padding: 0;
  border: none;

  font-size: clamp(1.2rem, 2.5vw, 1.65rem);
  font-style: italic;
  line-height: 1.6;
  color: var(--global-text-color);
}

.echo-hero p {
  margin: 0.75rem 0 0;
  font-size: 0.95rem;
  color: var(--global-text-color);
  opacity: 0.72;
}


/* ================================
   Project cards
================================ */

.project-card {
  display: grid;
  grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
  gap: 1.75rem;
  align-items: center;

  width: 100%;
  margin-bottom: 2rem;
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
  transform: translateY(-4px);
  border-color: var(--global-theme-color);
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.12);
}


/* ================================
   Media
================================ */

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
  height: auto;
  max-height: 420px;
  object-fit: contain;
}

.project-media img {
  height: auto;
  max-height: 420px;
  object-fit: cover;
}


/* Make included local videos fit their containers */
.project-media .img-fluid {
  width: 100%;
  height: auto;
  margin: 0;
}


/* ================================
   Text
================================ */

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


/* ================================
   Quote boxes
================================ */

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

html[data-theme="dark"] .echo-hero {
  background:
    linear-gradient(
      135deg,
      rgba(230, 237, 243, 0.07),
      rgba(230, 237, 243, 0.02)
    );
}

html[data-theme="dark"] .echo-quote {
  background: rgba(230, 237, 243, 0.05);
}


/* ================================
   Alternate card alignment
================================ */

.project-card:nth-child(even) .project-media {
  order: 2;
}

.project-card:nth-child(even) .project-content {
  order: 1;
}


/* ================================
   Responsive layout
================================ */

@media (max-width: 768px) {
  .echo-hero {
    margin-bottom: 2rem;
    padding: 1.4rem 1.2rem;
  }

  .project-card {
    grid-template-columns: 1fr;
    gap: 1.25rem;
    padding: 1rem;
  }

  .project-card:nth-child(even) .project-media,
  .project-card:nth-child(even) .project-content {
    order: initial;
  }

  .project-content h2 {
    font-size: 1.25rem;
  }
}

@media (max-width: 480px) {
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

  <!-- Bon Jovi -->
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
          href="https://www.youtube.com/watch?v=VUxIwnf_wZk"
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


  <!-- Alicia Keys -->
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
          href="https://www.youtube.com/watch?v=izyZLKIWGiA"
          target="_blank"
          rel="noopener noreferrer">
          Alicia Keys — Underdog
        </a>
      </h2>
      <p>
        For those who have been underestimated, yet continue to follow
        their own dreams.
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


  <!-- Forever Young 1 -->
  <article class="project-card">
    <div class="project-media">
      {% include video.liquid
        path="/assets/video/echo/Forever Young.mp4"
        class="img-fluid"
        controls=true
      %}
    </div>
    <div class="project-content">
      <h2>Forever Young, 2018</h2>
      <p>
        <em>May you remember how precious you are.</em>
      </p>
      <p class="echo-quote">
        <em>愿你在被打击时，记起你的珍贵，抵抗恶意。</em><br>
        <em>愿你在迷茫时，坚信你的珍贵。</em><br>
        <em>爱你所爱，行你所行，听从你心，无问西东。</em>
      </p>
    </div>
  </article>


  <!-- Forever Young 2 -->
  <article class="project-card">
    <div class="project-media">
      {% include video.liquid
        path="/assets/video/echo/Forever Young-1.mp4"
        class="img-fluid"
        controls=true
      %}
    </div>
    <div class="project-content">
      <h2>Forever Young, 2018</h2>
      <p class="echo-quote">
        <em>
          什么是真实：你看到什么，听到什么，做什么，和谁在一起，
          要有一种从心灵深处漫溢出的、不懊悔也不羞耻的平和与喜悦。
        </em>
      </p>
      <p>
        <em>
          人把自己置身于忙碌当中，有一种麻木的踏实，但丧失了真实。
          你的青春也不过只有这些日子。
        </em>
      </p>
    </div>
  </article>


  <!-- Groningen -->
  <article class="project-card">
    <div class="project-media">
      <img
        src="/assets/img/echo/rock.jpg"
        alt="A rock associated with memories of Groningen"
        loading="lazy">
    </div>
    <div class="project-content">
      <h2>Home, Sweet Home at Groningen, 2023</h2>
      <p class="echo-quote">
        <strong>You Rock!</strong>
      </p>
    </div>
  </article>

</div>