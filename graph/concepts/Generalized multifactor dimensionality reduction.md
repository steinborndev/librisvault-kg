---
type: concept
title: "Generalized multifactor dimensionality reduction"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000081
aliases: ["GMDR", "multifactor dimensionality reduction"]
tags: [gene-gene-interaction, statistics]
---

# Generalized multifactor dimensionality reduction

Generalized multifactor dimensionality reduction (GMDR) is a method for finding gene-gene interactions in case-control data. It folds the genotype combinations of a chosen set of loci into "high-risk" and "low-risk" groups, which reduces many dimensions to one, using scores from a generalized linear model. The best model for each number of loci is picked by the highest testing balanced accuracy and by cross-validation consistency, and its significance is checked by permutation.

Interaction models can be significant for loci that show no association on their own, which is why the method is used after single-SNP testing has missed most signals.

## Connections

- Applied to Alzheimer risk SNPs: [[TCF4 rs17594526]], [[APOE rs429358]], [[CLU rs1532278]]
- Disease studied: [[Late-onset Alzheimer disease]]
- Study: [[Late-onset Alzheimer disease association study in the Russian population]]
