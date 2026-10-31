---
type: concept
title: "ATAC-seq"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000335
aliases: ["assay for transposase-accessible chromatin using sequencing", "chromatin accessibility profiling"]
tags: [epigenomics, transcriptomics]
---

# ATAC-seq

ATAC-seq maps open chromatin by letting a hyperactive Tn5 transposase cut and tag accessible DNA, then sequencing the tagged fragments. Peaks mark candidate promoters and enhancers, and the peak sets can be tested for differential accessibility between groups, for transcription factor motif enrichment, and for enrichment of disease heritability.

## Workflow in the xenografted microglia study

- 100,000 FACS-sorted cells per sample were lysed and tagmented immediately, amplified for 10 cycles, size-selected at 175 to 225 bp and sequenced paired-end on a HiSeq 4000.
- Reads were aligned to GRCh38 with bowtie2, filtered for mitochondrial, duplicate, multi-mapping and low-quality reads, and counted with featureCounts, leaving 167,951 peaks. Differential accessibility used DESeq2, motif analysis used HOMER, and heritability enrichment used stratified LD score regression.

## Connections

- Paired with RNA-seq to show concordant promoter accessibility and expression changes across APOE isoforms; study: [[APOE isoforms shape transcriptome and chromatin of xenografted human microglia]]
- Model: [[Human microglia xenotransplantation model]]
- Heritability enrichment tests build on [[Genome-wide association study]] summary statistics
