---
title: "Team"
permalink: /team/
author_profile: true
---

{% include base_path %}

<style>
.team-hero {
  background: linear-gradient(135deg, #2c3e50 0%, #4a6572 100%);
  color: #fff;
  padding: 40px 30px;
  border-radius: 12px;
  margin-bottom: 30px;
}
.team-hero h2 { color: #fff; margin-top: 0; }
.team-hero p { font-size: 1.05em; opacity: 0.92; max-width: 700px; margin-bottom: 0; }

.team-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 14px;
  margin-bottom: 40px;
}
.team-stat {
  background: #f6f8fa;
  border-radius: 8px;
  padding: 14px 8px;
  text-align: center;
}
.team-stat .num { font-size: 1.5em; font-weight: 700; color: #2c3e50; display: block; }
.team-stat .label { font-size: 0.72em; color: #666; text-transform: uppercase; letter-spacing: 0.3px; }

.role-section-title {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 1.2em;
  font-weight: 700;
  color: #1f2933;
  margin: 40px 0 18px 0;
}
.role-section-title .emoji { font-size: 1.1em; }
.role-section-title .role-count {
  font-size: 0.65em;
  font-weight: 700;
  background: #eef2f5;
  color: #2c3e50;
  padding: 3px 10px;
  border-radius: 10px;
  text-transform: uppercase;
  letter-spacing: 0.4px;
}

.member-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
  margin-bottom: 10px;
}
.member-card {
  border: 1px solid #e1e4e8;
  border-radius: 12px;
  padding: 20px;
  background: #fff;
  text-align: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.member-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}
.member-photo {
  width: 90px;
  height: 90px;
  border-radius: 50%;
  background: #eef2f5;
  margin: 0 auto 14px auto;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2em;
  overflow: hidden;
  border: 3px solid #f0f2f4;
}
.member-photo img { width: 100%; height: 100%; object-fit: cover; }
.member-name { font-weight: 700; font-size: 1.02em; color: #1f2933; margin-bottom: 2px; }
.member-role { font-size: 0.85em; color: #666; margin-bottom: 12px; min-height: 2.4em; }
.member-links { display: flex; justify-content: center; gap: 8px; }
.member-links a {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background: #f6f8fa;
  color: #2c3e50 !important;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none !important;
  font-size: 0.85em;
  transition: background 0.15s ease;
}
.member-links a:hover { background: #e1e4e8; }

.alumni-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 15px 0 10px 0;
}
.alumni-pill {
  background: #f6f8fa;
  border: 1px solid #e1e4e8;
  border-radius: 20px;
  padding: 8px 16px;
  font-size: 0.88em;
  color: #333;
}
.alumni-pill .now { color: #888; font-size: 0.85em; }

.join-cta {
  background: linear-gradient(135deg, #1a3a4a 0%, #2c6975 100%);
  color: #fff;
  padding: 32px 28px;
  border-radius: 12px;
  margin: 45px 0 10px 0;
  text-align: center;
}
.join-cta h3 { color: #fff; margin-top: 0; }
.join-cta p { max-width: 600px; margin: 0 auto 16px auto; opacity: 0.95; font-size: 0.95em; }
.join-cta a {
  display: inline-block;
  background: #fff;
  color: #1a3a4a !important;
  font-weight: 700;
  padding: 10px 22px;
  border-radius: 6px;
  text-decoration: none !important;
  font-size: 0.9em;
}

.section-divider {
  border: none;
  height: 1px;
  background: linear-gradient(90deg, transparent, #ccc, transparent);
  margin: 40px 0;
}
</style>

<div class="team-hero" markdown="0">
  <h2>Our Team</h2>
  <p>Meet the researchers, engineers, and students behind our work in AI.</p>
</div>

<!--

<div class="role-section-title" markdown="0">
  <span class="emoji">🔬</span> Postdoctoral Researchers <span class="role-count">[X]</span>
</div>

<div class="member-grid" markdown="0">

  <div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">[Name]</div>
    <div class="member-role">[Research focus, e.g. Physics-informed neural networks]</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>

</div>

-->
<div class="role-section-title" markdown="0">
  <span class="emoji">🎓</span> Current 
</div>

<div class="member-grid" markdown="0">

  <div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Spencer Gerontzos</div>
    <div class="member-role">PhD Student, Safe RL</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Nivea Roy</div>
    <div class="member-role">PhD Student, Medical Imaging</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Bahman Jafari Tabaghsar</div>
    <div class="member-role">PhD Student, Explainable AI</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>


  <div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Nam Nguyen</div>
    <div class="member-role">PhD Student, Quantum AI/Op</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Nam Luu</div>
    <div class="member-role">PhD Student, Trajectory Forecast</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Minh Vu</div>
    <div class="member-role">Honours & RA, ML for Dynamic Modelling</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>

<div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Xinyi Wang</div>
    <div class="member-role">PhD Student, Early Dementia Detection</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>

<div class="member-card">
    <div class="member-photo">👤</div>
    <div class="member-name">Hieu Nguyen</div>
    <div class="member-role">PhD Student, Explainable AI</div>
    <div class="member-links">
      <a href="mailto:email@example.com" title="Email">✉️</a>
      <a href="#" title="Google Scholar">🎓</a>
      <a href="#" title="GitHub">💻</a>
    </div>
  </div>
  
</div>
<hr class="section-divider">

## Alumni

<div class="alumni-list" markdown="0">
  <span class="alumni-pill">Jamal Maktoubian <span class="now">— now at Menzies Institute for Medical Research</span></span>
  <span class="alumni-pill">Rami Mohawesh<span class="now">— now at xxx</span></span>
  <span class="alumni-pill">Yuchen Wei <span class="now">— now at xxx</span></span>
  <span class="alumni-pill">Taige Zhao</span>
  <span class="alumni-pill"> Jianping Yao</span> 
  <span class="alumni-pill">Guan Huang </span>
  <span class="alumni-pill">Jiejun Huo </span>
  <span class="alumni-pill">Bijaya Bhattarrai  </span>
  <span class="alumni-pill">Yunjue Zhou </span>
  <span class="alumni-pill"> Xinping Liu</span>
  <span class="alumni-pill">  Wenke Zhao</span>

  
  <span class="alumni-pill">[Name] <span class="now">— now at [Company/Institution]</span></span>
</div>

<div class="join-cta" markdown="0">
  <h3>Join Our Team</h3>
  <p>We're always looking for motivated students and collaborators. See our <a href="/" style="color:#fff;text-decoration:underline;">About page</a> for current openings and PhD application requirements.</p>
  <a href="mailto:your.email@example.com">Get in Touch →</a>
</div>
