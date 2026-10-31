---
type: concept
title: "Proteome-wide association study"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-000942
aliases: ["PWAS", "penalized regression based PWAS", "BLISS model"]
tags: [gwas-method, proteomics]
---

# Proteome-wide association study

A proteome-wide association study (PWAS) tests whether the genetically predicted level of a protein is associated with a disease. A prediction model is trained on reference data linking genotype to protein abundance (see [[Protein quantitative trait locus analysis]]) and is then applied to GWAS summary statistics, so a result is a gene-level association rather than a single-variant one. Penalized regression, which shrinks many small variant effects, is one way to build the prediction model; BLISS is the penalized-regression PWAS model named in the Alzheimer study below.

## Connections

- Applied to [[Alzheimer disease]] in European and African American samples with the BLISS model; it gave 37 associated genes including [[APOE]] and [[BCAM]], which fed the GREP drug-prioritisation step. Study: [[Penalized regression PWAS of Alzheimer disease in European and African American cohorts]]
- Input data: summary statistics from a [[Genome-wide association study]]
- Downstream use: [[Drug repurposing]]
