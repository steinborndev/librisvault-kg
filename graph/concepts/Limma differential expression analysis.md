---
type: concept
title: "Limma differential expression analysis"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001186
aliases: ["limma", "Linear Models for Microarray Data"]
tags: [microarray, transcriptomics]
---

# Limma differential expression analysis

Limma is an R package that fits linear models to microarray or other high-throughput expression data to call differentially expressed genes.

## Connections

- Used for male/female control, case/control and male-case versus female-case contrasts in three hippocampal GEO datasets, with an uncorrected p below 0.05 and the top 200 up and 200 down genes kept for Metascape enrichment. Study: [[Sex-specific hippocampal transcriptomes in Alzheimer disease from GEO datasets]]
- Related: [[Gene set enrichment analysis]], [[STRING protein interaction network analysis]]
- Applied to 97 Alzheimer and 98 control cortex microarrays (absolute log2 fold change above 1.2, adjusted P below 0.05) to find 2,149 genes, 25 of them in the synaptic vesicle cycle pathway. Study: [[Four synaptic vesicle cycle genes protective in Alzheimer disease by MR]]
- Used with a false discovery rate below 0.05 on five public brain microarray sets (including a prion disease cohort) to find genes raised in every set. Study: [[Multiomic analysis of Alzheimer brain finds five upregulated genes and antrocin]]
