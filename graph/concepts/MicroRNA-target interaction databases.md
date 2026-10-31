---
type: concept
title: "MicroRNA-target interaction databases"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000180
aliases: ["miRTarBase", "HMDD", "Human microRNA Disease Database", "miRNA-target interaction enrichment", "MTI"]
tags: [microrna, database-mining]
---

# MicroRNA-target interaction databases

Two public resources are commonly combined to prioritise microRNAs (miRNAs) as disease markers. miRTarBase lists experimentally validated miRNA-target gene interactions (MTI), each tagged with the method that confirmed it (for example reporter assay, RT-qPCR, Western blot or PAR-CLIP crosslinking). The Human microRNA Disease Database (HMDD) annotates which miRNAs are associated with a given disease phenotype. More than 380,000 validated human MTI have been reported.

Two ways of combining them were used for [[Alzheimer disease]]: join a list of disease-linked genes to a list of candidate miRNAs and keep the interactions miRTarBase supports, or join all disease-annotated miRNAs from HMDD to every target in miRTarBase. The first route gave 215 interactions and the second 942, with only four in common. Candidates were then graded by the sample type in which the original paper observed them: patient samples, disease models, non-disease models, or prediction only.

A limitation is that a database interaction may have been confirmed in an unrelated tissue; for example two of the shared interactions were validated in a gastric carcinoma sample.

## Connections

- Applied in: [[Circulating microRNA biomarkers for Alzheimer disease by database mining]]
- Subject: miRNAs such as [[MIR375]], [[MIR107]] and [[MIR34A]]
- Related carrier of miRNAs in body fluids: [[Extracellular vesicle]]
