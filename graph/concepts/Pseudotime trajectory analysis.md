---
type: concept
title: "Pseudotime trajectory analysis"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000788
aliases: ["pseudotime analysis", "Monocle3 trajectory analysis"]
tags: [single-cell, trajectory]
---

# Pseudotime trajectory analysis

Pseudotime analysis orders cells along an inferred path of gradual change in gene expression, so that a state transition can be read from a snapshot of many cells. In Monocle3, the dimensionality reduction and clustering from Seurat are passed in, and genes that change along the path are found by a spatial autocorrelation test (Moran's I) on the graph. The order is computational and needs independent confirmation of direction.

## Connections

- Used to order homeostatic and AD1 microglia subclusters in human cortex (0, 1, 5, 7, 9, 10), giving early, conversion, late and end gene groups; direction was supported by an inverse [[P2RY12]]-[[ITGAX]] relationship in tissue. Study: [[Amyloid-beta and tau-associated microglia profiles in Alzheimer brain snRNAseq]]
- Applied to nuclei from [[Single-nucleus RNA sequencing]]; states ordered: [[AD1 and AD2 microglia]]
- Used on cortical excitatory neurons (Alzheimer versus control) to place expression of four synaptic vesicle cycle genes along a branched path; the trajectory was computational only. Study: [[Four synaptic vesicle cycle genes protective in Alzheimer disease by MR]]
