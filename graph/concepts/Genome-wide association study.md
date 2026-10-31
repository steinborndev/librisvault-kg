---
type: concept
title: "Genome-wide association study"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000165
aliases: ["GWAS", "genome-wide meta-analysis", "meta-GWAS"]
tags: [gwas]
---

# Genome-wide association study

A genome-wide association study tests millions of common variants for association with a trait, usually by logistic regression in cases and controls adjusted for ancestry components, and calls a locus significant at p < 5 x 10^-8. Several studies can be pooled by fixed-effects inverse-variance-weighted meta-analysis of their summary statistics, and a by-proxy design stands in for direct diagnosis by using the disease status of a participant's parents. Hits are then replicated in independent cohorts, thinned by linkage-disequilibrium clumping to one lead variant per region, and annotated with expression and chromatin data to guess the causal gene.

In [[Alzheimer disease]], successive meta-analyses have grown from tens of thousands to nearly half a million participants; the effect sizes of the variants they find supply the weights of a [[Polygenic risk score]].

## Connections

- Used to find the loci in [[Meta-GWAS of Alzheimer disease finds six new loci and a polygenic risk score]]: [[APP rs2154481]], [[SHARPIN p.S17F]], [[SHARPIN p.P294S]], [[PRKD3 rs876461]], [[CHRNE rs72835061]], [[PLCG2 rs3935877]].
- The Alzheimer scores in [[Alzheimer polygenic risk score and motor impairment in older adults]] were built from GWAS summary statistics.
- A candidate-SNP counterpart in a smaller cohort: [[SNP association study of Alzheimer disease in southern Chinese population]].
- Its summary statistics supply the outcome in [[Mendelian randomization]], as in [[Single-nucleus sequencing and Mendelian randomization of Alzheimer risk genes]].
- Alzheimer GWAS summary statistics were used for MAGMA gene set analysis (genes lowered in APOE4 and APOE-knockout microglia were enriched in one of three GWAS) and for stratified LD score regression (open chromatin of xenografted microglia was enriched for Alzheimer but not ALS or autism heritability). Study: [[APOE isoforms shape transcriptome and chromatin of xenografted human microglia]]
- Follow-up of 33 Alzheimer GWAS SNPs on allelic expression by region, exon and cell type: [[Allele-specific eQTLs of Alzheimer disease variants by brain region and cell type]]
- An endophenotype design: GWAS of CSF amyloid-beta 42 and phosphorylated tau as quantitative traits (13,116 people, three stages, METAL meta-analysis) with colocalization and phenome-wide follow-up, giving higher heritability than the clinical diagnosis. Study: [[Genome-wide meta-analysis of CSF amyloid-beta 42 and phosphorylated tau]]; see [[Colocalization analysis]] and [[Phenome-wide association study]].

- GWAS summary statistics for Alzheimer disease in European and African American samples were the input to a proteome-wide association study; see [[Proteome-wide association study]].
- Summary statistics of the early-onset Alzheimer disease GWAS (6,282 cases, 13,386 controls) and a five-trait lipid GWAS (n = 1,320,016) were compared locus by locus and by [[Local genetic covariance analysis]]. Study: [[Local genetic covariance of early-onset Alzheimer disease with lipid traits]]
