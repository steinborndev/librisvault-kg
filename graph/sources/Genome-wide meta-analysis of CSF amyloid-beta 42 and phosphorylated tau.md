---
type: source
title: "Genome-wide meta-analysis of CSF amyloid-beta 42 and phosphorylated tau"
paper_title: "Genome-wide meta-analysis for Alzheimer’s disease cerebrospinal fluid biomarkers"
domain: neuroscience
status: developing
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000574
pmid: "36066633"
pmcid: "PMC9547780"
doi: "10.1007/s00401-022-02454-z"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9547780/"
sources: ["[[.raw/01M4DY94VW8KJWHVBXQ5WNC6DH/normalized.md]]"]
tags: [gwas, biomarker, alzheimer-risk-locus]
---

# Genome-wide meta-analysis of CSF amyloid-beta 42 and phosphorylated tau

A three-stage [[Genome-wide association study]] of two cerebrospinal fluid (CSF) markers of [[Alzheimer disease]] pathology, amyloid-beta 42 and phosphorylated tau (pTau), led by the European Alzheimer & Dementia Biobank. It combines 31 cohorts and 13,116 people (discovery 8,074 from 16 cohorts; replication 5,042 from 15 cohorts, mostly US-based) to ask which loci move the two hallmark proteins, and then sorts all known Alzheimer risk loci by their effect on each.

## Design

- Stage 1 discovery (16 European cohorts, 82% in the consortium, spanning subjective cognitive decline, mild cognitive impairment and dementia), stage 2 replication of variants with p < 1e-5, and stage 3 combined analysis. Genome-wide significance was p < 5e-8; stage 2 counted as replication at p < 0.05 with the same direction of effect.
- CSF Aβ42 was measured by ELISA, Lumipulse or V-PLEX and pTau by ELISA or Lumipulse; values were log10-transformed and normalised within cohort and assay. Tau and pTau were strongly correlated (rg = 0.94), so only pTau is reported.
- Genotypes came mostly from the Illumina Global Screening Array, imputed with the TOPMed panel; linear regression in PLINK 2.0 adjusted for sex, age, assay and ten principal components, and METAL pooled the cohorts with a sample-size-weighted p-value approach.
- Exploratory stratified analyses split stage 1 by [[APOE]] ε4 carrier status and by normal versus abnormal Aβ42 (cut-offs set by each cohort).
- Follow-up: [[Colocalization analysis]] against 63 brain and immune eQTL datasets, the AD GWAS of Kunkle et al. and ventricular volume GWAS; [[Phenome-wide association study]] of five top variants across 19,649 traits; FUMA and MAGMA gene mapping; association of the pTau variants with CSF proteomics (2,136 proteins by tandem mass tag in 366 people; 1,305 by SOMAscan in 717 people); and a heatmap of 83 AD risk variants against both CSF markers, clustered and tested for GO enrichment.

## Findings

### Heritability

- SNP-heritability by LD score regression was 0.13 for Aβ42 and 0.21 for pTau, against 0.07 for the clinical Alzheimer diagnosis; GCTA in the largest Dutch cohort gave 0.27 and 0.34. The authors read the higher values as support for biomarker-based genetics over diagnosis-based genetics.

### Loci

- [[APOE]] dominated both traits. The ε4 variant [[APOE rs429358]] lowered CSF Aβ42 (Z = -36.29, p = 2.0e-288) and raised pTau (Z = 18.31, p = 6.9e-75); the ε2 variant [[APOE rs7412]] did the opposite and replicated. In the replication cohorts, where rs429358 was not available, the proxies [[APOC1 rs4420638]] (Aβ42) and [[APOE rs769449]] (pTau) stood in. The result is a [[Decreased amyloid beta 42 peptide CSF concentration]] in ε4 carriers and an [[Increased CSF phosphorylated tau concentration]].
- [[GMNC]] (3q28; lead [[GMNC rs9877502]]) was confirmed for pTau (stage 1 Z = 9.06). Because the earlier discovery cohorts are this study's replication set, the replication is not independent. Combined, the pTau signal strengthened from p = 3.07e-11 in the previous largest study to 1.19e-36.
- [[C16orf95]] (16q24.2; lead [[C16orf95 rs4843559]], intronic) was a novel pTau locus, replicated in stage 2 (Z = 3.88, p = 1.0e-4).
- In the combined stage, [[CR1]] reached genome-wide significance for Aβ42 (1q32.2, Z = -6.01, p = 1.8e-9) and [[BIN1]] for pTau (2q14.3, Z = 6.15, p = 7.9e-10), both known Alzheimer risk loci now assigned to one protein. CR1 colocalized with the AD GWAS signal (posterior probability 0.97) and with a CR1 eQTL in six brain regions; BIN1 colocalized with the AD signal tagged by [[BIN1 rs6733839]] (0.84) and with a BIN1 eQTL in lymphoblastoid cell lines. CR1 is tied to Aβ42 and BIN1 to tau, and no non-APOE locus overlaps between the two markers.
- The stratified analyses gave two further, unreplicated Aβ42 loci: 7q11.22 in ε4 non-carriers (an intronic variant of a lncRNA expressed in testis and prostate) and 12q13.3 in people with abnormal amyloid (one rare intronic variant seen only in the largest Dutch cohort, n = 498).
- Loci from the previous largest CSF GWAS did not replicate except APOE and GMNC: GLIS1 was not testable (rs185031519, minor allele frequency 0.007), and SERPINB1 (Aβ42) and GLIS3, PCDH8, CTDP1 (pTau) showed p > 0.05 with more than 7,000 people.
- APOE colocalized unexpectedly with an eQTL for [[NKPD1]] in a helper T cell subset; the authors expect this to be a false positive given the known coding mechanism at APOE residues 112 and 158.

### Lateral ventricular volume

- PheWAS of the five top variants gave 529 associations at p < 1e-7, 490 of them for APOE ε4. The rest fell into three groups: brain ventricular volume (GMNC and C16orf95), Alzheimer diagnosis (BIN1 and CR1) and blood cell or lymphocyte counts (CR1).
- The pTau signals at both loci overlap those for [[Lateral ventricular volume]]. C16orf95 colocalized with a single shared causal variant (posterior probability 0.93); GMNC was inconclusive (0.63, rising to 0.74 on a credible set). The risk alleles for higher pTau go with smaller ventricles, a direction the authors call counterintuitive.
- CSF proteins associated with GMNC were enriched for axon guidance and ephrin signalling in both proteomics datasets (22% of proteins in one, 36% in the other); those for C16orf95 (EMIF-AD only, 6%) were enriched for glycosaminoglycan metabolism and extracellular matrix organisation. Only CDH9 and DPP6 overlapped, so the two loci appear to act through largely different routes.

### Clusters of Alzheimer risk loci

The 83 non-APOE AD variants formed four groups by their effect on the two markers:

- Cluster 1 (14 variants): lower Aβ42 and higher pTau; enrichment for 29 GO terms sharing "amyloid", driven by [[BIN1]], [[PICALM]], [[ABCA7]] and [[CLU]].
- Cluster 2 (21 variants): lower pTau with no Aβ42 effect; eight "immune" terms, driven by [[TREM2]] and [[GRN]], and including genes tied to other dementias such as [[MAPT]].
- Cluster 3 (22 variants): lower Aβ42 without a pTau rise; nine terms with "migration" and "tyrosine".
- Cluster 4 (20 variants): higher pTau without lower Aβ42; no enrichment.

The authors argue that Aβ42 is mostly an APOE trait while pTau has several genetic inputs, which fits a dual-cascade view rather than the strict [[Amyloid cascade hypothesis]] in which tau changes follow plaques, and propose that sub-scores for each cluster could one day match people to amyloid- or immune-targeted trials.

## Why This Source Matters

It moves the genetics of [[Alzheimer disease]] one step closer to mechanism: instead of asking which loci raise diagnosis risk, it asks which loci move the amyloid readout and which move the tau readout. CR1 lands on amyloid, BIN1 on tau, and two further tau loci, GMNC and C16orf95, link tau levels to ventricle size. The four-cluster map of known risk loci is a concrete starting point for splitting Alzheimer risk into amyloid-type and immune-type biology, and for stratifying future trials.

## Assessment

- The meta-analysis pools 31 heterogeneous cohorts (different arrays, imputation panels, assays and case-control mix), which the authors say lowers power; the number of new loci is modest.
- The GMNC replication reuses the discovery cohorts of the earlier study, so it confirms rather than independently tests the locus.
- The two stratified Aβ42 loci were not replicated, and the 12q13.3 one rests on a single rare variant in one cohort.
- The cluster analysis is explicitly exploratory; clusters 3 and 4 are hard to interpret and the authors call the first three subclasses the best approximation available, not a faithful picture.
- The proteomics follow-up used two assays with little protein overlap and small samples.
- Several internal inconsistencies appear in the text: the replication size is given as 5,042 in the abstract and methods but 5,402 in the discussion; the discussion refers to CR1 colocalization with a "CSF pTau" observation when CR1 is the Aβ42 locus; one sentence says the GMNC signal likely shares a causal variant with "AD" where the surrounding results concern ventricular volume; and one gene is written TMEM107B where the dementia-linked gene is presumably TMEM106B.
- The supplementary tables (per-cohort data, all colocalization and cluster results) were not part of the text read.
- Summary statistics are deposited in the GWAS Catalog under GCST90129599 and GCST90129600.

## Open Questions

- Does the CR1 association with CSF Aβ42 act through brain amyloid clearance, red blood cell CR1 capture of circulating amyloid-beta, or both (the study shows colocalization with brain eQTLs but no peripheral test)?
- Which gene at the 16q24.2 locus mediates the pTau and ventricular volume signal, given that the lead variants lie in introns of C16orf95 (no expression colocalization was reported)?
- Why do the alleles that raise CSF pTau at GMNC and C16orf95 go with smaller lateral ventricles (the direction is opposite to what neurodegeneration would predict, and was not explained)?
- Do the two unreplicated Aβ42 loci at 7q11.22 and 12q13.3 hold up in independent CSF cohorts (no replication data were available for the stratified analyses)?
- Can cluster-specific polygenic sub-scores separate people with amyloid-type and immune-type Alzheimer risk well enough to enrich trials (the authors say the present clusters are too coarse and the samples too small)?

## Connections

- Disease: [[Alzheimer disease]], [[Late-onset Alzheimer disease]]
- Genes: [[APOE]], [[CR1]], [[BIN1]], [[GMNC]], [[C16orf95]], [[NKPD1]], [[PICALM]], [[ABCA7]], [[CLU]], [[TREM2]], [[GRN]], [[MAPT]]
- Variants: [[APOE rs429358]], [[APOE rs7412]], [[APOE rs769449]], [[APOC1 rs4420638]], [[BIN1 rs6733839]], [[CR1 rs6656401]], [[GMNC rs9877502]], [[C16orf95 rs4843559]]
- Phenotypes: [[Decreased amyloid beta 42 peptide CSF concentration]], [[Increased CSF phosphorylated tau concentration]], [[Lateral ventricular volume]]
- Methods and ideas: [[Genome-wide association study]], [[Colocalization analysis]], [[Phenome-wide association study]], [[Expression quantitative trait locus analysis]], [[Gene set enrichment analysis]], [[Amyloid cascade hypothesis]]
- Related study: [[Perivascular spaces and CSF biomarkers in cognitively unimpaired Alzheimer continuum]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Aβ42 pathology in the brain is negatively correlated with CSF Aβ42 levels, where a decrease in CSF Aβ42 is indicative of AD." |
| [[MAPT]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "CSF (p)Tau is positively correlated with (p)Tau pathology in the brain, and therefore higher CSF (p)Tau levels are observed in patients with AD." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Besides the APOE locus, novel associations with two other well-established AD risk loci were observed; CR1 was shown a locus for Aβ42 and BIN1 for pTau." |
| [[CR1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Besides the APOE locus, novel associations with two other well-established AD risk loci were observed; CR1 was shown a locus for Aβ42 and BIN1 for pTau." |
| [[BIN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Besides the APOE locus, novel associations with two other well-established AD risk loci were observed; CR1 was shown a locus for Aβ42 and BIN1 for pTau." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Resolving the genetic background of Alzheimer’s disease (AD) has proven to contribute greatly to our understanding of underlying disease processes, for instance with the discovery of APP, PSEN1, and PSEN2 in family-based studies, leading to the amyloid cascade theory." |
| [[PSEN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Resolving the genetic background of Alzheimer’s disease (AD) has proven to contribute greatly to our understanding of underlying disease processes, for instance with the discovery of APP, PSEN1, and PSEN2 in family-based studies, leading to the amyloid cascade theory." |
| [[PSEN2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Resolving the genetic background of Alzheimer’s disease (AD) has proven to contribute greatly to our understanding of underlying disease processes, for instance with the discovery of APP, PSEN1, and PSEN2 in family-based studies, leading to the amyloid cascade theory." |
| Amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "It is possible to measure levels of amyloid-beta-42 (Aβ42) and (phosphorylated) tau (pTau and Tau) in cerebrospinal fluid (CSF), the two major proteins implicated in the AD pathological process." |
| [[CR1]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "Besides the APOE locus, novel associations with two other well-established AD risk loci were observed; CR1 was shown a locus for Aβ42 and BIN1 for pTau." |
| [[BIN1]] | biolink:associated_with | [[MAPT]] |  | "Besides the APOE locus, novel associations with two other well-established AD risk loci were observed; CR1 was shown a locus for Aβ42 and BIN1 for pTau." |
| [[GMNC]] | biolink:associated_with | [[MAPT]] |  | "GMNC and C16orf95 were further identified as loci for pTau, of which the latter is novel." |
| [[C16orf95]] | biolink:associated_with | [[MAPT]] |  | "GMNC and C16orf95 were further identified as loci for pTau, of which the latter is novel." |
| [[APOE]] | biolink:associated_with | [[MAPT]] |  | "The strongest associations were observed for both Aβ42 and pTau in the APOE locus (Table 2)." |
| [[APOE]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "The strongest associations were observed for both Aβ42 and pTau in the APOE locus (Table 2)." |
| [[APOE rs429358]] | biolink:affects | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | direction=decreased | "The variant that determines the APOE ɛ4 allele (rs429358-C) decreased Aβ42 (Z = − 36.29; P = 2.0 × 10–288) and increased pTau (Z = 18.31; P = 6.87 × 10–75) in CSF." |
| [[APOE rs7412]] | biolink:affects | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | direction=increased | "In contrast, the variant determining the APOE ɛ2 haplotype (rs7412-T) increased Aβ42 (Z = 11.97; P = 5.09 × 10–33) and decreased pTau (Z = − 6.59; P = 4.49 × 10–11)." |
| [[APOC1 rs4420638]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "The APOE ɛ2 association was replicated in stage 2 (Aβ42: Z = 7.27; P = 3.73 × 10–13, and pTau: Z = − 6.43; P = 1.26 × 10–10), and APOE ɛ4 with rs4420638-G for Aβ42 (Z = − 25.51; P = 1.57 × 10–143), and with rs769449-A for pTau (Z = 13.83; P = 1.66 × 10–43), both variants in high linkage disequilibrium with rs429358, as the original APOE ɛ4 variant was not genotyped or imputed in the replication datasets." |
| [[APOC1 rs4420638]] | biolink:correlated_with | [[APOE rs429358]] |  | "The APOE ɛ2 association was replicated in stage 2 (Aβ42: Z = 7.27; P = 3.73 × 10–13, and pTau: Z = − 6.43; P = 1.26 × 10–10), and APOE ɛ4 with rs4420638-G for Aβ42 (Z = − 25.51; P = 1.57 × 10–143), and with rs769449-A for pTau (Z = 13.83; P = 1.66 × 10–43), both variants in high linkage disequilibrium with rs429358, as the original APOE ɛ4 variant was not genotyped or imputed in the replication datasets." |
| [[APOE rs769449]] | biolink:correlated_with | [[APOE rs429358]] |  | "The APOE ɛ2 association was replicated in stage 2 (Aβ42: Z = 7.27; P = 3.73 × 10–13, and pTau: Z = − 6.43; P = 1.26 × 10–10), and APOE ɛ4 with rs4420638-G for Aβ42 (Z = − 25.51; P = 1.57 × 10–143), and with rs769449-A for pTau (Z = 13.83; P = 1.66 × 10–43), both variants in high linkage disequilibrium with rs429358, as the original APOE ɛ4 variant was not genotyped or imputed in the replication datasets." |
| [[APOE rs429358]] | biolink:has_phenotype | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "The variant that determines the APOE ɛ4 allele (rs429358-C) decreased Aβ42 (Z = − 36.29; P = 2.0 × 10–288) and increased pTau (Z = 18.31; P = 6.87 × 10–75) in CSF." |
| [[CR1]] | biolink:associated_with | AL137789.1 (HGNC:40160) |  | "Additionally for the dorsolateral prefrontal cortex, the CR1 locus also colocalized with an eQTL for the AL137789.1 gene." |
| [[APOE]] | biolink:associated_with | [[NKPD1]] |  | "The APOE locus for both Aβ42 and pTau colocalized with an eQTL for NKPD1 in a specific immune helper T cell." |
| [[GMNC]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Although these results are subthreshold to the predefined posterior probability limit of 0.8, they do imply that the same causal variant is likely underlying the GMNC association signals for pTau and AD." |
| [[BIN1 rs6733839]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "For the BIN1 locus of the AD GWAS two independent causal signals were observed, of which our BIN1 locus colocalized (posterior probability = 0.84) with the first signal that was tagged by rs6733839, which is the most significant variant of the BIN1 locus of the AD GWAS." |
| [[GMNC]] | biolink:associated_with | [[C16orf95]] |  | "Because of the overlap in effect of GMNC and C16orf95, we hypothesized that these two loci affect the same biological pathways." |
| [[GMNC]] | biolink:associated_with | CDH9 (HGNC:1768) |  | "Only 2 proteins (CDH9 and DPP6) overlapped between the 2 loci." |
| [[GMNC]] | biolink:associated_with | DPP6 (HGNC:3010) |  | "Only 2 proteins (CDH9 and DPP6) overlapped between the 2 loci." |
| [[C16orf95]] | biolink:associated_with | CDH9 (HGNC:1768) |  | "Only 2 proteins (CDH9 and DPP6) overlapped between the 2 loci." |
| [[C16orf95]] | biolink:associated_with | DPP6 (HGNC:3010) |  | "Only 2 proteins (CDH9 and DPP6) overlapped between the 2 loci." |
| [[BIN1]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "A pathway enrichment analysis of the genes associated with the variants showed 29 GO terms enriched and ‘amyloid’ is the common denominator in the names of these terms, of which the signal is mostly driven by BIN1, PICALM ABCA7 and CLU." |
| [[BIN1]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "The first cluster of 14 variants showed strong association with both decreased levels of Aβ42 and increased levels of pTau in CSF." |
| [[PICALM]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "A pathway enrichment analysis of the genes associated with the variants showed 29 GO terms enriched and ‘amyloid’ is the common denominator in the names of these terms, of which the signal is mostly driven by BIN1, PICALM ABCA7 and CLU." |
| [[PICALM]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "The first cluster of 14 variants showed strong association with both decreased levels of Aβ42 and increased levels of pTau in CSF." |
| [[ABCA7]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "A pathway enrichment analysis of the genes associated with the variants showed 29 GO terms enriched and ‘amyloid’ is the common denominator in the names of these terms, of which the signal is mostly driven by BIN1, PICALM ABCA7 and CLU." |
| [[ABCA7]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "The first cluster of 14 variants showed strong association with both decreased levels of Aβ42 and increased levels of pTau in CSF." |
| [[CLU]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "A pathway enrichment analysis of the genes associated with the variants showed 29 GO terms enriched and ‘amyloid’ is the common denominator in the names of these terms, of which the signal is mostly driven by BIN1, PICALM ABCA7 and CLU." |
| [[CLU]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "The first cluster of 14 variants showed strong association with both decreased levels of Aβ42 and increased levels of pTau in CSF." |
| [[GRN]] | biolink:associated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The second cluster contained 21 variants and included genes that have also been related to other dementia types (e.g., GRN, TMEM107B, SNX1, MAPT, CTSB and CTSH)." |
| TMEM106B (HGNC:22407) | biolink:associated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The second cluster contained 21 variants and included genes that have also been related to other dementia types (e.g., GRN, TMEM107B, SNX1, MAPT, CTSB and CTSH)." |
| SNX1 (HGNC:11172) | biolink:associated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The second cluster contained 21 variants and included genes that have also been related to other dementia types (e.g., GRN, TMEM107B, SNX1, MAPT, CTSB and CTSH)." |
| [[MAPT]] | biolink:associated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The second cluster contained 21 variants and included genes that have also been related to other dementia types (e.g., GRN, TMEM107B, SNX1, MAPT, CTSB and CTSH)." |
| [[CTSB]] | biolink:associated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The second cluster contained 21 variants and included genes that have also been related to other dementia types (e.g., GRN, TMEM107B, SNX1, MAPT, CTSB and CTSH)." |
| CTSH (HGNC:2535) | biolink:associated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The second cluster contained 21 variants and included genes that have also been related to other dementia types (e.g., GRN, TMEM107B, SNX1, MAPT, CTSB and CTSH)." |
| [[APOE]] | biolink:associated_with | Aβ42 (CHEBI:64647) |  | "We identified 2 loci (CR1 and APOE) for Aβ42, and 4 loci (BIN1, GMNC, C16orf95 and APOE) for pTau in a total of 13,116 individuals (discovery n = 8074; replication n = 5402 individuals)." |
| [[CR1]] | biolink:associated_with | Aβ42 (CHEBI:64647) |  | "We identified 2 loci (CR1 and APOE) for Aβ42, and 4 loci (BIN1, GMNC, C16orf95 and APOE) for pTau in a total of 13,116 individuals (discovery n = 8074; replication n = 5402 individuals)." |
| [[BIN1]] | biolink:associated_with | Amyloid-beta (CHEBI:64645; MESH:D016229) |  | "The involvement of these genes in amyloid-beta pathology is supported by previous studies." |
| [[PICALM]] | biolink:associated_with | Amyloid-beta (CHEBI:64645; MESH:D016229) |  | "The involvement of these genes in amyloid-beta pathology is supported by previous studies." |
| [[ABCA7]] | biolink:associated_with | Amyloid-beta (CHEBI:64645; MESH:D016229) |  | "The involvement of these genes in amyloid-beta pathology is supported by previous studies." |
| [[CLU]] | biolink:associated_with | Amyloid-beta (CHEBI:64645; MESH:D016229) |  | "The involvement of these genes in amyloid-beta pathology is supported by previous studies." |
| [[TREM2]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The largest genetic drivers of this signal are TREM2 and GRN which have been previously described for their functional role in AD via the immune system." |
| [[GRN]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The largest genetic drivers of this signal are TREM2 and GRN which have been previously described for their functional role in AD via the immune system." |
| APOE ɛ4 (variant) | biolink:affects | Amyloid-beta (CHEBI:64645; MESH:D016229) | direction=decreased | "In concordance with previous GWAS studies, both proteins showed the strongest association for APOE, where APOE ɛ4 decreased amyloid-beta levels and increased pTau levels, while APOE ɛ2 had the opposite effect." |
| APOE ɛ2 (variant) | biolink:affects | Amyloid-beta (CHEBI:64645; MESH:D016229) | direction=increased | "In concordance with previous GWAS studies, both proteins showed the strongest association for APOE, where APOE ɛ4 decreased amyloid-beta levels and increased pTau levels, while APOE ɛ2 had the opposite effect." |
| [[APOE]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "However, due to the convincing functional involvement of APOE in AD pathogenesis via the presence of cysteine or arginine at APOE amino acid residuals 112 and 158, that we anticipate this successful NKPD1 eQTL colocalization result to be a false positive." |
| [[APOE]] | biolink:associated_with | Cysteine (CHEBI:15356; MESH:D003545) |  | "However, due to the convincing functional involvement of APOE in AD pathogenesis via the presence of cysteine or arginine at APOE amino acid residuals 112 and 158, that we anticipate this successful NKPD1 eQTL colocalization result to be a false positive." |
| [[APOE]] | biolink:associated_with | Arginine (CHEBI:16467; MESH:D001120) |  | "However, due to the convincing functional involvement of APOE in AD pathogenesis via the presence of cysteine or arginine at APOE amino acid residuals 112 and 158, that we anticipate this successful NKPD1 eQTL colocalization result to be a false positive." |
| [[APOE]] | biolink:affects | Aβ42 (CHEBI:64647) | direction=increased | "In short, studies in human and mice models have shown higher Aβ42 levels and plaque load for APOE4 carriers." |
| [[APOE]] | biolink:positively_correlated_with | Amyloid plaque (MONDO:0019065; MESH:D058225) |  | "In short, studies in human and mice models have shown higher Aβ42 levels and plaque load for APOE4 carriers." |
| [[CR1]] | biolink:affects | Aβ42 (CHEBI:64647) |  | "In concordance with this observation is functional work on the effect of CR1 further which suggests that CR1 is involved in AD pathogenesis by regulating Aβ42 clearance in the brain itself, but also peripherally in blood cells." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The BIN1-locus furthermore localizes with the same locus in the AD GWAS, implying that a causal variant of the BIN1-locus for AD contributes to AD pathogenesis via tau pathology." |
| [[BIN1]] | biolink:physically_interacts_with | [[MAPT]] |  | "More recently, research in mice showed physical protein interaction between BIN1 and Tau, and BIN1 involvement in Tau-dependent hyperexcitability in AD." |
| [[MAPT]] | biolink:contributes_to | Neurotoxicity (MONDO:0005527) |  | "BIN1 has already been linked to Tau pathology in several functional studies, first shown in fruit flies where a decrease in the BIN1 ortholog gene expression suppressed Tau-mediated neurotoxicity." |
| [[MAPT]] | biolink:associated_with | [[Memory impairment]] |  | "In human subjects, BIN1-carriers were associated with lower memory performance, mediated by higher tau-PET levels." |
| [[BIN1]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The BIN1-locus furthermore localizes with the same locus in the AD GWAS, implying that a causal variant of the BIN1-locus for AD contributes to AD pathogenesis via tau pathology." |
| [[CR1 rs6656401]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The CR1-locus findings are in agreement with the well-known observed association for AD risk, where rs6656401 (R2 = 0.88 with lead SNP of current study) carriers are more susceptible for AD." |
| [[BIN1]] | biolink:contributes_to | Neurotoxicity (MONDO:0005527) |  | "BIN1 has already been linked to Tau pathology in several functional studies, first shown in fruit flies where a decrease in the BIN1 ortholog gene expression suppressed Tau-mediated neurotoxicity." |
| [[BIN1]] | biolink:associated_with | [[Memory impairment]] |  | "In human subjects, BIN1-carriers were associated with lower memory performance, mediated by higher tau-PET levels." |
| GLIS3 (HGNC:28510) | NOT biolink:associated_with | [[MAPT]] |  | "For the other loci that we were unable to replicate (SERPINB1 for Aβ42; and GLIS3, PCDH8, CTDP1 for pTau), there were no significant associations (P > 0.05) despite substantial sample sizes (n > 7000)." |
| PCDH8 (HGNC:8660) | NOT biolink:associated_with | [[MAPT]] |  | "For the other loci that we were unable to replicate (SERPINB1 for Aβ42; and GLIS3, PCDH8, CTDP1 for pTau), there were no significant associations (P > 0.05) despite substantial sample sizes (n > 7000)." |
| CTDP1 (HGNC:2498) | NOT biolink:associated_with | [[MAPT]] |  | "For the other loci that we were unable to replicate (SERPINB1 for Aβ42; and GLIS3, PCDH8, CTDP1 for pTau), there were no significant associations (P > 0.05) despite substantial sample sizes (n > 7000)." |
| [[MAPT]] | biolink:correlated_with | Neurodegeneration (HP:0002180) |  | "Similarly, the 3q28-locus for pTau from our findings colocalizes inconclusively (posterior probability of 0.73) to lateral ventricular volume by the CHARGE study, implying that the same genetic risk factors contribute to both phenotypes, strengthening the notion that neurodegeneration and (p)Tau pathology are highly correlated." |
| [[GMNC]] | biolink:associated_with | Neurodegeneration (HP:0002180) |  | "For both loci the allele that associated with an increase in pTau pathology in our dementia cohorts associated with a smaller ventricular volume, implying less neurodegeneration." |
| [[C16orf95]] | biolink:associated_with | Neurodegeneration (HP:0002180) |  | "For both loci the allele that associated with an increase in pTau pathology in our dementia cohorts associated with a smaller ventricular volume, implying less neurodegeneration." |
| GLIS1 (HGNC:29525) | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "For Aβ42, it was not possible to test the GLIS1-locus as this variant was not observed in our data, which is in concordance with the gnomAD browser reporting extremely low coverage and a MAF of 0.007 for rs185031519, the strongest GLIS1 SNP in Deming et al." |
| SERPINB1 (HGNC:3311) | NOT biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "For the other loci that we were unable to replicate (SERPINB1 for Aβ42; and GLIS3, PCDH8, CTDP1 for pTau), there were no significant associations (P > 0.05) despite substantial sample sizes (n > 7000)." |
| rs185031519 (variant) | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "For Aβ42, it was not possible to test the GLIS1-locus as this variant was not observed in our data, which is in concordance with the gnomAD browser reporting extremely low coverage and a MAF of 0.007 for rs185031519, the strongest GLIS1 SNP in Deming et al." |
