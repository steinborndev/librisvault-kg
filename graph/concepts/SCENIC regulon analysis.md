---
type: concept
title: "SCENIC regulon analysis"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000288
aliases: ["SCENIC", "single-cell regulatory network inference and clustering", "regulon activity score"]
tags: [single-cell, transcription-factor]
---

# SCENIC regulon analysis

SCENIC infers transcription factor regulons (a factor plus its co-expressed target genes) from single-cell expression data and scores each cell for regulon activity. Regulon specificity scores rank factors by how specific their activity is to a cell type, and entropy-based clustering can group factors into modules. Because links come from co-expression, the approach recovers positively associated regulator-target pairs only and does not show direct binding or causation.

## Connections

- Used on blood monocytes to rank the top ten regulators per monocyte type, define modules M1 to M9 and link ATF3, KLF4, HES4 and MAFB to TNF, CCR1 and APP. Study: [[Exercise-regulated monocyte transcription network in Alzheimer disease]]
- Related method: [[Single-cell RNA sequencing]]
- Used on aged monkey entorhinal cortex to find [[FOXN3]] as the main microglial regulator of age-related change and six neuronal hub regulators. Study: [[Single-nucleus atlas of aging monkey entorhinal cortex and Alzheimer disease]]
