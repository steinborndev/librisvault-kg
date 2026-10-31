---
type: source
title: "CR1, CLU and PICALM CpG island shore hypomethylation in Japanese Alzheimer blood"
paper_title: "Lower DNA methylation levels in CpG island shores of CR1, CLU, and PICALM in the blood of Japanese Alzheimer’s disease patients"
domain: neuroscience
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001393
pmid: "32991610"
pmcid: "PMC7523949"
doi: "10.1371/journal.pone.0239196"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC7523949/"
sources: ["[[.raw/01M4P89VC9CX3KB3RY6S3TMT4Y/normalized.md]]"]
tags: [epigenetics, biomarker]
---

# CR1, CLU and PICALM CpG island shore hypomethylation in Japanese Alzheimer blood

Case-control study of [[DNA methylation]] at the [[CpG island shore]] of six genes from the top of the late-onset [[Alzheimer disease]] genome-wide association meta-analysis ([[APOE]], [[BIN1]], [[PICALM]], [[CR1]], [[CLU]], [[ABCA7]]) in peripheral blood DNA from the National Center for Geriatrics and Gerontology biobank in Japan. [[TREM2]] was added as a replication of an earlier blood hypomethylation report.

## Design

- 293 people over 60: 96 with Alzheimer disease, 96 cognitively normal controls (Mini-Mental State Examination above 25), and 40 [[Vascular dementia]], 34 [[Dementia with Lewy bodies]] and 27 [[Frontotemporal dementia]] patients as disease comparators.
- The 48 Alzheimer patients and 48 age- and sex-matched controls were split into a test set and a replication set of the same size.
- Methylation was read by [[Bisulfite sequencing PCR]]: about 450 bp amplicons cloned and sequenced from 32 colonies, at least 20 clones per sample analysed with QUMA. Pyrosequencing (about 50 bp) was used only to confirm CLU and for TREM2.
- Target regions were chosen from CpG density plots drawn with the authors' own tool, CyGnusPlotter, as lightly (about 10%) to moderately (about 50%) methylated stretches flanking each promoter CpG island.
- Three GWAS variants were genotyped in 148 samples (80 Alzheimer, 68 control): [[CR1 rs3818361]], [[CLU rs11136000]] and [[PICALM rs3851179]]. Blood RNA sequencing of 32 samples (5 Alzheimer, 27 control) gave TMM-normalised expression.
- Group comparisons used Student t-test with Bonferroni-corrected thresholds (p below 0.00625 and 0.00125); classification used multiple logistic regression with APOE ε4 allele number as covariate, ROC curves and the DeLong test.

## Findings

- Mean methylation was significantly lower in Alzheimer blood at the shores of CR1, CLU and PICALM, and not different at APOE, BIN1 or ABCA7. The mean differences were all under 10%, and no single CpG survived Bonferroni correction on its own (threshold p below 0.88 x 10^-3).
- Absence of a difference in APOE and the CLU hypomethylation were reproduced in the replication set; CLU hypomethylation was confirmed by pyrosequencing in both sets. The TREM2 shore was also lower in Alzheimer blood, matching the earlier report.
- Methylation of the three genes did not track expression: linear regression of CR1, CLU and PICALM RNA-seq values on shore methylation was non-significant in 32 samples, although CLU transcript was said to be high in Alzheimer blood.
- None of the three GWAS variants affected methylation, so they are not [[Methylation quantitative trait locus]] variants. APOE ε4 homozygotes, by contrast, showed higher methylation at the APOE shore, a small difference the authors treat as tentative.
- Methylation of CR1, CLU and PICALM correlated with neither Mini-Mental State Examination score nor age, so it did not follow disease severity or ageing.
- CLU shore methylation was also lower in dementia with Lewy bodies but not in vascular or frontotemporal dementia; APOE methylation differed in none.
- Using two public resources of matched blood and brain methylation (BECon and the Blood Brain DNA methylation Comparison Tool, both on the Illumina 450K array), blood methylation at the five probes covering these regions did not correlate with brain methylation, except one PICALM CpG in the entorhinal cortex. See [[Blood-brain DNA methylation concordance]].
- Classification: CLU methylation alone gave an AUC of 0.66 (replication set) and 0.69 (test set); APOE ε4 allele number alone 0.78 and 0.73; the combination 0.85 and 0.80 (replication model applied to the test set), better than ε4 alone in both (DeLong p = 0.0083 and 0.0064). Sensitivity and specificity did not reach the 80% benchmark proposed for an ideal Alzheimer biomarker.

## Why This Source Matters

Genome-wide blood methylation arrays had not flagged CR1, CLU or PICALM; this targeted, clone-level sequencing of the shore regions finds small but consistent hypomethylation in three of six risk genes and ties CLU methylation to a modest gain in discrimination over APOE genotype. The lack of any link to risk variants, severity, age or expression, and to brain methylation, leaves open whether it is a cause, a peripheral response or a biomarker only.

## Assessment

- Small samples (48 per arm per set; 32 for expression) and effects under 10% mean the individual CpG tests were underpowered after multiple-testing correction; the authors invoke type II error for the null expression and APOE findings.
- The abstract gives AUCs of 0.84 and 0.80 for the test and replication analyses, while the results text gives 0.83 and 0.85 for models fitted in each set and the figure legend 0.85 and 0.80; the figures agree on the combined model's range but the labelling of sets is inconsistent.
- The "replication" model was fitted in the replication set and then applied to the test set, so the 0.80 is not an independent validation of a model built in the test set.
- Brain concordance was inferred in silico from other individuals' arrays, since no matched brain tissue was available; probe coverage was five CpGs.
- Single population (western and middle Japan) and clinical diagnosis only; DLB hypomethylation may reflect Alzheimer co-pathology or misclassification, as the authors note.

## Open Questions

- Is CLU shore hypomethylation in blood present before symptom onset in longitudinal samples (all participants were cross-sectional and methylation did not track Mini-Mental State Examination score)?
- Do CR1, CLU and PICALM shore methylation differences replicate in non-Japanese blood cohorts (only one Japanese biobank was studied)?
- Does lower shore methylation raise CR1, CLU or PICALM transcript in blood of a larger sample (the 32-sample RNA-seq test was non-significant and probably underpowered)?
- Is CLU hypomethylation in dementia with Lewy bodies independent of coexisting Alzheimer pathology (diagnosis was clinical, with 34 patients)?
- Does a higher APOE shore methylation in ε4 homozygotes hold in a larger sample (the difference was small and earlier studies of adjacent CpGs found none)?

## Connections

- Disease: [[Alzheimer disease]], [[Late-onset Alzheimer disease]], [[Dementia with Lewy bodies]], [[Vascular dementia]], [[Frontotemporal dementia]]
- Genes: [[CR1]], [[CLU]], [[PICALM]], [[APOE]], [[TREM2]], [[BIN1]], [[ABCA7]]
- Variants: [[CR1 rs3818361]], [[CLU rs11136000]], [[PICALM rs3851179]]
- Methods and concepts: [[DNA methylation]], [[CpG island shore]], [[Bisulfite sequencing PCR]], [[Methylation quantitative trait locus]], [[Blood-brain DNA methylation concordance]], [[Genome-wide association study]]
- Other blood methylation work on Alzheimer risk genes: [[BIN1 promoter hypomethylation in blood and preclinical Alzheimer disease]], [[Network-based integration of Alzheimer GWAS and DNA methylation finds BIN1 and GNAS module]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[CR1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The aim of the present study was to (1) investigate the relationship between late-onset Alzheimer’s disease (AD) and DNA methylation levels in six of the top seven AD-associated genes identified through a meta-analysis of recent genome wide association studies, APOE, BIN1, PICALM, CR1, CLU, and ABCA7, in blood, and (2) examine its applicability to the diagnosis of AD." |
| [[CLU]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The aim of the present study was to (1) investigate the relationship between late-onset Alzheimer’s disease (AD) and DNA methylation levels in six of the top seven AD-associated genes identified through a meta-analysis of recent genome wide association studies, APOE, BIN1, PICALM, CR1, CLU, and ABCA7, in blood, and (2) examine its applicability to the diagnosis of AD." |
| [[PICALM]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The aim of the present study was to (1) investigate the relationship between late-onset Alzheimer’s disease (AD) and DNA methylation levels in six of the top seven AD-associated genes identified through a meta-analysis of recent genome wide association studies, APOE, BIN1, PICALM, CR1, CLU, and ABCA7, in blood, and (2) examine its applicability to the diagnosis of AD." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The aim of the present study was to (1) investigate the relationship between late-onset Alzheimer’s disease (AD) and DNA methylation levels in six of the top seven AD-associated genes identified through a meta-analysis of recent genome wide association studies, APOE, BIN1, PICALM, CR1, CLU, and ABCA7, in blood, and (2) examine its applicability to the diagnosis of AD." |
| [[BIN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The aim of the present study was to (1) investigate the relationship between late-onset Alzheimer’s disease (AD) and DNA methylation levels in six of the top seven AD-associated genes identified through a meta-analysis of recent genome wide association studies, APOE, BIN1, PICALM, CR1, CLU, and ABCA7, in blood, and (2) examine its applicability to the diagnosis of AD." |
| [[ABCA7]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The aim of the present study was to (1) investigate the relationship between late-onset Alzheimer’s disease (AD) and DNA methylation levels in six of the top seven AD-associated genes identified through a meta-analysis of recent genome wide association studies, APOE, BIN1, PICALM, CR1, CLU, and ABCA7, in blood, and (2) examine its applicability to the diagnosis of AD." |
| single nucleotide polymorphism (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We assumed that DMRs in AD-associated genes, such as those identified by genome-wide association studies (GWASs), in the brain or any other tissues confer susceptibility to the onset of AD through subtle, but long-lasting expression changes in these genes, similar to single nucleotide polymorphisms (SNPs)." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "AD-related hypomethylation in blood samples was also reported for TREM2 (Triggering receptor expressed on myeloid cells 2), another AD-associated gene." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "We, however, found that APOE ε4, the highest risk allele of AD, may be a mQTL because a higher methylation level was detected in the ε4 hyomozygotes (S9 Fig)." |
| [[Methylation quantitative trait locus]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Previous studies suggested that DNA methylation acts as an intermediary of genetic risk and mQTLs associated with AD have been reported." |
| [[APOE]] | biolink:associated_with | [[Methylation quantitative trait locus]] |  | "We, however, found that APOE ε4, the highest risk allele of AD, may be a mQTL because a higher methylation level was detected in the ε4 hyomozygotes (S9 Fig)." |
| [[CLU]] | biolink:associated_with | [[Dementia with Lewy bodies]] |  | "Although no significant differences were observed in the methylation levels of APOE between the control and any dementia (Fig 5A), CLU methylation levels were lower in DLB than in the control, similar to AD samples (Fig 5B)." |
| [[CLU]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "This suggests that CLU hypomethylation is related to limited types of dementia." |
| [[APOE]] | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Although no significant differences were observed in the methylation levels of APOE between the control and any dementia (Fig 5A), CLU methylation levels were lower in DLB than in the control, similar to AD samples (Fig 5B)." |
| [[APOE]] | NOT biolink:associated_with | [[Dementia with Lewy bodies]] |  | "Although no significant differences were observed in the methylation levels of APOE between the control and any dementia (Fig 5A), CLU methylation levels were lower in DLB than in the control, similar to AD samples (Fig 5B)." |
| [[APOE]] | NOT biolink:associated_with | [[Vascular dementia]] (MESH:D015140) |  | "Although no significant differences were observed in the methylation levels of APOE between the control and any dementia (Fig 5A), CLU methylation levels were lower in DLB than in the control, similar to AD samples (Fig 5B)." |
| [[APOE]] | NOT biolink:associated_with | [[Frontotemporal dementia]] (MESH:D057180) |  | "Although no significant differences were observed in the methylation levels of APOE between the control and any dementia (Fig 5A), CLU methylation levels were lower in DLB than in the control, similar to AD samples (Fig 5B)." |
| [[APOE]] | NOT biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Although no significant differences were observed in the methylation levels of APOE between the control and any dementia (Fig 5A), CLU methylation levels were lower in DLB than in the control, similar to AD samples (Fig 5B)." |
| [[CR1 rs3818361]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Methylation rates in AD-associated DMR in CR1, CLU, and PICALM were plotted against the genotypes of AD-associated SNPs in CR1 (rs3818361) (A) and CLU (rs11136000), (B) and upstream of PICALM (rs3851179) (C)." |
| [[CLU rs11136000]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Methylation rates in AD-associated DMR in CR1, CLU, and PICALM were plotted against the genotypes of AD-associated SNPs in CR1 (rs3818361) (A) and CLU (rs11136000), (B) and upstream of PICALM (rs3851179) (C)." |
| [[PICALM rs3851179]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Methylation rates in AD-associated DMR in CR1, CLU, and PICALM were plotted against the genotypes of AD-associated SNPs in CR1 (rs3818361) (A) and CLU (rs11136000), (B) and upstream of PICALM (rs3851179) (C)." |
| [[TOMM40]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Absence of methylation differences in the same region in ABCA7, as we surveyed, or upstream of a possible AD-associated gene, TOMMO40, was reported by another group." |
| CpG dinucleotide (CHEBI:47885; MESH:C015772) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Alternatively, AD-associated DNA methylation changes may develop in a tissue-specific manner because CpG dinucleotides with AD pathology-related methylation were found in the ABCA7 and BIN1 loci in the brain DNA." |
| [[APOE]] | biolink:affects | CpG dinucleotide (CHEBI:47885; MESH:C015772) | direction=increased | "Contrary to these observations, we found an AD-related mQTL in APOE: a higher methylation level at the CpG island shore of APOE when the risk allele, ε4, was homozygous (S9 Fig), which suggests that APOE ε4 confers susceptibility to AD synergistically with methylation at the CpG island shore." |
| [[CLU]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "We demonstrated that in combination with the APOE genotype, CLU methylation in CpG island shores provides good predictive performance for the diagnosis of AD in our subjects." |
| [[CLU]] | NOT biolink:associated_with | Vascular dementia (MONDO:1040011; MESH:D015140) |  | "Furthermore, we discovered that the hypomethylation of CLU occurred in the blood of DLB, but not in VaD or FTD." |
| [[CLU]] | NOT biolink:associated_with | [[Frontotemporal dementia]] (MESH:D057180) |  | "Furthermore, we discovered that the hypomethylation of CLU occurred in the blood of DLB, but not in VaD or FTD." |
| ANK1 (HGNC:492) | biolink:associated_with | Neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Neurodegenerative disease-specific differential DNA methylation has also been reported for ANK1." |
| [[APOE]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ideal biomarkers for AD were proposed to have a sensitivity and specificity of >80%; however, the diagnostic ability obtained by the combinatorial use of CLU methylation and the APOE genotype did not meet these criteria." |
