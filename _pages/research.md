---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
.research-hero {
  background: linear-gradient(135deg, #2c3e50 0%, #4a6572 100%);
  color: #fff;
  padding: 40px 30px;
  border-radius: 12px;
  margin-bottom: 35px;
}
.research-hero h2 { color: #fff; margin-top: 0; }
.research-hero p { font-size: 1.05em; opacity: 0.92; }

.badge-row { margin: 15px 0 5px 0; }
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

.theme-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin: 25px 0 35px 0;
}
.theme-card {
  border: 1px solid #e1e4e8;
  border-radius: 10px;
  padding: 22px;
  background: #fff;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.theme-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 18px rgba(0,0,0,0.1);
}
.theme-card .icon {
  font-size: 1.8em;
  margin-bottom: 10px;
  display: block;
}
.theme-card h3 { margin-top: 0; font-size: 1.15em; }
.theme-card ul { padding-left: 18px; font-size: 0.9em; margin-bottom: 0; }

.timeline {
  border-left: 3px solid #4a6572;
  margin: 20px 0 35px 15px;
  padding-left: 25px;
}
.timeline-item { position: relative; margin-bottom: 22px; }
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
.timeline-item .tag {
  font-size: 0.75em;
  font-weight: 700;
  text-transform: uppercase;
  color: #4a6572;
  letter-spacing: 0.5px;
}

.collab-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 14px;
  margin: 20px 0 35px 0;
}
.collab-card {
  text-align: center;
  padding: 16px 10px;
  border-radius: 8px;
  background: #f6f8fa;
  font-size: 0.9em;
}
.collab-card .inst { font-size: 0.78em; color: #666; }

.tool-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 15px 0 35px 0; }
.tool-pill {
  background: #eef2f5;
  border-radius: 6px;
  padding: 6px 14px;
  font-size: 0.85em;
  font-family: monospace;
}

.section-divider {
  border: none;
  height: 1px;
  background: linear-gradient(90deg, transparent, #ccc, transparent);
  margin: 40px 0;
}
</style>

<div class="research-hero" markdown="0">
  <h2>What I work on</h2>
  <p>My research focuses on making AI more transparent, reliable, low-cost, and applicable. Check my <a href="https://scholar.google.com.au/citations?user=h82eCK8AAAAJ&hl=en">Google Scholar</a> for the full list of publications.</p>
  <div class="badge-row">
    <span class="badge">Connectionist</span>
    <span class="badge">Symbolic</span>
    <span class="badge">Quantum</span>
    <span class="badge">Applications</span>
  </div>
</div>

## Research Themes

<div class="theme-grid" markdown="0">

  <div class="theme-card">
    <!--<span class="icon">🧠</span> -->
    <h3>Theme 1: <a href="#">NeuroSymbolic/Neural-Symbolic</a></h3>
    <p>Bridging neural networks and symbolic reasoning to create AI that not only performs well, but can explain and justify its decisions.</p>
    <!--<ul>
      <li><a href="#">Confidence Neural Logic</a></li>
      <li><a href="#">Concept Logic Networks</a></li>
    </ul>-->
  </div>

  <div class="theme-card">
    <!--<span class="icon">🛡️</span>-->
    <h3>Theme 2: <a href="#">Reliable & Low-cost AI</a></h3>
    <p>Building AI that performs reliably under real-world conditions, without the heavy computational and financial overhead that limits deployment.</p>
    <!--<ul>
      <li><a href="#">Author et al., Venue Year</a></li>
    </ul>
    -->
  </div>

  <div class="theme-card">
    <!--<span class="icon">⚛️</span>-->
    <h3>Theme 3: <a href="#">Quantum AI</a></h3>
    <p>Researching quantum approaches to machine learning, probing where and how they can outperform classical methods in effectiveness and efficiency.</p>
    <!--<ul>
      <li><a href="#">Author et al., Venue Year</a></li>
    </ul>-->
  </div>

  <div class="theme-card">
    <!--<span class="icon">🚀</span>-->
    <h3>Theme 4: <a href="#">AI Applications</a></h3>
    <p>Applying advances in AI to tackle practical challenges  and  drive progress across Science, Agriculture, Healthcare, and Autonomous Systems.</p>
    <!--<ul>
      <li><a href="#">Author et al., Venue Year</a></li>
    </ul>
    -->
  </div>

</div>

<hr class="section-divider">

<!--
## Current Projects

<div class="timeline" markdown="0">
  <div class="timeline-item">
    <span class="tag">Ongoing</span>
    <h4>[Project Name]</h4>
    <p>One-sentence description of the project and its goal. Funded by [source], in collaboration with [partner].</p>
  </div>
  <div class="timeline-item">
    <span class="tag">Ongoing</span>
    <h4>[Project Name]</h4>
    <p>One-sentence description.</p>
  </div>
  <div class="timeline-item">
    <span class="tag">Completed</span>
    <h4>[Project Name]</h4>
    <p>One-sentence description and where the work led (paper, product, dataset).</p>
  </div>
</div>

<hr class="section-divider">

## Tools & Methods

<div class="tool-row" markdown="0">
  <span class="tool-pill">Python</span>
  <span class="tool-pill">PyTorch</span>
  <span class="tool-pill">[Method/Framework]</span>
  <span class="tool-pill">[Method/Framework]</span>
  <span class="tool-pill">[Dataset/Tool]</span>
</div>
-->
## Collaborators

<div class="collab-grid" markdown="0">
  <div class="collab-card"><strong>Dream AI</strong><br><span class="inst">Global</span></div>
  <div class="collab-card"><strong><a href="https://researchcentres.citystgeorges.ac.uk/acsml" target="_blank" rel="noopener noreferrer"> Research Centre for Machine Learning </a>  </strong><br><span class="inst">City st George's, University of London</span></div>
  <div class="collab-card"><strong><a href="https://blogs.deakin.edu.au/mila/" target="_blank" rel="noopener noreferrer"> Machine Intelligence Lab </a></strong><br><span class="inst">Deakin University</span></div>
</div>
<div class="collab-grid" markdown="0">
  <div class="collab-card"><strong>Data Mining and Knowledge Discovery Group</strong><br><span class="inst">Deakin University</span></div>  
  <div class="collab-card"><strong><a href="https://aisia.vn/" target="_blank" rel="noopener noreferrer"> AISIA Lab </a>  </strong><br><span class="inst">Vietnam</span></div>
  <div class="collab-card"><strong><a href="https://uet.vnu.edu.vn/~trongld/" target="_blank" rel="noopener noreferrer"> Trong's Lab </a></strong><br><span class="inst">UET-Vietnam National University Hanoi</span></div>
</div>

<hr class="section-divider">

<div class="notice--info" markdown="1">
For the full list of papers, visit my <a href="https://scholar.google.com.au/citations?user=h82eCK8AAAAJ&hl=en">Publications</a> page. For talks and slides, see <a href="/talks/">Talks</a>.
</div>
