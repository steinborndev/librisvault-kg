---
type: concept
title: "STRING protein interaction network analysis"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001187
aliases: ["STRING network", "protein-protein interaction network reconstruction", "Cytoscape STRING app"]
tags: [network-analysis]
---

# STRING protein interaction network analysis

Building a protein-protein interaction network from a gene list with the STRING database (here through Cytoscape) and reading off the first neighbours of genes of interest, with a confidence cutoff such as 0.7 to keep high-confidence links.

## Connections

- Applied to 518 of 766 DisGeNET Alzheimer susceptibility genes (1119 edges at confidence 0.7) to find neighbours of [[ESR1]], [[ESR2]] and [[GPER1]]. Study: [[Sex-specific hippocampal transcriptomes in Alzheimer disease from GEO datasets]]
- Related: [[Weighted gene co-expression network analysis]], [[Limma differential expression analysis]]
- Applied to 25 differentially expressed synaptic vesicle cycle genes at confidence 0.4, giving 87 pairs with SNAP25, NSF, STXBP1, VAMP2 and CLTB as the best connected. Study: [[Four synaptic vesicle cycle genes protective in Alzheimer disease by MR]]
- Applied to 34 targets shared by at least 5 of 7 herbs and Alzheimer disease, with node degree from Cytoscape NetworkAnalyzer ([[IL6]] 29, [[CASP3]] 26, [[VEGFA]] 24). Study: [[Network pharmacology of seven heat-clearing herbs for Alzheimer disease]]
