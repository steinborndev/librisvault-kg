---
type: concept
title: "Gene2Drug"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000613
aliases: ["gep2pep", "PathSEA"]
tags: [transcriptomics, drug-candidate]
---

# Gene2Drug

An online tool (with the R package gep2pep) that converts each drug's gene-expression profile in the Connectivity Map into a pathway-expression profile by gene set enrichment, then runs pathway set enrichment (PathSEA) to rank drugs by how strongly they up- or down-regulate the pathways containing an input gene. A drug can be chosen by acting on the gene directly or by shifting its pathway neighbourhood, so unrelated compounds that move the pathways are also picked up. Scores run from -1 to 1 and p-values are Benjamini-Hochberg adjusted.

## Connections

- Run on 255 GWAS risk genes and 717 cell-type differentially expressed genes for [[Alzheimer disease]], over eight pathway databases and five cell lines treated with 1,309 compounds. Study: [[Gene2Drug repurposing candidates for Alzheimer disease risk genes]]
- Builds on [[Gene set enrichment analysis]]; general strategy in [[Drug repurposing]]
