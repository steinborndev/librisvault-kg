---
type: concept
title: "Expression quantitative trait locus analysis"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000427
aliases: ["eQTL analysis", "genotype-expression association", "allele-specific expression", "allelic imbalance"]
tags: [eqtl, gene-expression]
---

# Expression quantitative trait locus analysis

An expression quantitative trait locus (eQTL) analysis tests whether the genotype or haplotype of a variant tracks the transcript level of a nearby (cis) or distant gene, usually in resources such as GTEx, CommonMind and the blood-based eQTLGen consortium. Allele-specific expression complements it within a single person: in a heterozygote, an unequal share of reads from the two alleles (allelic imbalance, tested against 0.5) shows that the variant itself acts in cis, and can be verified by droplet digital PCR.

## Connections

- Showed that NECTIN2 and APOC1 risk haplotypes lower blood NECTIN2 and raise brain APOE transcript, and that the ε4 variant lowers APOE transcript in brain; see [[Non-coding risk haplotypes at the APOE locus in Alzheimer disease]].
- Related: [[Mendelian randomization]], which draws on eQTL data, and [[Single-nucleus RNA sequencing]], which resolves expression by cell type.
- Variants: [[NECTIN2 rs6859]], [[NECTIN2 rs60389450]], [[APOE rs429358]]
- Related methods: [[Haplotype association analysis]], [[Hi-C chromatin interaction analysis]]
- Allele-specific QTL analysis of 33 Alzheimer GWAS SNPs by region and cell type, with the [[Hierarchical Poisson mixed model]], showed that linkage in double-heterozygous people can create false signals and that exon-level effects can differ in sign; see [[Allele-specific eQTLs of Alzheimer disease variants by brain region and cell type]].
- Brain and immune eQTL datasets (63 tested) were used for colocalization with CSF amyloid-beta 42 and phosphorylated tau loci, supporting CR1 in six brain regions and BIN1 in lymphoblastoid cell lines. Study: [[Genome-wide meta-analysis of CSF amyloid-beta 42 and phosphorylated tau]]; see [[Colocalization analysis]].
- MetaBrain cis-eQTLs (cortex n = 2,683; hippocampus n = 208, European ancestry) supplied one evidence line for ranking genes in three early-onset Alzheimer disease and lipid covariance regions, e.g. ANKDD1B cortex P = 3.18e-110. Study: [[Local genetic covariance of early-onset Alzheimer disease with lipid traits]]; see [[Composite gene prioritization score]].
- Control-cortex array eQTLs for three BACE2 probes were modified by APOE status, with [[BACE2 rs2012050]] linking lower expression to higher CSF Aβ1-42 in ε4 non-carriers. Study: [[Common BACE2 polymorphisms and CSF amyloid in APOE ε4 non-carriers]]
