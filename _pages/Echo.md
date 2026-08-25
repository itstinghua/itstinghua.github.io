.echo-container {
  width: 100%;
  max-width: 680px;
  margin: 0 auto;
}

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
   Item
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

.echo-media iframe {
  aspect-ratio: 16 / 9;
}

.echo-media video {
  height: auto;
  max-height: 430px;

  object-fit: contain;

  background: #000;
}

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

.echo-note {
  max-width: 560px;

  margin-top: 0.5rem;

  font-size: 0.92rem;
  line-height: 1.7;

  color: var(--global-text-color);
  opacity: 0.68;
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

  .echo-note {
    font-size: 0.88rem;
    line-height: 1.65;
  }

  .echo-meta {
    font-size: 0.68rem;
  }
}