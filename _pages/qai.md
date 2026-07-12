---
title: "[Theme Name]"
permalink: /qai/
author_profile: true
---

{% include base_path %}

<style>
.theme-hero {
  background: linear-gradient(135deg, #2c3e50 0%, #4a6572 100%);
  color: #fff;
  padding: 42px 30px;
  border-radius: 12px;
  margin-bottom: 30px;
}
.theme-hero-top { display: flex; align-items: center; gap: 16px; margin-bottom: 12px; }
.theme-hero-icon {
  font-size: 2em;
  width: 60px;
  height: 60px;
  background: rgba(255,255,255,0.15);
  border-radius: 14px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.theme-hero h2 { color: #fff; margin: 0; }
.theme-hero p { font-size: 1.05em; opacity: 0.92; max-width: 700px; margin-bottom: 0; }
.theme-badge-row { margin-top: 14px; }
.theme-badge {
  display: inline-block;
  background: rgba(255,255,255,0.15);
  border: 1px solid rgba(255,255,255,0.4);
  color: #fff;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.8em;
  margin: 3px 4px 3px 0;
}

.theme-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 14px;
  margin-bottom: 40px;
}
.theme-stat {
  background: #f6f8fa;
  border-radius: 8px;
  padding: 14px 8px;
  text-align: center;
}
.theme-stat .num { font-size: 1.5em; font-weight: 700; color: #2c3e50; display: block; }
.theme-stat .label { font-size: 0.72em; color: #666; text-transform: uppercase; letter-spacing: 0.3px; }

.section-title {
  font-size: 1.2em;
  font-weight: 700;
  color: #1f2933;
  margin: 40px 0 16px 0;
  padding-bottom: 8px;
  border-bottom: 2px solid #e4e7eb;
}
.section-title:first-of-type { margin-top: 0; }

/* Key questions */
.question-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 16px;
  margin-bottom: 10px;
}
.question-card {
  background: #f6f8fa;
  border-left: 4px solid #4a6572;
  border-radius: 8px;
  padding: 16px 18px;
  font-size: 0.92em;
  color: #333;
}
.question-card .q-num { font-weight: 700; color: #4a6572; margin-right: 6px; }

/* Publications */
.pub-list { list-style: none; padding: 0; margin: 0; }
.pub-item {
  padding: 14px 0;
  border-bottom: 1px solid #eee;
}
.pub-item:last-child { border-bottom: none; }
.pub-title { font-weight: 600; color: #1f2933; font-size: 0.95em; }
.pub-meta { font-size: 0.82em; color: #777; margin-top: 3px; }
.pub-links { margin-top: 5px; }
.pub-links a { font-size: 0.8em; font-weight: 600; color: #2c3e50; margin-right: 12px; text-decoration: none; }
.pub-links a:hover { text-decoration: underline; }

/* Projects */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 18px;
  margin-bottom: 10px;
}
.project-card {
  border: 1px solid #e1e4e8;
  border-radius: 10px;
  padding: 18px;
  background: #fff;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
}
.project-card h4 { margin: 0 0 6px 0; font-size: 1em; }
.project-card p { margin: 0; font-size: 0.87em; color: #555; }
.project-status {
  display: inline-block;
  font-size: 0.68em;
  font-weight: 700;
  text-transform: uppercase;
  padding: 2px 9px;
  border-radius: 10px;
  background: #e3f7e8;
  color: #1e8e3e;
  margin-bottom: 8px;
}

/* Team */
.team-avatars { display: flex; flex-wrap: wrap; gap: 14px; }
.avatar-chip {
  display: flex;
  align-items: center;
  gap: 8px;
  background: #f6f8fa;
  border-radius: 20px;
  padding: 6px 14px 6px 6px;
  font-size: 0.85em;
}
.avatar-circle {
  width: 28px;
  height: 28px;
  border-radius: 50%;
  background: #dde3e8;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.9em;
  overflow: hidden;
}
.avatar-circle img { width: 100%; height: 100%; object-fit: cover; }

/* Sponsors / funding */
.funding-row {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 10px;
}
.funding-pill {
  background: #fff4e0;
  color: #b06f00;
  font-size: 0.85em;
  font-weight: 600;
  padding: 7px 15px;
  border-radius: 16px;
}

.section-divider {
  border: none;
  height: 1px;
  background: linear-gradient(90deg, transparent, #ccc, transparent);
  margin: 40px 0;
}
</style>

<div class="theme-hero" markdown="0">
  <div class="theme-hero-top">
    <div class="theme-hero-icon">🧠</div>
    <h2>[Theme Name]</h2>
  </div>
  <p>[One to two sentence overview of the theme — what problem it addresses and why it matters, written for a mixed academic/sponsor audience.]</p>
  <div class="theme-badge-row">
    <span class="theme-badge">[Tag 1]</span>
    <span class="theme-badge">[Tag 2]</span>
    <span class="theme-badge">[Tag 3]</span>
  </div>
</div>

<div class="theme-stats" markdown="0">
  <div class="theme-stat"><span class="num">[X]</span><span class="label">Publications</span></div>
  <div class="theme-stat"><span class="num">[X]</span><span class="label">Active Projects</span></div>
  <div class="theme-stat"><span class="num">[X]</span><span class="label">Team Members</span></div>
  <div class="theme-stat"><span class="num">[X]</span><span class="label">Years Active</span></div>
</div>

<div class="section-title">Overview</div>

[Two to four sentences giving a fuller description of the theme: the core problem, your approach or angle, and what makes your group's take on it distinctive. This is the paragraph a prospective PhD student or sponsor reads to decide whether to keep reading.]

<div class="section-title">Key Research Questions</div>

<div class="question-grid" markdown="0">
  <div class="question-card"><span class="q-num">Q1.</span>[Research question 1]</div>
  <div class="question-card"><span class="q-num">Q2.</span>[Research question 2]</div>
  <div class="question-card"><span class="q-num">Q3.</span>[Research question 3]</div>
</div>

<div class="section-title">Active Projects</div>

<div class="project-grid" markdown="0">
  <div class="project-card">
    <span class="project-status">Ongoing</span>
    <h4>[Project Name]</h4>
    <p>Short description of the project's goal and current focus.</p>
  </div>
  <div class="project-card">
    <span class="project-status">Ongoing</span>
    <h4>[Project Name]</h4>
    <p>Short description of the project's goal and current focus.</p>
  </div>
</div>

<div class="section-title">Related Publications</div>

<ul class="pub-list" markdown="0">
  <li class="pub-item">
    <div class="pub-title">[Paper Title]</div>
    <div class="pub-meta">[Author list] &middot; [Venue], [Year]</div>
    <div class="pub-links">
      <a href="#">PDF</a>
      <a href="#">Code</a>
      <a href="#">BibTeX</a>
    </div>
  </li>
  <li class="pub-item">
    <div class="pub-title">[Paper Title]</div>
    <div class="pub-meta">[Author list] &middot; [Venue], [Year]</div>
    <div class="pub-links">
      <a href="#">PDF</a>
    </div>
  </li>
</ul>

<div class="section-title">Team</div>

<div class="team-avatars" markdown="0">
  <div class="avatar-chip"><span class="avatar-circle">👤</span> [Name]</div>
  <div class="avatar-chip"><span class="avatar-circle">👤</span> [Name]</div>
  <div class="avatar-chip"><span class="avatar-circle">👤</span> [Name]</div>
</div>

<div class="section-title">Funding & Support</div>

<div class="funding-row" markdown="0">
  <span class="funding-pill">[Funding Body / Grant Name]</span>
  <span class="funding-pill">[Industry Partner]</span>
</div>

<hr class="section-divider">

<p style="text-align:center; color:#888; font-size:0.9em;">
Interested in this research direction? See our <a href="/team/">Team</a> page or <a href="mailto:your.email@example.com">get in touch</a> about collaboration and sponsorship opportunities.
</p>
