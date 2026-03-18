---
permalink: /
title: "Huy Huynh"
redirect_from: 
  - /about/
  - /about.html
layout: portfolio
---

<div id="top" class="hero">
  <div class="hero-inner">
    <div class="hero-card">
      <div class="profile">
        <div class="avatar">
          <img src="/images/DSC02971%20(1).jpg" alt="Profile photo of Huy Huynh" />
        </div>
        <div>
          <h1 class="name">{{ site.author.name | default: site.name }}</h1>
          <p class="lead">
            Undergraduate CS student at the University of Washington. I build applied ML systems that connect
            research to real-world impact.
          </p>

          <div class="chip-row" aria-label="Focus areas">
            <span class="chip">Machine Learning</span>
            <span class="chip">Deep Learning</span>
            <span class="chip">Web Agents</span>
            <span class="chip">Super-resolution</span>
          </div>

          <div class="hero-actions">
            <a
              class="btn btn-primary"
              href="https://github.com/{{ site.author.github }}"
              target="_blank"
              rel="noopener"
            >
              GitHub
            </a>
            <a
              class="btn"
              href="https://www.linkedin.com/in/{{ site.author.linkedin }}/"
              target="_blank"
              rel="noopener"
            >
              LinkedIn
            </a>
            <a class="btn" href="mailto:{{ site.author.email }}">
              Email
            </a>
            <a class="btn" href="#resume">Resume</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<section id="projects" class="section">
  <div class="section-inner">
    <h2>Projects</h2>
    <p class="muted">
      A selection of work spanning ML pipelines, research prototypes, and classic systems projects.
    </p>

    <div class="projects-grid">
      <a
        class="project-card"
        href="https://github.com/huy-cao-huynh/Lora-TTS-Efficient-Dialect-Adaptation"
        target="_blank"
        rel="noopener"
      >
        <h3>LoRA-TTS</h3>
        <p>Text-to-speech pipeline fine-tuned for Taiwanese-Mandarin accents.</p>
      </a>

      <a class="project-card" href="https://ultra-zoom.github.io/" target="_blank" rel="noopener">
        <h3>UltraZoom</h3>
        <p>
          Multidiffusion transformer models for super-resolution text-to-image tasks.
        </p>
      </a>

      <a
        class="project-card"
        href="https://github.com/huy-cao-huynh/VisTumor"
        target="_blank"
        rel="noopener"
      >
        <h3>VisTumor</h3>
        <p>
          Deep learning pipeline for cancer detection in histopathology images, with Grad-CAM++ and saliency
          mapping for interpretability.
        </p>
      </a>

      <a class="project-card" href="https://github.com/huy-cao-huynh/MockFish" target="_blank" rel="noopener">
        <h3>Java Chess Engine</h3>
        <p>
          Fully functioning Java chess engine using Mini-Max with Alpha-Beta pruning for move selection.
        </p>
      </a>
    </div>
  </div>
</section>

<section id="biography" class="section">
  <div class="section-inner">
    <h2>Biography</h2>

    <div class="split">
      <div class="card">
        <h3>Research</h3>
        <p class="muted" style="margin: 0;">
          I’m an undergraduate researcher at the <a href="https://grail.cs.washington.edu/" target="_blank" rel="noopener">GRAIL Lab</a>
          under the mentorship of PhD Jingwei Ma, and advised by Prof. Steve Seitz, Prof. Ira Kemelmacher-Shlizerman,
          and Prof. Brian Curless. My work focuses on reference-based super-resolution tasks.
        </p>
        <p class="muted" style="margin: 10px 0 0;">
          I’m also an undergraduate researcher at the <a href="https://syslab.cs.washington.edu/" target="_blank" rel="noopener">UW Systems Lab</a>
          under the mentorship of PhD Tapan Chugh, and advised by Arvind Krishnamurthy, working on debugging Web Agent
          Gateway System (WAGS) failures.
        </p>
      </div>

      <div class="card">
        <h3>Personal / what I’m looking for</h3>
        <p class="muted" style="margin: 0;">
          I’m seeking opportunities to apply my technical skills to impactful work—especially in health, accessibility,
          and tools that improve everyday life. I’m particularly motivated by projects that bridge research with
          product.
        </p>
      </div>
    </div>
  </div>
</section>

<section id="resume" class="section">
  <div class="section-inner">
    <h2>Resume</h2>
    <p class="muted">Preview and download my resume.</p>

    <div class="resume-wrap">
      <iframe
        class="resume-frame"
        src="/_pages/Huy_Huynh_Resume.pdf"
        title="Resume (Huy_Huynh_Resume.pdf)"
        loading="lazy"
      ></iframe>
    </div>

    <div class="hero-actions" style="margin-top: 14px;">
      <a class="btn btn-primary" href="/_pages/Huy_Huynh_Resume.pdf" download>Download Resume</a>
      <a class="btn" href="#top">Back to top</a>
    </div>
  </div>
</section>
