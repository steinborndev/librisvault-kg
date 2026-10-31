---
type: concept
title: "Bayesian hierarchical model of cognitive decline trajectories"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001429
aliases: ["four-parameter logistic trajectory model", "data-driven trajectory analysis of cognitive decline"]
tags: [trajectory, statistics]
---

# Bayesian hierarchical model of cognitive decline trajectories

A longitudinal model that fits each person's repeated Mini-Mental State Examination scores with a four-parameter logistic curve: the plateau scores at young (A) and old (B) ages, the age at the midpoint of decline (M) and the rate of decline (R). Subject-level random effects on A and B absorb between-person variation, while covariates such as sex, education and the number of minor alleles (additive coding) enter linear terms on M and R. This separates the age at which decline happens from how fast it proceeds, two things a single slope blurs.

Fitting uses Gibbs sampling in WinBUGS (2,000 burn-in and 20,000 iterations in the Taiwanese study), significance is read from 95% credible intervals, Gibbs variable selection picks the best subset of markers by posterior model probability, and a posterior predictive p-value checks fit.

## Connections

- Used to test eight genetic markers in 299 Han Chinese Alzheimer and MCI patients and 385 [[Alzheimer's Disease Neuroimaging Initiative]] participants. Study: [[Genetic effects on cognitive decline trajectories in Han Chinese in Taiwan]]
- Outcome measured: [[Cognitive impairment]] in [[Alzheimer disease]] and [[Mild cognitive impairment]]
- Related longitudinal approach in expression space: [[Pseudotime trajectory analysis]]
