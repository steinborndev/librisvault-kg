---
type: source
title: "Late-onset Alzheimer disease association study in the Russian population"
paper_title: "Association and Gene-Gene Interactions Study of Late-Onset Alzheimer’s Disease in the Russian Population"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000082
pmid: "34681041"
pmcid: "PMC8535278"
doi: "10.3390/genes12101647"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8535278/"
sources: ["[[.raw/01M4DY94F8N8F41AYK95R2C26A/normalized.md]]"]
tags: [case-control, gwas-replication, snp-genotyping, alzheimer-risk-locus, gene-gene-interaction]
---

# Late-onset Alzheimer disease association study in the Russian population

A case-control study from Tomsk, Russia, that genotyped SNPs previously linked by genome-wide studies to Alzheimer disease, schizophrenia or cognition, and then looked for single-SNP, haplotype and gene-gene interaction effects on [[Late-onset Alzheimer disease]], plus a protein-protein interaction network of the genes tested.

## Design

- 185 unrelated patients with late-onset disease (mean age 72.2 years, onset at 65 or older; ICD-10-CM, DSM-IV TR and NINCDS-ADRDA criteria, with hippocampal atrophy on MRI) and 287 cognitively normal elderly Russian controls (mean age 71.8 years, MoCA score of 23 or more), all from the Tomsk region.
- Markers: SNPs with genome-wide significance (p < 5 x 10^-7) for cognition, Alzheimer disease or schizophrenia, minor allele frequency of 5% or more. 62 SNPs by iPLEX MALDI-TOF mass spectrometry; APOE rs7412 by TaqMan real-time PCR. After quality control (two SNPs with call rates under 87%, three out of Hardy-Weinberg equilibrium in controls), 58 SNPs were analysed.
- Chi-squared tests of allele and genotype frequencies with Benjamini-Hochberg false discovery rate correction; linkage disequilibrium and haplotypes in Haploview for eight SNPs of the APOE-TOMM40 region; [[Generalized multifactor dimensionality reduction]] for interactions; a STRING protein interaction network and Gene Ontology enrichment (PANTHER) for 41 genes.

## Findings

- Nine of 58 markers were nominally associated; after false discovery rate correction five remained, all on chromosome 19: [[TOMM40 rs2075650]], [[APOE rs429358]], [[APOE rs769449]], [[NECTIN2 rs6857]] (written "NECTIN" in the paper) and the [[APOE]] ε4 allele. FBXO40 rs3772130 and NECTIN2 rs6859 gave marginal p values only.
- The rs2075650 G allele frequency was 28% in these Russians, against 16% in other European populations in the 1000 Genomes project; the paper also reports lower-than-European frequencies for KLHL1 rs7984606 and DCHS2 rs1466662.
- Haplotypes of eight SNPs in the locus: two risk haplotypes (ATAGACCG, OR 1.90; ATAGACCA, OR 17.43 with a very wide interval of 2.24 to 135.62) and one protective haplotype (GCAAGTCA, OR 0.63), all surviving permutation testing. Cases showed a tighter linkage disequilibrium block joining rs429358 and rs7412 than controls.
- GMDR gave significant one-, two- and three-factor models. The lowest-risk two-factor combination was [[TCF4 rs17594526]] CC with APOE rs429358 TT (OR 0.25, 95% CI 0.14-0.45, p < 0.001); the three-factor model added [[CLU rs1532278]] CC, a roughly two-fold risk reduction, and was labelled preliminary because not all genotypes were available. The interaction involves TCF4 and CLU variants that showed no significant single-SNP association.
- The protein network had 24 nodes and 39 edges in three subnetworks centred on [[APOE]], [[CACNA1C]] and CTNNA2. Eight proteins had many links (APOE, [[SORL1]], [[APOC1]], [[CD33]], [[CLU]], [[TOMM40]], [[CNTNAP2]], CACNA1C), and [[RELN]], with APOE, CNTNAP2 and GRIN2B, bridged subnetworks. The gene set was enriched for cell adhesion molecule binding, neuron part and nervous system development.
- The discussion cites [[CR1]] as the strongest signal outside the APOE region in the genome-wide results it compares with (rs3818361, p = 6 x 10^-3); in this panel CR1 rs6656401 was not significant after correction.

## Why This Source Matters

It is a Russian-population replication that points to the APOE-TOMM40 region as the one robustly associated locus, with a notably high frequency of the TOMM40 rs2075650 risk allele, and shows how interaction and network analyses can add signals (TCF4, CLU) that single-SNP tests miss. The Russian population is far less studied than European or East Asian cohorts for Alzheimer genetics.

## Assessment

- The cohort is small (472 people), and the authors' own power estimate was 80% only for odds ratios of 1.5 or larger at common variants, so weaker effects are likely missed.
- Only the chromosome 19 signals survived correction; the TCF4 and CLU interaction rests on a preliminary three-factor model and on no single-SNP signal.
- The paper is inconsistent about counts: the abstract reports 63 SNPs, while the results analyse 58; STRING analysis covers 41 genes, while GMDR is described over 44; and a gene is written "NECTIN" where NECTIN2 is meant.
- The protein interaction network is exploratory; the authors say it needs preclinical and clinical validation.
- Markers were chosen from genome-wide studies of schizophrenia and cognition as well as Alzheimer disease, so the 58-marker panel is not a pure Alzheimer candidate set.

## Open Questions

- Does the high frequency of the TOMM40 rs2075650 G allele (28% against 16% in Europeans) hold in other Russian regions and in a larger cohort?
- Is the protective TCF4 rs17594526 CC with APOE rs429358 TT combination reproduced in an independent cohort of late-onset Alzheimer disease (the original three-factor model was labelled preliminary)?
- Does the APOE-TOMM40 haplotype structure explain risk independently of the APOE ε4 allele (the paper could not separate the two)?

## Connections

- Disease: [[Late-onset Alzheimer disease]], [[Alzheimer disease]]
- Genes: [[APOE]], [[TOMM40]], [[NECTIN2]], [[APOC1]], [[TCF4]], [[CLU]], [[CR1]], [[CD33]], [[SORL1]], [[CNTNAP2]], [[CACNA1C]], [[RELN]]
- Variants: [[TOMM40 rs2075650]], [[APOE rs429358]], [[APOE rs769449]], [[NECTIN2 rs6857]], [[TCF4 rs17594526]], [[CLU rs1532278]]
- Method: [[Generalized multifactor dimensionality reduction]]
- Related cohort study: [[SNP association study of Alzheimer disease in southern Chinese population]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[TOMM40]] | biolink:associated_with_increased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "The present study confirms the importance of the APOE-TOMM40 locus as the main risk locus of development and progress of LOAD in the Russian population." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "The present study confirms the importance of the APOE-TOMM40 locus as the main risk locus of development and progress of LOAD in the Russian population." |
| [[TOMM40 rs2075650]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We identified five genetic loci that were significantly associated with LOAD risk for the Russian population (TOMM40 rs2075650, APOE rs429358 and rs769449, NECTIN rs6857, APOE ε4)." |
| [[APOE rs429358]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We identified five genetic loci that were significantly associated with LOAD risk for the Russian population (TOMM40 rs2075650, APOE rs429358 and rs769449, NECTIN rs6857, APOE ε4)." |
| [[APOE rs769449]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We identified five genetic loci that were significantly associated with LOAD risk for the Russian population (TOMM40 rs2075650, APOE rs429358 and rs769449, NECTIN rs6857, APOE ε4)." |
| [[NECTIN2 rs6857]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We identified five genetic loci that were significantly associated with LOAD risk for the Russian population (TOMM40 rs2075650, APOE rs429358 and rs769449, NECTIN rs6857, APOE ε4)." |
| [[APOE]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We identified five genetic loci that were significantly associated with LOAD risk for the Russian population (TOMM40 rs2075650, APOE rs429358 and rs769449, NECTIN rs6857, APOE ε4)." |
| [[APP]] | biolink:contributes_to | Early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "The amyloid precursor protein (APP), presenilin1 (PSEN1), and presenilin2 (PSEN2) genes are primarily implicated in EOAD." |
| PSEN1 (HGNC:9508) | biolink:contributes_to | Early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "The amyloid precursor protein (APP), presenilin1 (PSEN1), and presenilin2 (PSEN2) genes are primarily implicated in EOAD." |
| PSEN2 (HGNC:9509) | biolink:contributes_to | Early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "The amyloid precursor protein (APP), presenilin1 (PSEN1), and presenilin2 (PSEN2) genes are primarily implicated in EOAD." |
| [[TOMM40]] | biolink:associated_with | [[APOE]] |  | "The present study confirms the importance of the APOE-TOMM40 locus as the main risk locus of development and progress of LOAD in the Russian population." |
| [[CLU]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, GWASs have identified many genomic loci characterized by small effect sizes associated with LOAD: CLU, CR1, PICALM, BIN1, ABCA7, CD33 and others." |
| [[CR1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, GWASs have identified many genomic loci characterized by small effect sizes associated with LOAD: CLU, CR1, PICALM, BIN1, ABCA7, CD33 and others." |
| PICALM (HGNC:15514) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, GWASs have identified many genomic loci characterized by small effect sizes associated with LOAD: CLU, CR1, PICALM, BIN1, ABCA7, CD33 and others." |
| BIN1 (HGNC:1052) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, GWASs have identified many genomic loci characterized by small effect sizes associated with LOAD: CLU, CR1, PICALM, BIN1, ABCA7, CD33 and others." |
| ABCA7 (HGNC:37) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, GWASs have identified many genomic loci characterized by small effect sizes associated with LOAD: CLU, CR1, PICALM, BIN1, ABCA7, CD33 and others." |
| [[CD33]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, GWASs have identified many genomic loci characterized by small effect sizes associated with LOAD: CLU, CR1, PICALM, BIN1, ABCA7, CD33 and others." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next-generation sequencing has assisted the identification of rare susceptibility modifying alleles in APP, TREM2, and PLD3." |
| TREM2 (HGNC:17761) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next-generation sequencing has assisted the identification of rare susceptibility modifying alleles in APP, TREM2, and PLD3." |
| PLD3 (HGNC:17158) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next-generation sequencing has assisted the identification of rare susceptibility modifying alleles in APP, TREM2, and PLD3." |
| rs3772130 (variant) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Power to detect an odds ratio of 1.5 or greater was 80% for six of the nine SNPs in Table 2, showing non-significant results after correction for multiple testing (FDR) for three studied variants: FBXO40 rs3772130, CR1 rs6656401, NECTIN2 rs6859." |
| rs6656401 (variant) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Power to detect an odds ratio of 1.5 or greater was 80% for six of the nine SNPs in Table 2, showing non-significant results after correction for multiple testing (FDR) for three studied variants: FBXO40 rs3772130, CR1 rs6656401, NECTIN2 rs6859." |
| rs6859 (variant) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Power to detect an odds ratio of 1.5 or greater was 80% for six of the nine SNPs in Table 2, showing non-significant results after correction for multiple testing (FDR) for three studied variants: FBXO40 rs3772130, CR1 rs6656401, NECTIN2 rs6859." |
| [[TOMM40]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "After correction for multiple testing the results remained statistically significant for five genetic variants in three genes: TOMM40 rs2075650, APOE ε4, rs429358 and rs769449, NECTIN rs6857 (Table 3)." |
| [[TCF4]] | biolink:genetically_interacts_with | [[APOE]] |  | "The combination of low-risk genotypes showed statistically significant differences between the studied groups: TCF4 rs17594526 “CC” and APOE rs429358 “TT” (p < 0.001; OR = 0.25; 95% CI: 0.14–0.45)." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "After correction for multiple testing the results remained statistically significant for five genetic variants in three genes: TOMM40 rs2075650, APOE ε4, rs429358 and rs769449, NECTIN rs6857 (Table 3)." |
| [[NECTIN2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "After correction for multiple testing the results remained statistically significant for five genetic variants in three genes: TOMM40 rs2075650, APOE ε4, rs429358 and rs769449, NECTIN rs6857 (Table 3)." |
| [[TCF4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The combination of low-risk genotypes showed statistically significant differences between the studied groups: TCF4 rs17594526 “CC” and APOE rs429358 “TT” (p < 0.001; OR = 0.25; 95% CI: 0.14–0.45)." |
| [[TOMM40 rs2075650]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "After correction for multiple testing the results remained statistically significant for five genetic variants in three genes: TOMM40 rs2075650, APOE ε4, rs429358 and rs769449, NECTIN rs6857 (Table 3)." |
| [[APOE rs429358]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "After correction for multiple testing the results remained statistically significant for five genetic variants in three genes: TOMM40 rs2075650, APOE ε4, rs429358 and rs769449, NECTIN rs6857 (Table 3)." |
| APOE rs7412 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Due to the fact that it is important for the LD analysis that the markers are in the same chromosome region, we included five SNPs in the LD analysis, which in our study were significantly associated with LOAD: TOMM40 rs2075650, APOE rs7412, rs429358 and rs769449, NECTIN rs6857." |
| [[APOE rs769449]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "After correction for multiple testing the results remained statistically significant for five genetic variants in three genes: TOMM40 rs2075650, APOE ε4, rs429358 and rs769449, NECTIN rs6857 (Table 3)." |
| [[NECTIN2 rs6857]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "After correction for multiple testing the results remained statistically significant for five genetic variants in three genes: TOMM40 rs2075650, APOE ε4, rs429358 and rs769449, NECTIN rs6857 (Table 3)." |
| NECTIN2 rs6859 (variant) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Markers TOMM40 rs157580, NECTIN rs6859, APOC1 rs4420638 were genotyped, but were not significantly associated with the LOAD in our study." |
| FBXO40 rs3772130 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Two variants demonstrated marginal p values for the allele and/or genotype frequency difference between the LOAD and control subjects: FBXO40 rs3772130 and NECTIN2 rs6859." |
| TOMM40 rs157580 (variant) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Markers TOMM40 rs157580, NECTIN rs6859, APOC1 rs4420638 were genotyped, but were not significantly associated with the LOAD in our study." |
| APOC1 rs4420638 (variant) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Markers TOMM40 rs157580, NECTIN rs6859, APOC1 rs4420638 were genotyped, but were not significantly associated with the LOAD in our study." |
| [[TCF4 rs17594526]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The combination of low-risk genotypes showed statistically significant differences between the studied groups: TCF4 rs17594526 “CC” and APOE rs429358 “TT” (p < 0.001; OR = 0.25; 95% CI: 0.14–0.45)." |
| [[TOMM40 rs2075650]] | biolink:correlated_with | [[NECTIN2 rs6857]] |  | "In controls, the first block consisted of four SNPs (rs6859, rs6857, rs157580, rs2075650) and the second included three SNPs (rs769449, rs429358, rs7412), while in the cases, the first block comprised four SNPs (rs6857, rs157580, rs2075650, rs769449) and the second block was made up of two closely located SNPs (rs429358, rs7412)." |
| [[TOMM40 rs2075650]] | biolink:correlated_with | TOMM40 rs157580 (variant) |  | "In controls, the first block consisted of four SNPs (rs6859, rs6857, rs157580, rs2075650) and the second included three SNPs (rs769449, rs429358, rs7412), while in the cases, the first block comprised four SNPs (rs6857, rs157580, rs2075650, rs769449) and the second block was made up of two closely located SNPs (rs429358, rs7412)." |
| [[APOE rs429358]] | biolink:correlated_with | APOE rs7412 (variant) |  | "Notably, this difference demonstrates the high level of LD in case group between rs429358 and rs7412 from the APOE gene, which are formed the APOE isoforms (ε2, ε3, ε4)." |
| [[NECTIN2 rs6857]] | biolink:correlated_with | TOMM40 rs157580 (variant) |  | "In controls, the first block consisted of four SNPs (rs6859, rs6857, rs157580, rs2075650) and the second included three SNPs (rs769449, rs429358, rs7412), while in the cases, the first block comprised four SNPs (rs6857, rs157580, rs2075650, rs769449) and the second block was made up of two closely located SNPs (rs429358, rs7412)." |
| [[APOE]] | biolink:physically_interacts_with | [[CD33]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | [[CR1]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | [[CLU]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | [[RELN]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | [[SORL1]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | [[NECTIN2]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | [[TOMM40]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | [[APOC1]] |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[APOE]] | biolink:physically_interacts_with | MPC2 (HGNC:24515) |  | "The first subnetwork consisted of 10 proteins with APOE in the center: CD33, CR1, CLU, RELN, SORL1, NECTIN2 (PRVL2), TOMM40, APOC, MPC2." |
| [[CR1]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "This gene is one of the ten highest risk factors for developing AD." |
| [[CACNA1C]] | biolink:physically_interacts_with | GRIN2B (HGNC:4586) |  | "The second subnetwork included 6 proteins with CACNA1C as the center component: GRIN2B, TENM4, CSMD1, NT5C2, POM121L2." |
| [[CACNA1C]] | biolink:physically_interacts_with | TENM4 (HGNC:29945) |  | "The second subnetwork included 6 proteins with CACNA1C as the center component: GRIN2B, TENM4, CSMD1, NT5C2, POM121L2." |
| [[CACNA1C]] | biolink:physically_interacts_with | CSMD1 (HGNC:14026) |  | "The second subnetwork included 6 proteins with CACNA1C as the center component: GRIN2B, TENM4, CSMD1, NT5C2, POM121L2." |
| [[CACNA1C]] | biolink:physically_interacts_with | NT5C2 (HGNC:8022) |  | "The second subnetwork included 6 proteins with CACNA1C as the center component: GRIN2B, TENM4, CSMD1, NT5C2, POM121L2." |
| [[CACNA1C]] | biolink:physically_interacts_with | POM121L2 (HGNC:13973) |  | "The second subnetwork included 6 proteins with CACNA1C as the center component: GRIN2B, TENM4, CSMD1, NT5C2, POM121L2." |
| CTNNA2 (HGNC:2510) | biolink:associated_with | FBXO40 (HGNC:29816) |  | "In addition, the third protein subgroup had 8 nodes with CTNNA2 in the center part: FBXO40, CNTN4, CTNNA2, CDON, CAMD2, TCF4, CHD6." |
| CTNNA2 (HGNC:2510) | biolink:associated_with | CNTN4 (HGNC:2174) |  | "In addition, the third protein subgroup had 8 nodes with CTNNA2 in the center part: FBXO40, CNTN4, CTNNA2, CDON, CAMD2, TCF4, CHD6." |
| CTNNA2 (HGNC:2510) | biolink:associated_with | CDON (HGNC:17104) |  | "In addition, the third protein subgroup had 8 nodes with CTNNA2 in the center part: FBXO40, CNTN4, CTNNA2, CDON, CAMD2, TCF4, CHD6." |
| CTNNA2 (HGNC:2510) | biolink:associated_with | CDH18 (HGNC:1757) |  | "In addition, the third protein subgroup had 8 nodes with CTNNA2 in the center part: FBXO40, CNTN4, CTNNA2, CDON, CAMD2, TCF4, CHD6." |
| CTNNA2 (HGNC:2510) | biolink:associated_with | [[TCF4]] |  | "In addition, the third protein subgroup had 8 nodes with CTNNA2 in the center part: FBXO40, CNTN4, CTNNA2, CDON, CAMD2, TCF4, CHD6." |
| CTNNA2 (HGNC:2510) | biolink:associated_with | CHD6 (HGNC:19057) |  | "In addition, the third protein subgroup had 8 nodes with CTNNA2 in the center part: FBXO40, CNTN4, CTNNA2, CDON, CAMD2, TCF4, CHD6." |
| rs3818361 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Outside the APOE region, the most significant association was found in CR1 gene on chromosome 1 (chr1:207611623, rs3818361, G/A, p = 6 × 10−3)." |
| [[APOE]] | biolink:genetically_interacts_with | [[CLU]] |  | "Notably, our data presented intergenic interaction between the three loci (CLU, TCF4, APOE), demonstrating no significant associations in our replicative analysis." |
| [[APOE]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, although APOE was identified as a susceptibility factor for LOAD over 25 years ago, it is still not clear how the ε4 allele contributes to disease risk." |
| [[APOE]] | biolink:contributes_to | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "In addition, although APOE was identified as a susceptibility factor for LOAD over 25 years ago, it is still not clear how the ε4 allele contributes to disease risk." |
| [[TOMM40]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Some observations indicate an independent effect of SNPs of the NECTIN2-TOMM40-APOE locus, while other studies showed that there are general effects of several SNPs." |
| [[TOMM40]] | biolink:associated_with | low-density lipoprotein cholesterol (CHEBI:47774; MESH:D008078) |  | "Salakhov et al. found that TOMM40 gene rs2075650 was associated with low-density lipoprotein cholesterol levels in healthy men group of the Russian population (Kemerovo, Russia), and G allele frequency in the total group was 21%." |
| [[NECTIN2]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Some observations indicate an independent effect of SNPs of the NECTIN2-TOMM40-APOE locus, while other studies showed that there are general effects of several SNPs." |
| [[CLU]] | biolink:genetically_interacts_with | [[TCF4]] |  | "Notably, our data presented intergenic interaction between the three loci (CLU, TCF4, APOE), demonstrating no significant associations in our replicative analysis." |
| [[TCF4]] | biolink:causes | Pitt-Hopkins syndrome (MONDO:0012589; MESH:C537403) |  | "The gene has been identified as the cause of Pitt-Hopkins syndrome (PTHS), and it has been implicated in various other neuropsychiatric diseases, including schizophrenia, autism and depression." |
| [[TCF4]] | biolink:associated_with | schizophrenia (MONDO:0005090; MESH:D012559) |  | "The gene has been identified as the cause of Pitt-Hopkins syndrome (PTHS), and it has been implicated in various other neuropsychiatric diseases, including schizophrenia, autism and depression." |
| [[TCF4]] | biolink:associated_with | autism (MONDO:0005260; MESH:D001321) |  | "The gene has been identified as the cause of Pitt-Hopkins syndrome (PTHS), and it has been implicated in various other neuropsychiatric diseases, including schizophrenia, autism and depression." |
| [[TCF4]] | biolink:associated_with | depression (MONDO:0002050) |  | "The gene has been identified as the cause of Pitt-Hopkins syndrome (PTHS), and it has been implicated in various other neuropsychiatric diseases, including schizophrenia, autism and depression." |
| [[TOMM40 rs2075650]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our study showed that the haplotypes that include the ε3 allele of APOE and the A allele of TOMM40 gene rs2075650 are associated with reduced risk for LOAD compared with haplotypes that include the ε4 allele of APOE and the G allele of rs2075650." |
| [[APOE rs429358]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Approximately two-fold reduced risk for LOAD was observed for the combination of CLU rs1532278 “CC”, TCF4 rs17594526 “CC”, APOE rs429358 “TT” genotypes in the three-locus model." |
| [[CLU rs1532278]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Approximately two-fold reduced risk for LOAD was observed for the combination of CLU rs1532278 “CC”, TCF4 rs17594526 “CC”, APOE rs429358 “TT” genotypes in the three-locus model." |
| [[TCF4 rs17594526]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Approximately two-fold reduced risk for LOAD was observed for the combination of CLU rs1532278 “CC”, TCF4 rs17594526 “CC”, APOE rs429358 “TT” genotypes in the three-locus model." |
| [[APOE]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, although APOE was identified as a susceptibility factor for LOAD over 25 years ago, it is still not clear how the ε4 allele contributes to disease risk." |
| APOE ε3 (variant) | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Our study showed that the haplotypes that include the ε3 allele of APOE and the A allele of TOMM40 gene rs2075650 are associated with reduced risk for LOAD compared with haplotypes that include the ε4 allele of APOE and the G allele of rs2075650." |
| [[TOMM40 rs2075650]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Our study showed that the haplotypes that include the ε3 allele of APOE and the A allele of TOMM40 gene rs2075650 are associated with reduced risk for LOAD compared with haplotypes that include the ε4 allele of APOE and the G allele of rs2075650." |
| [[APOE rs429358]] | biolink:associated_with_decreased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Approximately two-fold reduced risk for LOAD was observed for the combination of CLU rs1532278 “CC”, TCF4 rs17594526 “CC”, APOE rs429358 “TT” genotypes in the three-locus model." |
| [[CLU rs1532278]] | biolink:associated_with_decreased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Approximately two-fold reduced risk for LOAD was observed for the combination of CLU rs1532278 “CC”, TCF4 rs17594526 “CC”, APOE rs429358 “TT” genotypes in the three-locus model." |
| [[TCF4 rs17594526]] | biolink:associated_with_decreased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Approximately two-fold reduced risk for LOAD was observed for the combination of CLU rs1532278 “CC”, TCF4 rs17594526 “CC”, APOE rs429358 “TT” genotypes in the three-locus model." |
| [[APOE]] | biolink:contributes_to | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "In addition, although APOE was identified as a susceptibility factor for LOAD over 25 years ago, it is still not clear how the ε4 allele contributes to disease risk." |
| APOE ε3 (variant) | biolink:associated_with_decreased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Our study showed that the haplotypes that include the ε3 allele of APOE and the A allele of TOMM40 gene rs2075650 are associated with reduced risk for LOAD compared with haplotypes that include the ε4 allele of APOE and the G allele of rs2075650." |
| [[TOMM40 rs2075650]] | biolink:associated_with | low-density lipoprotein cholesterol (CHEBI:47774; MESH:D008078) |  | "Salakhov et al. found that TOMM40 gene rs2075650 was associated with low-density lipoprotein cholesterol levels in healthy men group of the Russian population (Kemerovo, Russia), and G allele frequency in the total group was 21%." |
| rs157580 (variant) | biolink:correlated_with | [[TOMM40 rs2075650]] |  | "Our data demonstrated that in both the cases and the controls rs157580 of TOMM40 gene is in high pairwise LD with the SNPs rs2075650 and rs769449 (D’ = 100)." |
| [[TOMM40 rs2075650]] | biolink:correlated_with | [[APOE]] |  | "Our study showed that the haplotypes that include the ε3 allele of APOE and the A allele of TOMM40 gene rs2075650 are associated with reduced risk for LOAD compared with haplotypes that include the ε4 allele of APOE and the G allele of rs2075650." |
| rs157580 (variant) | biolink:correlated_with | [[APOE rs769449]] |  | "Our data demonstrated that in both the cases and the controls rs157580 of TOMM40 gene is in high pairwise LD with the SNPs rs2075650 and rs769449 (D’ = 100)." |
| [[APOE rs429358]] | biolink:associated_with | [[APOE]] |  | "Notably, the haplotype block structure for cases demonstrates that Block2 included rs429358 and rs7412 from the APOE gene, which are formed the APOE isoforms (ε2, ε3, ε4)." |
| [[APOE rs429358]] | biolink:associated_with | APOE ε3 (variant) |  | "Notably, the haplotype block structure for cases demonstrates that Block2 included rs429358 and rs7412 from the APOE gene, which are formed the APOE isoforms (ε2, ε3, ε4)." |
| [[APOE rs429358]] | biolink:associated_with | APOE ε2 (variant) |  | "Notably, the haplotype block structure for cases demonstrates that Block2 included rs429358 and rs7412 from the APOE gene, which are formed the APOE isoforms (ε2, ε3, ε4)." |
| rs7412 (variant) | biolink:associated_with | [[APOE]] |  | "Notably, the haplotype block structure for cases demonstrates that Block2 included rs429358 and rs7412 from the APOE gene, which are formed the APOE isoforms (ε2, ε3, ε4)." |
| rs7412 (variant) | biolink:associated_with | APOE ε3 (variant) |  | "Notably, the haplotype block structure for cases demonstrates that Block2 included rs429358 and rs7412 from the APOE gene, which are formed the APOE isoforms (ε2, ε3, ε4)." |
| rs7412 (variant) | biolink:associated_with | APOE ε2 (variant) |  | "Notably, the haplotype block structure for cases demonstrates that Block2 included rs429358 and rs7412 from the APOE gene, which are formed the APOE isoforms (ε2, ε3, ε4)." |
| [[APOE]] | biolink:associated_with | [[NECTIN2]] |  | "The structure of linkage disequilibrium in the genomic region of the NECTIN2-TOMM40-APOE locus" |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The present study confirmed the importance of the APOE-TOMM40 locus as the main risk locus of development and progress of LOAD." |
| [[TOMM40]] | biolink:associated_with | [[NECTIN2]] |  | "The structure of linkage disequilibrium in the genomic region of the NECTIN2-TOMM40-APOE locus" |
| [[TOMM40]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The present study confirmed the importance of the APOE-TOMM40 locus as the main risk locus of development and progress of LOAD." |
| [[CACNA1C]] | biolink:associated_with | schizophrenia (MONDO:0005090; MESH:D012559) |  | "these proteins were connected through publication studies with psychiatric diseases, such as schizophrenia, bipolar disorder, depression, and others" |
| [[CACNA1C]] | biolink:associated_with | bipolar disorder (MONDO:0004985; MESH:D001714) |  | "these proteins were connected through publication studies with psychiatric diseases, such as schizophrenia, bipolar disorder, depression, and others" |
| [[CACNA1C]] | biolink:associated_with | depression (MONDO:0002050) |  | "these proteins were connected through publication studies with psychiatric diseases, such as schizophrenia, bipolar disorder, depression, and others" |
| [[CACNA1C]] | biolink:associated_with | psychiatric disorders (MESH:D001523) |  | "these proteins were connected through publication studies with psychiatric diseases, such as schizophrenia, bipolar disorder, depression, and others" |
| [[RELN]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Presumably, Reelin plays a significant role both in AD and in psychiatric disorders." |
| [[RELN]] | biolink:contributes_to | psychiatric disorders (MESH:D001523) |  | "Presumably, Reelin plays a significant role both in AD and in psychiatric disorders." |
| [[RELN]] | biolink:contributes_to | psychiatric disorder (HP:0000708; MESH:D001523) |  | "Presumably, Reelin plays a significant role both in AD and in psychiatric disorders." |
| [[APOE rs429358]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Strong evidence for association with LOAD was seen for the APOE-4 polymorphism, as well as for rs429358, rs769449 and rs2075650, using various approaches" |
| [[RELN]] | biolink:associated_with | [[APOE]] |  | "All these three subsystems are connected together by RELN as a bridge." |
| [[RELN]] | biolink:associated_with | [[CACNA1C]] |  | "All these three subsystems are connected together by RELN as a bridge." |
| [[RELN]] | biolink:associated_with | CTNNA2 (HGNC:2510) |  | "All these three subsystems are connected together by RELN as a bridge." |
