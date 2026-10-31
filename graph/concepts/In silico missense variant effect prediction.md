---
type: concept
title: "In silico missense variant effect prediction"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000729
aliases: ["PolyPhen-2", "SIFT", "PROVEAN", "missense pathogenicity prediction"]
tags: [in-silico]
---

# In silico missense variant effect prediction

Tools such as PolyPhen-2, SIFT and PROVEAN score how likely an amino-acid substitution is to damage a protein, from conservation and structure. They flag candidates but do not prove pathogenicity, and often disagree.

## Connections

- Applied to every missense variant in the Thai panel study; PolyPhen-2 and SIFT called [[CSF1R p.L536V]] damaging and [[CSF1R p.P54Q]] benign. Study: [[Fifty-gene neurodegeneration panel in eight Thai early-onset Alzheimer patients]]
- PolyPhen-2 and SIFT disagreed on [[APP p.V551M]] in another study: [[Double APP and PSEN2 mutations in a Korean patient with early-onset Alzheimer disease]]
- For the novel [[PSEN2 p.V226A]] the tools gave weak or mixed calls (PolyPhen-2 0.34, CADD 17.8, FATHMM damaging, M-CAP possibly pathogenic), and AlphaFold2 models of eleven helix variants were compared by hand. Study: [[Novel PSEN2 p.V226A in a Korean patient with atypical Alzheimer disease]]
