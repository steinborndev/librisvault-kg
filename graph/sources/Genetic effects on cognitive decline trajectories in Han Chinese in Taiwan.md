---
type: source
title: "Genetic effects on cognitive decline trajectories in Han Chinese in Taiwan"
paper_title: "Association between Alzheimer’s disease genes and trajectories of cognitive function decline in Han Chinese in Taiwan"
domain: neuroscience
status: developing
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001421
pmid: "34214049"
pmcid: "PMC8312434"
doi: "10.18632/aging.203204"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8312434/"
sources: ["[[.raw/01M4P89VCQ7QEA02ZB18GCC3E2/normalized.md]]"]
tags: [observational-cohort, snp-genotyping, trajectory, alzheimer-risk-locus]
---

# Genetic effects on cognitive decline trajectories in Han Chinese in Taiwan

A four-year longitudinal study of 299 Han Chinese patients in Taiwan (255 with [[Alzheimer disease]], 44 with [[Mild cognitive impairment]]) asking whether common risk variants shift the age at which cognition declines and how fast it falls. Variants in [[APOE]], [[ABCA7]], [[SORL1]], [[BIN1]], [[GAB2]] and [[CD33]] were tested against Mini-Mental State Examination (MMSE) trajectories fitted with a [[Bayesian hierarchical model of cognitive decline trajectories]]. Only APOE ε4, ABCA7 rs3764650 and SORL1 rs3737529 moved the timing of decline.

## Design

- Patients came from two teaching hospitals in the Biosignature Study of Alzheimer's Disease, a subproject of Taiwan Biobank followed yearly since 2012. Everyone had at least four MMSE measurements. Mean age at entry was 78.4 ± 7.0 years, 51.8% were women and mean baseline MMSE was 20.0 ± 4.9.
- Of the 44 MCI patients, 28 (63.6%) progressed to Alzheimer disease. Diagnosis followed the National Institute on Aging-Alzheimer's Association criteria for probable Alzheimer disease; MCI was set at 1.5 standard deviations below the age-adjusted norm on the Wechsler logical memory test. Onset after age 60 was required, and other neurological disease, major head trauma or structural brain abnormality excluded.
- Genotyping by TaqMan assay on an ABI 7500 system: [[APOE rs429358]] and [[APOE rs7412]] defined ε2, ε3 and ε4; seven further SNPs were chosen from the authors' earlier Taiwanese risk study ([[ABCA7 rs3764650]], [[SORL1 rs1784933]], [[SORL1 rs2298813]]), from SORL1 rs3737529 as a leading Asian SNP, and from the AlzGene top results ([[BIN1 rs744373]], [[CD33 rs3865444]], [[GAB2 rs2373115]]). All were in Hardy-Weinberg equilibrium.
- Replication used 385 patients from the [[Alzheimer's Disease Neuroimaging Initiative]] (150 Alzheimer, 235 MCI that progressed), with SORL1 rs3737529, SORL1 rs1784933 and GAB2 rs2373115 imputed to the 1000 Genomes reference.

## Findings

- Adjusted for sex and education, one ε4 copy shifted the midpoint age of decline by -2.39 years (95% credible interval -4.12 to -0.64); one G allele of ABCA7 rs3764650 by -1.75 years (-3.09 to -0.37); one T allele of SORL1 rs3737529 by +2.60 years (0.38 to 4.88), a later midpoint.
- The rate of decline was tied to APOE (posterior mean 0.96, interval 0.39 to 1.57) and SORL1 rs3737529 (0.58, interval 0.05 to 1.14). The mean trajectories show faster decline in people with two ε4 copies and in SORL1 rs3737529 CC homozygotes.
- SORL1 rs1784933, SORL1 rs2298813, BIN1 rs744373, GAB2 rs2373115 and CD33 rs3865444 showed no association with either parameter.
- Gibbs variable selection across the eight markers picked APOE and SORL1 rs3737529 as the best-fitting model; refitting just those two gave the same directions and a posterior predictive p-value of 0.937.
- Dropping the 16 MCI patients who never progressed (283 left) gave near-identical shifts: -2.10 years for ε4, -1.74 for ABCA7 and +2.65 for the SORL1 T allele.
- In the ADNI sample only APOE was associated with the midpoint age; the ABCA7 and SORL1 effects did not replicate, which the authors read as population-specific genetic effects.
- The authors infer that the SORL1 T allele protects against decline independently of APOE genotype.

## Assessment

- The cohort is small, there is no second Taiwanese cohort, and the ADNI check is of different ancestry and used imputed genotypes for three SNPs, so the failure of ABCA7 and SORL1 to replicate cannot separate ancestry from imputation or power.
- Diagnosis rested on clinical criteria without amyloid or tau biomarkers, only the MMSE tracked cognition (the authors note it may understate decline), and just eight markers were tested.
- Alzheimer and MCI patients were modelled together; the stability of the results when non-progressing MCI was dropped helps but does not separate the two groups.
- The credible intervals for ABCA7 and SORL1 are wide (the SORL1 midpoint shift spans 0.38 to 4.88 years), and no correction for testing eight markers is described.
- The text does not state the sign of the SORL1 rs3737529 rate estimate; direction is taken from the trajectory figure.
- Tables were not part of the text read, so genotype frequencies and the full model-selection probabilities are not recorded here.

## Open Questions

- Does ABCA7 rs3764650 shift the midpoint age of cognitive decline in an independent Han Chinese cohort (the original finding rests on one Taiwanese sample of 299 patients and was absent in the ADNI sample)?
- Does SORL1 rs3737529 delay cognitive decline in a Han Chinese cohort followed with biomarker-confirmed diagnosis (the Taiwanese diagnoses used clinical criteria only)?
- Why does the ABCA7 rs3764650 G allele bring earlier decline here when the authors' earlier Taiwanese study found the GG genotype protective against disease risk?
- Do the ABCA7 and SORL1 effects on decline trajectories reappear in ADNI once the three imputed SORL1 and GAB2 markers are directly genotyped?

## Why This Source Matters

Most Alzheimer genetics asks who gets the disease; this study asks when and how fast cognition falls once disease or MCI is present, and shows that the answer can differ by population. It gives Han Chinese effect sizes for APOE ε4 on age of decline and puts SORL1 rs3737529 forward as a variant that delays decline, while the null results at BIN1, GAB2, CD33 and two other SORL1 SNPs narrow the list of markers worth following in this population.

## Connections

- Genes: [[APOE]], [[ABCA7]], [[SORL1]], [[BIN1]], [[GAB2]], [[CD33]]
- Variants: [[APOE rs429358]], [[APOE rs7412]], [[ABCA7 rs3764650]], [[SORL1 rs3737529]], [[SORL1 rs1784933]], [[SORL1 rs2298813]], [[BIN1 rs744373]], [[GAB2 rs2373115]], [[CD33 rs3865444]]
- Diseases and features: [[Alzheimer disease]], [[Mild cognitive impairment]], [[Cognitive impairment]]
- Method: [[Bayesian hierarchical model of cognitive decline trajectories]]; replication cohort [[Alzheimer's Disease Neuroimaging Initiative]]
- Earlier Chinese and Taiwanese genetic work: [[Familial Alzheimer disease mutations in Han Chinese in Taiwan]], [[SNP association study of Alzheimer disease in southern Chinese population]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "There are many factors that contribute to the rate of cognitive decline, such as age of disease onset, gender, education, extrapyramidal signs, behavioral disorders, vascular risk factors and the most known AD susceptibility genetic locus, apolipoprotein E (APOE) genotypes." |
| [[ABCA7]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[SORL1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[BIN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[GAB2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[CD33]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[CR1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[CLU]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[PICALM]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[CD2AP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[EPHA1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[MS4A6A]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| [[MS4A4E]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recent GWAS have identified more than 20 AD susceptibility loci, including CR1, CLU, PICALM, BIN1, CD2AP, CD33, EPHA1, MS4A6A/MS4A4E, SORL1, GAB2, ABCA7, etc." |
| GCH1 (HGNC:4193) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In Han Chinese or Asian population, common variants in GCH1, KCNJ15, and rare missense variant in the C7 genes were also identified by whole-genome sequencing and whole-exome sequencing studies." |
| KCNJ15 (HGNC:6261) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In Han Chinese or Asian population, common variants in GCH1, KCNJ15, and rare missense variant in the C7 genes were also identified by whole-genome sequencing and whole-exome sequencing studies." |
| C7 (HGNC:1346) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In Han Chinese or Asian population, common variants in GCH1, KCNJ15, and rare missense variant in the C7 genes were also identified by whole-genome sequencing and whole-exome sequencing studies." |
| [[ABCA7 rs3764650]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In our previous studies, we identified ABCA7 rs3764650 and SORL1 rs1784933 as being associated with the risk of AD in Han Chinese individuals in Taiwan, the association between BIN1 rs744373 and AD was reported in Asian populations, but the effect of these AD risk genes on the rate of cognitive decline is not clear." |
| [[SORL1 rs1784933]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In our previous studies, we identified ABCA7 rs3764650 and SORL1 rs1784933 as being associated with the risk of AD in Han Chinese individuals in Taiwan, the association between BIN1 rs744373 and AD was reported in Asian populations, but the effect of these AD risk genes on the rate of cognitive decline is not clear." |
| [[BIN1 rs744373]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In our previous studies, we identified ABCA7 rs3764650 and SORL1 rs1784933 as being associated with the risk of AD in Han Chinese individuals in Taiwan, the association between BIN1 rs744373 and AD was reported in Asian populations, but the effect of these AD risk genes on the rate of cognitive decline is not clear." |
| [[APOE]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "In summary, APOE and SORL1 might be the most important genetic factors related to cognitive decline in Han Chinese population." |
| [[SORL1]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "In summary, APOE and SORL1 might be the most important genetic factors related to cognitive decline in Han Chinese population." |
| PDE7A (HGNC:8791) | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "The results from previous studies have shown that having at least one APOE ε4 allele was associated with faster cognitive decline in cognitively healthy older Taiwanese adults, and PDE7A and MTFR1 genes were associated with the rate of age-related cognitive decline." |
| MTFR1 (HGNC:29510) | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "The results from previous studies have shown that having at least one APOE ε4 allele was associated with faster cognitive decline in cognitively healthy older Taiwanese adults, and PDE7A and MTFR1 genes were associated with the rate of age-related cognitive decline." |
| [[APOE]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "Additionally, the rate of cognitive decline was associated with the APOE ε4 allele and SORL1 rs3737529." |
| [[ABCA7 rs3764650]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "After adjusting for sex and education years, the APOE ε4 allele was associated with an earlier mean change of −2.39 years in the age at midpoint of cognitive decline, the G allele in ABCA7 rs3764650 was associated with an earlier mean change of −1.75 years, and the T allele in SORL1 rs3737529 was associated with a later mean change of 2.6 years." |
| [[SORL1 rs3737529]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "Additionally, the rate of cognitive decline was associated with the APOE ε4 allele and SORL1 rs3737529." |
| [[BDNF p.V66M]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "Moreover, BDNF Val66Met was associated with faster cognitive decline and greater hippocampal atrophy in preclinical AD patients." |
| [[BDNF p.V66M]] | biolink:associated_with | [[Hippocampal atrophy]] |  | "Moreover, BDNF Val66Met was associated with faster cognitive decline and greater hippocampal atrophy in preclinical AD patients." |
| [[SORL1 rs1784933]] | NOT biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "No statistically significant associations were observed between either the age at midpoint or the rate of cognitive decline and the genetic markers of SORL1 rs1784933, SORL1 rs2298813, BIN1 rs744373, GAB2 rs2373115, and CD33 rs3865444." |
| [[SORL1 rs2298813]] | NOT biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "No statistically significant associations were observed between either the age at midpoint or the rate of cognitive decline and the genetic markers of SORL1 rs1784933, SORL1 rs2298813, BIN1 rs744373, GAB2 rs2373115, and CD33 rs3865444." |
| [[BIN1 rs744373]] | NOT biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "No statistically significant associations were observed between either the age at midpoint or the rate of cognitive decline and the genetic markers of SORL1 rs1784933, SORL1 rs2298813, BIN1 rs744373, GAB2 rs2373115, and CD33 rs3865444." |
| [[GAB2 rs2373115]] | NOT biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "No statistically significant associations were observed between either the age at midpoint or the rate of cognitive decline and the genetic markers of SORL1 rs1784933, SORL1 rs2298813, BIN1 rs744373, GAB2 rs2373115, and CD33 rs3865444." |
| [[CD33 rs3865444]] | NOT biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "No statistically significant associations were observed between either the age at midpoint or the rate of cognitive decline and the genetic markers of SORL1 rs1784933, SORL1 rs2298813, BIN1 rs744373, GAB2 rs2373115, and CD33 rs3865444." |
| [[ABCA7]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "In this study, we demonstrated that the APOE, ABCA7, and SORL1 genes were associated with cognitive function decline in the Han Chinese population." |
| [[CR1]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "One prior study in North America found that CLU and CR1 were associated with more rapid cognitive decline and that PICALM was associated with an earlier age at the midpoint of cognitive decline in patients with AD." |
| [[CLU]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "One prior study in North America found that CLU and CR1 were associated with more rapid cognitive decline and that PICALM was associated with an earlier age at the midpoint of cognitive decline in patients with AD." |
| [[PICALM]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "One prior study in North America found that CLU and CR1 were associated with more rapid cognitive decline and that PICALM was associated with an earlier age at the midpoint of cognitive decline in patients with AD." |
| [[SORL1 rs3737529]] | biolink:associated_with_decreased_likelihood_of | Cognitive decline (HP:0001268; MESH:D060825) |  | "The T allele in SORL1 rs3737529 seems to be protective against cognitive decline independent of APOE genotype." |
| [[APOE]] | biolink:associated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "Previous studies have shown that the effect of the APOE gene on the risk of cognitive decline and dementia was modified by other genetic factors, including ABCA7, SORL1, PICALM, CR1, BIN1, and TREM2, showing complex gene-gene interactions." |
| [[APOE]] | biolink:genetically_interacts_with | [[ABCA7]] |  | "Previous studies have shown that the effect of the APOE gene on the risk of cognitive decline and dementia was modified by other genetic factors, including ABCA7, SORL1, PICALM, CR1, BIN1, and TREM2, showing complex gene-gene interactions." |
| [[APOE]] | biolink:genetically_interacts_with | [[SORL1]] |  | "Previous studies have shown that the effect of the APOE gene on the risk of cognitive decline and dementia was modified by other genetic factors, including ABCA7, SORL1, PICALM, CR1, BIN1, and TREM2, showing complex gene-gene interactions." |
| [[APOE]] | biolink:genetically_interacts_with | [[BIN1]] |  | "Previous studies have shown that the effect of the APOE gene on the risk of cognitive decline and dementia was modified by other genetic factors, including ABCA7, SORL1, PICALM, CR1, BIN1, and TREM2, showing complex gene-gene interactions." |
| [[APOE]] | biolink:genetically_interacts_with | [[CR1]] |  | "Previous studies have shown that the effect of the APOE gene on the risk of cognitive decline and dementia was modified by other genetic factors, including ABCA7, SORL1, PICALM, CR1, BIN1, and TREM2, showing complex gene-gene interactions." |
| [[APOE]] | biolink:genetically_interacts_with | [[PICALM]] |  | "Previous studies have shown that the effect of the APOE gene on the risk of cognitive decline and dementia was modified by other genetic factors, including ABCA7, SORL1, PICALM, CR1, BIN1, and TREM2, showing complex gene-gene interactions." |
| [[APOE]] | biolink:genetically_interacts_with | [[TREM2]] |  | "Previous studies have shown that the effect of the APOE gene on the risk of cognitive decline and dementia was modified by other genetic factors, including ABCA7, SORL1, PICALM, CR1, BIN1, and TREM2, showing complex gene-gene interactions." |
| [[ABCA7]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "The functions of ABCA7 include lipid metabolism, regulation of phagocytosis, and amyloid β (Aβ) production and clearance." |
| [[SORL1]] | biolink:physically_interacts_with | [[APP]] |  | "In AD, the SORL1 encoded receptor interacts with the amyloid precursor protein (APP) and the Aβ peptide, participating in APP trafficking and processing and Aβ destruction." |
| [[SORL1]] | biolink:physically_interacts_with | [[Amyloid-beta]] (MESH:D016229) |  | "In AD, the SORL1 encoded receptor interacts with the amyloid precursor protein (APP) and the Aβ peptide, participating in APP trafficking and processing and Aβ destruction." |
| [[SORL1]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "These results suggest that SORL1 plays many different roles in AD pathogenesis that are significantly related to clinical manifestations." |
| [[ABCA7 rs3764650]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=decreased | "The minor allele of rs3764650 in ABCA7 was associated with increased neuritic plaque formation and decreased Aβ levels in cerebrospinal fluid." |
| SORL1 rs3824968 (variant) | biolink:affects | Aβ42 (MESH:C075222) | direction=decreased | "Previous studies have also shown that two SORL1 polymorphisms (rs3824968-A allele and rs2282649-T allele) were related to decreased cerebrospinal fluid (CSF) concentrations of Aβ42 and Aβ40, the rs2070045-G allele was associated with increased CSF tau and more hippocampal atrophy, and SORL1 rs11218343 was associated with cognitive performance." |
| SORL1 rs2282649 (variant) | biolink:affects | Aβ42 (MESH:C075222) | direction=decreased | "Previous studies have also shown that two SORL1 polymorphisms (rs3824968-A allele and rs2282649-T allele) were related to decreased cerebrospinal fluid (CSF) concentrations of Aβ42 and Aβ40, the rs2070045-G allele was associated with increased CSF tau and more hippocampal atrophy, and SORL1 rs11218343 was associated with cognitive performance." |
| SORL1 rs3824968 (variant) | biolink:affects | Aβ40 (MESH:C078592) | direction=decreased | "Previous studies have also shown that two SORL1 polymorphisms (rs3824968-A allele and rs2282649-T allele) were related to decreased cerebrospinal fluid (CSF) concentrations of Aβ42 and Aβ40, the rs2070045-G allele was associated with increased CSF tau and more hippocampal atrophy, and SORL1 rs11218343 was associated with cognitive performance." |
| SORL1 rs2282649 (variant) | biolink:affects | Aβ40 (MESH:C078592) | direction=decreased | "Previous studies have also shown that two SORL1 polymorphisms (rs3824968-A allele and rs2282649-T allele) were related to decreased cerebrospinal fluid (CSF) concentrations of Aβ42 and Aβ40, the rs2070045-G allele was associated with increased CSF tau and more hippocampal atrophy, and SORL1 rs11218343 was associated with cognitive performance." |
| [[SORL1 rs2298813]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In our previous study, SORL1 rs1784933 and rs2298813 were associated with AD and MCI risk in the Han Chinese population in Taiwan, and in the present study, SORL1 rs3737529 was associated with the midpoint and the rate of cognitive decline in AD and MCI patients in Han Chinese population." |
| [[SORL1 rs1784933]] | biolink:associated_with | Mild cognitive impairment (MESH:D060825) |  | "In our previous study, SORL1 rs1784933 and rs2298813 were associated with AD and MCI risk in the Han Chinese population in Taiwan, and in the present study, SORL1 rs3737529 was associated with the midpoint and the rate of cognitive decline in AD and MCI patients in Han Chinese population." |
| [[SORL1 rs2298813]] | biolink:associated_with | Mild cognitive impairment (MESH:D060825) |  | "In our previous study, SORL1 rs1784933 and rs2298813 were associated with AD and MCI risk in the Han Chinese population in Taiwan, and in the present study, SORL1 rs3737529 was associated with the midpoint and the rate of cognitive decline in AD and MCI patients in Han Chinese population." |
| SORL1 rs11218343 (variant) | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "Previous studies have also shown that two SORL1 polymorphisms (rs3824968-A allele and rs2282649-T allele) were related to decreased cerebrospinal fluid (CSF) concentrations of Aβ42 and Aβ40, the rs2070045-G allele was associated with increased CSF tau and more hippocampal atrophy, and SORL1 rs11218343 was associated with cognitive performance." |
| [[ABCA7 rs3764650]] | biolink:associated_with_increased_likelihood_of | [[Hippocampal atrophy]] |  | "Clinically, the ABCA7 rs3764650 minor allele was associated with cortical and hippocampal atrophy and with a later age at onset and shorter disease duration." |
| SORL1 rs2070045 (variant) | biolink:associated_with_increased_likelihood_of | [[Hippocampal atrophy]] |  | "Previous studies have also shown that two SORL1 polymorphisms (rs3824968-A allele and rs2282649-T allele) were related to decreased cerebrospinal fluid (CSF) concentrations of Aβ42 and Aβ40, the rs2070045-G allele was associated with increased CSF tau and more hippocampal atrophy, and SORL1 rs11218343 was associated with cognitive performance." |
| [[ABCA7 rs3764650]] | biolink:associated_with_increased_likelihood_of | cortical atrophy (HP:0002120) |  | "Clinically, the ABCA7 rs3764650 minor allele was associated with cortical and hippocampal atrophy and with a later age at onset and shorter disease duration." |
| [[ABCA7 rs3764650]] | biolink:associated_with_increased_likelihood_of | neuritic plaque (MESH:D058225) |  | "The minor allele of rs3764650 in ABCA7 was associated with increased neuritic plaque formation and decreased Aβ levels in cerebrospinal fluid." |
