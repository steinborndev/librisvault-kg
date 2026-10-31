---
type: concept
title: "Master regulator inference with ARACNe and metaVIPER"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-11
content_updated: 2026-10-11
address: c-000705
aliases: ["MARINa", "Master Regulator INference algorithm", "ARACNe-AP", "metaVIPER", "VIPER regulon activity", "differentially active regulators"]
tags: [single-cell, transcription-factor]
---

# Master regulator inference with ARACNe and metaVIPER

ARACNe-AP builds a regulon for each transcription factor, the factor plus the target genes whose expression shares mutual information with it (after pruning of indirect links by a data processing inequality and bootstrapping). VIPER, and its multi-network form metaVIPER, then scores how active each regulon is in each sample from the expression of its targets, so a factor's activity can be inferred even when its own RNA is barely measured. In single-nucleus data cells are first pooled into metacells to limit sparsity, and activity differences between disease and control are combined across clusters, for example with Stouffer's method. Links come from co-expression and so do not show direct binding; a separate transcription-factor enrichment check (ChEA3) can corroborate them. A related regulon approach is [[SCENIC regulon analysis]].

## Connections

- Used on Brodmann area 10 and 46 neurons and myeloid cells to call 20 differentially active regulators in [[Alzheimer disease]], among them [[ETV6]], [[ZEB2]], [[PAX6]] and [[ST18]]. Study: [[Lasmiditan prioritised for Alzheimer disease by regulator docking and dynamics]]
- Data type: [[Single-nucleus RNA sequencing]]
- The earlier ARACNe plus MARINa pairing built a 488,353-interaction neuronal interactome from laser-captured Alzheimer and control neurones and ranked candidate regulators of progression, including [[YY1]], [[EP300]] and [[ZMYM3]]. Study: [[Master regulators of Alzheimer progression from neuronal transcriptional networks]]
