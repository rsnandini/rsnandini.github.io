---
layout: page
permalink: /Conferences and Workshops/
# title: Conferences & Workshops
# description: Teaching & Talks
nav: true
nav_order: 5
---
<div>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- <title>Conferences and Workshops</title> -->
  <style>
    :root {
      --theme-primary: #17a2b8;
      --theme-primary-soft: rgba(23, 162, 184, 0.10);
      --theme-primary-border: rgba(23, 162, 184, 0.22);
      --theme-text: #1f2937;
      --theme-muted: #6b7280;
      --theme-bg: #f8fafc;
      --theme-card: #ffffff;
      --theme-shadow: 0 12px 30px rgba(15, 23, 42, 0.08);
      --radius-lg: 22px;
      --radius-md: 16px;
      --radius-sm: 12px;
      --max-width: 1100px;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background:
        radial-gradient(circle at top right, rgba(23, 162, 184, 0.10), transparent 28%),
        linear-gradient(180deg, #fcfcff 0%, var(--theme-bg) 100%);
      color: var(--theme-text);
      line-height: 1.6;
    }

    .section-wrap {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 64px 20px 80px;
    }

    .section-header {
      text-align: center;
      margin-bottom: 40px;
    }

    .eyebrow {
      display: inline-block;
      padding: 8px 14px;
      border-radius: 999px;
      background: var(--theme-primary-soft);
      color: var(--theme-primary);
      font-weight: 700;
      font-size: 0.84rem;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      margin-bottom: 14px;
    }

    .section-header h1 {
      margin: 0;
      font-size: clamp(2rem, 3.5vw, 3rem);
      line-height: 1.15;
    }

    .section-header p {
      max-width: 760px;
      margin: 14px auto 0;
      color: var(--theme-muted);
      font-size: 1.02rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 28px;
    }

    .panel {
      background: var(--theme-card);
      border: 1px solid rgba(15, 23, 42, 0.06);
      border-radius: var(--radius-lg);
      box-shadow: var(--theme-shadow);
      padding: 28px;
    }

    .panel-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      margin-bottom: 22px;
    }

    .panel-title h2 {
      margin: 0;
      font-size: 1.35rem;
    }

    .count-badge {
      min-width: 42px;
      height: 42px;
      padding: 0 12px;
      border-radius: 999px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      color: var(--theme-primary);
      background: var(--theme-primary-soft);
      border: 1px solid var(--theme-primary-border);
    }

    .timeline-year {
      margin-top: 22px;
      padding-top: 18px;
      border-top: 1px solid rgba(15, 23, 42, 0.08);
    }

    .timeline-year:first-of-type {
      margin-top: 0;
      padding-top: 0;
      border-top: 0;
    }

    .year-label {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 14px;
      font-size: 1rem;
      font-weight: 800;
      color: var(--theme-primary);
    }

    .year-label::before {
      content: "";
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: var(--theme-primary);
      box-shadow: 0 0 0 6px var(--theme-primary-soft);
    }

    .event-list {
      display: grid;
      gap: 14px;
    }

    .event-card {
      padding: 16px 18px;
      border-radius: var(--radius-md);
      background: #ffffff;
      border: 1px solid rgba(23, 162, 184, 0.12);
      transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
    }

    

    .event-card h3 {
      margin: 0 0 8px;
      font-size: 1.02rem;
      line-height: 1.4;
    }

    .meta {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-bottom: 8px;
    }

    .chip {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 6px 10px;
      border-radius: 999px;
      font-size: 0.86rem;
      color: var(--theme-text);
      background: rgba(15, 23, 42, 0.04);
    }

    .status {
      display: inline-block;
      margin-top: 4px;
      font-size: 0.9rem;
      font-weight: 700;
      color: var(--theme-primary);
    }

    @media (max-width: 900px) {
      .grid {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 640px) {
      .section-wrap {
        padding: 44px 16px 60px;
      }

      .panel {
        padding: 22px;
      }

      .panel-title {
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>
  <section class="section-wrap">
    <div class="section-header">
      <span class="eyebrow">Academic Journey</span>
      <h1>Conferences & Workshops</h1>
      <p>
        A curated timeline of conferences and workshops attended, highlighting research presentations,
        professional development, and international academic engagement.
      </p>
    </div>

    <div class="grid">
      <article class="panel">
        <div class="panel-title">
          <h2>Conferences Attended</h2>
          <span class="count-badge">8</span>
        </div>

        <div class="timeline-year">
          <div class="year-label">2025</div>
          <div class="event-list">
            <div class="event-card">
              <h3>APS Global Physics Summit 2025</h3>
              <div class="meta">
                <span class="chip">Anaheim, CA, USA</span>
                <span class="chip">March 2025</span>
              </div>
              <span class="status">Poster Presented</span>
            </div>
          </div>
        </div>

        <div class="timeline-year">
          <div class="year-label">2023</div>
          <div class="event-list">
            <div class="event-card">
              <h3>MagIC + Magnetism, Interactions and Complexity 2023</h3>
              <div class="meta">
                <span class="chip">Bedlevo, Poland</span>
                <span class="chip">July 2023</span>
              </div>
              <span class="status">Poster Presented</span>
            </div>
            <div class="event-card">
              <h3>8th International Conference on Nanomaterials for Better Living (NBL 2023)</h3>
              <div class="meta">
                <span class="chip">Srinagar, Kashmir, India</span>
                <span class="chip">May 2023</span>
              </div>
              <span class="status">Poster Presented</span>
            </div>
          </div>
        </div>

        <div class="timeline-year">
          <div class="year-label">2022</div>
          <div class="event-list">
            <div class="event-card">
              <h3>Recent Advancement in Sustainable Materials (GC-RASM 2022)</h3>
              <div class="meta">
                <span class="chip">Mangalore, Karnata, India</span>
                <span class="chip">July 2022</span>
              </div>
              <span class="status">Talk Presented</span>
            </div>
            <div class="event-card">
              <h3>International Conference on Higher Education Research and Innovation (ICHERI'22)</h3>
              <div class="meta">
                <span class="chip">Virtually</span>
                <span class="chip">November 2022</span>
              </div>
            </div>
          </div>
        </div>

        <div class="timeline-year">
          <div class="year-label">2021</div>
          <div class="event-list">
            <div class="event-card">
              <h3>International Conference on Advanced Materials and Mechanical Characterization (ICAMMC) 2021</h3>
              <div class="meta">
                <span class="chip">Virtually</span>
                <span class="chip">December 2021</span>
              </div>
            </div>
          </div>
        </div>

        <div class="timeline-year">
          <div class="year-label">2019</div>
          <div class="event-list">
            <div class="event-card">
              <h3>International Conference on Functional Nanomaterials 2019</h3>
              <div class="meta">
                <span class="chip">Dept. of Physics, IIT (BHU), Varanasi, India</span>
                <span class="chip">February 2019</span>
              </div>
              <span class="status">Poster Presented</span>
            </div>
          </div>
        </div>

        <div class="timeline-year">
          <div class="year-label">2017</div>
          <div class="event-list">
            <div class="event-card">
              <h3>2nd International Conference on Condensed Matter and Applied Physics 2017</h3>
              <div class="meta">
                <span class="chip">Govt. Engineering College, Bikaner, India</span>
                <span class="chip">2017</span>
              </div>
              <span class="status">Poster Presented</span>
            </div>
            <div class="event-card">
              <h3>4th International Conference on Nano Structuring by Ion Beam 2017</h3>
              <div class="meta">
                <span class="chip">Devi Ahilya Vishwavidyalaya, Indore, India</span>
                <span class="chip">2017</span>
              </div>
              <span class="status">Poster Presented</span>
            </div>
          </div>
        </div>
      </article>

      <article class="panel">
        <div class="panel-title">
          <h2>Workshops Attended</h2>
          <span class="count-badge">3</span>
        </div>

        <div class="timeline-year">
          <div class="year-label">2019</div>
          <div class="event-list">
            <div class="event-card">
              <h3>The European School on Magnetism 2019 (Experimental Techniques)</h3>
              <div class="meta">
                <span class="chip">Brno, Czech Republic</span>
                <span class="chip">September 2019</span>
              </div>
              <span class="status">Poster Presented</span>
            </div>
          </div>
        </div>

        <div class="timeline-year">
          <div class="year-label">2017</div>
          <div class="event-list">
            <div class="event-card">
              <h3>First Order Phase Transition Workshop 2017</h3>
              <div class="meta">
                <span class="chip">UGC - DAE CSR, Indore, India</span>
                <span class="chip">2017</span>
              </div>
            </div>
            <div class="event-card">
              <h3>M.P. Young Scientist Congress and Associated Events 2017</h3>
              <div class="meta">
                <span class="chip">M.P. Council of Science and Technology, Bhopal, India</span>
              </div>
              <span class="status">Advance course on Research Methodology and Scientific Paper Writing</span>
            </div>
          </div>
        </div>
      </article>
    </div>
  </section>
</body>
</html>
</div>