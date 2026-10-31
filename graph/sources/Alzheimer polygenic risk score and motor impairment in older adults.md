---
type: source
title: "Alzheimer polygenic risk score and motor impairment in older adults"
paper_title: "Genetic risk for Alzheimer’s dementia predicts motor deficits through multi-omic systems in older adults"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000033
pmid: "31582723"
pmcid: "PMC6776503"
doi: "10.1038/s41398-019-0577-4"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC6776503/"
sources: ["[[.raw/01M4DY94CTM176X9F6KVBMFV6S/normalized.md]]"]
tags: [polygenic-risk-score, multi-omics, motor-function, alzheimer-risk-locus]
---

# Alzheimer polygenic risk score and motor impairment in older adults

A study of 1885 older adults from the Religious Orders Study and the Rush Memory and Aging Project (ROSMAP) that asks whether the common-variant genetic risk of [[Alzheimer disease]] also predicts late-life [[Motor impairment]], and which brain molecular layers carry that link.

## Design

- Participants: 1885 genotyped older adults with motor testing (99.4% non-Latino white), all brain donors with annual clinical evaluation. Alzheimer dementia was diagnosed by NINCDS/ADRDA criteria.
- Genetic exposure: an Alzheimer [[Polygenic risk score]] (AD-PRS) built from two genome-wide association studies, the International Genomics of Alzheimer's Project (25,580 cases, 48,466 controls) and a family-history GWAS that adds UK Biobank (CCACE), after removing the signal contributed by ROSMAP participants. After linkage-disequilibrium pruning these gave 1215 and 1197 independent SNPs. A Parkinson disease PRS (399 SNPs) served as a contrast, and variants of the [[APOE]] and [[TOMM40]] region were removed or tested alone.
- Outcomes: a global parkinsonism score (gait, bradykinesia, rigidity, tremor) and a global motor score (grip and pinch strength, dexterity, gait, balance), signed so that higher means worse.
- Molecular layers from dorsolateral prefrontal cortex (552 donors with at least four of five layers): genotypes for 7.16 million SNPs, DNA methylation (about 130,000 loci), histone H3K9 acetylation (26,384 regions), gene expression (13,484 genes), 292 microRNAs and 67 targeted proteins, collapsed into co-varying modules, plus 14 neuropathology measures (560 variables in total).
- Analysis: linear and logistic regression adjusted for age, sex, education and three genotype principal components; variance-explained decomposition; Bayesian network modelling of the paths from AD-PRS to motor scores.

## Findings

- The AD-PRS was associated with both the global parkinsonism score and the global motor score (significance threshold p = 0.001; strongest with an SNP inclusion threshold of p < 0.5), with both source GWASs. Strong domain associations were with gait and rigidity (parkinsonism) and with dexterity and hand strength (motor); tremor and the stand-balance tests were not associated.
- The associations were present in participants with Alzheimer dementia (N = 557) and not in non-demented participants (N = 1211), which the authors read as motor impairment tied to dementia.
- The [[APOE]] and [[TOMM40]] region was not the main driver: the PRS without those SNPs kept similar effects, and the region alone was only moderately linked to dexterity (p = 0.002).
- The Parkinson disease PRS was moderately associated with a clinical diagnosis of [[Parkinson disease]] (odds ratio 1.2, p = 0.0008) but not with the motor scores, and the AD-PRS was not associated with Parkinson disease.
- Of 560 molecular variables, 13 passed Bonferroni correction (p < 8.9 x 10^-5) for the parkinsonism score or dexterity: three pathologies (tau [[Neurofibrillary tangle]] density, [[Arteriolosclerosis]], nigral neuronal loss), four histone co-acetylation modules (m28, m117, m434, m450), three microRNAs ([[MIR132]] and miR-129-5p and miR-129-3p, from [[MIR129-1]]) and three proteins ([[IGFBP5]], [[VGF]], [[SYT12]]).
- Eight of these were also associated with the AD-PRS: one pathology (tangle density), two histone modules, two microRNAs and three proteins. Beta-amyloid burden tracked the AD-PRS strongly (p = 5.5 x 10^-14) but motor scores only weakly (p = 0.03 and 0.02), whereas tangle density tracked both (AD-PRS p = 2.3 x 10^-13; parkinsonism p = 4.0 x 10^-7; dexterity p = 1.1 x 10^-5).
- Each feature explained 15-30% of the AD-PRS effect on motor scores and together about 60%. In the Bayesian networks the direct upstream nodes of the parkinsonism score were miR-132, tangle density, module m434 and IGFBP5, and those of dexterity were VGF and miR-129-5p.
- Module m434 (436 acetylation peaks) was enriched for glial cell development and for a neuromuscular process controlling balance, supported by [[DRD2]] and [[PRKN]] (parkin); m450 was enriched for autophagy and response to viruses; m117 for epithelial morphogenesis and actin filament organisation.
- Tangle density, miR-132, VGF and IGFBP5 also explained the AD-PRS association with cognitive decline, pointing to shared mechanisms for cognitive and motor decline.

## Why This Source Matters

It shows that the polygenic burden of Alzheimer risk, mostly from loci below genome-wide significance and not from the APOE region, reaches into motor function, and it narrows the candidate mediators to a short list (tau tangles, one histone co-acetylation module, two microRNAs and three proteins) that can be taken to model systems. It also separates features that follow Alzheimer genetic risk without affecting movement (amyloid, neuritic plaques) from those that do.

## Assessment

- Multi-omic data come only from dorsolateral prefrontal cortex, not from motor cortex, basal ganglia, substantia nigra, spinal cord or muscle, so the real motor-system mediators may be missed.
- Participants are volunteers, highly educated and almost all of European descent, so generalisation needs replication in more diverse cohorts.
- The mediation reading rests on cross-sectional associations and a Bayesian network inference, not on causal experiments.
- The Parkinson disease PRS used a public subset of summary statistics and parkinsonism scores may be low in treated patients, so the null result for the Parkinson disease PRS on motor scores does not rule out an effect of Parkinson disease genetics.
- The Supplementary tables and methods were not available in the text read, so exact effect sizes for most associations are not recorded here.

## Open Questions

- Do the tau tangle, histone module m434, miR-132, miR-129-5p, VGF and IGFBP5 mediators of Alzheimer genetic risk on motor function replicate in a cohort of non-European ancestry?
- Do the same mediators appear in motor-related tissue such as motor cortex, substantia nigra, spinal cord or muscle (only dorsolateral prefrontal cortex was profiled)?
- Which genes below genome-wide significance drive the PRS association with motor scores (the PRS signal came from many sub-threshold loci)?
- Do VGF, IGFBP5 or miR-132 manipulation in an animal model change motor performance (the study gives only observational associations)?

## Connections

- Disease and phenotype: [[Alzheimer disease]], [[Parkinson disease]], [[Parkinsonism]], [[Motor impairment]]
- Genes: [[APOE]], [[TOMM40]], [[IGFBP5]], [[VGF]], [[SYT12]], [[MIR132]], [[MIR129-1]], [[DRD2]], [[PRKN]]
- Pathology: [[Neurofibrillary tangle]], [[Arteriolosclerosis]]
- Method: [[Polygenic risk score]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The major genetic risk factor for sporadic Alzheimer’s dementia, the APOE/TOMM40 locus, was not a major driver of these associations." |
| [[TOMM40]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The major genetic risk factor for sporadic Alzheimer’s dementia, the APOE/TOMM40 locus, was not a major driver of these associations." |
| PSEN1 (HGNC:9508) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "While a few genetic variants associated with Alzheimer’s dementia, including variants in the ApoE and presenilin 1 regions, have also been linked to motor deficits, the overall effect of AD genetics on motor impairment in older adults is yet to be examined in detail." |
| [[Alzheimer disease]] (MESH:D000544) | biolink:associated_with | amyloid-beta (CHEBI:64645; MESH:D016229) |  | "For instance, the AD-PRS was associated strongly with β-amyloid burden (p = 5.5 × 10–14), but β-amyloid showed less association with motor abilities (p = 0.03 for global parkinsonism score and p = 0.02 for dexterity), while PHFtau tangles was associated with both the AD-PRS (p = 2.3 × 10–13) and motor abilities (p = 4.0 × 10–7 for global parkinsonism score and p = 1.1 × 10–5 for dexterity) (Fig. 3a)." |
| [[MIR132]] | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "In this comparison, we identified three brain pathologies (PHFtau-tangles, arteriolosclerosis, and nigral neuronal loss), four histone coacetylation modules (m28, m117, m434, and m450), three miRNAs (miR-132, miR-129-5p, and miR-129-3p), and three proteins (IGFBP5, VGF, and SYT12) that were associated with either global parkinsonism, dexterity, or both (p < 8.9 × 10−5) (Fig. 2a and Supplementary Table 7)." |
| MIR129-1 (HGNC:31512) | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "In this comparison, we identified three brain pathologies (PHFtau-tangles, arteriolosclerosis, and nigral neuronal loss), four histone coacetylation modules (m28, m117, m434, and m450), three miRNAs (miR-132, miR-129-5p, and miR-129-3p), and three proteins (IGFBP5, VGF, and SYT12) that were associated with either global parkinsonism, dexterity, or both (p < 8.9 × 10−5) (Fig. 2a and Supplementary Table 7)." |
| [[IGFBP5]] | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "In this comparison, we identified three brain pathologies (PHFtau-tangles, arteriolosclerosis, and nigral neuronal loss), four histone coacetylation modules (m28, m117, m434, and m450), three miRNAs (miR-132, miR-129-5p, and miR-129-3p), and three proteins (IGFBP5, VGF, and SYT12) that were associated with either global parkinsonism, dexterity, or both (p < 8.9 × 10−5) (Fig. 2a and Supplementary Table 7)." |
| [[VGF]] | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "In this comparison, we identified three brain pathologies (PHFtau-tangles, arteriolosclerosis, and nigral neuronal loss), four histone coacetylation modules (m28, m117, m434, and m450), three miRNAs (miR-132, miR-129-5p, and miR-129-3p), and three proteins (IGFBP5, VGF, and SYT12) that were associated with either global parkinsonism, dexterity, or both (p < 8.9 × 10−5) (Fig. 2a and Supplementary Table 7)." |
| [[SYT12]] | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "In this comparison, we identified three brain pathologies (PHFtau-tangles, arteriolosclerosis, and nigral neuronal loss), four histone coacetylation modules (m28, m117, m434, and m450), three miRNAs (miR-132, miR-129-5p, and miR-129-3p), and three proteins (IGFBP5, VGF, and SYT12) that were associated with either global parkinsonism, dexterity, or both (p < 8.9 × 10−5) (Fig. 2a and Supplementary Table 7)." |
| [[DRD2]] | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "Interestingly, the association of m434 with neuromuscular processes controlling balance was supported by dopamine receptor D2 (DRD2) and parkin (PARK2), both of which are regarded as key molecules for parkinsonism." |
| [[PRKN]] | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "Interestingly, the association of m434 with neuromuscular processes controlling balance was supported by dopamine receptor D2 (DRD2) and parkin (PARK2), both of which are regarded as key molecules for parkinsonism." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "For instance, the AD-PRS was associated strongly with β-amyloid burden (p = 5.5 × 10–14), but β-amyloid showed less association with motor abilities (p = 0.03 for global parkinsonism score and p = 0.02 for dexterity), while PHFtau tangles was associated with both the AD-PRS (p = 2.3 × 10–13) and motor abilities (p = 4.0 × 10–7 for global parkinsonism score and p = 1.1 × 10–5 for dexterity) (Fig. 3a)." |
| [[MIR132]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Interestingly, miR-132, VGF, and PHFtau-tangles are reported to be dysregulated in brains of both Alzheimer’s dementia and PD patients." |
| [[VGF]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Interestingly, miR-132, VGF, and PHFtau-tangles are reported to be dysregulated in brains of both Alzheimer’s dementia and PD patients." |
| MAPT (HGNC:6893) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Interestingly, miR-132, VGF, and PHFtau-tangles are reported to be dysregulated in brains of both Alzheimer’s dementia and PD patients." |
| [[MIR132]] | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "Interestingly, miR-132, VGF, and PHFtau-tangles are reported to be dysregulated in brains of both Alzheimer’s dementia and PD patients." |
| [[VGF]] | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "Interestingly, miR-132, VGF, and PHFtau-tangles are reported to be dysregulated in brains of both Alzheimer’s dementia and PD patients." |
| [[DRD2]] | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "Also, m434 was enriched for cis-regulatory region coding genes involved in neuromuscular processes controlling balance, such as dopamine receptor D2, parkin, and NKX6-2 that are associated with PD or ataxia." |
| [[PRKN]] | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "Also, m434 was enriched for cis-regulatory region coding genes involved in neuromuscular processes controlling balance, such as dopamine receptor D2, parkin, and NKX6-2 that are associated with PD or ataxia." |
| NKX6-2 (HGNC:19321) | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "Also, m434 was enriched for cis-regulatory region coding genes involved in neuromuscular processes controlling balance, such as dopamine receptor D2, parkin, and NKX6-2 that are associated with PD or ataxia." |
| MAPT (HGNC:6893) | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "Interestingly, miR-132, VGF, and PHFtau-tangles are reported to be dysregulated in brains of both Alzheimer’s dementia and PD patients." |
| [[MIR132]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "PHFtau-tangles, miR-132, VGF, and IGFBP5 also explained the association of AD-PRS with cognitive decline, suggesting these are involved in the common molecular mechanisms leading to cognitive decline and motor impairment in older adults." |
| [[IGFBP5]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "PHFtau-tangles, miR-132, VGF, and IGFBP5 also explained the association of AD-PRS with cognitive decline, suggesting these are involved in the common molecular mechanisms leading to cognitive decline and motor impairment in older adults." |
| [[VGF]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "PHFtau-tangles, miR-132, VGF, and IGFBP5 also explained the association of AD-PRS with cognitive decline, suggesting these are involved in the common molecular mechanisms leading to cognitive decline and motor impairment in older adults." |
| MAPT (HGNC:6893) | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "PHFtau-tangles, miR-132, VGF, and IGFBP5 also explained the association of AD-PRS with cognitive decline, suggesting these are involved in the common molecular mechanisms leading to cognitive decline and motor impairment in older adults." |
| MAPT (HGNC:6893) | biolink:associated_with | [[Parkinsonism]] (MESH:D020734) |  | "Further, the BN models indicated that direct upstream regulators for the global parkinsonism score were miR-132, PHFtau-tangles, m434, and IGFBP5, and those for dexterity were VGF and miR-129-p5." |
| [[DRD2]] | biolink:associated_with | ataxia (HP:0001251; MESH:D001259) |  | "Also, m434 was enriched for cis-regulatory region coding genes involved in neuromuscular processes controlling balance, such as dopamine receptor D2, parkin, and NKX6-2 that are associated with PD or ataxia." |
| [[PRKN]] | biolink:associated_with | ataxia (HP:0001251; MESH:D001259) |  | "Also, m434 was enriched for cis-regulatory region coding genes involved in neuromuscular processes controlling balance, such as dopamine receptor D2, parkin, and NKX6-2 that are associated with PD or ataxia." |
| NKX6-2 (HGNC:19321) | biolink:associated_with | ataxia (HP:0001251; MESH:D001259) |  | "Also, m434 was enriched for cis-regulatory region coding genes involved in neuromuscular processes controlling balance, such as dopamine receptor D2, parkin, and NKX6-2 that are associated with PD or ataxia." |
