---
type: concept
title: "Mouse-human module comparison"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001381
aliases: ["cross-species co-expression module comparison", "mouse-human module overlap and correlation"]
tags: [transcriptomics, network-analysis, mouse-model]
---

# Mouse-human module comparison

A two-step way to ask which human disease processes a mouse perturbation resembles. First, co-expression modules from mouse brain ([[Weighted gene co-expression network analysis]]) are mapped to human orthologues through Ensembl and tested for gene overlap with human disease modules by Jaccard index, with significance from 10,000 random gene samples. Because overlap ignores direction, a second step correlates, within each human module, the human log2 fold change (disease versus control) with the mouse perturbation's regression coefficient over orthologous genes.

## Connections

- Applied to five Alzheimer risk-gene mouse strains and APP/PS1 against the 30 [[AMP-AD consensus clusters]]; correlations were small (mostly 0.05 to 0.3 in absolute value). Study: [[Late-onset Alzheimer risk gene mouse models mapped to human brain modules]]
- Related: [[Mouse model validity for Alzheimer disease]], [[AMP-AD brain RNAseq cohorts]]
