---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
.resume-wrap {
  display: flex;
  flex-wrap: wrap;
  min-height: 500px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0,0,0,0.12);
  margin-bottom: 30px;
}

/* ---- Sidebar ---- */
.resume-sidebar {
  flex: 1 1 280px;
  background: #1f2933;
  color: #e4e7eb;
  padding: 45px 30px;
  text-align: center;
}
.resume-photo {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  background: #3e4c59;
  margin: 0 auto 20px auto;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2.5em;
  border: 4px solid #52606d;
  overflow: hidden;
}
.resume-photo img { width: 100%; height: 100%; object-fit: cover; }
.resume-sidebar h2 { color: #fff; margin: 0 0 4px 0; font-size: 1.4em; }
.resume-sidebar .role { color: #9aa5b1; font-size: 0.95em; margin-bottom: 20px; }

.social-row {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 25px;
}
.social-row a {
  width: 38px;
  height: 38px;
  border-radius: 50%;
  background: #323f4b;
  color: #fff !important;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none !important;
  font-size: 1em;
  transition: background 0.15s ease;
}
.social-row a:hover { background: #52606d; }

.sidebar-contact {
  text-align: left;
  border-top: 1px solid #3e4c59;
  padding-top: 20px;
  font-size: 0.88em;
}
.sidebar-contact div { margin-bottom: 10px; color: #cbd2d9; }
.sidebar-contact span { color: #7b8794; display: block; font-size: 0.78em; text-transform: uppercase; letter-spacing: 0.4px; }

/* ---- Main content ---- */
.resume-main {
  flex: 3 1 500px;
  background: #fff;
  padding: 45px 40px;
}
.resume-section { margin-bottom: 38px; }
.resume-section:last-child { margin-bottom: 0; }
.resume-section-title {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 1.15em;
  font-weight: 700;
  color: #1f2933;
  margin-bottom: 18px;
  padding-bottom: 8px;
  border-bottom: 2px solid #e4e7eb;
}
.resume-section-title .emoji { font-size: 1.1em; }

.entry { margin-bottom: 22px; padding-left: 2px; }
.entry:last-child { margin-bottom: 0; }
.entry-top { display: flex; justify-content: space-between; flex-wrap: wrap; align-items: baseline; gap: 6px; }
.entry-title { font-weight: 700; color: #1f2933; }
.entry-org { color: #52606d; font-size: 0.92em; }
.entry-date {
  font-size: 0.75em;
  font-weight: 600;
  color: #fff;
  background: #52606d;
  padding: 3px 10px;
  border-radius: 12px;
  white-space: nowrap;
}
.entry p { margin: 6px 0 0 0; font-size: 0.92em; color: #444; }

.skills-row { display: flex; flex-wrap: wrap; gap: 8px; }
.skill-pill {
  background: #e4e7eb;
  color: #1f2933;
  font-size: 0.82em;
  font-weight: 600;
  padding: 6px 14px;
  border-radius: 20px;
}

@media (max-width: 640px) {
  .resume-sidebar { text-align: center; }
  .sidebar-contact { text-align: center; }
}
</style>

<div class="resume-wrap" markdown="0">

  <!-- Sidebar -->
  <div class="resume-sidebar">
    <div class="resume-photo">
      <!-- Replace with: <img src="/images/profile.jpg" alt="Your Name"> -->
      🧑‍🔬
    </div>
    <h2>[Your Name]</h2>
    <div class="role">[Your Title, e.g. PhD Candidate]</div>

    <div class="social-row">
      <a href="mailto:your.email@example.com" title="Email">✉️</a>
      <a href="https://github.com/yourusername" title="GitHub">💻</a>
      <a href="https://scholar.google.com/" title="Google Scholar">🎓</a>
      <a href="https://linkedin.com/in/yourusername" title="LinkedIn">🔗</a>
      <a href="https://twitter.com/yourusername" title="Twitter">🐦</a>
    </div>

    <div class="sidebar-contact">
      <div><span>Location</span>[City, Country]</div>
      <div><span>Institution</span>[University/Lab]</div>
      <div><span>Email</span>your.email@example.com</div>
    </div>
  </div>

  <!-- Main content -->
  <div class="resume-main">

    <div class="resume-section">
      <div class="resume-section-title"><span class="emoji">👋</span> About Me</div>
      <p>I am a <strong>[your role]</strong> in <strong>[Department/Program]</strong> at <strong>[University]</strong>, advised by <strong>[Advisor Name]</strong>. My research focuses on <strong>[1–2 sentence description of your research area]</strong>. I'm broadly interested in [interest 1], [interest 2], and [interest 3].</p>
    </div>

    <div class="resume-section">
      <div class="resume-section-title"><span class="emoji">💼</span> Experience</div>

      <div class="entry">
        <div class="entry-top">
          <span class="entry-title">[Role Title]</span>
          <span class="entry-date">[Year – Present]</span>
        </div>
        <div class="entry-org">[Institution / Company]</div>
        <p>One or two sentences on what you do in this role and key contributions.</p>
      </div>

      <div class="entry">
        <div class="entry-top">
          <span class="entry-title">[Role Title]</span>
          <span class="entry-date">[Year – Year]</span>
        </div>
        <div class="entry-org">[Institution / Company]</div>
        <p>One or two sentences on what you did in this role.</p>
      </div>
    </div>

    <div class="resume-section">
      <div class="resume-section-title"><span class="emoji">🎓</span> Education</div>

      <div class="entry">
        <div class="entry-top">
          <span class="entry-title">Ph.D. in [Field]</span>
          <span class="entry-date">[Year – Present]</span>
        </div>
        <div class="entry-org">[University]</div>
        <p>Brief note on thesis focus or advisor.</p>
      </div>

      <div class="entry">
        <div class="entry-top">
          <span class="entry-title">M.S. in [Field]</span>
          <span class="entry-date">[Year]</span>
        </div>
        <div class="entry-org">[University]</div>
      </div>

      <div class="entry">
        <div class="entry-top">
          <span class="entry-title">B.S. in [Field]</span>
          <span class="entry-date">[Year]</span>
        </div>
        <div class="entry-org">[University]</div>
      </div>
    </div>

    <div class="resume-section">
      <div class="resume-section-title"><span class="emoji">🛠️</span> Skills</div>
      <div class="skills-row">
        <span class="skill-pill">Python</span>
        <span class="skill-pill">PyTorch</span>
        <span class="skill-pill">[Skill]</span>
        <span class="skill-pill">[Skill]</span>
        <span class="skill-pill">[Skill]</span>
      </div>
    </div>

  </div>
</div>

## News

* **[Month Year]**: [Paper/award/talk] accepted at [venue]!
* **[Month Year]**: Started as a [role] at [institution].
* **[Month Year]**: Gave a talk on [topic] at [event].
