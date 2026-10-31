---
type: concept
title: "Pedigree linkage and identity-by-descent analysis"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001029
aliases: ["parametric linkage analysis", "LOD score", "IBD segment analysis", "segregation analysis"]
tags: [familial-alzheimer, variant-interpretation]
---

# Pedigree linkage and identity-by-descent analysis

Ways to ask whether a rare variant found by [[Whole-exome sequencing]] in a family is the likely cause. Segregation tests whether carriers are affected and non-carriers are not. Parametric linkage (for example in Merlin) turns that into a LOD score under an assumed inheritance model, penetrance and disease prevalence. Identity-by-descent (IBD) detection (for example Beagle) finds chromosome segments that relatives inherited from a recent common ancestor, restricting candidate variants to shared segments.

## Connections

- In an Italian late-onset Alzheimer family, 8 of 16 filtered rare variants fell inside IBD segments, 5 on chromosome 17, and a single-point autosomal dominant model (penetrance 0.90, prevalence 1%) gave a LOD of 2.070 (p = 0.001) for [[GRIN2C p.A1072V]], below the conventional threshold of 3. Study: [[Exome sequencing finds GRIN2C p.A1072V in an Italian late-onset Alzheimer family]]
- Related: [[Case-only rare variant analysis]], [[Familial Alzheimer disease]]
- In a German late-onset Alzheimer family, Merlin linkage with a rare dominant model gave a maximal LOD of 1.20 for six sequenced members and 1.81 after Sanger genotyping of four more, pointing to [[ADAM17 p.R215I]]. Study: [[ADAM17 p.R215I loss-of-function variant in a late-onset Alzheimer family]]
