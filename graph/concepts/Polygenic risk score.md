---
type: concept
title: "Polygenic risk score"
domain: methods
status: developing
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000032
aliases: ["PRS", "genetic risk score", "AD-PRS"]
tags: [polygenic-risk-score]
---

# Polygenic risk score

A polygenic risk score (PRS) summarises an individual's inherited liability to a trait as a weighted count of risk-increasing alleles across many variants, with weights taken from the effect sizes (beta or log odds) of a genome-wide association study. Variants are first thinned by linkage-disequilibrium pruning and by a p-value inclusion threshold, so a score can include variants far below genome-wide significance.

In the ROSMAP study of Alzheimer risk and motor function, scores were built with PRSice-2 from two Alzheimer GWASs and one Parkinson disease GWAS, then centred and scaled; variants in the [[APOE]] and [[TOMM40]] region were removed or analysed alone to test whether the strongest single locus drove an association.

A score can also be restricted to the variants that reach genome-wide significance in a [[Genome-wide association study]], as in a 39-variant Alzheimer score validated in clinically and autopsy-diagnosed cases.

## Connections

- Used as the exposure in [[Alzheimer polygenic risk score and motor impairment in older adults]].
- Scores for [[Alzheimer disease]] and [[Parkinson disease]] were compared there.
- A 39-variant score of genome-wide significant Alzheimer variants outside APOE, weighted by earlier IGAP effect sizes, gave OR 1.27 per standard deviation and stratified age at onset within APOE ε4 carriers; see [[Meta-GWAS of Alzheimer disease finds six new loci and a polygenic risk score]]. Variants below genome-wide significance did not improve it there, in contrast with the threshold-sweeping scores of the motor study.
- Converted to an absolute probability by age group, APOE genotype and rare-variant carriage, using only prevalence and the score distribution in cases and controls; see [[Disease probability from polygenic risk score]]. The paper argues scores are not comparable between studies unless the case-control mean difference is also considered, and that high-effect variants are better modelled outside the score. Study: [[Probability of Alzheimer disease from polygenic score, APOE and rare variants]]
- An Alzheimer score built from FDR-filtered, LD-pruned summary statistics and excluding APOE was not associated with any of about 2000 blood analytes in 2831 healthy adults, with or without adjustment for ε4; the authors suggest summing effects dilutes single-gene signals and that the score may matter more in older, impaired people. Study: [[Blood multiomic associations of Alzheimer disease risk variants in healthy adults]]
