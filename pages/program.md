---
layout: page
title: Program
permalink: /program/
---

<style>
.ai4hr-schedule, .ai4hr-schedule * {
  box-sizing: border-box;
}

.ai4hr-schedule {
  max-width: 780px;
  margin: 2rem auto;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  text-align: left;
}

.ai4hr-item {
  display: flex;
  align-items: flex-start;
  gap: 1.25rem;
  padding: 0.9rem 1rem;
  border-left: 3px solid #e2e2e2;
  float: none;
  clear: both;
  text-align: left;
}

.ai4hr-item + .ai4hr-item {
  margin-top: 2px;
}

.ai4hr-time {
  flex: 0 0 108px;
  font-variant-numeric: tabular-nums;
  font-weight: 600;
  color: #555;
  font-size: 0.92rem;
  padding-top: 0.15rem;
  text-align: left;
  float: none;
}

.ai4hr-content {
  flex: 1;
  text-align: left;
  float: none;
  min-width: 0;
}

.ai4hr-label {
  display: inline-block;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  padding: 0.15rem 0.55rem;
  border-radius: 999px;
  margin-bottom: 0.35rem;
  text-align: center;
  float: none;
}

.ai4hr-title {
  font-size: 1.02rem;
  color: #1a1a1a;
  line-height: 1.4;
  text-align: left;
  float: none;
}

.ai4hr-title em {
  font-style: italic;
  color: #2a2a2a;
}

.ai4hr-meta {
  margin-top: 0.35rem;
  font-size: 0.85rem;
  color: #6b6b6b;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.5rem;
  text-align: left;
  float: none;
}

.ai4hr-meta .ai4hr-speaker {
  font-weight: 600;
  color: #444;
}

.ai4hr-meta .ai4hr-speaker::before {
  content: "🎤";
  margin-right: 0.35rem;
  font-size: 0.8rem;
}

.ai4hr-meta .ai4hr-location::before {
  content: "📍";
  margin-right: 0.3rem;
  font-size: 0.8rem;
}

.ai4hr-online-badge {
  display: inline-block;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  background: #e8f1fb;
  color: #2266aa;
  padding: 0.1rem 0.5rem;
  border-radius: 999px;
  float: none;
}

/* Keynote */
.ai4hr-item.ai4hr-keynote {
  border-left-color: #6a4fbf;
  background: linear-gradient(90deg, rgba(106,79,191,0.07), rgba(106,79,191,0));
}
.ai4hr-item.ai4hr-keynote .ai4hr-label {
  background: #6a4fbf;
  color: #fff;
}
.ai4hr-item.ai4hr-keynote .ai4hr-title {
  font-weight: 700;
  font-size: 1.12rem;
}

/* Talk */
.ai4hr-item.ai4hr-talk {
  border-left-color: #2f8f6f;
}
.ai4hr-item.ai4hr-talk .ai4hr-label {
  background: #e4f4ee;
  color: #1f6e54;
}

/* Discussion */
.ai4hr-item.ai4hr-discussion {
  border-left-color: #d3a02a;
}
.ai4hr-item.ai4hr-discussion .ai4hr-label {
  background: #fbf0d9;
  color: #8a6a15;
}
.ai4hr-item.ai4hr-discussion .ai4hr-title {
  font-style: italic;
  color: #6b6b6b;
}

/* Break */
.ai4hr-item.ai4hr-break {
  border-left-color: #cfcfcf;
  opacity: 0.85;
}
.ai4hr-item.ai4hr-break .ai4hr-label {
  background: #f0f0f0;
  color: #777;
}
.ai4hr-item.ai4hr-break .ai4hr-title {
  color: #777;
  font-style: italic;
}

.ai4hr-divider {
  height: 1px;
  background: #ececec;
  margin: 0.4rem 0 0.4rem 108px;
  float: none;
  clear: both;
}

/* Speaker & paper info cards */
.ai4hr-info, .ai4hr-info * {
  box-sizing: border-box;
}

.ai4hr-info {
  max-width: 780px;
  margin: 2.5rem auto 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  text-align: left;
}

.ai4hr-info h2 {
  font-size: 1.15rem;
  color: #333;
  border-bottom: 2px solid #ececec;
  padding-bottom: 0.4rem;
  margin-bottom: 1rem;
  text-align: left;
  float: none;
}

.ai4hr-info-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 0.75rem;
  margin-bottom: 1.5rem;
}

.ai4hr-info-card {
  border: 1px solid #ececec;
  border-radius: 10px;
  padding: 0.75rem 1rem;
  text-align: left;
  float: none;
}

.ai4hr-info-card .ai4hr-name {
  font-weight: 700;
  color: #222;
  font-size: 0.95rem;
  text-align: left;
  float: none;
}

.ai4hr-info-card .ai4hr-detail {
  font-size: 0.82rem;
  color: #777;
  margin-top: 0.15rem;
  text-align: left;
  float: none;
}

.ai4hr-tag {
  display: inline-block;
  font-size: 0.66rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.03em;
  padding: 0.08rem 0.45rem;
  border-radius: 999px;
  margin-top: 0.3rem;
  float: none;
}

.ai4hr-tag.ai4hr-academia { background: #e4f4ee; color: #1f6e54; }
.ai4hr-tag.ai4hr-industry { background: #e8f1fb; color: #2266aa; }
.ai4hr-tag.ai4hr-pes { background: #fbf0d9; color: #8a6a15; }
</style>

<div class="ai4hr-schedule">

  <div class="ai4hr-item ai4hr-break">
    <div class="ai4hr-time">10:00 – 10:30</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Break</span>
      <div class="ai4hr-title">Coffee Break</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Break Area</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-keynote">
    <div class="ai4hr-time">10:30 – 11:10</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Keynote 1</span>
      <div class="ai4hr-title">Sabrina Mühlbauer</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-talk">
    <div class="ai4hr-time">11:10 – 11:25</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Contributed Presentation 1</span>
      <div class="ai4hr-title"><em>DRAFT: A Dataset for Recruitment Assessment and Fairness Tracking</em></div>
      <div class="ai4hr-meta">
        <span class="ai4hr-speaker">Tristan Cladière</span>
        <span class="ai4hr-location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-talk">
    <div class="ai4hr-time">11:25 – 11:40</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Contributed Presentation 2</span>
      <div class="ai4hr-title"><em>JobHop~v2: A Large-Scale Multilingual Career Trajectory Dataset from Unstructured Resumes</em></div>
      <div class="ai4hr-meta">
        <span class="ai4hr-speaker">Iman Johary</span>
        <span class="ai4hr-location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-discussion">
    <div class="ai4hr-time">11:40 – 11:55</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Discussion</span>
      <div class="ai4hr-title">Open discussion</div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-break">
    <div class="ai4hr-time">11:55 – 12:05</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Break</span>
      <div class="ai4hr-title">Coffee Break</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Break Area</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-keynote">
    <div class="ai4hr-time">12:05 – 12:45</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Keynote 2</span>
      <div class="ai4hr-title">Charlotte Laclau</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-talk">
    <div class="ai4hr-time">12:45 – 13:00</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Contributed Presentation 3</span>
      <div class="ai4hr-title"><em>An Agentic Hybrid Top-Down and Bottom-Up Approach to Knowledge Graph Generation</em></div>
      <div class="ai4hr-meta">
        <span class="ai4hr-speaker">Marc Palyart</span>
        <span class="ai4hr-location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-talk">
    <div class="ai4hr-time">13:00 – 13:15</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Contributed Presentation 4</span>
      <div class="ai4hr-title"><em>Evaluating RAG for French immigration law: a benchmark and baseline study</em></div>
      <div class="ai4hr-meta">
        <span class="ai4hr-speaker">Annia Abtout</span>
        <span class="ai4hr-location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-discussion">
    <div class="ai4hr-time">13:15 – 13:30</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Discussion</span>
      <div class="ai4hr-title">Open discussion</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-break">
    <div class="ai4hr-time">13:30 – 14:30</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Break</span>
      <div class="ai4hr-title">Lunch Break</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Lunch Area</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-keynote">
    <div class="ai4hr-time">14:30 – 15:10</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Keynote 3</span>
      <div class="ai4hr-title">Thom Lake <span class="ai4hr-online-badge">Online</span></div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Conference Rooms</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-talk">
    <div class="ai4hr-time">15:10 – 15:25</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Contributed Presentation 5</span>
      <div class="ai4hr-title"><em>Generative AI and Workplace Discrimination: How Algorithmic Restructuring Creates New Precarity for Vulnerable Groups</em></div>
      <div class="ai4hr-meta">
        <span class="ai4hr-speaker">Yanzheng Pan</span>
        <span class="ai4hr-location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-talk">
    <div class="ai4hr-time">15:25 – 15:40</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Contributed Presentation 6</span>
      <div class="ai4hr-title"><em>What heterogeneity do labour market indicators ignore?</em></div>
      <div class="ai4hr-meta">
        <span class="ai4hr-speaker">Guillaume Bied</span>
        <span class="ai4hr-location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-talk">
    <div class="ai4hr-time">15:40 – 15:55</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Contributed Presentation 7</span>
      <div class="ai4hr-title"><em>Inequality Decompositions with Machine Learning: A Potential Outcomes Approach under Limited Overlap</em></div>
      <div class="ai4hr-meta">
        <span class="ai4hr-speaker">Bertille Picard <span class="ai4hr-online-badge">Online</span></span>
        <span class="ai4hr-location">Conference Rooms</span>
      </div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-break">
    <div class="ai4hr-time">16:00 – 16:30</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Break</span>
      <div class="ai4hr-title">Coffee Break</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Break Area</span></div>
    </div>
  </div>
  <div class="ai4hr-divider"></div>

  <div class="ai4hr-item ai4hr-keynote">
    <div class="ai4hr-time">16:30 – 17:30</div>
    <div class="ai4hr-content">
      <span class="ai4hr-label">Wrap-up</span>
      <div class="ai4hr-title">Final Discussion and Wrap-up</div>
      <div class="ai4hr-meta"><span class="ai4hr-location">Conference Rooms</span></div>
    </div>
  </div>

</div>
