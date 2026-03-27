---
title: "Island Biogeography — Biodiversity Patterns in French Polynesia"
excerpt: "First curated biogeographic dataset and master thesis for marine and terrestrial animal species across 119 islands and atolls of French Polynesia, with bias quantification and multi-scale biodiversity analyses (Ifremer Pacific Center, RMPF Unity, Tahiti).<br/><img src='/images/portfolio_m2internship_display.jpeg' width='500' height='300' style='display: block; clear: both; margin: 12px 0 12px 0;'>Taxonomic bias assessment. (A) Major class representation in sampling effort (i.e., observed - ideal). Over- and under-representation of each class are illustrated by the green and orange bars respectively. An inverse hyperbolic-sine transformation was used for the x-axis.""
collection: portfolio
---

<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Mono:wght@300;400&display=swap');

:root {
  --kb-accent:        #2d7a5f;
  --kb-accent-bg:     rgba(45,122,95,0.07);
  --kb-accent-border: rgba(45,122,95,0.25);
  --kb-gold:          #a07840;
  --kb-heading:       #1a1a1a;
  --kb-muted:         #6b6b6b;
}

.kb-section-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.66rem;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--kb-accent);
  margin-top: 2rem;
  margin-bottom: 0.6rem;
}

.kb-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin: 0.6rem 0 1.2rem;
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

.kb-highlight {
  background: var(--kb-accent-bg);
  border: 1px solid var(--kb-accent-border);
  border-radius: 4px;
  padding: 1rem 1.3rem;
  margin: 1.5rem 0;
  font-size: 0.92rem;
  color: var(--kb-muted);
  line-height: 1.8;
}

.kb-download {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.74rem;
  letter-spacing: 0.08em;
  color: var(--kb-accent);
  border: 1px solid var(--kb-accent-border);
  background: var(--kb-accent-bg);
  padding: 0.4rem 0.9rem;
  border-radius: 2px;
  text-decoration: none;
  margin-top: 1rem;
  margin-right: 0.5rem;
}
</style>

<p class="kb-section-label">✦ Context</p>

This project constitutes my Master's thesis, carried out at the **Ifremer Pacific Center** (Tahiti, French Polynesia) under the supervision of Dr. Cristián Monaco, as part of my MSc in Mathematical & Computational Biology at Aix-Marseille University (CENTURI). It led to a peer-reviewed publication in *Scientific Reports* (2025) and an open dataset on SEANOE.

The work addresses a critical gap: despite French Polynesia's status as a marine biodiversity hotspot, no comprehensive, curated biogeographic dataset existed for the region. Using data from **GBIF** and 56 complementary sources, we built the first such dataset and investigated the sampling biases structuring it.

<p class="kb-section-label">✦ Tools & Skills</p>

<div class="kb-tags">
  <span class="kb-tag">R</span>
  <span class="kb-tag">GBIF / OBIS</span>
  <span class="kb-tag">QGIS</span>
  <span class="kb-tag">worrms</span>
  <span class="kb-tag">vegan</span>
  <span class="kb-tag">sampbias</span>
  <span class="kb-tag">ggplot2</span>
  <span class="kb-tag">Jaccard dissimilarity</span>
  <span class="kb-tag">PCoA</span>
  <span class="kb-tag">Bayesian accessibility bias</span>
  <span class="kb-tag">α & β diversity</span>
  <span class="kb-tag">Taxonomic validation</span>
  <span class="kb-tag">Big data cleaning</span>
</div>

<p class="kb-section-label">✦ Key Findings</p>

<div class="kb-highlight">
  156,727 curated occurrences across 7,101 species — with taxonomic reliability of 97–98%. Species richness is heavily concentrated in the Society archipelago (71% of marine species), while Tuamotu and Gambier remain severely under-surveyed. Inventory completeness ranges from 1.9 to 98.4% across islands. Roads, ports, and airports are the dominant accessibility bias factors in both marine and terrestrial datasets. A positive correlation between marine and terrestrial species richness was observed across archipelagos.
</div>

![Observed species richness across French Polynesia — marine (left) and terrestrial (right)](/images/portfolio_m2internship_display.jpeg)

<p class="kb-section-label">✦ Outputs</p>

<a class="kb-download" href="/files/Portfolio_Master_Thesis_Biogeography.pdf">
  📄 Master thesis (PDF)
</a>
<a class="kb-download" href="https://doi.org/10.1038/s41598-025-06631-4">
  📰 Scientific Reports (2025)
</a>
<a class="kb-download" href="https://doi.org/10.17882/99018">
  🗃 Open dataset (SEANOE)
</a>