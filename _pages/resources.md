---
title: "Resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

<style>
.res-hero {
  background: linear-gradient(135deg, #1a3a4a 0%, #2c6975 100%);
  color: #fff;
  padding: 45px 30px;
  border-radius: 12px;
  margin-bottom: 30px;
}
.res-hero h2 { color: #fff; margin-top: 0; }
.res-hero p { font-size: 1.05em; opacity: 0.92; max-width: 700px; }

.res-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
  gap: 14px;
  margin-bottom: 35px;
}
.res-stat {
  background: #f6f8fa;
  border-radius: 8px;
  padding: 16px 10px;
  text-align: center;
}
.res-stat .num { font-size: 1.6em; font-weight: 700; color: #1a3a4a; display: block; }
.res-stat .label { font-size: 0.78em; color: #666; text-transform: uppercase; letter-spacing: 0.4px; }

.filter-note {
  font-size: 0.85em;
  color: #777;
  margin: -10px 0 25px 0;
  font-style: italic;
}

.res-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin: 20px 0 40px 0;
}
.res-card {
  border: 1px solid #e1e4e8;
  border-radius: 12px;
  padding: 22px;
  background: #fff;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
  display: flex;
  flex-direction: column;
}
.res-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}
.res-card-top { display: flex; justify-content: space-between; align-items: flex-start; }
.res-card .icon { font-size: 1.7em; }
.res-status {
  font-size: 0.68em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.4px;
  padding: 3px 9px;
  border-radius: 10px;
}
.status-active { background: #e3f7e8; color: #1e8e3e; }
.status-beta { background: #fff4e0; color: #b06f00; }
.status-archived { background: #f0f0f0; color: #777; }

.res-card h3 { margin: 12px 0 6px 0; font-size: 1.12em; }
.res-card p.desc { font-size: 0.9em; color: #555; flex-grow: 1; margin-bottom: 14px; }

.tag-row { margin-bottom: 14px; }
.res-tag {
  display: inline-block;
  background: #eef2f5;
  color: #333;
  font-family: monospace;
  font-size: 0.72em;
  padding: 3px 9px;
  border-radius: 6px;
  margin: 0 5px 5px 0;
}

.btn-row { display: flex; gap: 8px; flex-wrap: wrap; margin-top: auto; }
.res-btn {
  font-size: 0.82em;
  font-weight: 600;
  padding: 7px 14px;
  border-radius: 6px;
  text-decoration: none !important;
  transition: opacity 0.15s ease;
}
.res-btn:hover { opacity: 0.85; }
.btn-primary { background: #1a3a4a; color: #fff !important; }
.btn-secondary { background: #eef2f5; color: #1a3a4a !important; }

.dataset-table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0 40px 0;
  font-size: 0.92em;
}
.dataset-table th {
  text-align: left;
  background: #1a3a4a;
  color: #fff;
  padding: 10px 14px;
  font-size: 0.8em;
  text-transform: uppercase;
  letter-spacing: 0.4px;
}
.dataset-table th:first-child { border-radius: 8px 0 0 0; }
.dataset-table th:last-child { border-radius: 0 8px 0 0; }
.dataset-table td {
  padding: 12px 14px;
  border-bottom: 1px solid #eee;
}
.dataset-table tr:hover td { background: #f6f8fa; }
.dataset-table a { font-weight: 600; }

.demo-banner {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  background: #f6f8fa;
  border: 1px solid #e1e4e8;
  border-radius: 12px;
  padding: 20px 24px;
  margin-bottom: 16px;
}
.demo-banner .demo-info h4 { margin: 0 0 4px 0; }
.demo-banner .demo-info p { margin: 0; font-size: 0.88em; color: #555; }

.sponsor-cta {
  background: linear-gradient(135deg, #b8860b 0%, #d4a017 100%);
  color: #fff;
  padding: 35px 30px;
  border-radius: 12px;
  margin: 40px 0 20px 0;
  text-align: center;
}
.sponsor-cta h3 { color: #fff; margin-top: 0; }
.sponsor-cta p { max-width: 600px; margin: 0 auto 18px auto; opacity: 0.95; }
.sponsor-cta .res-btn { background: #fff; color: #b8860b !important; font-size: 0.9em; padding: 10px 22px; }

.section-divider {
  border: none;
  height: 1px;
  background: linear-gradient(90deg, transparent, #ccc, transparent);
  margin: 40px 0;
}
</style>

<div class="sponsor-cta" markdown="0">
  <h3>Interested in Sponsoring or Collaborating?</h3>
  <p>We partner with companies and organizations to extend our tools, scale our datasets, and bring research into real-world use. If our resources are useful to your work, we'd love to talk.</p>
  <a class="res-btn" href="mailto:sontn.fz@gmail.com">Get in Touch →</a>
</div>

## Software & Code

<p class="filter-note">All repositories are open-source under permissive licenses unless noted. Click a card to view the code, docs, or paper.</p>

<div class="res-grid" markdown="0">

  <div class="res-card">
    <div class="res-card-top">
      <span class="icon">⚙️</span>
      <span class="res-status status-active">Active</span>
    </div>
    <h3>CNLM</h3>
    <p class="desc">Confidence Neural Logic Machines</p>
    <div class="tag-row">
      <span class="res-tag">Python</span>
      <span class="res-tag">CC BY-NC</span>
    </div>
    <div class="btn-row">
      <a class="res-btn btn-primary" href="#">💻 GitHub</a>
      <!-- <a class="res-btn btn-secondary" href="#">📄 Docs</a> -->
      <!--<a class="res-btn btn-secondary" href="#">📝 Paper</a>-->
    </div>
  </div>

  <div class="res-card">
    <div class="res-card-top">
      <span class="icon">⚙️</span>
      <span class="res-status status-active">Active</span>
    </div>
    <h3>FysAI</h3>
    <p class="desc">Physics and AI</p>
    <div class="tag-row">
      <span class="res-tag">Python</span>
      <span class="res-tag">CC BY-NC</span>
    </div>
    <div class="btn-row">
      <a class="res-btn btn-primary" href="#">💻 GitHub</a>
      <!-- <a class="res-btn btn-secondary" href="#">📄 Docs</a> -->
      <!-- <a class="res-btn btn-secondary" href="#">📝 Paper</a> -->
    </div>
  </div>

</div>

<div class="res-card">
    <div class="res-card-top">
      <span class="icon">📄</span>
      <span class="res-status status-archived">Paper Code</span>
    </div>
    <h3>AI4Plant</h3>
    <p class="desc">Multi-output Deep Learning methods for plant pathology</p>
    <div class="tag-row">
      <span class="res-tag">Python</span>
      <span class="res-tag">GPL-3.0</span>
    </div>
    <div class="btn-row">
      <a class="res-btn btn-secondary" href="https://github.com/funzi-son/AI4Plant">💻 GitHub</a>
    </div>
  </div>
<hr class="section-divider">

## Datasets

<table class="dataset-table" markdown="0">
  <thead>
    <tr>
      <th>Dataset</th>
      <th>Description</th>
      <th>Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong></strong></td>
      <td>CT Data Preparation for Laryngeal CT Imaging</td>
      <td><a href="https://github.com/funzi-son/LaryngealCT">Download ↓</a></td>
    </tr>
  
  </tbody>
</table>

<hr class="section-divider">

## Live Demos

<div class="demo-banner" markdown="0">
  <div class="demo-info">
    <h4>🎮 [Demo Name]</h4>
    <p>Try [tool/model] directly in your browser — no installation required.</p>
  </div>
  <a class="res-btn btn-primary" href="#">Launch Demo →</a>
</div>

<div class="demo-banner" markdown="0">
  <div class="demo-info">
    <h4>📊 [Demo Name]</h4>
    <p>Interactive visualization of [dataset/model output].</p>
  </div>
  <a class="res-btn btn-primary" href="#">Launch Demo →</a>
</div>

<div class="demo-banner" markdown="0">
  <div class="demo-info">
    <h4>🤖 [Demo Name]</h4>
    <p>Hosted notebook — run [model/pipeline] on your own data.</p>
  </div>
  <a class="res-btn btn-primary" href="#">Open Notebook →</a>
</div>

<hr class="section-divider">

<!--
## Citing Our Work

If you use our software or datasets in your research, please cite:

```bibtex
@article{yourname2026resource,
  title   = {Title of the Paper or Software},
  author  = {Your Name and Collaborators},
  journal = {Venue},
  year    = {2026}
}
```
-->

