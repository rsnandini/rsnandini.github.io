---
layout: page
permalink: /Conferences and Workshops/
title: Conferences & Workshops
description: A curated timeline of conferences and workshops attended, highlighting research presentations, professional development, and international academic engagement.
nav: true
nav_order: 5
---

<style>
  .conferences-wrapper {
    max-width: 100%;
  }

  .conferences-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(min(100%, 450px), 1fr));
    gap: 2rem;
    margin-top: 2rem;
  }

  .conference-panel {
    background: var(--global-card-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 16px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    padding: 1.75rem;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  html[data-theme='dark'] .conference-panel {
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
  }

  .conference-panel:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
  }

  html[data-theme='dark'] .conference-panel:hover {
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
  }

  .panel-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
    margin-bottom: 1.5rem;
    padding-bottom: 1rem;
    border-bottom: 2px solid var(--global-theme-color);
  }

  .panel-header h2 {
    margin: 0;
    font-size: 1.5rem;
    font-weight: 700;
    color: var(--global-text-color);
  }

  .count-badge {
    min-width: 2.5rem;
    height: 2.5rem;
    padding: 0 0.75rem;
    border-radius: 50%;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 1.1rem;
    color: var(--global-bg-color);
    background: var(--global-theme-color);
  }

  .timeline-year {
    margin-top: 1.5rem;
    padding-top: 1.25rem;
    border-top: 1px solid var(--global-divider-color);
  }

  .timeline-year:first-of-type {
    margin-top: 0;
    padding-top: 0;
    border-top: none;
  }

  .year-label {
    display: inline-flex;
    align-items: center;
    gap: 0.625rem;
    margin-bottom: 1rem;
    font-size: 1.1rem;
    font-weight: 800;
    color: var(--global-theme-color);
  }

  .year-label::before {
    content: "";
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: var(--global-theme-color);
    box-shadow: 0 0 0 4px var(--global-hover-color);
    opacity: 0.6;
  }

  .event-list {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }

  .event-card {
    padding: 1rem 1.25rem;
    border-radius: 12px;
    background: var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    transition: all 0.2s ease;
  }

  .event-card:hover {
    border-color: var(--global-theme-color);
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
  }

  html[data-theme='dark'] .event-card:hover {
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.4);
  }

  .event-card h3 {
    margin: 0 0 0.75rem;
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.4;
    color: var(--global-text-color);
  }

  .event-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 0.5rem;
  }

  .meta-chip {
    display: inline-flex;
    align-items: center;
    gap: 0.375rem;
    padding: 0.375rem 0.75rem;
    border-radius: 999px;
    font-size: 0.875rem;
    color: var(--global-text-color);
    background: var(--global-code-bg-color);
    opacity: 0.9;
  }

  .event-status {
    display: inline-block;
    margin-top: 0.25rem;
    font-size: 0.9rem;
    font-weight: 600;
    color: var(--global-theme-color);
  }

  @media (max-width: 768px) {
    .conferences-grid {
      grid-template-columns: 1fr;
      gap: 1.5rem;
    }

    .conference-panel {
      padding: 1.5rem;
    }

    .panel-header h2 {
      font-size: 1.35rem;
    }
  }
</style>

<div class="conferences-wrapper"> 

  <div class="conferences-grid">
    <article class="conference-panel">
      <div class="panel-header">
        <h2>Conferences Attended</h2>
        <span class="count-badge">8</span>
      </div>

      <div class="timeline-year">
        <div class="year-label">2025</div>
        <div class="event-list">
          <div class="event-card">
            <h3>APS Global Physics Summit 2025</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Anaheim, CA, USA</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> March 2025</span>
            </div>
            <span class="event-status">Poster Presented</span>
          </div>
        </div>
      </div>

      <div class="timeline-year">
        <div class="year-label">2023</div>
        <div class="event-list">
          <div class="event-card">
            <h3>MagIC + Magnetism, Interactions and Complexity 2023</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Bedlevo, Poland</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> July 2023</span>
            </div>
            <span class="event-status">Poster Presented</span>
          </div>
          <div class="event-card">
            <h3>8th International Conference on Nanomaterials for Better Living (NBL 2023)</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Srinagar, Kashmir, India</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> May 2023</span>
            </div>
            <span class="event-status">Poster Presented</span>
          </div>
        </div>
      </div>

      <div class="timeline-year">
        <div class="year-label">2022</div>
        <div class="event-list">
          <div class="event-card">
            <h3>Recent Advancement in Sustainable Materials (GC-RASM 2022)</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Mangalore, Karnataka, India</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> July 2022</span>
            </div>
            <span class="event-status">Talk Presented</span>
          </div>
          <div class="event-card">
            <h3>International Conference on Higher Education Research and Innovation (ICHERI'22)</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-video"></i> Virtual</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> November 2022</span>
            </div>
          </div>
        </div>
      </div>

      <div class="timeline-year">
        <div class="year-label">2021</div>
        <div class="event-list">
          <div class="event-card">
            <h3>International Conference on Advanced Materials and Mechanical Characterization (ICAMMC) 2021</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-video"></i> Virtual</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> December 2021</span>
            </div>
          </div>
        </div>
      </div>

      <div class="timeline-year">
        <div class="year-label">2019</div>
        <div class="event-list">
          <div class="event-card">
            <h3>International Conference on Functional Nanomaterials 2019</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> IIT (BHU), Varanasi, India</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> February 2019</span>
            </div>
            <span class="event-status">Poster Presented</span>
          </div>
        </div>
      </div>

      <div class="timeline-year">
        <div class="year-label">2017</div>
        <div class="event-list">
          <div class="event-card">
            <h3>2nd International Conference on Condensed Matter and Applied Physics 2017</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Bikaner, India</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> 2017</span>
            </div>
            <span class="event-status">Poster Presented</span>
          </div>
          <div class="event-card">
            <h3>4th International Conference on Nano Structuring by Ion Beam 2017</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Indore, India</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> 2017</span>
            </div>
            <span class="event-status">Poster Presented</span>
          </div>
        </div>
      </div>
    </article>

    <article class="conference-panel">
      <div class="panel-header">
        <h2>Workshops Attended</h2>
        <span class="count-badge">3</span>
      </div>

      <div class="timeline-year">
        <div class="year-label">2019</div>
        <div class="event-list">
          <div class="event-card">
            <h3>The European School on Magnetism 2019 (Experimental Techniques)</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Brno, Czech Republic</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> September 2019</span>
            </div>
            <span class="event-status">Poster Presented</span>
          </div>
        </div>
      </div>

      <div class="timeline-year">
        <div class="year-label">2017</div>
        <div class="event-list">
          <div class="event-card">
            <h3>First Order Phase Transition Workshop 2017</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> UGC-DAE CSR, Indore, India</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> 2017</span>
            </div>
          </div>
          <div class="event-card">
            <h3>M.P. Young Scientist Congress 2017</h3>
            <div class="event-meta">
              <span class="meta-chip"><i class="fas fa-map-marker-alt"></i> Bhopal, India</span>
              <span class="meta-chip"><i class="fas fa-calendar"></i> 2017</span>
            </div>
            <span class="event-status">Advanced Course: Research Methodology & Scientific Paper Writing</span>
          </div>
        </div>
      </div>
    </article>
  </div>
</div>