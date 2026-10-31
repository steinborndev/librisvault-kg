---
type: concept
title: "Predictive gene expression signatures with ASSIGN"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-001043
aliases: ["ASSIGN", "Adaptive Signature Selection and InteGratioN", "predicted AD activity"]
tags: [transcriptomics, biomarker]
---

# Predictive gene expression signatures with ASSIGN

ASSIGN (Adaptive Signature Selection and Integration) is a Bayesian R toolkit that takes a gene signature, learns its weights from a training set of reference and perturbed samples, and returns for every other sample a pathway activity score between 0 and 1. Applied to disease tissue, the score is a continuous "disease activity" that can be compared with pathology and clinical grades.

## Connections

- Built from DESeq2 differentially expressed genes of each brain region, trained on strictly defined control and Alzheimer groups, and validated by t-tests against Braak stage, CERAD score, Thal phase and diagnosis, by correlation with plaque density, and by logistic models with leave-one-out cross-validation (AUC 0.729 to 0.995). Study: [[Predictive gene expression signatures of Alzheimer disease in six brain regions]]
- Related: [[Gene set enrichment analysis]], [[AMP-AD brain RNAseq cohorts]], [[Braak staging]]
