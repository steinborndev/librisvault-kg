---
type: concept
title: "Statistical fine-mapping"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000424
aliases: ["fine-mapping", "credible variant analysis", "CAVIAR"]
tags: [haplotype, gwas-method]
---

# Statistical fine-mapping

Fine-mapping narrows an associated genomic region to the variants most likely to be causal. Association statistics for each variant are combined with the pairwise linkage disequilibrium matrix, and a tool such as CAVIAR returns, for each variant, a posterior probability of being causal, so that a credible set can be listed instead of a single sentinel SNP.

## Connections

- Applied to the 200 kb APOE region in sequence data, it separated three causal signals (NECTIN2, APOE and APOC1 regions) rather than one; see [[Non-coding risk haplotypes at the APOE locus in Alzheimer disease]].
- Related methods: [[Haplotype association analysis]], [[Genome-wide association study]]
- Variants it prioritised: [[NECTIN2 rs11668861]], [[APOC1 rs56131196]], [[APOE rs429358]]
