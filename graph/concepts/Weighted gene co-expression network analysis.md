---
type: concept
title: "Weighted gene co-expression network analysis"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000272
aliases: ["WGCNA", "weighted gene correlation network analysis"]
tags: [transcriptomics, network-analysis]
---

# Weighted gene co-expression network analysis

WGCNA clusters genes whose expression correlates across samples into modules, summarises each module by an eigengene (the first principal component), and tests modules for enrichment, preservation across datasets and association with traits. Modules are built from a soft-thresholded correlation matrix, a topological overlap matrix and dynamic tree cutting.

## Connections

- Used on 14,456 brain and 11,379 blood coding genes from ROSMAP; four brain modules were preserved in blood (Zsummary > 5) and the light green module was enriched for Alzheimer-associated genes and had higher eigengene values in APOE ε4 carriers. Study: [[Blood and brain transcriptome of Alzheimer disease by APOE genotype]]
- Related method: [[Gene set enrichment analysis]]
- Applied to RNA-seq of xenografted human microglia: of the modules tested across APOE isoforms, only two were differential, both higher in APOE2 (proliferation and migration; immune response). Study: [[APOE isoforms shape transcriptome and chromatin of xenografted human microglia]]
- Run on 80 Alzheimer brain samples split by [[CDK5R1]] level: 30 modules, with antiquewhite4 (r = 0.69) and darkseagreen4 (r = -0.62) most correlated; their overlap with differentially expressed genes fed [[Consensus clustering]]. Study: [[CDK5R1-related subtypes and immune infiltrates in Alzheimer disease]]
- Run on 10,704 mouse brain genes (unsigned, power 8): 26 modules, 13 of them driven by Apoe, Clu, APOE ε4 or APP/PS1 strains, then compared with human modules in [[Mouse-human module comparison]]. Study: [[Late-onset Alzheimer risk gene mouse models mapped to human brain modules]]
