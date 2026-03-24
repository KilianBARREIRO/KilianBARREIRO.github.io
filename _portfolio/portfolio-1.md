---
title: "RNA World — Codon Bias & Amino Acid Symmetry"
excerpt: "A simulation framework in R to generate synthetic RNA sequences across five nucleotide profiles and explore codon redundancy, nucleotide biases, melting temperatures and amino acid distributions.<br/><img src='/images/portfolio_rnaworld_display.jpeg' width='500' height='300' style='display: block; clear: both; margin: 12px 0 12px 0;'>Figure 4: Most highly deviated amino acids from the balanced codon usage profile, illustrating shifts in amino acid frequenceis under AT- and GC-biased scenarios."
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
}
</style>

<p class="kb-section-label">✦ Context</p>

This project was carried out during my research position at the **University of Aberdeen** (School of Natural & Computing Sciences), under the supervision of Dr. Juliano Morimoto, as part of an Origins of Life investigation. The work explores how nucleotide composition constraints shape amino acid distributions in synthetic RNA sequences — a question directly relevant to early molecular evolution.

<p class="kb-section-label">✦ Tools & Skills</p>

<div class="kb-tags">
  <span class="kb-tag">R</span>
  <span class="kb-tag">Custom simulation framework</span>
  <span class="kb-tag">Spearman correlation</span>
  <span class="kb-tag">Two-way ANOVA</span>
  <span class="kb-tag">Linear modelling</span>
  <span class="kb-tag">ggplot2</span>
  <span class="kb-tag">Genetic code translation</span>
  <span class="kb-tag">Melting temperature</span>
</div>

<p class="kb-section-label">✦ Key Findings</p>

<div class="kb-highlight">
  Strong positive correlation between codon redundancy and amino acid frequency (ρ up to 0.75), particularly under balanced and GC-rich conditions. Nucleotide bias shifts amino acid composition predictably — GC-rich profiles favour Proline, Glycine and Alanine, while AU-rich conditions enrich Isoleucine and Asparagine. Despite these biases, strand compositional symmetry is preserved as sequence length increases.
</div>

![Key result — amino acid deviations across nucleotide profiles](/images/portfolio_rnaworld_display.jpeg)

<p class="kb-section-label">✦ Report</p>

<a class="kb-download" href="/files/Portfolio_RNA_world_report.pdf">
  📄 Full report (PDF)
</a>

&nbsp;&nbsp;
<a class="kb-download" href="https://github.com/KilianBARREIRO/RNA-World">
  💻 GitHub repository
</a>