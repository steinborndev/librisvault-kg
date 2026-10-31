---
type: concept
title: "Local genetic covariance analysis"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001297
aliases: ["SUPERGNOVA", "local genetic correlation", "local genetic covariance"]
tags: [gwas-method]
---

# Local genetic covariance analysis

Local genetic covariance analysis estimates how much two traits share genetic signal within a defined stretch of the genome, rather than as one genome-wide correlation. SUPERGNOVA does this from GWAS summary statistics: it decorrelates local z-scores with the eigenvectors of the local linkage disequilibrium matrix and then fits a weighted least squares regression in each region. It can find shared regions that a genome-wide estimate such as LD score regression averages away, and it does not require overlapping samples.

## Connections

- Used to relate early-onset Alzheimer disease to five blood lipid traits over 2,353 approximately independent regions (LDetect partition, 1000 Genomes European LD), with a Bonferroni threshold of P < 2.12e-5 and a requirement of P < 5e-5 for each trait in the region. Study: [[Local genetic covariance of early-onset Alzheimer disease with lipid traits]]
- Follow-up of a covariance region: [[Composite gene prioritization score]]
- Input data: [[Genome-wide association study]] summary statistics
- Related method: [[Stratified LD score regression]]
