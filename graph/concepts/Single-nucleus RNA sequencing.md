---
type: concept
title: "Single-nucleus RNA sequencing"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000239
aliases: ["sn-RNA-Seq", "snRNA-seq", "single-nucleus transcriptomics"]
tags: [single-cell, cell-type-resolution]
---

# Single-nucleus RNA sequencing

Single-nucleus RNA sequencing reads the RNA of individual nuclei isolated from frozen tissue, which makes it usable on postmortem brain where intact cells cannot be recovered. A typical analysis filters nuclei by gene count and mitochondrial read fraction, normalises and corrects batch effects, reduces dimensions by principal component analysis and UMAP, clusters nuclei, and labels clusters from known marker genes. Cell-type proportions and cluster-specific differentially expressed genes can then be compared between disease and control brains.

Nuclei capture mainly nuclear transcripts, so cytoplasmic and immune-activation signals can be under-read, and cell-type calls such as macrophage versus microglia depend on the markers chosen.

## Connections

- Used on dorsolateral prefrontal cortex in [[Single-nucleus sequencing and Mendelian randomization of Alzheimer risk genes]] to find a macrophage expansion and 305 macrophage differentially expressed genes in [[Alzheimer disease]].
- The candidate list was passed to [[Mendelian randomization]] for a causal test.
- Related method for intact cells such as blood: [[Single-cell RNA sequencing]].
- Used to call unique-molecular-identifier-level allelic counts in prefrontal nuclei, where 3' read bias left most exonic SNPs unmeasured and few microglia were captured. Study: [[Allele-specific eQTLs of Alzheimer disease variants by brain region and cell type]]
- Used on prefrontal cortex of 81 donors across three cohorts (neuronal and myeloid nuclei) to infer transcription-factor activity with [[Master regulator inference with ARACNe and metaVIPER]]. Study: [[Lasmiditan prioritised for Alzheimer disease by regulator docking and dynamics]]
- Used on 482,472 neuron- and oligodendrocyte-depleted nuclei from occipital and occipitotemporal cortex of 10 Alzheimer and 8 control donors, giving about 9000 microglia per donor; see [[Nuclei depletion for microglia enrichment]] and [[Pseudotime trajectory analysis]]. Study: [[Amyloid-beta and tau-associated microglia profiles in Alzheimer brain snRNAseq]]
- Used on 76,839 nuclei from young and aged cynomolgus monkey entorhinal cortex (seven cell types, Harmony batch correction, Seurat clustering). Study: [[Single-nucleus atlas of aging monkey entorhinal cortex and Alzheimer disease]]
