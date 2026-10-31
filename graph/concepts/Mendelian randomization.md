---
type: concept
title: "Mendelian randomization"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000238
aliases: ["MR", "Mendelian randomisation"]
tags: [causal-inference, eqtl]
---

# Mendelian randomization

Mendelian randomization uses inherited genetic variants as instrumental variables to test whether an exposure, such as the expression level of a gene, causally changes a disease outcome. Because alleles are assigned at conception, the design is less open to confounding and reverse causation than an observational association. The variants must be associated with the exposure, independent of confounders, and act on the outcome only through the exposure.

In a gene-expression version, cis expression quantitative trait loci (eQTLs) near a gene serve as instruments, thinned by linkage-disequilibrium clumping, and their effects on expression are set against their effects on disease in a [[Genome-wide association study]]. The main estimator is inverse variance weighting, which is most powerful but fails under directional pleiotropy. The weighted median stays consistent when over half the weight comes from valid instruments, and MR-Egger reads pleiotropy from its intercept at a cost in power. A leave-one-out analysis drops each variant in turn to see whether one drives the estimate.

## Connections

- Applied to 305 macrophage genes against an Alzheimer outcome in [[Single-nucleus sequencing and Mendelian randomization of Alzheimer risk genes]], giving [[CACNA2D3]], [[INPP5D]], [[RBM47]], [[TBXAS1]], [[EPB41L2]], [[MYO1F]] and [[SSH2]].
- Candidate genes are chosen upstream by [[Single-nucleus RNA sequencing]].
- Disease context: [[Alzheimer disease]]
- Applied to 15 differentially expressed synaptic vesicle cycle genes with an FinnGen-derived Alzheimer outcome (3,899 cases), giving four protective genes whose direction matched their lower expression in brain; here MR served as a filter after differential expression. Study: [[Four synaptic vesicle cycle genes protective in Alzheimer disease by MR]]
