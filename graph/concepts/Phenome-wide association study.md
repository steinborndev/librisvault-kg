---
type: concept
title: "Phenome-wide association study"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000586
aliases: ["PheWAS"]
tags: [gwas-method]
---

# Phenome-wide association study

A PheWAS starts from one or a few variants and tests them against many traits, the reverse of a GWAS. A common implementation queries public summary statistics, such as the MRC IEU OpenGWAS database (19,649 traits as of May 2021), and lists the traits a variant is associated with at a chosen threshold.

## Connections

- Run on the lead CSF variants at [[APOE]], [[CR1]], [[BIN1]], [[GMNC]] and [[C16orf95]]: 529 associations at p < 1e-7, 490 of them for APOE ε4, and the rest clustering as ventricular volume, Alzheimer diagnosis and blood cell counts. Study: [[Genome-wide meta-analysis of CSF amyloid-beta 42 and phosphorylated tau]]
- Related: [[Genome-wide association study]], [[Colocalization analysis]]
- Run in the opposite direction, from 25 Alzheimer variants and the APOE ε2 SNP to 2008 blood analytes in the [[Arivale Scientific Wellness cohort]], with per-SNP FDR correction and a SNP x sex interaction test; 33 associations were significant. Study: [[Blood multiomic associations of Alzheimer disease risk variants in healthy adults]]
