---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=DM+Mono:wght@300;400&display=swap');

:root {
  --kb-accent:        #2d7a5f;
  --kb-accent-bg:     rgba(45,122,95,0.07);
  --kb-accent-border: rgba(45,122,95,0.25);
  --kb-gold:          #a07840;
  --kb-heading:       #1a1a1a;
  --kb-muted:         #6b6b6b;
}

.kb-cv-title {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(1.6rem, 4vw, 2.2rem);
  font-weight: 400;
  color: var(--kb-heading);
  margin-bottom: 0.2rem;
}

.kb-section-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.66rem;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--kb-accent);
  margin-top: 2.5rem;
  margin-bottom: 0.8rem;
  display: flex;
  align-items: center;
  gap: 0.8rem;
}

.kb-section-label::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--kb-accent-border);
}

.kb-timeline-item {
  border-left: 2px solid var(--kb-accent-border);
  padding-left: 1.2rem;
  margin-bottom: 1.8rem;
  position: relative;
}

.kb-timeline-item::before {
  content: '';
  position: absolute;
  left: -5px;
  top: 6px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--kb-accent);
}

.kb-timeline-degree {
  font-weight: 600;
  color: var(--kb-heading);
  font-size: 0.97rem;
  margin-bottom: 0.1rem;
}

.kb-timeline-institution {
  font-family: 'DM Mono', monospace;
  font-size: 0.74rem;
  color: var(--kb-gold);
  margin-bottom: 0.25rem;
}

.kb-timeline-date {
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  color: var(--kb-muted);
  margin-bottom: 0.4rem;
}

.kb-timeline-detail {
  font-size: 0.88rem;
  color: var(--kb-muted);
  line-height: 1.7;
}

.kb-timeline-detail ul {
  margin: 0.3rem 0 0 0;
  padding-left: 1.1rem;
}

.kb-timeline-detail li {
  margin-bottom: 0.2rem;
}

.kb-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin: 0.5rem 0 1rem;
}

.kb-tag {
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  color: var(--kb-accent);
  border: 1px solid var(--kb-accent-border);
  background: var(--kb-accent-bg);
  padding: 0.2rem 0.6rem;
  border-radius: 2px;
}

.kb-tag-lang {
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  color: var(--kb-gold);
  border: 1px solid rgba(160,120,64,0.3);
  background: rgba(160,120,64,0.07);
  padding: 0.2rem 0.6rem;
  border-radius: 2px;
}

.kb-publi-item {
  border-left: 2px solid var(--kb-accent-border);
  padding-left: 1.2rem;
  margin-bottom: 1.2rem;
  position: relative;
  font-size: 0.88rem;
  color: var(--kb-muted);
  line-height: 1.7;
}

.kb-publi-item::before {
  content: '';
  position: absolute;
  left: -5px;
  top: 6px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--kb-accent);
}

.kb-publi-item strong {
  color: var(--kb-heading);
}

.kb-publi-item a {
  color: var(--kb-accent);
  font-family: 'DM Mono', monospace;
  font-size: 0.72rem;
}

.kb-achieve-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-top: 0.5rem;
}

.kb-achieve-tag {
  font-size: 0.82rem;
  color: var(--kb-muted);
  background: var(--kb-accent-bg);
  border: 1px solid var(--kb-accent-border);
  padding: 0.25rem 0.7rem;
  border-radius: 2px;
}
</style>

<h1 class="kb-cv-title">Curriculum Vitæ</h1>

---

<p class="kb-section-label">✦ Research Experience</p>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">Research Contributor — Origins of Life Project</div>
  <div class="kb-timeline-institution">University of Aberdeen, School of Natural & Computing Sciences · Scotland</div>
  <div class="kb-timeline-date">May 2025 – July 2025 · Supervisor: Dr. Juliano Morimoto</div>
  <div class="kb-timeline-detail"><ul>
    <li>Developed custom R & Python tools for simulating prebiotic RNA strand generation and evolution.</li>
    <li>Modelled emergence of functional sequences to explore plausible origins of life.</li>
  </ul></div>
</div>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">Research Assistant — Spatial Ecology &amp; Conservation Planning</div>
  <div class="kb-timeline-institution">University of Queensland · WAITT Foundation, Brisbane · Australia</div>
  <div class="kb-timeline-date">December 2023 – May 2024 · Supervisor: Prof. Anthony Richardson</div>
  <div class="kb-timeline-detail"><ul>
    <li>Built and optimised Shiny dashboards and R packages for large-scale spatial analysis and conservation planning.</li>
    <li>Handled vector/raster data processing, projection issues, parallelisation and input validation.</li>
  </ul></div>
</div>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">Master Thesis Research Placement — Island Biogeography &amp; Big Data</div>
  <div class="kb-timeline-institution">Ifremer Pacific Center (PDG-RBE-RMPF) · Tahiti, French Polynesia</div>
  <div class="kb-timeline-date">May 2023 – October 2023 · Supervisor: Dr. Cristián Monaco</div>
  <div class="kb-timeline-detail"><ul>
    <li>Analysed marine and terrestrial biodiversity patterns across fragmented island systems using GBIF &amp; OBIS.</li>
    <li>Quantified data biases and produced the first open biogeographic dataset for French Polynesia.</li>
  </ul></div>
</div>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">Master Research Placement — Aquaculture Modelling</div>
  <div class="kb-timeline-institution">Ifremer Palavas · L3AS Lab, France</div>
  <div class="kb-timeline-date">May 2022 – August 2022 · Supervisor: Dr. Myriam Callier</div>
  <div class="kb-timeline-detail"><ul>
    <li>Validated and improved a Python particle-tracking model of aquaculture waste dispersal.</li>
  </ul></div>
</div>

---

<p class="kb-section-label">✦ Education</p>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">MSc — Mathematical &amp; Computational Biology</div>
  <div class="kb-timeline-institution">Aix-Marseille University · CENTURI</div>
  <div class="kb-timeline-date">2021 – 2023</div>
  <div class="kb-timeline-detail">
    Thesis: <em>Biodiversity patterns of marine and terrestrial biogeography in French Polynesia.</em>
    Graduated with honours.
  </div>
</div>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">BSc — Mathematics (Major) &amp; Mechanics (Minor)</div>
  <div class="kb-timeline-institution">University of Nîmes</div>
  <div class="kb-timeline-date">2017 – 2020</div>
  <div class="kb-timeline-detail">
    Foundations in mathematical analysis, logic, calculus, physics and mechanics.
    Graduated with honours.
  </div>
</div>

---

<p class="kb-section-label">✦ Other Experience</p>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">Volunteer Crew &amp; Research Support</div>
  <div class="kb-timeline-institution">Sea Shepherd France — Greek waters, French Guiana, Brazil, Antarctica (upcoming)</div>
  <div class="kb-timeline-date">July 2025 – October 2025</div>
  <div class="kb-timeline-detail">
    Crew member (deck, machinery, navigation) and support for media/communication and ecological policy work.
  </div>
</div>

<div class="kb-timeline-item">
  <div class="kb-timeline-degree">Warehouse Operator &amp; Sales</div>
  <div class="kb-timeline-institution">Troc &amp; Stock, France</div>
  <div class="kb-timeline-date">Summers 2019 – 2022</div>
  <div class="kb-timeline-detail">
    Managed stock of over 10,000 items; handled delicate deliveries with forklift and transpalette.
  </div>
</div>

---

<p class="kb-section-label">✦ Skills</p>

**Programming & Tools**
<div class="kb-tags">
  <span class="kb-tag">R (3+ ans)</span>
  <span class="kb-tag">Python (2+ ans)</span>
  <span class="kb-tag">Shiny</span>
  <span class="kb-tag">Spatial analysis</span>
  <span class="kb-tag">Parallelisation</span>
  <span class="kb-tag">LaTeX (5+ ans)</span>
  <span class="kb-tag">QGIS</span>
  <span class="kb-tag">GitHub / GitLab</span>
</div>

**Languages**
<div class="kb-tags">
  <span class="kb-tag-lang">Français — natif</span>
  <span class="kb-tag-lang">English — C1</span>
  <span class="kb-tag-lang">Español — B1</span>
</div>

---

<p class="kb-section-label">✦ Achievements &amp; Extracurricular</p>

<div class="kb-achieve-grid">
  <span class="kb-achieve-tag">Summer School — Marine Protected Areas (Marseille, 2023)</span>
  <span class="kb-achieve-tag">Open Water Diver</span>
  <span class="kb-achieve-tag">Boat licence (coastal)</span>
  <span class="kb-achieve-tag">Motorcycle licence</span>
  <span class="kb-achieve-tag">Driving licence (manual)</span>
  <span class="kb-achieve-tag">BAFA</span>
  <span class="kb-achieve-tag">BIA</span>
  <span class="kb-achieve-tag">PSC1 (first aid)</span>
  <span class="kb-achieve-tag">French Conservatory Classical Guitar (2nd cycle)</span>
</div>