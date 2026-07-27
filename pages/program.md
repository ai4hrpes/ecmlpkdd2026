---
layout: page
title: Program
permalink: /program/
---

<style>
.schedule {
  max-width: 780px;
  margin: 2rem auto;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
}

.schedule-item {
  display: flex;
  align-items: flex-start;
  gap: 1.25rem;
  padding: 0.9rem 1rem;
  border-left: 3px solid #e2e2e2;
  position: relative;
}

.schedule-item + .schedule-item {
  margin-top: 2px;
}

.schedule-item .time {
  flex: 0 0 108px;
  font-variant-numeric: tabular-nums;
  font-weight: 600;
  color: #555;
  font-size: 0.92rem;
  padding-top: 0.15rem;
}

.schedule-item .content {
  flex: 1;
}

.schedule-item .label {
  display: inline-block;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  padding: 0.15rem 0.55rem;
  border-radius: 999px;
  margin-bottom: 0.35rem;
}

.schedule-item .title {
  font-size: 1.02rem;
  color: #1a1a1a;
  line-height: 1.4;
}

.schedule-item .title em {
  font-style: italic;
  color: #2a2a2a;
}

.schedule-item .meta {
  margin-top: 0.35rem;
  font-size: 0.85rem;
  color: #6b6b6b;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.5rem;
}

.schedule-item .meta .speaker {
  font-weight: 600;
  color: #444;
}

.schedule-item .meta .speaker::before {
  content: "🎤";
  margin-right: 0.35rem;
  font-size: 0.8rem;
}

.schedule-item .meta .location::before {
  content: "📍";
  margin-right: 0.3rem;
  font-size: 0.8rem;
}

.online-badge {
  display: inline-block;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  background: #e8f1fb;
  color: #2266aa;
  padding: 0.1rem 0.5rem;
  border-radius: 999px;
}

/* Keynote */
.schedule-item.keynote {
  border-left-color: #6a4fbf;
  background: linear-gradient(90deg, rgba(106,79,191,0.07), rgba(106,79,191,0));
}
.schedule-item.keynote .label {
  background: #6a4fbf;
  color: #fff;
}
.schedule-item.keynote .title {
  font-weight: 700;
  font-size: 1.12rem;
}

/* Talk */
.schedule-item.talk {
  border-left-color: #2f8f6f;
}
.schedule-item.talk .label {
  background: #e4f4ee;
  color: #1f6e54;
}

/* Discussion */
.schedule-item.discussion {
  border-left-color: #d3a02a;
}
.schedule-item.discussion .label {
  background: #fbf0d9;
  color: #8a6a15;
}
.schedule-item.discussion .title {
  font-style: italic;
  color: #6b6b6b;
}

/* Break */
.schedule-item.break {
  border-left-color: #cfcfcf;
  opacity: 0.85;
}
.schedule-item.break .label {
  background: #f0f0f0;
  color: #777;
}
.schedule-item.break .title {
  color: #777;
  font-style: italic;
}

.schedule-divider {
  height: 1px;
  background: #ececec;
  margin: 0.4rem 0 0.4rem 108px;
}

/* Speaker & paper info cards */
.info-section {
  max-width: 780px;
  margin: 2.5rem auto 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
}

.info-section h2 {
  font-size: 1.15rem;
  color: #333;
  border-bottom: 2px solid #ececec;
  padding-bottom: 0.4rem;
  margin-bottom: 1rem;
}

.info-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 0.75rem;
  margin-bottom: 1.5rem;
}

.info-card {
  border: 1px solid #ececec;
  border-radius: 10px;
  padding: 0.75rem 1rem;
}

.info-card .name {
  font-weight: 700;
  color: #222;
  font-size: 0.95rem;
}

.info-card .detail {
  font-size: 0.82rem;
  color: #777;
  margin-top: 0.15rem;
}

.tag {
  display: inline-block;
  font-size: 0.66rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.03em;
  padding: 0.08rem 0.45rem;
  border-radius: 999px;
  margin-top: 0.3rem;
}

.tag.academia { background: #e4f4ee; color: #1f6e54; }
.tag.industry { background: #e8f1fb; color: #2266aa; }
.tag.pes { background: #fbf0d9; color: #8a6a15; }
</style>

<div class="schedule">

  <div class="schedule-item break">
    <div class="time">10:00 – 10:30</div>
    <div class="content">
      <span class="label">Break</span>
      <div class="title">Coffee Break</div>
      <div class="meta"><span class="location">Break Area</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item keynote">
    <div class="time">10:30 – 11:10</div>
    <div class="content">
      <span class="label">Keynote 1</span>
      <div class="title">Charlotte Laclau</div>
      <div class="meta"><span class="location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item talk">
    <div class="time">11:10 – 11:25</div>
    <div class="content">
      <span class="label">Contributed Presentation 1</span>
      <div class="title"><em>An Agentic Hybrid Top-Down and Bottom-Up Approach to Knowledge Graph Generation</em></div>
      <div class="meta">
        <span class="speaker">Marc Palyart</span>
        <span class="location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item talk">
    <div class="time">11:25 – 11:40</div>
    <div class="content">
      <span class="label">Contributed Presentation 2</span>
      <div class="title"><em>Evaluating RAG for French immigration law: a benchmark and baseline study</em></div>
      <div class="meta">
        <span class="speaker">Annia Abtout</span>
        <span class="location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item discussion">
    <div class="time">11:40 – 11:55</div>
    <div class="content">
      <span class="label">Discussion</span>
      <div class="title">Open discussion</div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item break">
    <div class="time">11:55 – 12:05</div>
    <div class="content">
      <span class="label">Break</span>
      <div class="title">Coffee Break</div>
      <div class="meta"><span class="location">Break Area</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item keynote">
    <div class="time">12:05 – 12:45</div>
    <div class="content">
      <span class="label">Keynote 2</span>
      <div class="title">Thom Lake <span class="online-badge">Online</span></div>
      <div class="meta"><span class="location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item talk">
    <div class="time">12:45 – 13:00</div>
    <div class="content">
      <span class="label">Contributed Presentation 3</span>
      <div class="title"><em>DRAFT: A Dataset for Recruitment Assessment and Fairness Tracking</em></div>
      <div class="meta">
        <span class="speaker">Tristan Cladière</span>
        <span class="location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item talk">
    <div class="time">13:00 – 13:15</div>
    <div class="content">
      <span class="label">Contributed Presentation 4</span>
      <div class="title"><em>JobHop~v2: A Large-Scale Multilingual Career Trajectory Dataset from Unstructured Resumes</em></div>
      <div class="meta">
        <span class="speaker">Iman Johary</span>
        <span class="location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item discussion">
    <div class="time">13:15 – 13:30</div>
    <div class="content">
      <span class="label">Discussion</span>
      <div class="title">Open discussion</div>
      <div class="meta"><span class="location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item break">
    <div class="time">13:30 – 14:30</div>
    <div class="content">
      <span class="label">Break</span>
      <div class="title">Lunch Break</div>
      <div class="meta"><span class="location">Lunch Area</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item keynote">
    <div class="time">14:30 – 15:10</div>
    <div class="content">
      <span class="label">Keynote 3</span>
      <div class="title">Sabrina Mühlbauer</div>
      <div class="meta"><span class="location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item talk">
    <div class="time">15:10 – 15:25</div>
    <div class="content">
      <span class="label">Contributed Presentation 5</span>
      <div class="title"><em>Generative AI and Workplace Discrimination: How Algorithmic Restructuring Creates New Precarity for Vulnerable Groups</em></div>
      <div class="meta">
        <span class="speaker">Yanzheng Pan</span>
        <span class="location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item talk">
    <div class="time">15:25 – 15:40</div>
    <div class="content">
      <span class="label">Contributed Presentation 6</span>
      <div class="title"><em>What heterogeneity do labour market indicators ignore?</em></div>
      <div class="meta">
        <span class="speaker">Guillaume Bied</span>
        <span class="location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item talk">
    <div class="time">15:40 – 15:55</div>
    <div class="content">
      <span class="label">Contributed Presentation 7</span>
      <div class="title"><em>Inequality Decompositions with Machine Learning: A Potential Outcomes Approach under Limited Overlap</em></div>
      <div class="meta">
        <span class="speaker">Bertille Picard <span class="online-badge">Online</span></span>
        <span class="location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item break">
    <div class="time">16:00 – 16:30</div>
    <div class="content">
      <span class="label">Break</span>
      <div class="title">Coffee Break</div>
      <div class="meta"><span class="location">Break Area</span></div>
    </div>
  </div>
  <div class="schedule-divider"></div>

  <div class="schedule-item keynote">
    <div class="time">16:30 – 17:30</div>
    <div class="content">
      <span class="label">Wrap-up</span>
      <div class="title">Final Discussion and Wrap-up</div>
      <div class="meta"><span class="location">Conference Rooms</span></div>
    </div>
  </div>
