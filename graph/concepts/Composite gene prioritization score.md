---
type: concept
title: "Composite gene prioritization score"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001298
aliases: ["multi-omic gene prioritisation", "z-score sum gene ranking"]
tags: [gwas-method]
---

# Composite gene prioritization score

A way to pick the likely causal gene at a GWAS locus by turning each line of evidence into one number per gene, standardising each as a z-score and summing them; the top-scoring gene in a region is nominated. Where a gene has several variants or probes, the one with the smallest P-value stands for it.

## Connections

- Evidence lines in the early-onset Alzheimer disease and lipid study: MAGMA gene-based association (run in FUMA; 19,163 genes, threshold 2.61e-6); Agora target risk score (0 to 5, genetic plus multi-omic); MetaBrain cortex (n = 2,683) and hippocampus (n = 208) cis-eQTL; maximum H4 from [[Colocalization analysis]] across 61 eQTL datasets; ROSMAP prefrontal cortex [[DNA methylation]] (761 participants) against amyloid and PHF-tau load; and a [[Single-cell RNA sequencing]] score (expression proportion x expression level x a differential-expression index) in human and [[Danio rerio]] brain. Study: [[Local genetic covariance of early-onset Alzheimer disease with lipid traits]]
- Limits named by the authors: genes with missing data in some resources are disadvantaged, and the scheme only considers genes under the early-onset top-hit peak.
- Used after [[Local genetic covariance analysis]] to rank 26 genes in three regions; top genes [[ANKDD1B]], [[CUZD1]] and [[MS4A6A]].
- Related: [[Expression quantitative trait locus analysis]]
