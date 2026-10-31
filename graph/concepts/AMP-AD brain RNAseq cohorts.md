---
type: concept
title: "AMP-AD brain RNAseq cohorts"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000669
aliases: ["Mayo Clinic brain RNAseq", "Mount Sinai Brain Bank RNAseq", "MSBB", "ROSMAP", "Religious Orders Study and Memory and Aging Project"]
tags: [transcriptomics, dementia]
---

# AMP-AD brain RNAseq cohorts

Three postmortem brain bulk RNAseq resources distributed through the AMP-AD Knowledge Portal: the Mayo Clinic cohort (temporal cortex and cerebellum), the Mount Sinai/JJ Peters VA Medical Center Brain Bank, MSBB (Brodmann areas 10, 22, 36 and 44), and the Religious Orders Study and Memory and Aging Project, ROSMAP (dorsolateral prefrontal cortex). Case and control status comes from neuropathology and clinical diagnosis fields in each cohort's metadata.

## Connections

- Reprocessed through one Kallisto pipeline with 153 to 423 subjects per region (Mayo temporal cortex 82 Alzheimer and 78 control; ROSMAP 222 and 201). Study: [[Differential transcript usage in Alzheimer disease brain RNAseq by lobe]]
- Methods used on them: [[Differential transcript usage analysis]], [[Gene set enrichment analysis]]
- Staging used in MSBB: [[Braak staging]]
- Disease: [[Alzheimer disease]]
- Harmonized counts from all three cohorts (632 DLPFC, 160 parahippocampal, 187 inferior frontal, 191 superior temporal, 262 temporal cortex and 261 cerebellum samples) trained six region signatures; external validation used GSE104687. Study: [[Predictive gene expression signatures of Alzheimer disease in six brain regions]]
- ROSMAP donors supplied the postmortem hippocampus and prefrontal cortex for sorted-nucleus H3K27ac ChIP-seq, with data deposited in the AD Knowledge Portal. Study: [[Cell-type H3K27ac profiling of Alzheimer hippocampus and prefrontal cortex]]
- Their 30 harmonized co-expression modules (ROSMAP, Mount Sinai, Mayo; seven regions) were the human reference for mouse risk-gene perturbations; see [[AMP-AD consensus clusters]]. Study: [[Late-onset Alzheimer risk gene mouse models mapped to human brain modules]]
