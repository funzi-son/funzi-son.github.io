---
title: "Invited Talks"
permalink: /talks-invited/
author_profile: true
---

{% include base_path %}

<style>
.talks-hero {
  background: linear-gradient(135deg, #2c3e50 0%, #4a6572 100%);
  color: #fff;
  padding: 42px 30px;
  border-radius: 12px;
  margin-bottom: 30px;
}
.talks-hero h2 { color: #fff; margin-top: 0; }
.talks-hero p { font-size: 1.05em; opacity: 0.92; max-width: 700px; margin-bottom: 0; }

.talks-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 14px;
  margin-bottom: 40px;
}
.talks-stat {
  background: #f6f8fa;
  border-radius: 8px;
  padding: 14px 8px;
  text-align: center;
}
.talks-stat .num { font-size: 1.5em; font-weight: 700; color: #2c3e50; display: block; }
.talks-stat .label { font-size: 0.72em; color: #666; text-transform: uppercase; letter-spacing: 0.3px; }

.legend-row {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: -10px 0 30px 0;
  font-size: 0.82em;
  color: #666;
}
.legend-row span { display: flex; align-items: center; gap: 5px; }
.legend-dot { width: 10px; height: 10px; border-radius: 50%; display: inline-block; }

.year-heading {
  font-size: 1.3em;
  font-weight: 700;
  color: #1f2933;
  margin: 40px 0 18px 0;
  padding-bottom: 8px;
  border-bottom: 2px solid #e4e7eb;
}
.year-heading:first-of-type { margin-top: 0; }

.talk-entry {
  display: grid;
  grid-template-columns: 130px 1fr;
  gap: 20px;
  border: 1px solid #e1e4e8;
  border-radius: 12px;
  padding: 20px 22px;
  margin-bottom: 18px;
  background: #fff;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  transition: box-shadow 0.15s ease;
}
.talk-entry:hover { box-shadow: 0 8px 18px rgba(0,0,0,0.09); }

.talk-when {
  text-align: left;
  border-right: 1px solid #eee;
  padding-right: 16px;
}
.talk-month { font-size: 0.78em; font-weight: 700; color: #4a6572; text-transform: uppercase; }
.talk-day { font-size: 1.6em; font-weight: 700; color: #1f2933; line-height: 1.1; }
.talk-loc { font-size: 0.78em; color: #888; margin-top: 6px; }

.talk-type-badge {
  display: inline-block;
  font-size: 0.68em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.4px;
  padding: 3px 10px;
  border-radius: 10px;
  margin-bottom: 8px;
}
.type-keynote { background: #fdecea; color: #c0392b; }
.type-invited { background: #e8f0fe; color: #1a56b0; }
.type-seminar { background: #e6f6ea; color: #1e8e3e; }
.type-panel   { background: #fff4e0; color: #b06f00; }

.talk-title { font-size: 1.1em; font-weight: 700; color: #1f2933; margin: 0 0 4px 0; }
.talk-venue { font-size: 0.9em; color: #555; margin-bottom: 10px; }
.talk-venue strong { color: #333; }
.talk-abstract { font-size: 0.88em; color: #555; margin-bottom: 12px; line-height: 1.5; }

.talk-footer { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 10px; }
.talk-links { display: flex; flex-wrap: wrap; gap: 14px; }
.talk-links a {
  font-size: 0.82em;
  font-weight: 600;
  color: #2c3e50;
  text-decoration: none;
}
.talk-links a:hover { text-decoration: underline; }
.talk-format {
  font-size: 0.76em;
  color: #888;
  font-style: italic;
}

@media (max-width: 560px) {
  .talk-entry { grid-template-columns: 1fr; }
  .talk-when { border-right: none; border-bottom: 1px solid #eee; padding-right: 0; padding-bottom: 10px; margin-bottom: 4px; display: flex; align-items: baseline; gap: 8px; }
}

.section-divider {
  border: none;
  height: 1px;
  background: linear-gradient(90deg, transparent, #ccc, transparent);
  margin: 40px 0;
}
</style>

<div class="talks-hero" markdown="0">
  <h2>Invited Talks</h2>
  <p>Keynotes, invited lectures, and seminar talks presenting our research on physics-informed AI and dynamic systems to academic and industry audiences worldwide.</p>
</div>

<div class="talks-stats" markdown="0">
  <div class="talks-stat"><span class="num">[X]</span><span class="label">Total Talks</span></div>
  <div class="talks-stat"><span class="num">[X]</span><span class="label">Keynotes</span></div>
  <div class="talks-stat"><span class="num">[X]</span><span class="label">Countries</span></div>
  <div class="talks-stat"><span class="num">[X]</span><span class="label">Institutions</span></div>
</div>

<div class="legend-row" markdown="0">
  <span><span class="legend-dot" style="background:#c0392b;"></span> Keynote</span>
  <span><span class="legend-dot" style="background:#1a56b0;"></span> Invited Talk</span>
  <span><span class="legend-dot" style="background:#1e8e3e;"></span> Seminar</span>
  <span><span class="legend-dot" style="background:#b06f00;"></span> Panel</span>
</div>

<div class="year-heading">2026</div>

<div class="talk-entry" markdown="0">
  <div class="talk-when">
    <div class="talk-month">[Mon]</div>
    <div class="talk-day">[DD]</div>
    <div class="talk-loc">📍 [City, Country]</div>
  </div>
  <div class="talk-body">
    <span class="talk-type-badge type-keynote">Keynote</span>
    <div class="talk-title">[Talk Title]</div>
    <div class="talk-venue"><strong>[Conference/Event Name]</strong> — hosted by [Organization]</div>
    <div class="talk-abstract">One or two sentences summarizing what the talk covered — key ideas, results, or the story you told the audience.</div>
    <div class="talk-footer">
      <div class="talk-links">
        <a href="#">📑 Slides</a>
        <a href="#">🎥 Video</a>
        <a href="#">📄 Related Paper</a>
      </div>
      <span class="talk-format">In-person</span>
    </div>
  </div>
</div>

<div class="talk-entry" markdown="0">
  <div class="talk-when">
    <div class="talk-month">[Mon]</div>
    <div class="talk-day">[DD]</div>
    <div class="talk-loc">📍 [City, Country]</div>
  </div>
  <div class="talk-body">
    <span class="talk-type-badge type-invited">Invited Talk</span>
    <div class="talk-title">[Talk Title]</div>
    <div class="talk-venue"><strong>[Workshop/Symposium Name]</strong>, co-located with [Parent Conference]</div>
    <div class="talk-abstract">One or two sentences summarizing what the talk covered.</div>
    <div class="talk-footer">
      <div class="talk-links">
        <a href="#">📑 Slides</a>
      </div>
      <span class="talk-format">Hybrid</span>
    </div>
  </div>
</div>

<div class="year-heading">2025</div>

<div class="talk-entry" markdown="0">
  <div class="talk-when">
    <div class="talk-month">[Mon]</div>
    <div class="talk-day">[DD]</div>
    <div class="talk-loc">📍 [City, Country] (Virtual)</div>
  </div>
  <div class="talk-body">
    <span class="talk-type-badge type-seminar">Seminar</span>
    <div class="talk-title">[Talk Title]</div>
    <div class="talk-venue"><strong>[Department Seminar Series]</strong>, [University Name]</div>
    <div class="talk-abstract">One or two sentences summarizing what the talk covered.</div>
    <div class="talk-footer">
      <div class="talk-links">
        <a href="#">🎥 Video</a>
      </div>
      <span class="talk-format">Virtual</span>
    </div>
  </div>
</div>

<div class="talk-entry" markdown="0">
  <div class="talk-when">
    <div class="talk-month">[Mon]</div>
    <div class="talk-day">[DD]</div>
    <div class="talk-loc">📍 [City, Country]</div>
  </div>
  <div class="talk-body">
    <span class="talk-type-badge type-panel">Panel</span>
    <div class="talk-title">[Panel Title / Topic]</div>
    <div class="talk-venue"><strong>[Conference Name]</strong> — panel discussion</div>
    <div class="talk-abstract">Brief note on the panel's theme and your role/contribution in the discussion.</div>
    <div class="talk-footer">
      <div class="talk-links">
        <a href="#">🎥 Video</a>
      </div>
      <span class="talk-format">In-person</span>
    </div>
  </div>
</div>

<hr class="section-divider">

<p style="text-align:center; color:#888; font-size:0.9em;">
For a full record of publications and academic service, see <a href="/publications/">Publications</a> and <a href="/service/">Talks & Service</a>.
</p>
