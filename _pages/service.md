---
title: "Service"
permalink: /service/
author_profile: true
---

{% include base_path %}

<style>
.service-hero {
  background: linear-gradient(135deg, #2c3e50 0%, #4a6572 100%);
  color: #fff;
  padding: 40px 30px;
  border-radius: 12px;
  margin-bottom: 30px;
}
.service-hero h2 { color: #fff; margin-top: 0; }
.service-hero p { font-size: 1.05em; opacity: 0.92; max-width: 700px; margin-bottom: 0; }

.service-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
  gap: 14px;
  margin-bottom: 40px;
}
.service-stat {
  background: #f6f8fa;
  border-radius: 8px;
  padding: 16px 10px;
  text-align: center;
}
.service-stat .num { font-size: 1.6em; font-weight: 700; color: #2c3e50; display: block; }
.service-stat .label { font-size: 0.78em; color: #666; text-transform: uppercase; letter-spacing: 0.4px; }

/* ---- Invited Talks timeline ---- */
.talks-timeline {
  border-left: 3px solid #4a6572;
  margin: 20px 0 45px 15px;
  padding-left: 28px;
}
.talk-item { position: relative; margin-bottom: 26px; }
.talk-item:last-child { margin-bottom: 0; }
.talk-item::before {
  content: '🎤';
  position: absolute;
  left: -47px;
  top: -2px;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background: #fff;
  border: 2px solid #4a6572;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.85em;
}
.talk-card {
  background: #fff;
  border: 1px solid #e1e4e8;
  border-radius: 10px;
  padding: 16px 20px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.04);
}
.talk-date {
  font-size: 0.72em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  color: #4a6572;
}
.talk-title { font-weight: 700; font-size: 1.03em; margin: 4px 0 3px 0; color: #1f2933; }
.talk-venue { font-size: 0.88em; color: #555; }
.talk-venue .loc { color: #888; }
.talk-links { margin-top: 8px; }
.talk-links a {
  font-size: 0.8em;
  font-weight: 600;
  color: #2c3e50;
  margin-right: 14px;
  text-decoration: none;
}
.talk-links a:hover { text-decoration: underline; }

/* ---- Service section ---- */
.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin: 20px 0 40px 0;
}
.service-card {
  border: 1px solid #e1e4e8;
  border-radius: 12px;
  padding: 24px;
  background: #fff;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
}
.service-card-header {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 16px;
  padding-bottom: 12px;
  border-bottom: 2px solid #f0f2f4;
}
.service-card-header .emoji { font-size: 1.4em; }
.service-card-header h3 { margin: 0; font-size: 1.08em; }
.service-card-header .count {
  margin-left: auto;
  font-size: 0.75em;
  font-weight: 700;
  background: #eef2f5;
  color: #2c3e50;
  padding: 3px 10px;
  border-radius: 10px;
}

.service-list { list-style: none; padding: 0; margin: 0; }
.service-list li {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 10px;
  padding: 9px 0;
  border-bottom: 1px solid #f4f5f6;
  font-size: 0.9em;
}
.service-list li:last-child { border-bottom: none; }
.service-list .venue { color: #333; }
.service-list .years {
  font-size: 0.78em;
  color: #888;
  white-space: nowrap;
  font-family: monospace;
}

/* ---- Reviewer tag cloud ---- */
.reviewer-cloud {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 4px;
}
.reviewer-tag {
  background: #eef2f5;
  color: #2c3e50;
  font-size: 0.82em;
  font-weight: 600;
  padding: 6px 13px;
  border-radius: 16px;
}

.section-divider {
  border: none;
  height: 1px;
  background: linear-gradient(90deg, transparent, #ccc, transparent);
  margin: 40px 0;
}
</style>



## Professional Service

<div class="service-grid" markdown="0">

  <div class="service-card">
    <div class="service-card-header">
      <span class="emoji">🧑‍⚖️</span>
      <h3>Organizing Roles</h3>
      <span class="count">[X]</span>
    </div>
    <ul class="service-list">
      <li><span class="venue">Special Session Organiser [Reliable, Robust and Secure Machine Learning Algorithms]</span><span class="years">2026</span></li>
      <li><span class="venue">Application Track Chair [ICONIP]</span><span class="years">2026</span></li>
      <li><span class="venue">Industry Engagment Chair [ICONIP]</span><span class="years">2026</span></li>
      <li><span class="venue">Local Organiser [KR]</span><span class="years">2026</span></li>
      <li><span class="venue">Organizer [ICDAR]</span><span class="years">2025, 2026</span></li>
    </ul>
  </div>

</div>

## Senior PC Member

<div class="reviewer-cloud" markdown="0">
  <span class="reviewer-tag">ECAI</span>
</div>


## PC Member

<div class="reviewer-cloud" markdown="0">
  <span class="reviewer-tag">NeurIPS</span>
  <span class="reviewer-tag">ICML</span>
  <span class="reviewer-tag">AAAI</span>
  <span class="reviewer-tag">IJCAI</span>
  <span class="reviewer-tag">AAMAS</span>
  <span class="reviewer-tag">KR</span>
  <span class="reviewer-tag">ECML</span>
  <span class="reviewer-tag">EMNLP</span>
  <span class="reviewer-tag">ACL</span>
</div>

## Session Chair

<div class="reviewer-cloud" markdown="0">
  <span class="reviewer-tag">AAAI</span>
  <span class="reviewer-tag">ICONIP</span>
</div>

## Journal Reviewer

<p class="filter-note">Journals I have reviewed for as a peer reviewer:</p>

<div class="reviewer-cloud" markdown="0">
  <span class="reviewer-tag">AI Journal</span>
  <span class="reviewer-tag">IEEE TNNLS</span>
  <span class="reviewer-tag">IJAR</span>
  <span class="reviewer-tag">Neural Networks</span>
  <span class="reviewer-tag">IEEE TETC</span>
  <span class="reviewer-tag">IEEE CYB</span>
</div>


## Conference Reviewer

<p class="filter-note">Conferences I have reviewed for as a peer reviewer:</p>

<div class="reviewer-cloud" markdown="0">
  <span class="reviewer-tag">NeurIPS</span>
  <span class="reviewer-tag">ICML</span>
  <span class="reviewer-tag">AAAI</span>
  <span class="reviewer-tag">IJCAI</span>
  <span class="reviewer-tag">AAMAS</span>
  <span class="reviewer-tag">KR</span>
  <span class="reviewer-tag">NeSy</span>
  <span class="reviewer-tag">ECML</span>
  <span class="reviewer-tag">EMNLP</span>
  <span class="reviewer-tag">ACL</span>
  <span class="reviewer-tag">ECAI</span>
  <span class="reviewer-tag">SoICT</span>
</div>


<!--
## Invited Talks

<div class="talks-timeline" markdown="0">

  <div class="talk-item">
    <div class="talk-card">
      <div class="talk-date">[Month Year]</div>
      <div class="talk-title">[Talk Title]</div>
      <div class="talk-venue">[Event / Institution Name] &middot; <span class="loc">[City, Country]</span></div>
      <div class="talk-links">
        <a href="#">Slides</a>
        <a href="#">Video</a>
      </div>
    </div>
  </div>

  <div class="talk-item">
    <div class="talk-card">
      <div class="talk-date">[Month Year]</div>
      <div class="talk-title">[Talk Title]</div>
      <div class="talk-venue">[Event / Institution Name] &middot; <span class="loc">[City, Country]</span></div>
      <div class="talk-links">
        <a href="#">Slides</a>
      </div>
    </div>
  </div>

  <div class="talk-item">
    <div class="talk-card">
      <div class="talk-date">[Month Year]</div>
      <div class="talk-title">[Talk Title]</div>
      <div class="talk-venue">[Event / Institution Name] &middot; <span class="loc">[City, Country] (Virtual)</span></div>
      <div class="talk-links">
        <a href="#">Video</a>
      </div>
    </div>
  </div>

</div>

<hr class="section-divider">

-->