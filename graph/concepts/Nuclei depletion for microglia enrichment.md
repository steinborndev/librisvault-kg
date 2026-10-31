---
type: concept
title: "Nuclei depletion for microglia enrichment"
domain: methods
status: seed
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-000789
aliases: ["NEUN and OLIG2 nuclei depletion", "FACS depletion of neuronal and oligodendrocyte nuclei"]
tags: [single-cell, cell-sorting]
---

# Nuclei depletion for microglia enrichment

Neurons and oligodendrocytes make up about 90% of nuclei isolated from frozen human cortex, which leaves few microglia in unsorted single-nucleus data. Staining nuclei for NEUN (RBFOX3) and OLIG2 and sorting the DAPI-positive, NEUN-negative, OLIG2-negative fraction removes them and enriches microglia, astrocytes and rarer types, at the price of low power to see changes in the depleted neurons and oligodendrocytes. Bulk RNAseq of the removed fractions can confirm that no microglial or astrocytic transcripts were lost with them.

## Connections

- Gave 482,472 nuclei and 148,606 microglia nuclei (about 9000 per donor) from 36 cortical samples; the removed fractions showed no consistent Alzheimer-associated change by bulk RNAseq. Study: [[Amyloid-beta and tau-associated microglia profiles in Alzheimer brain snRNAseq]]
- Applied before library preparation in [[Single-nucleus RNA sequencing]]; reveals [[AD1 and AD2 microglia]]
