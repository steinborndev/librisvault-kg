---
type: source
title: "Brain metabolism and Alzheimer risk gene expression in normal elderly"
paper_title: "In Alzheimer-prone brain regions, metabolism and risk-gene expression are strongly correlated"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000316
pmid: "36092303"
pmcid: "PMC9453434"
doi: "10.1093/braincomms/fcac216"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9453434/"
sources: ["[[.raw/01M4DY94P6JV88D41K4FP8GWE1/normalized.md]]"]
tags: [neuroimaging, gene-expression, alzheimer-risk-locus, secondary-analysis]
---

# Brain metabolism and Alzheimer risk gene expression in normal elderly

A secondary analysis of public data that links two things usually studied apart: how strongly brain regions talk to each other metabolically, and how much of each [[Alzheimer disease]] risk gene those regions express. The authors took [[FDG PET]] scans of 117 cognitively normal older adults from the Alzheimer's Disease Neuroimaging Initiative (ADNI), split them by what happened over the next five years, built a metabolic network per group, and then correlated regional metabolism with regional expression of ten risk genes from the [[Allen Human Brain Atlas]].

## Why This Source Matters

It is one of few studies to ask whether the regional pattern of risk-gene expression in the healthy brain lines up with regional glucose metabolism, and it finds that it does for most genes. [[APOE]] expression tracks low metabolism most closely, [[SORL1]] expression tracks high metabolism, and the link is strongest in the module of regions where the disease starts. It also shows that the metabolic network of people who later develop disease is already more fragmented before symptoms. Both results are correlations across brain regions in group averages, not tests of cause (see Assessment).

## Design

- Cohort: ADNI cognitively normal (CN) participants with a usable five-year outcome, in three age-matched groups: stayed CN (81), progressed to mild cognitive impairment only (21, "CN to MCI") and progressed to Alzheimer disease (15, "CN to AD"). A fourth group of 150 patients already diagnosed at baseline ("AD", APOE 3/3, 3/4 or 4/4 only) was added without age matching. Two clinicians reviewed the diagnoses of the progression and patient groups.
- Imaging: preprocessed FDG PET, co-registered to T1 MRI parcellated with FreeSurfer 5.3 into 72 regions (68 Desikan-Killiany cortical regions plus hippocampus and amygdala on both sides); uptake was scaled to the pons as SUVR.
- Network: Pearson correlation of regional SUVR across participants gave a 72 by 72 matrix per group, clustered into modules by consensus Louvain clustering (100 runs repeated to a stable partition) with a modularity definition that handles negative links. See [[Brain metabolic network modularity]].
- Genes: expression from the [[Allen Human Brain Atlas]] (20,736 genes, six donors) in the Desikan-Killiany atlas. Known Alzheimer risk genes with a high donor-consistency score (above 0.446) left ten: [[APOE]], [[BIN1]], [[CD33]], [[CLU]], [[CELF1]], [[MAPT]], [[MEF2C]], [[FERMT2]], [[SORL1]] and [[TREM2]]. Each gene's regional expression was correlated with the group's mean regional SUVR, and each correlation was ranked against the correlations of all 20,736 genes with metabolism of the pooled CN groups (z-score and one-tailed P).

## Findings

- Metabolic connections weakened and the network became more modular as risk rose: modularity was 0.0209 in the stable CN group and 0.0570 in the Alzheimer group, rising monotonically across the four groups. The decline came mainly from weaker links between modules. All groups gave three modules; hippocampus, amygdala and entorhinal cortex always fell in Module 3. The strongest positive correlation between regions was 0.990 and the strongest negative only -0.453.
- Entorhinal cortex had the weakest links to the rest of the network in the stable CN group, and its correlation turned negative in the CN to AD group.
- Women had weaker and more modular networks than men in the stable CN, CN to AD and AD groups; the CN to MCI group showed no sex difference. In the AD group men were older (74.7 against 71.5 years, P = 0.0097).
- Eight of ten genes correlated significantly with metabolism in every group; [[CELF1]] and [[MAPT]] did not. [[SORL1]] and [[MEF2C]] correlated positively; [[BIN1]], [[CLU]], [[TREM2]], [[FERMT2]], [[CD33]] and [[APOE]] correlated negatively. APOE was strongest negative in every group (r of -0.733 or lower) and SORL1 strongest positive (r of 0.677 or higher).
- The APOE correlation grew with risk group: -0.733 (CN to CN), -0.758 (CN to MCI), -0.778 (CN to AD). SORL1, FERMT2, CD33 and APOE all strengthened as risk rose.
- Against the whole-transcriptome null distribution, three genes were more than two standard deviations out: APOE (r = -0.746, z = -2.353, one-tailed P = 0.0093), SORL1 (r = 0.710, z = 2.228, P = 0.0130) and CD33 (r = -0.700, z = -2.208, P = 0.0136).
- APOE and CD33 expression was high, and SORL1 expression and SUVR low, in the most vulnerable regions such as parahippocampal and entorhinal cortex.
- By module, the APOE correlation was strongest in Module 3 (regions affected first), weaker in Module 2 and weakest in Module 1 (regions largely spared). For APOE the module correlation also grew from the stable CN to the CN to AD group. SORL1 followed a similar pattern. Splitting participants by APOE genotype (3/3, 3/4, 4/4) gave no significant correlations.
- Four of the ten genes (CD33, CLU, MEF2C, TREM2) are immune-related, and the authors read the pattern as support for an interaction between immune response and brain metabolism ("immunometabolism") in the disease.

## Assessment

- The gene expression data come from six donors of the Allen atlas, not from the imaged participants, and the donors' APOE genotype was not recorded. A correlation across 68 cortical regions of a group-average SUVR map with an expression map cannot say that expression drives metabolism; the authors say no causal relationship can be drawn.
- Cortical regions neighbouring each other share both expression and metabolic profile (spatial autocorrelation), so the per-gene P values across regions are probably too small. The whole-transcriptome null partly addresses this, but the three genes beyond two standard deviations have one-tailed P near 0.01 and no multiple-testing correction across ten genes is described.
- Only 15 people formed the CN to AD group and 21 the CN to MCI group, and the stratification used a strict five-year definition; the authors call for larger samples. Modularity per group is a single value from a correlation across participants, with no confidence interval or permutation test given in the text.
- The study population is old (mean 78 years); the authors expect the pattern may differ in younger people. The subcortical regions had no expression data, so the gene correlations cover cortex only.
- The risk gene list was reduced to ten by an atlas donor-consistency filter, so other known risk genes were left untested for technical reasons unrelated to their biology.
- Data are open (ADNI), but the participant ID list and code are available only on request.

## Open Questions

- Does the negative correlation of APOE expression with regional glucose metabolism hold when expression and FDG PET are measured in the same people (the study used atlas donors' expression)?
- Would younger adults or midlife APOE ε4 carriers show the same regional correlation of risk-gene expression with metabolism (the cohort was aged about 78 years on average)?
- Does the stronger metabolic modularity in women than in men reflect biology or longer lifespan and survivor effects (the groups were small and the CN to MCI group showed no difference)?
- Is the immune-gene correlation with metabolism explained by microglial energy metabolism, as the authors speculate (no cell-type-resolved data were used)?

## Connections

- Disease: [[Alzheimer disease]], [[Mild cognitive impairment]]
- Genes: [[APOE]], [[SORL1]], [[CD33]], [[CLU]], [[BIN1]], [[MAPT]], [[MEF2C]], [[FERMT2]], [[TREM2]], [[CELF1]]
- Methods: [[FDG PET]], [[Brain metabolic network modularity]], [[Allen Human Brain Atlas]]
- Related immune and glial biology: [[Neuroinflammation]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We then set out to determine the correlation between regional brain metabolism, particularly in the modules derived from the previous analysis, and the regional expression of Alzheimer-risk genes in the brain, obtained from the Allen Human Brain Atlas." |
| [[CD33]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We then set out to determine the correlation between regional brain metabolism, particularly in the modules derived from the previous analysis, and the regional expression of Alzheimer-risk genes in the brain, obtained from the Allen Human Brain Atlas." |
| [[SORL1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We then set out to determine the correlation between regional brain metabolism, particularly in the modules derived from the previous analysis, and the regional expression of Alzheimer-risk genes in the brain, obtained from the Allen Human Brain Atlas." |
| Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Measured in vivo with fluorodeoxyglucose (18F-FDG) PET, regional metabolism has been used to predict the conversion of mild cognitive impairment (MCI) to Alzheimer’s disease and even the likelihood that a cognitively normal (CN) individual will develop MCI or, later, Alzheimer’s disease." |
| [[Alzheimer disease]] (MESH:D000544) | biolink:associated_with | Glucose (CHEBI:17234; MESH:D005947) |  | "Alzheimer’s disease affects regional brain glucose metabolism early in the course of the disease and with a characteristic anatomic distribution, including posterior cingulate and temporo-parietal cortex." |
| Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) | biolink:biomarker_for | Mild cognitive impairment (MESH:D060825) |  | "Measured in vivo with fluorodeoxyglucose (18F-FDG) PET, regional metabolism has been used to predict the conversion of mild cognitive impairment (MCI) to Alzheimer’s disease and even the likelihood that a cognitively normal (CN) individual will develop MCI or, later, Alzheimer’s disease." |
| [[APOE]] | biolink:negatively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "Among the genes, APOE and CD33 showed the strongest negative correlation and SORL1 showed the strongest positive correlation with brain metabolism." |
| [[CD33]] | biolink:negatively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "Among the genes, APOE and CD33 showed the strongest negative correlation and SORL1 showed the strongest positive correlation with brain metabolism." |
| [[SORL1]] | biolink:positively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "Among the genes, APOE and CD33 showed the strongest negative correlation and SORL1 showed the strongest positive correlation with brain metabolism." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "More than 25 risk genes have been identified for Alzheimer’s disease, with APOE4 contributing the highest risk." |
| [[BIN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The mRNA expression of most Alzheimer-related genes correlated strongly with the mean FDG PET SUVR in all four groups, as well as a combination of all CN groups (‘CN to CN’, ‘CN to MCI’ and ‘CN to AD’ combined, referred to as ‘all CN’ group; Fig. 3)." |
| [[CLU]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The mRNA expression of most Alzheimer-related genes correlated strongly with the mean FDG PET SUVR in all four groups, as well as a combination of all CN groups (‘CN to CN’, ‘CN to MCI’ and ‘CN to AD’ combined, referred to as ‘all CN’ group; Fig. 3)." |
| [[CELF1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The mRNA expression of most Alzheimer-related genes correlated strongly with the mean FDG PET SUVR in all four groups, as well as a combination of all CN groups (‘CN to CN’, ‘CN to MCI’ and ‘CN to AD’ combined, referred to as ‘all CN’ group; Fig. 3)." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The mRNA expression of most Alzheimer-related genes correlated strongly with the mean FDG PET SUVR in all four groups, as well as a combination of all CN groups (‘CN to CN’, ‘CN to MCI’ and ‘CN to AD’ combined, referred to as ‘all CN’ group; Fig. 3)." |
| [[MEF2C]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The mRNA expression of most Alzheimer-related genes correlated strongly with the mean FDG PET SUVR in all four groups, as well as a combination of all CN groups (‘CN to CN’, ‘CN to MCI’ and ‘CN to AD’ combined, referred to as ‘all CN’ group; Fig. 3)." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The mRNA expression of most Alzheimer-related genes correlated strongly with the mean FDG PET SUVR in all four groups, as well as a combination of all CN groups (‘CN to CN’, ‘CN to MCI’ and ‘CN to AD’ combined, referred to as ‘all CN’ group; Fig. 3)." |
| PLEKHA1 (HGNC:14335) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The mRNA expression of most Alzheimer-related genes correlated strongly with the mean FDG PET SUVR in all four groups, as well as a combination of all CN groups (‘CN to CN’, ‘CN to MCI’ and ‘CN to AD’ combined, referred to as ‘all CN’ group; Fig. 3)." |
| [[BIN1]] | biolink:negatively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "All groups followed the same correlation pattern: (i) all genes showed significant correlations with FDG PET SUVR, except for CELF1 and MAPT; (ii) SORL1 and MEF2C positively correlated with FDG PET SUVR, while (iii) BIN1, CLU, TREM2, PLEKCH1, CD33, and APOE negatively correlated with FDG PET SUVR." |
| [[CLU]] | biolink:negatively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "All groups followed the same correlation pattern: (i) all genes showed significant correlations with FDG PET SUVR, except for CELF1 and MAPT; (ii) SORL1 and MEF2C positively correlated with FDG PET SUVR, while (iii) BIN1, CLU, TREM2, PLEKCH1, CD33, and APOE negatively correlated with FDG PET SUVR." |
| [[CELF1]] | NOT biolink:correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "All groups followed the same correlation pattern: (i) all genes showed significant correlations with FDG PET SUVR, except for CELF1 and MAPT; (ii) SORL1 and MEF2C positively correlated with FDG PET SUVR, while (iii) BIN1, CLU, TREM2, PLEKCH1, CD33, and APOE negatively correlated with FDG PET SUVR." |
| [[MAPT]] | NOT biolink:correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "All groups followed the same correlation pattern: (i) all genes showed significant correlations with FDG PET SUVR, except for CELF1 and MAPT; (ii) SORL1 and MEF2C positively correlated with FDG PET SUVR, while (iii) BIN1, CLU, TREM2, PLEKCH1, CD33, and APOE negatively correlated with FDG PET SUVR." |
| [[MEF2C]] | biolink:positively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "All groups followed the same correlation pattern: (i) all genes showed significant correlations with FDG PET SUVR, except for CELF1 and MAPT; (ii) SORL1 and MEF2C positively correlated with FDG PET SUVR, while (iii) BIN1, CLU, TREM2, PLEKCH1, CD33, and APOE negatively correlated with FDG PET SUVR." |
| [[TREM2]] | biolink:negatively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "All groups followed the same correlation pattern: (i) all genes showed significant correlations with FDG PET SUVR, except for CELF1 and MAPT; (ii) SORL1 and MEF2C positively correlated with FDG PET SUVR, while (iii) BIN1, CLU, TREM2, PLEKCH1, CD33, and APOE negatively correlated with FDG PET SUVR." |
| PLEKHA1 (HGNC:14335) | biolink:negatively_correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "All groups followed the same correlation pattern: (i) all genes showed significant correlations with FDG PET SUVR, except for CELF1 and MAPT; (ii) SORL1 and MEF2C positively correlated with FDG PET SUVR, while (iii) BIN1, CLU, TREM2, PLEKCH1, CD33, and APOE negatively correlated with FDG PET SUVR." |
| [[APOE]] | biolink:correlated_with | Glucose (CHEBI:17234; MESH:D005947) |  | "APOE, CD33 and SORL1 showed especially strong correlation with brain metabolism." |
| [[CD33]] | biolink:correlated_with | Glucose (CHEBI:17234; MESH:D005947) |  | "APOE, CD33 and SORL1 showed especially strong correlation with brain metabolism." |
| [[SORL1]] | biolink:correlated_with | Glucose (CHEBI:17234; MESH:D005947) |  | "APOE, CD33 and SORL1 showed especially strong correlation with brain metabolism." |
| [[FERMT2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The brain expression of 8 of the 10 Alzheimer-related genes had a significant correlation with brain metabolism across all four groups, and among them SORL1, FERMT2, CD33 and APOE showed a stronger absolute correlation with brain metabolism as risk for Alzheimer’s disease increased in CN participants (Fig. 3)." |
| Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We interpreted the correlation in FDG PET networks as metabolic co-activation." |
| [[FERMT2]] | biolink:correlated_with | Fludeoxyglucose F-18 (CHEBI:750387; MESH:D019788) |  | "The brain expression of 8 of the 10 Alzheimer-related genes had a significant correlation with brain metabolism across all four groups, and among them SORL1, FERMT2, CD33 and APOE showed a stronger absolute correlation with brain metabolism as risk for Alzheimer’s disease increased in CN participants (Fig. 3)." |
| [[APOE]] | biolink:affects | lipoprotein (CHEBI:6495; MESH:D008074) |  | "Though most studies focused on isoform-specific differences in structure and function, the main function of the ApoE protein, the redistribution of lipoproteins and cholesterol, is not sufficient to explain APOE’s detrimental effect in Alzheimer’s disease." |
| [[APOE]] | biolink:affects | cholesterol (CHEBI:16113; MESH:D002784) |  | "Though most studies focused on isoform-specific differences in structure and function, the main function of the ApoE protein, the redistribution of lipoproteins and cholesterol, is not sufficient to explain APOE’s detrimental effect in Alzheimer’s disease." |
| [[SORL1]] | biolink:physically_interacts_with | [[APOE]] |  | "Scherzer et al. suggested that SORL1 interacts with APOE as an encoder of the mosaic ApoE receptor." |
| [[APOE]] | biolink:negatively_correlated_with | Glucose (CHEBI:17234; MESH:D005947) |  | "Concordantly, we demonstrated that APOE had a strong negative correlation with brain glucose metabolism in an older population (Fig. 3)." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Its isoform, APOE ε4, is the strongest genetic risk factor for Alzheimer’s disease." |
| [[SORL1]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "They observed a significant reduction in SORL1 expression in brain tissue of Alzheimer’s disease patients, postulating a protective effect of SORL1." |
| [[CD33]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The strong negative correlation between CD33 expression and FDG PET SUVR observed here (Fig. 3) echoed the finding that elevated CD33 expression may increase risk for Alzheimer’s disease." |
| [[SORL1]] | biolink:associated_with | [[LDLR]] |  | "SORL1 encodes a mosaic protein of the low-density lipoprotein receptor family." |
| [[SORL1]] | biolink:positively_correlated_with | Glucose (CHEBI:17234; MESH:D005947) |  | "Our results support this postulate, as we observed the strongest positive correlation between SORL1 mRNA expression and brain glucose metabolism, opposite the direction of correlation between APOE and metabolism." |
| [[CD33]] | biolink:directly_physically_interacts_with | sialic acid (CHEBI:26667; MESH:D019158) |  | "CD33 is a sialic acid-binding immunoglobulin-like lectin that regulates innate immunity." |
| [[CD33]] | biolink:negatively_correlated_with | Glucose (CHEBI:17234; MESH:D005947) |  | "Higher CD33 expression corresponds to hypometabolism in the brain, which is associated with Alzheimer’s disease, though no causal relationship can be derived from the correlation." |
| [[APOE]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "While others have investigated differential expression of APOE and SORL1 between brain regions susceptible to Alzheimer’s disease and brain regions resistant to Alzheimer’s disease, evidence presented here point out that these genes may contribute to the regional vulnerability of human brain to Alzheimer’s disease pathology through interaction with brain metabolism." |
| [[SORL1]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "While others have investigated differential expression of APOE and SORL1 between brain regions susceptible to Alzheimer’s disease and brain regions resistant to Alzheimer’s disease, evidence presented here point out that these genes may contribute to the regional vulnerability of human brain to Alzheimer’s disease pathology through interaction with brain metabolism." |
