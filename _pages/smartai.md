---
title: "[Theme Name]"
permalink: /smartai/
author_profile: true
---

{% include base_path %}

<style>
.tv2-banner {
  height: 220px;
  border-radius: 14px;
  background: linear-gradient(135deg, #1a3a4a 0%, #2c6975 55%, #3d8f8f 100%);
  display: flex;
  align-items: flex-end;
  padding: 26px 32px;
  margin-bottom: 28px;
  position: relative;
  overflow: hidden;
}
.tv2-banner-icon {
  position: absolute;
  top: 24px;
  right: 30px;
  font-size: 4.5em;
  opacity: 0.18;
}
.tv2-banner h1 {
  color: #fff;
  margin: 0;
  font-size: 1.8em;
}
.tv2-banner .subtitle {
  color: rgba(255,255,255,0.85);
  font-size: 0.95em;
  margin-top: 4px;
}

.tv2-layout {
  display: grid;
  grid-template-columns: 260px 1fr;
  gap: 34px;
}
@media (max-width: 750px) {
  .tv2-layout { grid-template-columns: 1fr; }
}

/* ---- Sidebar ---- */
.tv2-sidebar {
  position: sticky;
  top: 20px;
  align-self: start;
}
.tv2-box {
  background: #f6f8fa;
  border-radius: 10px;
  padding: 18px 20px;
  margin-bottom: 16px;
}
.tv2-box h5 {
  font-size: 0.72em;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  color: #888;
  margin: 0 0 10px 0;
}
.tv2-fact { display: flex; justify-content: space-between; font-size: 0.87em; padding: 6px 0; border-bottom: 1px solid #e8eaed; }
.tv2-fact:last-child { border-bottom: none; }
.tv2-fact .k { color: #666; }
.tv2-fact .v { font-weight: 700; color: #1f2933; }

.tv2-tags { display: flex; flex-wrap: wrap; gap: 6px; }
.tv2-tag { background: #fff; border: 1px solid #dde1e5; font-size: 0.78em; padding: 4px 10px; border-radius: 12px; color: #444; }

.tv2-people { display: flex; flex-direction: column; gap: 10px; }
.tv2-person { display: flex; align-items: center; gap: 10px; font-size: 0.85em; }
.tv2-person .dot { width: 26px; height: 26px; border-radius: 50%; background: #dde3e8; display: flex; align-items: center; justify-content: center; font-size: 0.85em; flex-shrink: 0; overflow: hidden; }
.tv2-person .dot img { width: 100%; height: 100%; object-fit: cover; }

.tv2-cta {
  display: block;
  text-align: center;
  background: #1a3a4a;
  color: #fff !important;
  font-weight: 700;
  font-size: 0.85em;
  padding: 11px;
  border-radius: 8px;
  text-decoration: none !important;
}

/* ---- Main article column ---- */
.tv2-lead {
  font-size: 1.08em;
  color: #333;
  line-height: 1.65;
  border-left: 3px solid #2c6975;
  padding-left: 18px;
  margin-bottom: 30px;
}

.tv2-h { font-size: 1.15em; font-weight: 700; color: #1f2933; margin: 34px 0 14px 0; }

.tv2-pullquote {
  background: #fbf8f1;
  border-left: 4px solid #d4a017;
  padding: 16px 20px;
  border-radius: 6px;
  font-size: 0.95em;
  color: #4a4a4a;
  font-style: italic;
  margin: 20px 0;
}

/* Milestone timeline (horizontal on wide screens) */
.tv2-milestones {
  display: flex;
  overflow-x: auto;
  gap: 0;
  margin: 10px 0 20px 0;
  padding-bottom: 8px;
}
.tv2-milestone {
  flex: 0 0 200px;
  border-top: 3px solid #2c6975;
  padding: 12px 16px 0 0;
  margin-right: 18px;
}
.tv2-milestone .yr { font-size: 0.75em; font-weight: 700; color: #2c6975; }
.tv2-milestone .desc { font-size: 0.86em; color: #444; margin-top: 4px; }

/* Publication rows */
.tv2-pub {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 14px;
  padding: 14px 0;
  border-bottom: 1px solid #eee;
}
.tv2-pub:last-child { border-bottom: none; }
.tv2-pub-title { font-weight: 600; font-size: 0.93em; color: #1f2933; }
.tv2-pub-meta { font-size: 0.8em; color: #888; margin-top: 3px; }
.tv2-pub-link { font-size: 0.8em; font-weight: 700; color: #2c6975; white-space: nowrap; text-decoration: none; }
.tv2-pub-link:hover { text-decoration: underline; }
</style>

<div class="tv2-banner" markdown="0">
  <span class="tv2-banner-icon">🧠</span>
  <div>
    <h1>[Theme Name]</h1>
    <div class="subtitle">[One-line tagline describing the research direction]</div>
  </div>
</div>

<div class="tv2-layout" markdown="0">

  <!-- Sidebar -->
  <div class="tv2-sidebar">

    <div class="tv2-box">
      <h5>At a Glance</h5>
      <div class="tv2-fact"><span class="k">Publications</span><span class="v">[X]</span></div>
      <div class="tv2-fact"><span class="k">Active Projects</span><span class="v">[X]</span></div>
      <div class="tv2-fact"><span class="k">Team Members</span><span class="v">[X]</span></div>
      <div class="tv2-fact"><span class="k">Since</span><span class="v">[Year]</span></div>
    </div>

    <div class="tv2-box">
      <h5>Keywords</h5>
      <div class="tv2-tags">
        <span class="tv2-tag">[Tag]</span>
        <span class="tv2-tag">[Tag]</span>
        <span class="tv2-tag">[Tag]</span>
        <span class="tv2-tag">[Tag]</span>
      </div>
    </div>

    <div class="tv2-box">
      <h5>Contributors</h5>
      <div class="tv2-people">
        <div class="tv2-person"><span class="dot">👤</span> [Name]</div>
        <div class="tv2-person"><span class="dot">👤</span> [Name]</div>
        <div class="tv2-person"><span class="dot">👤</span> [Name]</div>
      </div>
    </div>

    <a class="tv2-cta" href="mailto:your.email@example.com">Collaborate With Us →</a>

  </div>

  <!-- Main content -->
  <div class="tv2-main">

    <p class="tv2-lead">[A strong opening paragraph — 2 to 3 sentences — that states the core problem this theme addresses and why it matters. This is the "hook" a sponsor or prospective student reads first.]</p>

    <p>[A further paragraph of context: your group's specific angle, methods, or philosophy on this theme. What makes your approach distinctive compared to others working in the same space.]</p>

    <div class="tv2-pullquote">"[A short, quotable framing of the theme's mission or a key insight — pulled from a paper abstract, talk, or grant proposal.]"</div>

    <div class="tv2-h">Milestones</div>
    <div class="tv2-milestones">
      <div class="tv2-milestone"><div class="yr">[Year]</div><div class="desc">[Milestone description, e.g. first paper published]</div></div>
      <div class="tv2-milestone"><div class="yr">[Year]</div><div class="desc">[Milestone description, e.g. grant awarded]</div></div>
      <div class="tv2-milestone"><div class="yr">[Year]</div><div class="desc">[Milestone description, e.g. open-source release]</div></div>
      <div class="tv2-milestone"><div class="yr">[Year]</div><div class="desc">[Milestone description]</div></div>
    </div>

    <div class="tv2-h">Selected Publications</div>

    <div class="tv2-pub">
      <div>
        <div class="tv2-pub-title">[Paper Title]</div>
        <div class="tv2-pub-meta">[Authors] &middot; [Venue] [Year]</div>
      </div>
      <a class="tv2-pub-link" href="#">PDF →</a>
    </div>

    <div class="tv2-pub">
      <div>
        <div class="tv2-pub-title">[Paper Title]</div>
        <div class="tv2-pub-meta">[Authors] &middot; [Venue] [Year]</div>
      </div>
      <a class="tv2-pub-link" href="#">PDF →</a>
    </div>

    <div class="tv2-pub">
      <div>
        <div class="tv2-pub-title">[Paper Title]</div>
        <div class="tv2-pub-meta">[Authors] &middot; [Venue] [Year]</div>
      </div>
      <a class="tv2-pub-link" href="#">PDF →</a>
    </div>

  </div>

</div>
