---
type: concept
title: "Immune infiltration analysis"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001468
aliases: ["ssGSEA immune cell scoring", "immune cell infiltration scoring", "single-sample GSEA immune profiling"]
tags: [transcriptomics, neuroinflammation]
---

# Immune infiltration analysis

Immune infiltration analysis estimates how much of each immune cell type a bulk expression profile contains. In the single-sample gene set enrichment version (ssGSEA, from the GSVA package) each sample gets an activity score per immune cell type from the ranked expression of that type's marker genes (28 types in a common panel), and groups are then compared with a rank test and the scores correlated with genes of interest. The scores are relative enrichment estimates, not cell counts, and depend on how well the marker sets fit the tissue. A deconvolution alternative is [[CIBERSORT immune cell deconvolution]].

## Connections

- Applied to 195 cortex samples (97 Alzheimer, 98 control): 19 of 28 types differed, 17 higher in Alzheimer (activated and central memory CD8 T cells among them) and two lower (effector memory CD4 T cells, eosinophils); four synaptic vesicle cycle genes correlated negatively with the raised types. Study: [[Four synaptic vesicle cycle genes protective in Alzheimer disease by MR]]
- Related method: [[Gene set enrichment analysis]]
- Disease context: [[Neuroinflammation]], [[Alzheimer disease]]
