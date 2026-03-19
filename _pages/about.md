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

        <div class="bio-links" aria-label="Social links">
          <a
            class="bio-link"
            href="https://github.com/{{ site.author.github }}"
            target="_blank"
            rel="noopener"
          >
            GitHub
          </a>
          <a
            class="bio-link"
            href="https://www.linkedin.com/in/{{ site.author.linkedin }}/"
            target="_blank"
            rel="noopener"
          >
            LinkedIn
          </a>
          <a class="bio-link" href="mailto:{{ site.author.email }}">Email</a>
        </div>

        <div class="bio-block">
          <h2 class="bio-h2">Research</h2>
          <p class="bio-p muted2">
            I'm an undergraduate researcher at the
            <a href="https://grail.cs.washington.edu/" target="_blank" rel="noopener">GRAIL Lab</a>
            under the mentorship of PhD Jingwei Ma, and advised by Prof. Steve Seitz, Prof. Ira Kemelmacher-Shlizerman,
            and Prof. Brian Curless. My work focuses on reference-based super-resolution tasks.
          </p>
          <p class="bio-p muted2">
            I'm also an undergraduate researcher at the
            <a href="https://syslab.cs.washington.edu/" target="_blank" rel="noopener">UW Systems Lab</a>
            under the mentorship of PhD Tapan Chugh, and advised by Arvind Krishnamurthy, working on debugging Web Agent
            Gateway System (WAGS) failures.
          </p>
        </div>

        <div class="bio-block">
          <h2 class="bio-h2">Personal / what I'm looking for</h2>
          <p class="bio-p muted2">
            I'm seeking opportunities to apply my technical skills to impactful work—especially in health, accessibility,
            and tools that improve everyday life. I'm particularly motivated by projects that bridge research with
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
      {% for project in site.data.projects %}
      <button
        type="button"
        class="project-card reveal"
        style="--i: {{ forloop.index }};"
        data-project-id="{{ project.id }}"
        data-project-title="{{ project.title }}"
        data-project-short="{{ project.short_desc }}"
        data-project-sub="{{ project.sub_desc }}"
        data-project-image="{{ project.image }}"
        data-project-github="{{ project.github }}"
        data-project-demo="{{ project.demo }}"
        data-project-details="{{ project.details | strip_newlines | escape }}"
        data-project-tech="{{ project.tech }}"
        aria-label="View details for {{ project.title }}"
      >
        <h3>{{ project.title }}</h3>
        <p>{{ project.short_desc }}</p>
        <p class="project-sub">{{ project.sub_desc }}</p>
        <span class="project-card-cta">Click here to see more</span>
      </button>
      {% endfor %}
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
