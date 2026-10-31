---
type: source
title: "SNP association study of Alzheimer disease in southern Chinese population"
paper_title: "Genetic Association of FERMT2, HLA-DRB1, CD2AP, and PTK2B Polymorphisms With Alzheimer’s Disease Risk in the Southern Chinese Population"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000018
pmid: "32116649"
pmcid: "PMC7010721"
doi: "10.3389/fnagi.2020.00016"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC7010721/"
sources: ["[[.raw/01M4DY94A1JK4447G7VWMHHDF0/normalized.md]]"]
tags: [case-control, gwas-replication, eqtl, snp-genotyping, alzheimer-risk-locus]
---

# SNP association study of Alzheimer disease in southern Chinese population

A single-centre case-control study (Ruijin Hospital, Shanghai) that tested 18 SNPs, picked from European-ancestry genome-wide association studies, for association with [[Alzheimer disease]] in a southern Chinese cohort, and followed the leading hits up with brain expression data.

## Design

- 215 patients with probable Alzheimer disease (NINCDS-ADRDA criteria; recruited September 2016 to March 2019) and 205 sex- and age-matched cognitively healthy controls.
- Genotyping by SNaPshot multiplex extension and PCR; APOE (rs429358, rs7412) by PCR-RFLP.
- Logistic regression adjusted for age and sex under dominant, recessive, overdominant and additive models, with Bonferroni correction; analyses stratified by [[APOE]] ε4 carrier status and by age at onset (49 cases, 22.79%, had [[Early-onset Alzheimer disease]], onset before 65 years).
- Expression quantitative trait locus (eQTL) look-up in GTEx and the Braineac dataset (10 brain regions, 134 post-mortem donors of European descent).

## Findings

- [[FERMT2 rs17125924]]: the G-allele raised risk in the dominant (OR 1.57, 95% CI 1.07-2.32, P = 0.022) and overdominant (OR 1.76, 95% CI 1.18-2.61, P = 0.005) models. Among APOE ε4 carriers the allele frequency differed between cases and controls (OR 1.895, P = 0.029) and the dominant model was stronger (OR 2.739, P = 0.009). No effect on FERMT2 brain expression was seen.
- [[HLA-DRB1 rs9271058]]: associated with early-onset disease (allele OR 2.038, P = 0.011; dominant OR 2.563). The AA genotype went with higher HLA-DRB1 expression in many GTEx brain regions.
- [[CD2AP rs9473117]]: associated with early-onset disease with an OR below 1 (dominant OR 0.327, P = 0.035). The C-allele raised CD2AP expression in thalamus and cerebellar cortex in Braineac.
- [[PTK2B rs73223431]]: associated with early-onset disease (dominant OR 3.108, P = 0.007). The TT genotype raised PTK2B expression in temporal cortex.
- [[APH1B rs35408871]]: recessive-model association with early-onset disease (OR 0.36, P = 0.047), suggesting protection for G-allele homozygotes.
- [[EPHA1 rs11763230]]: recessive-model association with late-onset disease only (OR 0.111, P = 0.046), suggesting protection for T-allele homozygotes.
- The remaining 12 SNPs, including the two ADAM10 variants, did not replicate.
- No association survived Bonferroni correction.

## Why This Source Matters

It is a replication attempt in an East Asian cohort of loci found in European-ancestry studies, and it reports what appears to be the first link between a PTK2B variant and early-onset disease. It also pairs each genetic signal with brain eQTL data for [[HLA-DRB1]], [[CD2AP]] and [[PTK2B]].

## Assessment

- The cohort is small and single-centre, and the early-onset subgroup has only 49 patients, so the subgroup odds ratios are imprecise.
- Every reported association was nominal (P between 0.005 and 0.049) and lost significance after Bonferroni correction, so the findings are hypothesis-generating.
- The eQTL data come from donors of European descent (Braineac) and a mixed non-diseased panel (GTEx), not from the Chinese cohort studied.
- The text gives two variant identifiers inconsistently (rs1715924 in the results and conclusion, rs17125944 in the discussion); the abstract and methods use rs17125924, which is used throughout this wiki.

## Open Questions

- Does the FERMT2 rs17125924 association with Alzheimer disease, and its stronger effect in APOE ε4 carriers, replicate in a larger East Asian cohort (the original study had 215 cases and its signal did not survive Bonferroni correction)?
- Do HLA-DRB1 rs9271058, CD2AP rs9473117 and PTK2B rs73223431 associate with early-onset Alzheimer disease in a cohort with more than 49 early-onset cases (the original subgroup was small)?
- Is the brain eQTL effect of rs9473117 on CD2AP expression seen in East Asian donors (the data used came from European-descent donors)?

## Connections

- Disease: [[Alzheimer disease]], [[Early-onset Alzheimer disease]]
- Genes: [[FERMT2]], [[HLA-DRB1]], [[CD2AP]], [[PTK2B]], [[APOE]], [[APH1B]], [[EPHA1]]
- Variants: [[FERMT2 rs17125924]], [[HLA-DRB1 rs9271058]], [[CD2AP rs9473117]], [[PTK2B rs73223431]], [[APH1B rs35408871]], [[EPHA1 rs11763230]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[FERMT2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our study found that rs17125924 of FERMT2 was associated with the risk of developing AD in the dominant (P = 0.022, odds ratio [OR] = 1.57, 95% confidence interval [CI]: 1.07–2.32) and overdominant (P = 0.005, OR = 1.76, 95% CI: 1.18–2.61) models." |
| [[HLA-DRB1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The rs9271058 of HLA-DRB1 (dominant, overdominant, and additive models), rs9473117 of CD2AP (dominant and additive models), and rs73223431 of PTK2B (dominant, overdominant, and additive models) were associated with early onset AD (EOAD)." |
| [[CD2AP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Meta-analyses of GWAS in populations of European ancestry have identified multiple susceptibility genes associated with AD, such as CLU, CR1, MS4A4, CD2AP, CD33, and EPHA1." |
| [[PTK2B]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The rs9271058 of HLA-DRB1 (dominant, overdominant, and additive models), rs9473117 of CD2AP (dominant and additive models), and rs73223431 of PTK2B (dominant, overdominant, and additive models) were associated with early onset AD (EOAD)." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The apolipoprotein E (APOE) ε4 allele, which plays a vital role in liquid absorption and redistribution, is regarded as the strongest genetic risk factor for LOAD." |
| CLU (HGNC:2095) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Meta-analyses of GWAS in populations of European ancestry have identified multiple susceptibility genes associated with AD, such as CLU, CR1, MS4A4, CD2AP, CD33, and EPHA1." |
| CR1 (HGNC:2334) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Meta-analyses of GWAS in populations of European ancestry have identified multiple susceptibility genes associated with AD, such as CLU, CR1, MS4A4, CD2AP, CD33, and EPHA1." |
| MS4A4A (HGNC:13371) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Meta-analyses of GWAS in populations of European ancestry have identified multiple susceptibility genes associated with AD, such as CLU, CR1, MS4A4, CD2AP, CD33, and EPHA1." |
| CD33 (HGNC:1659) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Meta-analyses of GWAS in populations of European ancestry have identified multiple susceptibility genes associated with AD, such as CLU, CR1, MS4A4, CD2AP, CD33, and EPHA1." |
| [[EPHA1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Meta-analyses of GWAS in populations of European ancestry have identified multiple susceptibility genes associated with AD, such as CLU, CR1, MS4A4, CD2AP, CD33, and EPHA1." |
| ABCA7 (HGNC:37) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In East Asian studies, no significant differences were observed in the genotype and estimated allele frequency distribution of single nucleotide polymorphisms (SNPs) within ABCA7, CD2AP, and EPHA1, suggesting that the genetic basis for AD susceptibility may be ethnicity-specific." |
| MS4A6A (HGNC:13375) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our previous study found that rs3865444 of CD33 and rs610932 of MS4A6A may contribute to AD risk in the Chinese Han population, which was in line with the findings of preceding GWAS studies." |
| APP (HGNC:620) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Approximately 10% of EOAD cases are familial in nature, based on autosomal dominant variants in the genes encoding amyloid precursor protein (APP), presenilin 1 (PSEN1), and presenilin 2 (PSEN2)." |
| PSEN1 (HGNC:9508) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Approximately 10% of EOAD cases are familial in nature, based on autosomal dominant variants in the genes encoding amyloid precursor protein (APP), presenilin 1 (PSEN1), and presenilin 2 (PSEN2)." |
| PSEN2 (HGNC:9509) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Approximately 10% of EOAD cases are familial in nature, based on autosomal dominant variants in the genes encoding amyloid precursor protein (APP), presenilin 1 (PSEN1), and presenilin 2 (PSEN2)." |
| [[FERMT2 rs17125924]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Our study identifies the G-allele at rs17125924 as a risk factor for developing AD, especially in APOE ε4 carriers." |
| [[HLA-DRB1 rs9271058]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The rs9271058 of HLA-DRB1 (dominant, overdominant, and additive models), rs9473117 of CD2AP (dominant and additive models), and rs73223431 of PTK2B (dominant, overdominant, and additive models) were associated with early onset AD (EOAD)." |
| [[CD2AP rs9473117]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The rs9271058 of HLA-DRB1 (dominant, overdominant, and additive models), rs9473117 of CD2AP (dominant and additive models), and rs73223431 of PTK2B (dominant, overdominant, and additive models) were associated with early onset AD (EOAD)." |
| [[PTK2B rs73223431]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The rs9271058 of HLA-DRB1 (dominant, overdominant, and additive models), rs9473117 of CD2AP (dominant and additive models), and rs73223431 of PTK2B (dominant, overdominant, and additive models) were associated with early onset AD (EOAD)." |
| rs3865444 (variant) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Our previous study found that rs3865444 of CD33 and rs610932 of MS4A6A may contribute to AD risk in the Chinese Han population, which was in line with the findings of preceding GWAS studies." |
| rs610932 (variant) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Our previous study found that rs3865444 of CD33 and rs610932 of MS4A6A may contribute to AD risk in the Chinese Han population, which was in line with the findings of preceding GWAS studies." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The apolipoprotein E (APOE) ε4 allele, which plays a vital role in liquid absorption and redistribution, is regarded as the strongest genetic risk factor for LOAD." |
| [[FERMT2 rs17125924]] | biolink:associated_with | [[APOE]] |  | "Our study identifies the G-allele at rs17125924 as a risk factor for developing AD, especially in APOE ε4 carriers." |
| IQCK (HGNC:28556) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, a GWAS meta-analysis of non-Hispanic whites confirmed 20 previously described LOAD risk loci and proposed 5 such novel loci including IQCK, ACE, ADAM10, ADAMTS1, and WWOX." |
| ACE (HGNC:2707) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, a GWAS meta-analysis of non-Hispanic whites confirmed 20 previously described LOAD risk loci and proposed 5 such novel loci including IQCK, ACE, ADAM10, ADAMTS1, and WWOX." |
| ADAM10 (HGNC:188) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, a GWAS meta-analysis of non-Hispanic whites confirmed 20 previously described LOAD risk loci and proposed 5 such novel loci including IQCK, ACE, ADAM10, ADAMTS1, and WWOX." |
| ADAMTS1 (HGNC:217) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, a GWAS meta-analysis of non-Hispanic whites confirmed 20 previously described LOAD risk loci and proposed 5 such novel loci including IQCK, ACE, ADAM10, ADAMTS1, and WWOX." |
| WWOX (HGNC:12799) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, a GWAS meta-analysis of non-Hispanic whites confirmed 20 previously described LOAD risk loci and proposed 5 such novel loci including IQCK, ACE, ADAM10, ADAMTS1, and WWOX." |
| [[FERMT2 rs17125924]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In contrast, regarding SNP genotype frequencies, we found that, at rs1715924, the genotypes GG and GA conferred a higher risk for AD than the genotype AA (Table 2)." |
| [[FERMT2 rs17125924]] | biolink:associated_with | [[APOE]] |  | "In APOE ε4 carriers, the allele and genotype frequencies of FERMT2 rs17125924 were significantly different between AD patients and controls (allele: P = 0.029, OR = 1.895, 95% CI: 1.06–3.38; genotype: P = 0.036), with allele G found to be higher in the case group than in the control (Table 2)." |
| [[EPHA1 rs11763230]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "With regard to LOAD, we only found that rs11763230 of EPHA1 may be associated with AD susceptibility using the recessive model (P = 0.046, OR = 0.111, 95% CI: 0.01–0.96) (Supplementary Tables 6, 7)." |
| [[HLA-DRB1]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "We found that rs9271058 of HLA-DRB1 was associated with the risk of developing EOAD in allele and genotype frequencies (allele: P = 0.011, OR = 2.038, 95% CI: 1.17–3.56; genotype: P = 0.038)." |
| [[FERMT2]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "Another significant discrepancy was observed in the genotype frequencies of FERMT2 rs17125924 polymorphism (P = 0.024) (Supplementary Table 4)." |
| [[PTK2B]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "After adjustments for age and sex, rs9271058 of HLA-DRB1 and rs73223431 of PTK2B were associated with the risk of EOAD in the dominant, overdominant, and additive models (rs9271058: dominant model: P = 0.03, OR = 2.563, 95% CI: 1.10–5.99; overdominant model: P = 0.049, OR = 2.363, 95% CI: 1.01–5.56; additive model: P = 0.033, OR = 2.23, 95% CI: 1.07–4.68; rs73223431: dominant model: P = 0.007, OR = 3.108, 95% CI: 1.36–7.09; overdominant model: P = 0.027, OR = 2.523, 95% CI: 1.11–5.72; additive model: P = 0.008, OR = 2.438, 95% CI: 1.26–4.71)." |
| [[CD2AP]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "Additionally, rs9473117 of CD2AP was associated with the risk of developing EOAD in both the dominant and additive models (dominant model: P = 0.035, OR = 0.327, 95% CI: 0.12–0.93; additive model: P = 0.034, OR = 0.39, 95% CI: 0.16–0.93)." |
| [[APH1B]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "The results also showed an association between rs35408871 of APH1B and EOAD in the recessive model (P = 0.047, OR = 0.36, 95% CI: 0.13–0.99)." |
| [[HLA-DRB1 rs9271058]] | biolink:associated_with_increased_likelihood_of | early-onset Alzheimer disease (MESH:D000544) |  | "We found that rs9271058 of HLA-DRB1 was associated with the risk of developing EOAD in allele and genotype frequencies (allele: P = 0.011, OR = 2.038, 95% CI: 1.17–3.56; genotype: P = 0.038)." |
| [[FERMT2 rs17125924]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "Another significant discrepancy was observed in the genotype frequencies of FERMT2 rs17125924 polymorphism (P = 0.024) (Supplementary Table 4)." |
| [[PTK2B rs73223431]] | biolink:associated_with_increased_likelihood_of | early-onset Alzheimer disease (MESH:D000544) |  | "After adjustments for age and sex, rs9271058 of HLA-DRB1 and rs73223431 of PTK2B were associated with the risk of EOAD in the dominant, overdominant, and additive models (rs9271058: dominant model: P = 0.03, OR = 2.563, 95% CI: 1.10–5.99; overdominant model: P = 0.049, OR = 2.363, 95% CI: 1.01–5.56; additive model: P = 0.033, OR = 2.23, 95% CI: 1.07–4.68; rs73223431: dominant model: P = 0.007, OR = 3.108, 95% CI: 1.36–7.09; overdominant model: P = 0.027, OR = 2.523, 95% CI: 1.11–5.72; additive model: P = 0.008, OR = 2.438, 95% CI: 1.26–4.71)." |
| [[CD2AP rs9473117]] | biolink:associated_with_decreased_likelihood_of | early-onset Alzheimer disease (MESH:D000544) |  | "Additionally, rs9473117 of CD2AP was associated with the risk of developing EOAD in both the dominant and additive models (dominant model: P = 0.035, OR = 0.327, 95% CI: 0.12–0.93; additive model: P = 0.034, OR = 0.39, 95% CI: 0.16–0.93)." |
| [[APH1B rs35408871]] | biolink:associated_with_decreased_likelihood_of | early-onset Alzheimer disease (MESH:D000544) |  | "The results also showed an association between rs35408871 of APH1B and EOAD in the recessive model (P = 0.047, OR = 0.36, 95% CI: 0.13–0.99)." |
| [[EPHA1]] | biolink:associated_with | late-onset Alzheimer disease (MONDO:0007089; MESH:D000544) |  | "With regard to LOAD, we only found that rs11763230 of EPHA1 may be associated with AD susceptibility using the recessive model (P = 0.046, OR = 0.111, 95% CI: 0.01–0.96) (Supplementary Tables 6, 7)." |
| [[EPHA1 rs11763230]] | biolink:associated_with_decreased_likelihood_of | late-onset Alzheimer disease (MONDO:0007089; MESH:D000544) |  | "With regard to LOAD, we only found that rs11763230 of EPHA1 may be associated with AD susceptibility using the recessive model (P = 0.046, OR = 0.111, 95% CI: 0.01–0.96) (Supplementary Tables 6, 7)." |
| [[FERMT2]] | biolink:regulates | APP (HGNC:620) |  | "As previously reported, FERMT2 silencing leads to an increase in Aβ production, thus demonstrating its regulatory impact on APP metabolism." |
| [[FERMT2]] | biolink:affects | Aβ (CHEBI:64645) |  | "A new study found that FERMT2 expression in human neurons has effects on both Aβ and Tau." |
| [[FERMT2]] | biolink:affects | MAPT (HGNC:6893) |  | "A new study found that FERMT2 expression in human neurons has effects on both Aβ and Tau." |
| [[FERMT2]] | biolink:genetically_interacts_with | [[APOE]] |  | "We provide evidence that the G-allele at rs17125924 located within the intronic regions of FERMT2 is a risk factor for AD and is particularly prominent in APOE ε4 carriers." |
| [[PTK2B]] | biolink:physically_interacts_with | MAPT (HGNC:6893) |  | "The interaction between PTK2B and hyperphosphorylated and oligomeric Tau in the brain is involved in pathophysiological processes of AD." |
| rs17125944 (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "A meta-analysis of GWAS in individuals of European ancestry identified rs17125944 of FERMT2 as a risk factor for LOAD, even though this was inconsistent in different ethnic groups." |
| rs9271192 (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, Tan et al. found that the C-allele at rs9271192 may contribute to LOAD risk in the northern Chinese population." |
| [[CD2AP]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Case-control studies of the southern Chinese population found the C-allele at rs9296559 of CD2AP to be associated with the risk of sporadic AD and suggested decreased expression of CD2AP in peripheral blood lymphocytes of AD patients as a potential biomarker." |
| rs9296559 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Case-control studies of the southern Chinese population found the C-allele at rs9296559 of CD2AP to be associated with the risk of sporadic AD and suggested decreased expression of CD2AP in peripheral blood lymphocytes of AD patients as a potential biomarker." |
| rs9349407 (variant) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "In a meta-analysis of East Asian, American, Canadian, and European populations, the polymorphism of rs9349407 within CD2AP was shown to contribute to AD susceptibility." |
| rs28834970 (variant) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Although the rs28834970 of PTK2B has been identified to be a genetic contributor to the susceptibility of LOAD in several studies, no studies, to date, have investigated whether this genetic polymorphism is associated with EOAD." |
| [[APH1B rs35408871]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In our study, we found that homozygosity for the G-allele at rs35408871 may have a protective effect on EOAD susceptibility, whereas homozygosity for the T-allele at rs11763230 may protect from LOAD susceptibility." |
| rs11767557 (variant) | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, rs11767557 and rs11771145 of EPHA1 have been associated with reduced LOAD risk." |
| rs11771145 (variant) | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, rs11767557 and rs11771145 of EPHA1 have been associated with reduced LOAD risk." |
| [[HLA-DRB1]] | biolink:associated_with | autoimmune disease (MONDO:0007179; MESH:D001327) |  | "HLA-DRB1 is a member of major histocompatibility complex Class II (MHCII), which is associated with autoimmune and infectious diseases and is a key player in the regulation of numerous immune responses." |
| [[HLA-DRB1]] | biolink:associated_with | infectious disease (MONDO:0005550; MESH:D003141) |  | "HLA-DRB1 is a member of major histocompatibility complex Class II (MHCII), which is associated with autoimmune and infectious diseases and is a key player in the regulation of numerous immune responses." |
| [[CD2AP]] | biolink:directly_physically_interacts_with | CTTN (HGNC:3338) |  | "CD2-associated protein (CD2AP) is an adaptor protein that is expressed in brain capillaries and binds to cortactin, a protein involved in the regulation of receptor-mediated endocytosis." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "This suggests that this polymorphism may interact with APOE to increase the AD risk in a Han Chinese population." |
| rs593742 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A GWAS meta-analysis has identified the polymorphisms rs593742 and rs442495 within ADAM10 as novel risk loci associated with AD." |
| rs442495 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A GWAS meta-analysis has identified the polymorphisms rs593742 and rs442495 within ADAM10 as novel risk loci associated with AD." |
| rs1715924 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In conclusion, the SNP rs1715924 of FERMT2 was associated with AD in the southern Chinese population, with a particularly significant risk in APOE ε4 carriers." |
| [[HLA-DRB1]] | biolink:contributes_to | early-onset Alzheimer disease (MESH:D000544) |  | "Also, we aimed to investigate the association of candidate loci with the age at the onset of AD and confirmed that the candidate genes including HLA-DRB1, CD2AP, and PTK2B may contribute to the development of early onset dementia." |
| [[CD2AP]] | biolink:contributes_to | early-onset Alzheimer disease (MESH:D000544) |  | "Also, we aimed to investigate the association of candidate loci with the age at the onset of AD and confirmed that the candidate genes including HLA-DRB1, CD2AP, and PTK2B may contribute to the development of early onset dementia." |
| [[PTK2B]] | biolink:contributes_to | early-onset Alzheimer disease (MESH:D000544) |  | "Also, we aimed to investigate the association of candidate loci with the age at the onset of AD and confirmed that the candidate genes including HLA-DRB1, CD2AP, and PTK2B may contribute to the development of early onset dementia." |
| [[HLA-DRB1 rs9271058]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "The SNPs rs9271058 of HLA-DRB1, rs9473117 of CD2AP, and rs73223431 of PTK2B were found to be associated with EOAD." |
| [[CD2AP rs9473117]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "The SNPs rs9271058 of HLA-DRB1, rs9473117 of CD2AP, and rs73223431 of PTK2B were found to be associated with EOAD." |
| [[PTK2B rs73223431]] | biolink:associated_with | early-onset Alzheimer disease (MESH:D000544) |  | "The SNPs rs9271058 of HLA-DRB1, rs9473117 of CD2AP, and rs73223431 of PTK2B were found to be associated with EOAD." |
| [[HLA-DRB1]] | biolink:contributes_to | dementia (MONDO:0001627; MESH:D003704) |  | "Also, we aimed to investigate the association of candidate loci with the age at the onset of AD and confirmed that the candidate genes including HLA-DRB1, CD2AP, and PTK2B may contribute to the development of early onset dementia." |
| [[CD2AP]] | biolink:contributes_to | dementia (MONDO:0001627; MESH:D003704) |  | "Also, we aimed to investigate the association of candidate loci with the age at the onset of AD and confirmed that the candidate genes including HLA-DRB1, CD2AP, and PTK2B may contribute to the development of early onset dementia." |
| [[PTK2B]] | biolink:contributes_to | dementia (MONDO:0001627; MESH:D003704) |  | "Also, we aimed to investigate the association of candidate loci with the age at the onset of AD and confirmed that the candidate genes including HLA-DRB1, CD2AP, and PTK2B may contribute to the development of early onset dementia." |
| rs1715924 (variant) | biolink:associated_with | [[APOE]] |  | "In conclusion, the SNP rs1715924 of FERMT2 was associated with AD in the southern Chinese population, with a particularly significant risk in APOE ε4 carriers." |
