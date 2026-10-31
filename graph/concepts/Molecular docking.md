---
type: concept
title: "Molecular docking"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000703
aliases: ["virtual screening", "protein-ligand docking", "AutoDock Vina docking"]
tags: [in-silico, drug-candidate]
---

# Molecular docking

Molecular docking predicts how a small molecule sits in a pocket of a protein structure and scores the fit as a binding energy in kcal/mol, where a more negative value means tighter predicted binding. Run over a library of approved drugs it becomes a virtual screen for [[Drug repurposing]]. A typical workflow adds hydrogens and charges, defines a grid box around a known or predicted pocket, runs a flexible-ligand search (here the Lamarckian genetic algorithm in AutoDock Vina), and then redocks top hits with a second engine to reduce single-scoring-function bias. Scores are crude estimates and are usually followed by [[Molecular dynamics simulation]].

## Connections

- Used to dock 2,200 DrugBank approved drugs onto 23 transcription regulators from Alzheimer prefrontal cortex, with a cut-off near -7 kcal/mol, redocking in DockThor and pocket druggability from DoGSiteScorer. Study: [[Lasmiditan prioritised for Alzheimer disease by regulator docking and dynamics]]
- Output feeds: [[Blood-brain barrier permeability prediction]]
- Used to dock [[Antrocin]] onto the products of five upregulated Alzheimer genes, with high predicted affinity for [[CAMK4]], [[TOMM70]] and [[TIPRL]]. Study: [[Multiomic analysis of Alzheimer brain finds five upregulated genes and antrocin]]
- Run with CB-Dock2 (AutoDock Vina engine) for [[6-Gingerol]] against 16 Alzheimer-linked proteins; the lowest energies were [[MMP2]] -8.7, [[ACHE]] -8.3, [[PTGS2]] -7.9 and [[CASP3]] -6.0 kcal/mol, with no reference inhibitor for comparison. Study: [[6-Gingerol from ginger screened for Alzheimer disease by docking and dynamics]]
- Used to dock the tripeptides [[EDR peptide]] and [[KED peptide]] onto all 2,080 unique hexanucleotide B-form dsDNA sequences with ICM-Pro (best ICM scores -44.7 and -26.6, minor groove), then to search 11 Alzheimer-related gene promoters for the best sequences; no experimental binding data. Study: [[EDR and KED tripeptides restore dendritic spines in 5xFAD mice]]
- AutoDock Vina 0.8 with a rigid receptor, exhaustiveness 8 and a 40 Å cubic grid gave -5.8 to -6.8 kcal/mol for [[Antrocin]] against the five signature proteins, with hydrogen-bond counts offered as the explanation for the ranking. Study: [[Multiomic analysis of Alzheimer brain finds five upregulated genes and antrocin]]
