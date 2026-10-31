---
type: concept
title: "CIBERSORT immune cell deconvolution"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-001054
aliases: ["CIBERSORT", "Cell-type Identification by Estimating Relative Subsets of RNA Transcripts", "immune cell infiltration estimation"]
tags: [transcriptomics, neuroinflammation]
---

# CIBERSORT immune cell deconvolution

CIBERSORT estimates the relative fractions of 22 immune cell types in a bulk expression profile by fitting it against a reference signature matrix of cell-type marker genes. The fractions are estimates of composition, not counts of cells, and depend on how well the reference matches the tissue.

## Connections

- Applied to bulk brain microarray data to compare two Alzheimer subtypes: plasma cells, follicular helper T cells and activated NK cells were higher in one, [[Monocyte]], M2 macrophage, gamma delta T and activated dendritic cell fractions in the other. Study: [[CDK5R1-related subtypes and immune infiltrates in Alzheimer disease]]
- Related methods: [[Gene set variation analysis]], [[Gene set enrichment analysis]]
