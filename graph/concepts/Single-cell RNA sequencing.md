---
type: concept
title: "Single-cell RNA sequencing"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000287
aliases: ["scRNA-seq", "single-cell transcriptomics"]
tags: [single-cell, cell-type-resolution]
---

# Single-cell RNA sequencing

Single-cell RNA sequencing reads the transcripts of thousands of individual intact cells, so that cell types, their proportions and their expression can be compared between groups. A common workflow filters cells by gene count and mitochondrial fraction, normalises, reduces dimensions (PCA, UMAP, t-SNE), clusters cells and annotates clusters with reference tools (SingleR) and marker genes. Downstream steps include ligand-receptor communication scoring (CellPhoneDB, CellChat), regulon inference ([[SCENIC regulon analysis]]) and pseudotime ordering (Monocle2). Blood and other fluid samples suit it because cells are already free, unlike brain tissue, which usually needs the nucleus-only variant [[Single-nucleus RNA sequencing]].

## Connections

- Applied to 36,849 peripheral blood nucleated cells from three Alzheimer patients and two controls to follow monocyte signalling and transcription factors. Study: [[Exercise-regulated monocyte transcription network in Alzheimer disease]]
- Related method: [[Single-nucleus RNA sequencing]]
- Middle temporal gyrus single-cell signatures (seven cell types) were used to assign bulk RNAseq changes indirectly to cell types. Study: [[Differential transcript usage in Alzheimer disease brain RNAseq by lobe]]
- Human snRNA-seq (GSE157827; 4 Alzheimer cases, 4 controls, 44,132 cells) and in-house [[Danio rerio]] data from Aβ42-injected animals were scored for differential expression as one evidence line in [[Composite gene prioritization score]]; MS4A6A was differentially expressed in human cells (P = 3.74e-20). Study: [[Local genetic covariance of early-onset Alzheimer disease with lipid traits]]
- GSE157827 (173,281 cells, 22 clusters, seven cell types) was used to localise four synaptic vesicle cycle genes: [[NSF]] and [[CLTB]] mainly in neurons, [[ATP6V1D]] broadly, with cell-cell communication scored by CellChat. Study: [[Four synaptic vesicle cycle genes protective in Alzheimer disease by MR]]
