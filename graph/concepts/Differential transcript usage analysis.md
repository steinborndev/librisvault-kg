---
type: concept
title: "Differential transcript usage analysis"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000667
aliases: ["DTU analysis", "isoform switch analysis", "IsoformSwitchAnalyzeR"]
tags: [transcriptomics, alternative-splicing]
---

# Differential transcript usage analysis

Differential transcript usage (DTU) analysis asks whether the share of a gene's total expression carried by each of its isoforms differs between groups, so it can flag a gene whose total expression is unchanged but whose dominant isoform has switched. A gene with significant usage change is called a gDTU, and the effect size is the differential isoform fraction (dIF). A typical pipeline pseudo-aligns reads to the transcriptome with Kallisto, tests usage with DRIMSeq, confirms isoforms with stageR, and predicts consequences (coding potential, domains, signal peptides, disordered regions, nonsense-mediated decay sensitivity) with IsoformSwitchAnalyzeR and external tools. Classical gene-level differential expression tools such as DESeq2 and edgeR are blind to such switches.

## Connections

- Applied to five postmortem brain RNAseq datasets with thresholds dIF above 0.05 and overall false discovery rate below 0.01 (FDR below 0.05 for the gene-level call); it found 2509 and 1843 gDTUs in the Mayo and Mount Sinai temporal lobe datasets, and only 34 of 435 shared temporal gDTUs were also differentially expressed. Study: [[Differential transcript usage in Alzheimer disease brain RNAseq by lobe]]
- Cohorts: [[AMP-AD brain RNAseq cohorts]]
- Complements gene-level [[Gene set enrichment analysis]] and cell-type assignment from [[Single-cell RNA sequencing]]
- Biology it reveals: [[Alternative splicing]]
