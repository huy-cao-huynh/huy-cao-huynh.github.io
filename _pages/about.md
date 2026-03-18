---
permalink: /
title: "Huy Huynh"
redirect_from: 
  - /about/
  - /about.html
layout: portfolio
---

<section
  id="biography"
  class="snap-section snap-biography"
  data-section="biography"
>
  <div class="snap-inner">
    <div class="biography-grid">
      <div class="bio-photo reveal" style="--i: 0;">
        <div class="bio-photo-frame" aria-hidden="true"></div>
        <img src="/images/DSC02971%20(1).jpg" alt="Profile photo of Huy Huynh" class="bio-photo-img" />
      </div>

      <div class="bio-content reveal" style="--i: 1;">
        <h1 class="bio-name">{{ site.author.name | default: site.name }}</h1>
        <p class="bio-lead muted2">
          Undergraduate CS student at the University of Washington. I build applied ML systems that connect
          research to real-world impact.
        </p>

        <div class="bio-block">
          <h2 class="bio-h2">Research</h2>
          <p class="bio-p muted2">
            I’m an undergraduate researcher at the
            <a href="https://grail.cs.washington.edu/" target="_blank" rel="noopener">GRAIL Lab</a>
            under the mentorship of PhD Jingwei Ma, and advised by Prof. Steve Seitz, Prof. Ira Kemelmacher-Shlizerman,
            and Prof. Brian Curless. My work focuses on reference-based super-resolution tasks.
          </p>
          <p class="bio-p muted2">
            I’m also an undergraduate researcher at the
            <a href="https://syslab.cs.washington.edu/" target="_blank" rel="noopener">UW Systems Lab</a>
            under the mentorship of PhD Tapan Chugh, and advised by Arvind Krishnamurthy, working on debugging Web Agent
            Gateway System (WAGS) failures.
          </p>
        </div>

        <div class="bio-block">
          <h2 class="bio-h2">Personal / what I’m looking for</h2>
          <p class="bio-p muted2">
            I’m seeking opportunities to apply my technical skills to impactful work—especially in health, accessibility,
            and tools that improve everyday life. I’m particularly motivated by projects that bridge research with
            product.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>

<section
  id="projects"
  class="snap-section snap-projects"
  data-section="projects"
>
  <div class="snap-inner">
    <div class="section-head reveal" style="--i: 0;">
      <h2 class="section-title">Projects</h2>
      <p class="section-sub muted2">
        A selection of work spanning ML pipelines, research prototypes, and classic systems projects.
      </p>
    </div>

    <div class="projects-grid">
      <a
        class="project-card reveal"
        style="--i: 1;"
        href="https://github.com/huy-cao-huynh/Lora-TTS-Efficient-Dialect-Adaptation"
        target="_blank"
        rel="noopener"
      >
        <h3>LoRA-TTS</h3>
        <p>Text-to-speech pipeline fine-tuned for Taiwanese-Mandarin accents.</p>
      </a>

      <a
        class="project-card reveal"
        style="--i: 2;"
        href="https://ultra-zoom.github.io/"
        target="_blank"
        rel="noopener"
      >
        <h3>UltraZoom</h3>
        <p>Multidiffusion transformer models for super-resolution text-to-image tasks.</p>
      </a>

      <a
        class="project-card reveal"
        style="--i: 3;"
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

      <a
        class="project-card reveal"
        style="--i: 4;"
        href="https://github.com/huy-cao-huynh/MockFish"
        target="_blank"
        rel="noopener"
      >
        <h3>Java Chess Engine</h3>
        <p>Mini-Max + Alpha-Beta pruning chess engine for move selection.</p>
      </a>
    </div>
  </div>
</section>

<section
  id="resume"
  class="snap-section snap-resume"
  data-section="resume"
>
  <div class="snap-inner">
    <div class="section-head reveal" style="--i: 0;">
      <h2 class="section-title">Resume</h2>
      <p class="section-sub muted2">Preview and download my resume.</p>
    </div>

    <div class="resume-wrap reveal" style="--i: 1;">
      <iframe
        class="resume-frame"
        src="/_pages/Huy_Huynh_Resume.pdf"
        title="Resume (Huy_Huynh_Resume.pdf)"
        loading="lazy"
      ></iframe>
    </div>

    <div class="resume-actions reveal" style="--i: 2;">
      <a class="btn btn-primary" href="/_pages/Huy_Huynh_Resume.pdf" download>Download Resume</a>
    </div>
  </div>
</section>
