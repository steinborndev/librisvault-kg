---
type: concept
title: "Promoter mapping and transcription factor binding assays"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-11
content_updated: 2026-10-11
address: c-000116
aliases: ["Promoter deletion luciferase assay", "DNA pull-down and EMSA"]
tags: [transcription-factor]
---

# Promoter mapping and transcription factor binding assays

A workflow for finding which stretch of a gene's upstream DNA drives expression and which protein binds it. Progressively shorter 5' fragments of the promoter are cloned in front of firefly luciferase and compared with a co-transfected Renilla control; the step where activity jumps or collapses brackets the active element. Biotinylated fragments on streptavidin beads then pull proteins from nuclear extract for mass spectrometry, candidates are cross-checked with a prediction tool (PROMO), and the gel-shift assay (EMSA) with wild-type and mutant competitor probes tests binding to a single predicted site. Mutating that site in the reporter and knocking down the factor with shRNA test function.

Limits seen in use: shorter inserts can outperform the empty vector backbone for reasons unrelated to the promoter, and in vitro binding does not prove occupancy on native chromatin.

## Connections

- Applied to the [[TREM2]] promoter, where it located a core region at -370 to -118 and the [[YY1]] site. Study: [[TREM2 regulation by YY1 in microglia and Alzheimer disease models]]
- Cell systems: [[BV2]], [[Neuro2a]], [[HEK293]]
- The same question for the [[BACE1]] promoter: [[YY1]] binds a putative site and raises promoter activity in rat cells (abstract only, assay details not given). Study: [[YY1 activates the BACE1 promoter in rat cells and reactive astrocytes]]
