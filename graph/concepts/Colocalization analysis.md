---
type: concept
title: "Colocalization analysis"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000585
aliases: ["genetic colocalization", "coloc"]
tags: [gwas-method]
---

# Colocalization analysis

Colocalization asks whether two association signals at one locus, for example a disease GWAS and an expression quantitative trait locus, are driven by the same causal variant rather than by two nearby ones. The coloc package returns posterior probabilities for each hypothesis; the single-causal-variant version (coloc.abf) can be relaxed to several variants with SuSiE, and a posterior probability above 0.8 for a shared variant is the usual bar.

## Connections

- Applied to CSF amyloid-beta 42 and phosphorylated tau loci against 63 brain and immune eQTL datasets and against Alzheimer and ventricular volume GWAS: [[CR1]] (0.97) and [[BIN1]] (0.84) matched Alzheimer risk signals and brain or lymphoblastoid eQTLs, [[C16orf95]] matched ventricular volume (0.93), and the [[NKPD1]] hit at [[APOE]] was judged a likely false positive. Study: [[Genome-wide meta-analysis of CSF amyloid-beta 42 and phosphorylated tau]]
- Related methods: [[Expression quantitative trait locus analysis]], [[Statistical fine-mapping]], [[Genome-wide association study]]
- Run with the coloc R package between genes in three early-onset Alzheimer disease and lipid covariance regions and 61 eQTL datasets; the maximum H4 per gene was a scoring input (ANKDD1B 0.82, CUZD1 0.84, MS4A6A 0.96). Study: [[Local genetic covariance of early-onset Alzheimer disease with lipid traits]]; see [[Composite gene prioritization score]].
