---
type: concept
title: "Dense module search of GWAS"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-000907
aliases: ["dmGWAS", "dense module search"]
tags: [gwas, network-analysis]
---

# Dense module search of GWAS

dmGWAS is a network-based tool that overlays genome-wide association signals on a protein interaction network and searches for dense modules of interacting genes whose combined signal is higher than expected, so that weak individual associations can add up. Other omics layers, such as [[DNA methylation]] scores, can be folded in as gene-level evidence.

## Connections

- Used to merge an Alzheimer GWAS with methylation data, giving 286 significant modules led by one with [[BIN1]] and [[GNAS]]. Study: [[Network-based integration of Alzheimer GWAS and DNA methylation finds BIN1 and GNAS module]]
- Module genes were followed by cell-type enrichment ([[Monocyte]]) and drug target enrichment for [[Drug repurposing]].
- Related network method: [[Weighted gene co-expression network analysis]]
