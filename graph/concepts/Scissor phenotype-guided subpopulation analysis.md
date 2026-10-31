---
type: concept
title: "Scissor phenotype-guided subpopulation analysis"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001204
aliases: ["Scissor", "Single-Cell Identification of Subpopulations with Bulk Sample Phenotype Correlation"]
tags: [single-cell, bulk-integration]
---

# Scissor phenotype-guided subpopulation analysis

Scissor links single-cell data to bulk samples with a known phenotype. It measures the similarity of every cell to every bulk sample, then fits a regression of the sample phenotype on that correlation matrix to pick the cells whose profile tracks the phenotype (positively or negatively). It needs no prior clusters, but the result depends on the bulk cohort and the regularisation setting, and the selected cells are associations, not shown causes.

## Connections

- Applied with bulk Alzheimer and non-Alzheimer entorhinal transcriptomes (binomial model, alpha 0.01) to aged monkey entorhinal single-nucleus data; 1,370 of 31,617 excitatory neurons were flagged. Study: [[Single-nucleus atlas of aging monkey entorhinal cortex and Alzheimer disease]]
- Related methods: [[Single-nucleus RNA sequencing]], [[Single-cell RNA sequencing]]
