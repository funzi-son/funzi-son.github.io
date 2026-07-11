---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.about-hero {
  background: linear-gradient(135deg, #2c3e50 0%, #4a6572 100%);
  color: #fff;
  padding: 40px 30px;
  border-radius: 12px;
  margin-bottom: 35px;
}
.about-hero h2 { color: #fff; margin-top: 0; }
.about-hero p { font-size: 1.05em; opacity: 0.92; margin-bottom: 0; }

.badge-row { margin: 15px 0 0 0; }
.badge {
  display: inline-block;
  background: rgba(255,255,255,0.15);
  border: 1px solid rgba(255,255,255,0.4);
  color: #fff;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.8em;
  margin: 3px 4px 3px 0;
}

.quickfacts {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
  gap: 14px;
  margin: 0 0 35px 0;
}
.quickfact {
  background: #f6f8fa;
  border-radius: 8px;
  padding: 14px 10px;
  text-align: center;
}
.quickfact .num { font-size: 1.5em; font-weight: 700; color: #2c3e50; display: block; }
.quickfact .label { font-size: 0.78em; color: #666; text-transform: uppercase; letter-spacing: 0.4px; }

.interest-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 16px;
  margin: 20px 0 35px 0;
}
.interest-card {
  border: 1px solid #e1e4e8;
  border-radius: 10px;
  padding: 18px;
  background: #fff;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.interest-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 18px rgba(0,0,0,0.1);
}
.interest-card .icon { font-size: 1.6em; display: block; margin-bottom: 8px; }
.interest-card h4 { margin: 0 0 6px 0; font-size: 1.02em; }
.interest-card p { margin: 0; font-size: 0.87em; color: #555; }

.timeline {
  border-left: 3px solid #4a6572;
  margin: 20px 0 35px 15px;
  padding-left: 25px;
}
.timeline-item { position: relative; margin-bottom: 20px; }
.timeline-item::before {
  content: '';
  position: absolute;
  left: -32px;
  top: 4px;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #4a6572;
  border: 2px solid #fff;
  box-shadow: 0 0 0 2px #4a6572;
}
.timeline-item .date {
  font-size: 0.75em;
  font-weight: 700;
  text-transform: uppercase;
  color: #4a6572;
  letter-spacing: 0.5px;
}
.timeline-item p { margin: 3px 0 0 0; }

.edu-list { list-style: none; padding: 0; margin: 20px 0 35px 0; }
.edu-item {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  border-bottom: 1px solid #eee;
  padding: 12px 4px;
}
.edu-item:last-child { border-bottom: none; }
.edu-item .degree { font-weight: 600; }
.edu-item .school { color: #666; font-size: 0.9em; }
.edu-item .year {
  font-size: 0.8em;
  background: #eef2f5;
  padding: 3px 10px;
  border-radius: 12px;
  white-space: nowrap;
}

.contact-row { display: flex; flex-wrap: wrap; gap: 10px; margin: 20px 0 10px 0; }
.contact-pill {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: #2c3e50;
  color: #fff !important;
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 0.85em;
  text-decoration: none !important;
}
.contact-pill:hover { background: #4a6572; }

.section-divider {
  border: none;
  height: 1px;
  background: linear-gradient(90deg, transparent, #ccc, transparent);
  margin: 40px 0;
}
</style>

<div class="about-hero" markdown="0">
  <h2>Hi, I'm [Your Name] 👋</h2>
  <p>I am a <strong>[your role, e.g. PhD Student]</strong> in <strong>[Department/Program]</strong> at <strong>[University/Institution]</strong>, advised by <strong>[Advisor Name]</strong>. My research focuses on <strong>[1-sentence description of your research area]</strong>.</p>
  <div class="badge-row">
    <span class="badge">📍 [City, Country]</span>
    <span class="badge">🎓 [Field of Study]</span>
    <span class="badge">✉️ [email]</span>
  </div>
</div>

<div class="quickfacts" markdown="0">
  <div class="quickfact"><span class="num">[X]</span><span class="label">Publications</span></div>
  <div class="quickfact"><span class="num">[X]</span><span class="label">Years Researching</span></div>
  <div class="quickfact"><span class="num">[X]</span><span class="label">Talks Given</span></div>
  <div class="quickfact"><span class="num">[X]</span><span class="label">Collaborators</span></div>
</div>

Before joining [Institution], I completed my [degree] in [field] at [Previous Institution], where I worked with [Name] on [topic]. My current work explores [current project, 1-2 sentences with a bit more technical detail than the intro above].

## Research Interests

<div class="interest-grid" markdown="0">
  <div class="interest-card">
    <span class="icon">🧠</span>
    <h4>[Interest 1]</h4>
    <p>Brief one-line description of what draws you to this area.</p>
  </div>
  <div class="interest-card">
    <span class="icon">📊</span>
    <h4>[Interest 2]</h4>
    <p>Brief one-line description.</p>
  </div>
  <div class="interest-card">
    <span class="icon">🌐</span>
    <h4>[Interest 3]</h4>
    <p>Brief one-line description.</p>
  </div>
</div>

<hr class="section-divider">

## News

<div class="timeline" markdown="0">
  <div class="timeline-item">
    <span class="date">[Month Year]</span>
    <p>🎉 [Paper title] accepted at <strong>[Venue]</strong>!</p>
  </div>
  <div class="timeline-item">
    <span class="date">[Month Year]</span>
    <p>🚀 Started as a [role] at [Institution].</p>
  </div>
  <div class="timeline-item">
    <span class="date">[Month Year]</span>
    <p>🎤 Gave a talk on [topic] at [Event].</p>
  </div>
  <div class="timeline-item">
    <span class="date">[Month Year]</span>
    <p>🏆 Received [Award Name].</p>
  </div>
</div>

<hr class="section-divider">

## Education

<ul class="edu-list" markdown="0">
  <li class="edu-item">
    <div><span class="degree">Ph.D. in [Field]</span><br><span class="school">[University]</span></div>
    <span class="year">[Year–Present]</span>
  </li>
  <li class="edu-item">
    <div><span class="degree">M.S. in [Field]</span><br><span class="school">[University]</span></div>
    <span class="year">[Year]</span>
  </li>
  <li class="edu-item">
    <div><span class="degree">B.S. in [Field]</span><br><span class="school">[University]</span></div>
    <span class="year">[Year]</span>
  </li>
</ul>

<hr class="section-divider">

## Get in Touch

I'm always happy to chat about research, collaborations, or opportunities. Reach out below: test

<div class="contact-row" markdown="0">
  <a class="contact-pill" href="mailto:your.email@example.com">✉️ Email</a>
  <a class="contact-pill" href="https://scholar.google.com/">🎓 Google Scholar</a>
  <a class="contact-pill" href="https://github.com/yourusername">💻 GitHub</a>
  <a class="contact-pill" href="https://linkedin.com/in/yourusername">🔗 LinkedIn</a>
  <a class="contact-pill" href="https://twitter.com/yourusername">🐦 Twitter</a>
</div>
