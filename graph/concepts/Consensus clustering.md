---
type: concept
title: "Consensus clustering"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-001055
aliases: ["ConsensusClusterPlus", "consensus cluster analysis"]
tags: [transcriptomics, network-analysis]
---

# Consensus clustering

Consensus clustering repeats a clustering algorithm (here k-means) on random subsamples of the samples, records how often each pair lands together, and picks the number of clusters from the cumulative distribution function curve and the delta area plot of that consensus matrix. It is used to define molecular subtypes from expression data.

## Connections

- Two clusters (C1, n = 39; C2, n = 41) were chosen for 80 Alzheimer brain samples using 266 CDK5R1-related genes. Study: [[CDK5R1-related subtypes and immune infiltrates in Alzheimer disease]]
- Gene input came from [[Weighted gene co-expression network analysis]]
