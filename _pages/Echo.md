/* ========================================
   Main container
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
  margin-top: 0.8rem;
  font-size: 0.9rem;
  color: var(--global-text-color);
  opacity: 0.6;
}


/* ========================================
   Cards
======================================== */

.project-card {
  display: grid;
  grid-template-columns: minmax(0, 1.15fr) minmax(0, 0.85fr);
  gap: 2.4rem;
  align-items: center;

  width: 100%;
  margin-bottom: 2.5rem;
  padding: 1.4rem;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 16px;

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


/* alternate layout */
.project-card:nth-of-type(even) .project-media {
  order: 2;
}

.project-card:nth-of-type(even) .project-content {
  order: 1;
}


/* ========================================
   Media
======================================== */

.project-media {
  width: 100%;
  min-width: 0;
  overflow: hidden;
  border-radius: 12px;
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
  max-height: 460px;
  object-fit: contain;
  background: #000;
}

.project-media img {
  height: auto;
  max-height: 460px;
  object-fit: cover;
}


/* ========================================
   Content
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
   Quote
======================================== */

.echo-quote {
  margin-top: 1rem;
  padding: 0.9rem 0 0.9rem 1.2rem;

  border: none;
  border-left: 3px solid var(--global-theme-color);
  border-radius: 0;

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
   Mobile
======================================== */

@media (max-width: 768px) {

  .echo-hero {
    margin: 1.5rem auto 2.8rem;
  }

  .project-card {
    grid-template-columns: 1fr;
    gap: 1.3rem;

    padding: 1rem;
    margin-bottom: 1.8rem;

    border-radius: 14px;
  }

  .project-card:nth-of-type(even) .project-media,
  .project-card:nth-of-type(even) .project-content {
    order: initial;
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
    font-size: 1.3rem;
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

  .echo-quote {
    padding-left: 0.9rem;
    font-size: 0.92rem;
  }
}