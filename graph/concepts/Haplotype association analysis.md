---
type: concept
title: "Haplotype association analysis"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000425
aliases: ["haplotype-based association", "haplotype phasing and testing"]
tags: [haplotype, gwas-method]
---

# Haplotype association analysis

Instead of testing one variant at a time, phased alleles along a haplotype block are treated as a unit. Each person receives a 0, 1 or 2 count of every common haplotype, the most frequent one is dropped as reference, and a multivariate regression estimates each minor haplotype against it, optionally adjusting for other loci such as APOE genotype. Cohort results are then pooled by random-effects meta-analysis. The method depends on accurate phasing, which can be checked against array data or long-read sequencing.

## Connections

- Used to show that NECTIN2 and APOC1 haplotypes, and long-range haplotypes spanning NECTIN2, APOE and APOC1, raise [[Alzheimer disease]] risk independently of APOE ε4 and ε2; see [[Non-coding risk haplotypes at the APOE locus in Alzheimer disease]].
- Related methods: [[Statistical fine-mapping]], [[Expression quantitative trait locus analysis]]
- Genes: [[NECTIN2]], [[APOC1]], [[APOE]]
