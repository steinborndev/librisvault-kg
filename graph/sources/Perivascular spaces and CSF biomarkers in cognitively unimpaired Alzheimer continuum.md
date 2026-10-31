---
type: source
title: "Perivascular spaces and CSF biomarkers in cognitively unimpaired Alzheimer continuum"
paper_title: "Perivascular spaces are associated with tau pathophysiology and synaptic dysfunction in early Alzheimer’s continuum"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000250
pmid: "34353353"
pmcid: "PMC8340485"
doi: "10.1186/s13195-021-00878-5"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8340485/"
sources: ["[[.raw/01M4DY94M1D41F2NY2EAEFCSKH/normalized.md]]"]
tags: [biomarker, mri]
---

# Perivascular spaces and CSF biomarkers in cognitively unimpaired Alzheimer continuum

A cross-sectional study of 322 cognitively unimpaired, middle-aged adults from the ALFA+ cohort in Barcelona (mean age 60.4 years, 64.5% female), many of them in the [[Alzheimer disease]] continuum. It asks whether [[Enlarged perivascular spaces]] (ePVS) on MRI track cerebrospinal fluid (CSF) markers of different pathophysiological mechanisms, and whether the answer depends on amyloid status.

## Design

- Cohort: ALFA+ is a nested study of the ALFA parent cohort (2743 cognitively unimpaired adults aged 45-75, enriched for offspring of Alzheimer patients), with participants invited on an Alzheimer-risk profile built from parental history, age, number of APOE ε4 alleles, memory score and CAIDE score. All 322 had APOE genotype, MRI, CSF and cardiovascular data; MRI and CSF sampling were a mean of 44 days apart.
- Imaging: 3 T MRI with 1 mm isotropic T2-weighted images; perivascular spaces were scored by one blinded radiologist in the basal ganglia (BG) and centrum semiovale (CS) with a 0-4 scale, see [[Visual rating of perivascular spaces on MRI]]. White matter hyperintensities were segmented from FLAIR images.
- CSF: p-tau(181P) and t-tau with Elecsys immunoassays, and Aβ42, Aβ40, [[NEFL]] (NfL), [[NRGN]] (neurogranin), soluble [[TREM2]], [[CHI3L1]] (YKL40), GFAP, [[IL6]], S100 and α-synuclein with NeuroToolKit prototype assays. Amyloid positivity was an Aβ42/40 ratio below 0.071 (two-Gaussian mixture cut-off), met by 122 participants.
- Statistics: logistic regression for BG and multinomial regression for CS, adjusted for age, sex, APOE ε4 status, physical inactivity, grey matter volume, intracranial volume and blood pressure; stratified by amyloid status, with and without correction for CSF Aβ40; false discovery rate correction.

## Findings

- Age: the odds of ePVS rose with age in both regions, independently of cardiovascular risk factors (BG odds ratio 1.14 per year, 95% CI 1.07-1.23; CS degree 3+4 versus 1, 1.27, 1.13-1.45).
- Sex and vascular factors: women had higher odds of CS ePVS once cardiovascular factors were included (degree 3+4 versus 1, OR 5.5, 1.59-21.06). Diastolic blood pressure and white matter hyperintensities predicted CS ePVS alone but not after adjustment. The number of [[APOE]] ε4 alleles was not associated with ePVS.
- Uncorrected for Aβ40, higher p-tau, t-tau, YKL40, sTREM2 and neurogranin were associated with BG ePVS in the whole sample, and p-tau, t-tau and neurogranin with CS ePVS; in amyloid-positive people alone only NfL and neurogranin were associated with BG ePVS.
- Higher CSF Aβ40 went with higher ePVS degree in both regions, in amyloid-positive and amyloid-negative people alike.
- After correcting for Aβ40, only p-tau (OR 1.16, 1.03-1.35), t-tau (OR 1.02, 1.01-1.04) and neurogranin (OR 1.004, 1.001-1.008) stayed associated, and only with CS ePVS in amyloid-positive participants (degree 2 versus 3+4). No such association appeared in amyloid-negative participants or in the basal ganglia.

## Interpretation by the authors

The authors read the CS result as a link between ePVS and tau pathophysiology, neurodegeneration and synaptic dysfunction in the asymptomatic stage of the continuum. They also propose that the broad rise of many CSF markers with ePVS, and the Aβ40 association, may partly reflect impaired CSF clearance rather than a role of those mechanisms in forming ePVS.

## Why This Source Matters

It ties a vascular-clearance imaging marker to the tau side of early Alzheimer pathology in people without symptoms, and shows that the association with [[MAPT]] markers and neurogranin is specific to the centrum semiovale and to amyloid-positive individuals. The Aβ40 analysis is a useful reminder that CSF concentrations can shift with clearance itself.

## Assessment

- Cross-sectional, so direction of effect cannot be settled; p-tau, t-tau and neurogranin were highly correlated (Pearson r above 0.90), so their effects are hard to separate.
- A single rater, one scale, one MRI protocol and two regions; dichotomising the scale loses power. Intra-rater agreement was substantial (kappa 0.77 BG, 0.76 CS).
- The cohort is young, low in cardiovascular risk and enriched for ε4 carriers, so the null APOE result may not hold in older or high-risk groups. Individual-level data are not public.
- Aβ40 is not a validated measure of overall protein clearance, which limits the correction.

## Open Questions

- Do enlarged perivascular spaces in the centrum semiovale precede or follow rises in CSF phosphorylated tau (longitudinal MRI and CSF were not available in this cross-sectional cohort)?
- Is the association between enlarged perivascular spaces and CSF tau markers present in older or higher cardiovascular-risk cohorts, where APOE ε4 has been reported to relate to perivascular spaces?

## Connections

- Disease: [[Alzheimer disease]]; related small-vessel pathology: [[Cerebral amyloid angiopathy]]
- Phenotype: [[Enlarged perivascular spaces]]; method: [[Visual rating of perivascular spaces on MRI]]
- Genes and markers: [[MAPT]], [[APP]], [[NRGN]], [[NEFL]], [[CHI3L1]], [[TREM2]], [[IL6]], [[APOE]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[Enlarged perivascular spaces]] | biolink:associated_with | [[MAPT]] |  | "Higher levels of p-tau, t-tau, and neurogranin were significantly associated with ePVS in the CS of Aβ positive individuals, after accounting for relevant confounders." |
| [[Enlarged perivascular spaces]] | biolink:associated_with | [[NRGN]] |  | "Higher levels of p-tau, t-tau, and neurogranin were significantly associated with ePVS in the CS of Aβ positive individuals, after accounting for relevant confounders." |
| [[Enlarged perivascular spaces]] | biolink:associated_with | Amyloid-β (CHEBI:64645; MESH:D016229) |  | "Interestingly, water influx into the CSF flow through PVS could play a role equivalent to the one in the lymphatic system and it recently gained substantial attention due to its relation to amyloid-β (Aβ) clearance." |
| [[Enlarged perivascular spaces]] | biolink:associated_with | Water (CHEBI:15377; MESH:D014867) |  | "Interestingly, water influx into the CSF flow through PVS could play a role equivalent to the one in the lymphatic system and it recently gained substantial attention due to its relation to amyloid-β (Aβ) clearance." |
| [[Enlarged perivascular spaces]] | biolink:associated_with | Cerebrospinal fluid (CHEBI:191852; MESH:D002556) |  | "Perivascular spaces (PVS), also known as Virchow-Robin spaces, facilitate CSF transport from the basal cisterns into the brain interstitial fluid (ISF) and have an important role in the elimination of metabolic waste and fluid from the brain." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The impairment of this biological mechanism might contribute to the development of AD pathophysiology, characterized by Aβ plaques and tau tangles." |
| [[NEFL]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| [[NRGN]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| [[CHI3L1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| GFAP (HGNC:4235) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| [[IL6]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| SNCA (HGNC:11138) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| Amyloid-β (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The impairment of this biological mechanism might contribute to the development of AD pathophysiology, characterized by Aβ plaques and tau tangles." |
| [[IL6]] | biolink:biomarker_for | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "Moreover, we sought for associations between PVS with additional CSF biomarkers of several pathophysiological mechanisms involved in AD and other neurodegenerative disorders such as axonal damage (NfL), synaptic dysfunction (neurogranin), microglial (sTREM2), astroglial-related response (GFAP, YKL40, S100), other neuroinflammatory biomarkers (IL6), and α-synuclein." |
| [[APOE]] | NOT biolink:associated_with | [[Enlarged perivascular spaces]] |  | "Finally, we did not find a significant association between the risk of ePVS and the number of APOE-ε4 alleles." |
| [[MAPT]] | biolink:biomarker_for | Neurodegeneration (HP:0002180; MESH:D019636) |  | "CSF p-tau, t-tau and neurogranin are widely accepted biomarkers of tau protein pathophysiology, neurodegeneration, and synaptic dysfunction, respectively." |
| Amyloid-β 42 (CHEBI:64647; MESH:C075222) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "CSF Aβ40 concentration values are typically used to normalize CSF Aβ42 levels to render a superior performance (Aβ42/40 ratio) in discriminating patients with AD." |
| [[APOE]] | NOT biolink:associated_with | [[Enlarged perivascular spaces]] |  | "Contrary to them, some studies performed in healthy younger individuals were in line with our results and did not find significant associations between APOE and ePVS." |
| APOE-ε4 (variant) | biolink:affects | Amyloid-β (CHEBI:64645; MESH:D016229) | direction=increased | "Because APOE-ε4 enhances Aβ deposition, several studies focused on associations between APOE genotypes and ePVS, with controversial results." |
| [[MAPT]] | biolink:positively_correlated_with | [[NRGN]] |  | "In particular, p-tau, t-tau, and neurogranin had pair-wise Pearson’s r > 0.90." |
| [[MAPT]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Nevertheless, p-tau measurements obtained with the same essay have been shown to be able to predict clinical decline and conversion to AD and have been approved for clinical use." |
| [[MAPT]] | biolink:associated_with | Neurodegeneration (HP:0002180; MESH:D019636) |  | "This high correlation might reflect a tight association between tau pathophysiology, AD-related neurodegeneration, and synaptic dysfunction in our sample or be due to other technical or physiological confounding factors." |
| [[MAPT]] | biolink:positively_correlated_with | [[Enlarged perivascular spaces]] |  | "In conclusion, our findings showed, for the first time, an association between ePVS in the CS and higher levels of CSF core AD biomarkers p-tau and t-tau, as well as CSF neurogranin, in cognitively unimpaired Aβ + individuals." |
| [[MAPT]] | biolink:biomarker_for | Cognitive decline (HP:0001268; MESH:D060825) |  | "Nevertheless, p-tau measurements obtained with the same essay have been shown to be able to predict clinical decline and conversion to AD and have been approved for clinical use." |
| [[NRGN]] | biolink:positively_correlated_with | [[Enlarged perivascular spaces]] |  | "In conclusion, our findings showed, for the first time, an association between ePVS in the CS and higher levels of CSF core AD biomarkers p-tau and t-tau, as well as CSF neurogranin, in cognitively unimpaired Aβ + individuals." |
