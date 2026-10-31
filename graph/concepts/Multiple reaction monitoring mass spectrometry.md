---
type: concept
title: "Multiple reaction monitoring mass spectrometry"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000371
aliases: ["MRM-MS", "MRM", "LC-MRM-MS", "selected reaction monitoring"]
tags: [blood-biomarker]
---

# Multiple reaction monitoring mass spectrometry

Multiple reaction monitoring (MRM) is a targeted mass spectrometry method in which a triple-quadrupole instrument is set to follow chosen peptide ions and their fragments, so that a fixed list of proteins is quantified by liquid chromatography coupled to the mass spectrometer. Spiking each digest with stable isotope-labelled synthetic peptide standards turns the signals into absolute concentrations through calibration curves.

Compared with antibody-based multiplex platforms such as Olink proximity extension assays and SomaScan aptamers, it quantifies hundreds rather than thousands of proteins but offers high specificity, strong reproducibility and no dependence on antibody reagents. It is commonly used to verify candidates found by those wider platforms, and in plasma it is applied to protein panels for [[Alzheimer disease]] and [[Mild cognitive impairment]].

## Example workflow

In a Moscow plasma study a commercial kit of labelled peptides for 125 plasma proteins was run on 10 microlitres of non-depleted plasma on a SCIEX QTRAP 6500+, with quantities calculated in Skyline. After log transformation, median imputation within diagnostic group and empirical-Bayes batch correction, 82 proteins passed quality, variability and detection-rate filters in both cohorts. Study: [[Plasma protein panel for Alzheimer disease risk by MRM mass spectrometry]]

## Connections

- Used to quantify the 13-protein panel including [[APOE]], [[APOA4]], [[ORM1]], [[LBP]], [[HP]], [[FN1]] and [[TF]]
