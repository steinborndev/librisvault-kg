---
type: concept
title: "Disease probability from polygenic risk score"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000248
aliases: ["polygenic disease probability", "absolute risk from polygenic score"]
tags: [polygenic-risk-score]
---

# Disease probability from polygenic risk score

A way to express a [[Polygenic risk score]] as the absolute probability (0 to 1) that a person has or develops a disease, so that scores built from different variant sets and standardisations can be compared. The probability is a logistic function of the standardised score. Its two coefficients are derived in closed form from the disease prevalence and the mean and variance of the score in cases and non-cases, assuming normal distributions, so no individual-level genotypes are needed.

Two kinds of high-effect variant are kept out of the score. A rare, highly penetrant variant adds an intrinsic probability, estimated from its odds ratio, so the curve cannot fall below it. A common high-effect variant such as [[APOE]] changes the prevalence itself, so each genotype gets its own prevalence (derived from overall prevalence, allele frequency and odds ratio under Hardy-Weinberg equilibrium) and its own curve. Prevalence can also be stratified by age, which matters for [[Alzheimer disease]].

## Connections

- Worked through for Alzheimer disease, with the [[SORL1]] and [[TREM2]] rare variants and APOE genotype strata, in [[Probability of Alzheimer disease from polygenic score, APOE and rare variants]].
- Limits: tested only on simulated data; assumes independence of rare variants and the score.
