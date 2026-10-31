---
type: concept
title: "Domain mapping of disease mutations"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000202
aliases: ["DMDM", "domain-mapping of disease mutations"]
tags: [variant-interpretation, rare-variant-burden]
---

# Domain mapping of disease mutations

Domain mapping of disease mutations (DMDM) is a way to rank rare missense variants by transferring pathogenicity from homologous residues. A protein is split into its structured domains, the repeats of each domain are aligned to reveal strictly and moderately conserved residues, and a variant that hits such a residue is prioritised if the same position in a homologous protein carries disease-causing variants.

For [[SORL1]], the borrowed knowledge came from the low-density-lipoprotein receptor family (variants in the CR-like and YWTD-EGF domains cause familial hypercholesterolemia) and from fibronectin-like proteins (holoprosencephaly). Variants were sorted into high-, moderate-, low- and no-priority classes; the high-priority class was chosen independent of REVEL score, with a REVEL cut-off above 0.5 only in the VPS10p domain, which has no well-characterised homologues. In the SORL1 study the 107 high-priority variants carried a larger aggregate risk (6.1-fold) than variants flagged only by REVEL or AlphaMissense above 0.9 (3.9-fold and 3.5-fold).

## Connections

- Applied to [[SORL1]] in [[Domain mapping of SORL1 missense variants in Alzheimer disease]].
- Output feeds burden testing of rare variants in [[Alzheimer disease]], including [[Early-onset Alzheimer disease]] and [[Late-onset Alzheimer disease]].
- Residue 146 of PSEN1 lies in a conserved hydrophobic putative transmembrane helix, and hydrophobic-to-hydrophobic replacements there ([[PSEN1 p.M146I]]) are read as pathogenic. Study: [[Familial Alzheimer disease mutations in Han Chinese in Taiwan]]
- Contrasting approach for presenilin variants: nine PSEN2 changes, eight of them in transmembrane regions (the authors call these a mutation hotspot), were classed by ACMG criteria and tested in cells instead. Study: [[PSEN2 mutation spectrum and functionally validated variants in a Chinese Alzheimer cohort]]; see [[ACMG variant classification]]
- Eleven missense changes in the fifth transmembrane helix of [[PSEN2]] were placed on AlphaFold2 models; see [[Presenilin transmembrane domain 5]]. Study: [[Novel PSEN2 p.V226A in a Korean patient with atypical Alzheimer disease]]
- Related region-level stratification of PSEN1 variants into transmembrane and cytoplasmic classes: [[PSEN1 transmembrane and cytoplasmic domain grouping]]. Study: [[PSEN1 transmembrane versus cytoplasmic variants and progression in DIAN]]
