---
type: concept
title: "Case-only rare variant analysis"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000524
aliases: ["cases-only variant filtering"]
tags: [rare-variant-burden, variant-interpretation]
---

# Case-only rare variant analysis

A way to prioritise very rare variants by listing those that occur repeatedly in cases and never in controls, filtered for predicted functional impact. Standard association tests cannot score such variants because the control cell is empty, however many cases carry them; the cost is that significance cannot be shown and every hit needs replication.

## Connections

- Applied to exomes of 5,617 cases and 4,594 controls to nominate [[NOTCH3 p.A284T]], [[TREM2 p.Q33X]] and haplotypes in [[ABCD4]], [[CELSR1]] and [[GTSE1]]; supported by haplotype and identity-by-descent checks for common ancestry ([[Haplotype association analysis]]). Study: [[Case-only rare variant search in Alzheimer Disease Sequencing Project exomes]]
- Complemented by gene-set burden tests with Combined and Multivariate Collapsing.
- Related: [[Whole-exome sequencing]], [[Domain mapping of disease mutations]]
