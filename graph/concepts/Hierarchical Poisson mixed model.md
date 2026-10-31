---
type: concept
title: "Hierarchical Poisson mixed model"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000467
aliases: ["HPMM"]
tags: [allele-specific-expression, eqtl]
---

# Hierarchical Poisson mixed model

The hierarchical Poisson mixed model (HPMM) tests whether a variant is associated with allelic expression of a nearby gene. Counts of reads from the two alleles of a heterozygous person are modelled as a pair: the library size is halved for each allele and a person-level random effect captures individual noise, with a second random effect for overdispersion. Homozygous people contribute a single count each, so their genotype-level expression adds power when few people are double-heterozygous at the variant and the exonic marker SNP. The model can be fitted with the glmer function of the lme4 R package and accepts covariates and interaction terms such as diagnosis, age or sex. A version for single-nucleus data counts unique molecular identifiers instead of reads.

In simulations of 500 subjects the HPMM controlled type I error and beat the beta-binomial model, which matched the HPMM restricted to heterozygous people. Its caveat is shared by all SNP-level allele-specific analyses: in double-heterozygous people the two variants can look strongly correlated even when linkage disequilibrium in the whole sample is weak, especially at low minor allele frequency or small sample size, so a classification of each signal by linkage disequilibrium and by the exonic SNP's own association is needed before interpretation.

## Connections

- Developed and applied in [[Allele-specific eQTLs of Alzheimer disease variants by brain region and cell type]]
- Part of the wider family of [[Expression quantitative trait locus analysis]]
- Applied to cell-type data from [[Single-nucleus RNA sequencing]]
- Genes where it was decisive: [[ZNF232]], [[BIN1]]
