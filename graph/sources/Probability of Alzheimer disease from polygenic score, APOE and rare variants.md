---
type: source
title: "Probability of Alzheimer disease from polygenic score, APOE and rare variants"
paper_title: "Probability of Alzheimer’s disease based on common and rare genetic variants"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000247
pmid: "34404470"
pmcid: "PMC8369699"
doi: "10.1186/s13195-021-00884-7"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8369699/"
sources: ["[[.raw/01M4DY94KMVNHVFWVQTMTCZ9JF/normalized.md]]"]
tags: [polygenic-risk-score, alzheimer-risk-locus]
---

# Probability of Alzheimer disease from polygenic score, APOE and rare variants

A theoretical and simulation study that turns a [[Polygenic risk score]] into an absolute probability of [[Alzheimer disease]], rather than a standardised score that cannot be compared between studies. The probability is computed separately for age group, [[APOE]] genotype and carriage of a rare high-effect variant, using only summary statistics: the mean and variance of the score in cases and controls, and the disease prevalence. The framework is described in [[Disease probability from polygenic risk score]].

## Design

- Common variants enter through a score; the disease probability is a logistic function of the standardised score whose two coefficients follow from the prevalence and the score distribution in cases and non-cases, so no individual genotypes need to be shared.
- Rare variants (the paper names [[TREM2]], [[PLCG2]], [[ABI3]] and [[SORL1]], and the very rare highly penetrant mutations in [[APP]], [[PSEN1]] and [[PSEN2]]) are taken out of the score and added at the probability level as an intrinsic probability of disease, estimated from the variant's odds ratio. The method assumes they act independently of the polygenic score, which it supports with the small linkage disequilibrium between rare and common variants (maximum r2 of 0.04 for a variant with allele frequency 0.01 against one with 0.2).
- [[APOE]] is handled as a separate predictor because it shifts the prevalence itself: the prevalence in carriers of zero, one and two risk alleles is back-calculated from the overall prevalence, the allele frequency and the odds ratio under Hardy-Weinberg equilibrium, and a probability curve is drawn for each genotype.
- Validation was by simulation: 10,000 cases and 10,000 controls were simulated with 39 genome-wide significant variants (the APOE proxy [[APOE rs429358]] excluded) and 10,000 further LD-pruned variants, and the closed-form coefficients were compared with logistic regression on simulated genotypes and on sampled score distributions. Score distributions for the illustrations came from a published real case-control study. R code is available on GitHub (DRI-Cardiff/AD-probability).

## Findings

- Probability depends strongly on the reference prevalence. The paper quotes 3%, 17% and 33% Alzheimer prevalence in the 65-74, 75-84 and 85+ age groups and illustrates 2% (lifetime), 10% (65+) and 30% (85+).
- In the 65+ group, probability rises with the score from 0.03 to 0.18 without APOE and from 0.07 to 0.7 in ε4/ε4 carriers; in the 85+ group the ranges are 0.08 to 0.6 and 0.3 to 0.85.
- Treating APOE separately matters most at high prevalence. When prevalence is 30%, the combined score of APOE and the score without APOE discriminates far better than a standard score, because case and control means that ignore the fall in ε4 frequency with age mislead; the ε4 allele frequency was set to 0.18 at 55+ and 0.05 at 85+. In the 65+ group, ε4 raised probability from 0.01 to 0.07 at the lowest score and from 0.2 to 0.66 at the highest; in the 85+ group the values were 0.06 to 0.3 and 0.65 to 0.92.
- Rare variants lift the whole curve. With an odds ratio of 7.2 for a [[SORL1]] variant, probability in the 65+ group rose from about 0 to 0.4 at the lowest score and from 0.6 to 0.76 at the highest; with an odds ratio of 2.46 for a [[TREM2]] variant the values were 0 to 0.13 and 0.6 to 0.66. Curves for APP, PSEN1 and PSEN2 are in the supplement.
- The probability curve approaches the rare variant's intrinsic probability at very low polygenic scores, so a carrier with low common-variant risk still has a clearly raised probability.
- Early-onset and late-onset age groups were also plotted: the late-onset group has an elevated probability even at a low score, and ε4 carriers are higher than any other genotype. Excluding the APOE region puts the score-only curve slightly above ε4 non-carriers, since it cannot tell ε2 carriers from non-carriers of ε4.

## Why This Source Matters

It gives a way to compare genetic risk across scores built from different variant sets and to fold a rare pathogenic variant, [[APOE]] status and age into one number, which is the form a clinician or trial recruiter would need. The same framework could be used for other complex diseases; the authors note that for a neurodevelopmental disorder such as schizophrenia, where prevalence does not depend on age and no APOE-like variant exists, only the common-plus-rare combination would apply.

## Assessment

- The work is theoretical. It uses published effect sizes and score distributions and simulated genotypes; nothing was tested in a real cohort. The authors say validation needs a large population dataset, and that the UK Biobank is too young and lacks dementia phenotyping, while ADNI has too few rare-variant carriers.
- It assumes normally distributed scores, that rare and common variant effects are independent, and that APOE genotype does not change the distribution of the score without APOE.
- Effect sizes and prevalence come from European-ancestry studies; extension to other ancestries depends on reliable local effect estimates. Sex and non-genetic factors are not modelled.
- The abstract gives a rise from 0.02 to 0.3 for a TREM2 variant in the 65+ group, while the figure caption gives 0 to 0.13 for the odds ratio of 2.46 used there; the two use different variants or settings and are not reconciled in the text.

## Open Questions

- Does the probability model stay calibrated in a real prospective cohort with dementia follow-up (the study used simulated genotypes and published summary statistics only)?
- How well does the independence of rare-variant effects and polygenic risk hold for carriers of SORL1 or TREM2 variants (assumed from low linkage disequilibrium, not tested)?
- How should the model be parameterised for non-European ancestries (effect sizes and prevalence were taken from European studies)?

## Connections

- Method: [[Disease probability from polygenic risk score]], [[Polygenic risk score]]
- Disease and subtypes: [[Alzheimer disease]], [[Early-onset Alzheimer disease]], [[Late-onset Alzheimer disease]]
- Genes: [[APOE]], [[TREM2]], [[SORL1]], [[ABI3]], [[PLCG2]], [[APP]], [[PSEN1]], [[PSEN2]]
- The 39-variant score used for simulation comes from the common-variant work summarised in [[Meta-GWAS of Alzheimer disease finds six new loci and a polygenic risk score]]; the SORL1 odds ratios can be set against [[Domain mapping of SORL1 missense variants in Alzheimer disease]].

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The AD probability varies with respect to age, APOE status and presence of rare variants." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The APOE-ε4 allele is a known common variant associated with high risk to AD, but also associated with earlier onset." |
| [[TREM2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Presence of rare mutations, e.g. in TREM2, may increase the probability (in 65+) from 0.02 at the negative tail of the PRS to 0.3." |
| [[PLCG2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, the PRS may not well reflect the effect of rare variants in TREM2, PLCG2, ABI3, SORL1 and very rare highly penetrant mutations in APP, PSEN1 and PSEN2, as the cumulation of many SNPs of small effect sizes tends to mask the strong effect of a single variant." |
| [[ABI3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, the PRS may not well reflect the effect of rare variants in TREM2, PLCG2, ABI3, SORL1 and very rare highly penetrant mutations in APP, PSEN1 and PSEN2, as the cumulation of many SNPs of small effect sizes tends to mask the strong effect of a single variant." |
| [[SORL1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, the PRS may not well reflect the effect of rare variants in TREM2, PLCG2, ABI3, SORL1 and very rare highly penetrant mutations in APP, PSEN1 and PSEN2, as the cumulation of many SNPs of small effect sizes tends to mask the strong effect of a single variant." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, the PRS may not well reflect the effect of rare variants in TREM2, PLCG2, ABI3, SORL1 and very rare highly penetrant mutations in APP, PSEN1 and PSEN2, as the cumulation of many SNPs of small effect sizes tends to mask the strong effect of a single variant." |
| [[PSEN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, the PRS may not well reflect the effect of rare variants in TREM2, PLCG2, ABI3, SORL1 and very rare highly penetrant mutations in APP, PSEN1 and PSEN2, as the cumulation of many SNPs of small effect sizes tends to mask the strong effect of a single variant." |
| [[PSEN2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, the PRS may not well reflect the effect of rare variants in TREM2, PLCG2, ABI3, SORL1 and very rare highly penetrant mutations in APP, PSEN1 and PSEN2, as the cumulation of many SNPs of small effect sizes tends to mask the strong effect of a single variant." |
| single nucleotide polymorphism (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "While causal fully penetrant mutations almost certainly lead to development of the disease, most of the identified singular nucleotide polymorphism (SNP) risk alleles have not been proven to be causal but replicated as carrying an increased disease risk." |
| rare variants (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Presence of rare mutations, e.g. in TREM2, may increase the probability (in 65+) from 0.02 at the negative tail of the PRS to 0.3." |
| common variants (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Probability of Alzheimer’s disease based on common and rare genetic variants" |
| [[APOE]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Genome-wide association studies (GWAS) identified genetic risk variants of late onset “sporadic” disease beyond the APOE locus, followed by exome chip analyses identifying rare variants with moderate risk." |
| single nucleotide polymorphism (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Genome-wide association studies (GWAS) identified genetic risk variants of late onset “sporadic” disease beyond the APOE locus, followed by exome chip analyses identifying rare variants with moderate risk." |
| rare variants (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Genome-wide association studies (GWAS) identified genetic risk variants of late onset “sporadic” disease beyond the APOE locus, followed by exome chip analyses identifying rare variants with moderate risk." |
| common variants (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Genome-wide association studies (GWAS) identified genetic risk variants of late onset “sporadic” disease beyond the APOE locus, followed by exome chip analyses identifying rare variants with moderate risk." |
| [[APOE]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Variants in the APOE gene highly affect the AD risk (OR = 3.2, MAF = 0.14)." |
| [[APOE]] | biolink:associated_with | age at onset (HP:0003674) |  | "APOE is also associated with lower odds of reaching the over 90th percentile age as it modifies the age at onset; for example, the age at onset of AD for ε4ε4 carriers is ~ 68 years." |
| APOE ε4ε4 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "APOE is also associated with lower odds of reaching the over 90th percentile age as it modifies the age at onset; for example, the age at onset of AD for ε4ε4 carriers is ~ 68 years." |
| APOE ε2 (variant) | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "PRS.AD - PRS calculated as a weighted sum of PRS.no.APOE, including SNPs with a pT ≤ 0.1 excluding APOE region (CHR19:44.4-46.5), and APOE (ε2 + ε4), where APOE effects were weighted with effect sizes (B(ε2) = -0.47 and B(ε4) = 1.12) as in Kunkle et al. 2019" |
| APOE ε4ε4 (variant) | biolink:associated_with_increased_likelihood_of | cardiovascular disease (MONDO:0004995; MESH:D002318) |  | "Also, ε4ε4 carriers are more likely to develop other conditions associated with lower life expectancy such as cardiovascular disease and diabetes." |
| APOE ε4ε4 (variant) | biolink:associated_with_increased_likelihood_of | diabetes (MONDO:0005015) |  | "Also, ε4ε4 carriers are more likely to develop other conditions associated with lower life expectancy such as cardiovascular disease and diabetes." |
| APOE ε4ε4 (variant) | biolink:associated_with | age at onset (HP:0003674) |  | "APOE is also associated with lower odds of reaching the over 90th percentile age as it modifies the age at onset; for example, the age at onset of AD for ε4ε4 carriers is ~ 68 years." |
| [[SORL1]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The rare variant effect sizes and minor allele frequencies correspond to known variants in SORL1 (OR = 7.2) and TREM2 (OR = 2.46) genes." |
| SORL1 mutations (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In age group 65+ (red) the presence of SORL1 mutations (left) increases the AD probability from ~ 0 to 0.4 when PRS is the lowest and from 0.6 to 0.76 when the PRS is highest (solid line vs dashed line)." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | Early-onset Alzheimer disease (MESH:D000544) |  | "As expected, the late onset group shows elevated AD probability even if the PRS is low and APOE ε4 carriers show consistently higher probability than any other genotypes." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | Late-onset Alzheimer disease (HP:0003584; MESH:D000544) |  | "As expected, the late onset group shows elevated AD probability even if the PRS is low and APOE ε4 carriers show consistently higher probability than any other genotypes." |
| common high-effect variants (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The impact of common high-effect variants such as APOE for AD can vary due to confounders such as age stratification, so taking a summary effect size from a reference study may result in a suboptimal PRS; this becomes apparent when APOE and PRS are used as separate predictors in bivariate logistic regression." |
| APOE risk allele (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We propose calculating separate probability curves for each APOE status, based on the disease prevalence calculated for each APOE status from the disease prevalence in the population, the risk allele frequency and the odds ratio." |
| rare variants (variant) | biolink:associated_with | schizophrenia (MONDO:0005090; MESH:D012559) |  | "For example, schizophrenia is a highly polygenic disorder and has an increased burden of rare variants and CNVs." |
| copy number variants (variant) | biolink:associated_with | schizophrenia (MONDO:0005090; MESH:D012559) |  | "For example, schizophrenia is a highly polygenic disorder and has an increased burden of rare variants and CNVs." |
| rare variants (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The proposed method gives an estimate of the probability of developing AD based on an individual’s PRS, APOE genotype and the presence or absence of rare genetic variants associated with AD." |
| SNP (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Nevertheless, the approach presented here can be used in small studies focusing on rare and common genetic variants, for example to identify individuals most at risk of developing the disease." |
