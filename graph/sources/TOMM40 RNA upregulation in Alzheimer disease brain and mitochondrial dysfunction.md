---
type: source
title: "TOMM40 RNA upregulation in Alzheimer disease brain and mitochondrial dysfunction"
paper_title: "TOMM40 RNA Transcription in Alzheimer’s Disease Brain and Its Implication in Mitochondrial Dysfunction"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000083
pmid: "34204109"
pmcid: "PMC8226536"
doi: "10.3390/genes12060871"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8226536/"
sources: ["[[.raw/01M4DY94FP6G53R3XZB5CRVTKD/normalized.md]]"]
tags: [gene-expression, mitochondria, pseudogene, rt-qpcr, alzheimer-risk-locus]
---

# TOMM40 RNA upregulation in Alzheimer disease brain and mitochondrial dysfunction

A laboratory study from the University of Washington Alzheimer's Disease Research Center that asks whether [[TOMM40]] RNA is higher or lower in [[Alzheimer disease]] brain than in control brain, a question earlier studies answered in both directions. The authors first show that the human genome carries [[TOMM40 pseudogene RNAs]] that are expressed and are co-measured by ordinary TOMM40 expression assays, then build a [[Primary transcript RT-qPCR assay]] that avoids them, apply it to postmortem frontal lobe, test the RNA against genotypes at the [[APOE]]/TOMM40 locus, and follow TOMM40 RNA in cultured cell lines under oxidative stress.

## Design

- Postmortem middle frontal gyrus from the University of Washington brain bank, frozen within 10 hours of death. Alzheimer cases were confirmed neuropathologically (Braak stage V to VI); controls were over 65 years old, never diagnosed, with no Alzheimer neuropathology (Braak I to III). Group sizes for the main comparison are given in a demographics table that is not reproduced in the text; a digital PCR subset had 29 cases and 16 controls.
- Genotyping by TaqMan for [[APOE rs429358]], rs7412, rs71352238, [[TOMM40 rs2075650]], [[TOMM40 rs741780]] and rs10119, and by capillary electrophoresis fragment sizing for the poly-T length marker [[TOMM40 rs10524523]] (S, L and VL classes).
- RNA read out by RT-qPCR normalised to ACTB (smaller delta-CT means more RNA), and by digital PCR for absolute fractions of pseudogene and surrogate RNA in the total TOMM40-related pool. Statistics were independent-samples t-tests.
- Cell work in [[HepG2]], [[U-87 MG]], [[U-118 MG]], [[LN-229]] and [[SH-SY5Y]]: oxidative stress with 500 µM [[Hydrogen peroxide]] for 24 hours, then TOMM40 surrogate RNA, mitochondrial DNA copy number (against HGB) and mitochondrial membrane potential (JC-1 red to green ratio, with CCCP as a control).

## Findings

- A BLAT search of the TOMM40 cDNA against hg38 found six further hits: TOMM40L, which is moderately similar, and five loci with 87% to 96% identity that lack introns or a full open reading frame (the pseudogenes [[TOMM40P1]], [[TOMM40P2]], [[TOMM40P3]], [[TOMM40P4]] and an unnamed one the authors call P1b). All of them gave RNA in HepG2, U-87 and SH-SY5Y cells, and P1 primers also amplified TOMM40 cDNA.
- Allele-specific primers could not cleanly separate TOMM40 from the pseudogenes: even junction-spanning exon 1-2 and exon 3-4 assays cross-amplified pseudogene templates, as did an exon 4-5 assay modelled on a widely used commercial TaqMan assay (Hs01587378_mH).
- A P1b/P2 assay put pseudogene RNA at about 10% to 18% of the total TOMM40-related RNA pool, a lower bound because P1 was not measured. The intron 9 surrogate assay (IVS9) reflected roughly 7% to 20% of the pool.
- With the commercial assay there was no difference between Alzheimer and control frontal lobe. With the IVS9 assay TOMM40 RNA was about 2.5-fold higher in Alzheimer brain (p < 0.001); an exon 6 to intron 6 assay gave a similar roughly 2 delta-CT separation in a pilot.
- Genotype effects on the IVS9 signal: significant for the poly-T marker rs10524523 (p < 0.02; S carriers had higher RNA than VL carriers) and for rs741780 in intron 8 (p < 0.01). No association for rs429358 (ε4-defining C allele) or rs2075650, and none for rs71352238 or rs10119.
- In four cell lines, hydrogen peroxide raised TOMM40 surrogate RNA about 1.2 to 1.5-fold while mitochondrial DNA copy number fell to roughly 20% to 60% and membrane potential to roughly 20% to 75% of untreated levels, which the authors read as TOMM40 upregulation tracking [[Mitochondrial dysfunction]]. The copy-number and potential assays were run in separate cultures and were not statistically compared.

## Why This Source Matters

It offers a reason why published TOMM40 expression results in Alzheimer brain disagree (the assays also count pseudogene RNA) and shows that, once the pseudogenes are excluded, TOMM40 RNA is higher in diseased frontal cortex. It also gives an expression-based handle on TOMM40 that does not depend on [[APOE]] ε4 status, since the two best-known risk SNPs did not predict RNA level, while two SNPs in introns 6 to 8 did. The finding links the locus to mitochondrial protein import and bioenergetics rather than lipid transport.

## Assessment

- Sample sizes for the brain comparison are small and the authors call for replication in larger cohorts and other brain regions; only frontal lobe was studied.
- The IVS9 assay measures unspliced primary transcript as a surrogate for mRNA, on the assumption that the splicing ratio is constant across samples. That was argued rather than tested, and protein was not measured.
- Pseudogene RNA fractions come from one primer set that itself cross-amplifies other pseudogenes, so the true fraction is unknown; the biological role of the pseudogene RNAs (a buffering effect is proposed) is speculation.
- The link to mitochondrial dysfunction comes from acute hydrogen peroxide stress in cancer-derived cell lines, not from brain tissue, and the authors read the RNA rise as a possible compensatory feedback response; the direction of cause is not established.
- The discussion once writes "rs10527523" where rs10524523 is meant. The S-versus-VL direction contradicts an earlier report (Linnertz and colleagues) that the authors attribute to pseudogene co-measurement.
- The genotype comparisons use t-tests across several variants with no stated multiple-testing correction.

## Open Questions

- Does the roughly 2.5-fold rise in TOMM40 RNA in Alzheimer frontal cortex replicate in a larger cohort and in other brain regions (the study used one region and a small sample)?
- Is TOM40 protein also raised in Alzheimer brain when TOMM40 RNA is raised (protein was not measured)?
- Which of the TOMM40 pseudogenes are transcribed in human brain tissue, and what do their RNAs do (only cell lines were tested directly, and the primers cross-amplify)?
- Does the primary transcript surrogate track spliced TOMM40 mRNA equally well in Alzheimer and control brain (the splicing ratio was assumed constant)?
- Does the poly-T length at rs10524523 change TOMM40 transcription in a direction that agrees across studies once pseudogene RNA is excluded (this study and an earlier one disagree)?

## Connections

- Disease: [[Alzheimer disease]], [[Mitochondrial dysfunction]]
- Genes: [[TOMM40]], [[APOE]], [[TOMM40P1]], [[TOMM40P2]], [[TOMM40P3]], [[TOMM40P4]]
- Variants: [[TOMM40 rs10524523]], [[TOMM40 rs741780]], [[TOMM40 rs2075650]], [[APOE rs429358]]
- Chemical: [[Hydrogen peroxide]]
- Cell lines: [[HepG2]], [[U-87 MG]], [[U-118 MG]], [[LN-229]], [[SH-SY5Y]]
- Methods: [[Primary transcript RT-qPCR assay]], [[TOMM40 pseudogene RNAs]]
- Genetic association at the same locus: [[Late-onset Alzheimer disease association study in the Russian population]], [[SNP association study of Alzheimer disease in southern Chinese population]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[TOMM40]] | biolink:associated_with | [[APOE]] |  | "Because of the strong linkage disequilibrium (LD) of these genes with APOE, researchers have always assumed that the disease-associated genetic signals from these genes solely reflect their associations with the APOE ε4 allele." |
| [[TOMM40]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Increasing evidence suggests that the Translocase of Outer Mitochondria Membrane 40 (TOMM40) gene may contribute to the risk of Alzheimer’s disease (AD)." |
| [[TOMM40]] | biolink:biomarker_for | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "Overall, differential transcription of TOMM40 RNA in the brain is associated with AD and could be an indicator of mitochondrial dysfunction." |
| [[TOMM40]] | biolink:negatively_correlated_with | DNA (CHEBI:16991; MESH:D004247) |  | "Additionally, elevated TOMM40 RNA levels were associated with decreases in mitochondrial DNA copy number and mitochondrial membrane potential in oxidative stress-challenged cells." |
| [[NECTIN2]] | biolink:associated_with | [[APOE]] |  | "Because of the strong linkage disequilibrium (LD) of these genes with APOE, researchers have always assumed that the disease-associated genetic signals from these genes solely reflect their associations with the APOE ε4 allele." |
| [[APOC1]] | biolink:associated_with | [[APOE]] |  | "Because of the strong linkage disequilibrium (LD) of these genes with APOE, researchers have always assumed that the disease-associated genetic signals from these genes solely reflect their associations with the APOE ε4 allele." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The strength of the association between APOE and AD risk is orders of magnitude larger than all other AD loci combined, suggesting that this locus is a major biological contributor to the risk of AD." |
| [[NECTIN2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Besides APOE itself, the extended region surrounding APOE has also been consistently identified by genome-wide association studies (GWAS) to strongly associate with AD." |
| [[APOC1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Besides APOE itself, the extended region surrounding APOE has also been consistently identified by genome-wide association studies (GWAS) to strongly associate with AD." |
| RNA (CHEBI:33697; MESH:D012313) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Using this assay, we showed that TOMM40 RNA was upregulated in AD PMB." |
| DNA (CHEBI:16991; MESH:D004247) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Thus, abnormal mitochondrial dynamics, including components, morphology, membrane potential, and DNA copy number could contribute to AD risk." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, multiple studies have shown that individuals who carry an African ε4 haplotype of APOE have less risk of developing AD when compared to those with a Caucasian ε4 haplotype." |
| RNA (CHEBI:33697; MESH:D012313) | biolink:biomarker_for | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "Overall, differential transcription of TOMM40 RNA in the brain is associated with AD and could be an indicator of mitochondrial dysfunction." |
| [[TOMM40]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "TOMM40 has not only been genetically linked to AD risk but may also be functionally connected with AD pathophysiology." |
| [[APP]] | biolink:physically_interacts_with | [[TOMM40]] |  | "For example, the Aβ peptide is imported into the mitochondria via the TOM40 protein and the amyloid precursor protein has been reported to be associated with TOM40 in AD, but not controls; Aβ peptides and mis-directed amyloid precursor protein interfere with mitochondrial protein import and disrupt mitochondrial function; and the accumulation of Aβ in mitochondria leads to the overproduction of reactive oxygen species." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:physically_interacts_with | [[TOMM40]] |  | "For example, the Aβ peptide is imported into the mitochondria via the TOM40 protein and the amyloid precursor protein has been reported to be associated with TOM40 in AD, but not controls; Aβ peptides and mis-directed amyloid precursor protein interfere with mitochondrial protein import and disrupt mitochondrial function; and the accumulation of Aβ in mitochondria leads to the overproduction of reactive oxygen species." |
| [[TOMM40]] | biolink:associated_with | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "Consequently, TOMM40 expression levels may be impacting mitochondrial function and contributing to AD risk." |
| [[TOMM40 rs10524523]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A deoxythymidine homopolymer (poly-T) at rs10524523 within intron 6 of the TOMM40 has been associated with the risk and age at onset of AD; and the “VL” variant of this poly-T marker has been associated with increased mRNA expression of both TOMM40 and APOE in APOE ε3/ε3 brain." |
| mRNA (CHEBI:33699; MESH:D012333) | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Numerous studies consistently showed lower TOMM40 mRNA levels in AD blood samples compared to controls, and a decrease in TOM40 protein level has also been observed in AD blood." |
| RNA (CHEBI:33697; MESH:D012313) | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Numerous studies consistently showed lower TOMM40 mRNA levels in AD blood samples compared to controls, and a decrease in TOM40 protein level has also been observed in AD blood." |
| SNP (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In a Chinese cohort, SNPs in TOMM40 remained statistically significantly associated with AD after adjusting for age, sex, and APOE ε4 status." |
| [[APP]] | biolink:causes | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "For example, the Aβ peptide is imported into the mitochondria via the TOM40 protein and the amyloid precursor protein has been reported to be associated with TOM40 in AD, but not controls; Aβ peptides and mis-directed amyloid precursor protein interfere with mitochondrial protein import and disrupt mitochondrial function; and the accumulation of Aβ in mitochondria leads to the overproduction of reactive oxygen species." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:affects | reactive oxygen species (CHEBI:26523; MESH:D017382) | direction=increased | "For example, the Aβ peptide is imported into the mitochondria via the TOM40 protein and the amyloid precursor protein has been reported to be associated with TOM40 in AD, but not controls; Aβ peptides and mis-directed amyloid precursor protein interfere with mitochondrial protein import and disrupt mitochondrial function; and the accumulation of Aβ in mitochondria leads to the overproduction of reactive oxygen species." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:causes | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "For example, the Aβ peptide is imported into the mitochondria via the TOM40 protein and the amyloid precursor protein has been reported to be associated with TOM40 in AD, but not controls; Aβ peptides and mis-directed amyloid precursor protein interfere with mitochondrial protein import and disrupt mitochondrial function; and the accumulation of Aβ in mitochondria leads to the overproduction of reactive oxygen species." |
| [[TOMM40 rs10524523]] | biolink:associated_with | mRNA (CHEBI:33699; MESH:D012333) |  | "A deoxythymidine homopolymer (poly-T) at rs10524523 within intron 6 of the TOMM40 has been associated with the risk and age at onset of AD; and the “VL” variant of this poly-T marker has been associated with increased mRNA expression of both TOMM40 and APOE in APOE ε3/ε3 brain." |
| [[TOMM40 rs10524523]] | biolink:associated_with | RNA (CHEBI:33697; MESH:D012313) |  | "A deoxythymidine homopolymer (poly-T) at rs10524523 within intron 6 of the TOMM40 has been associated with the risk and age at onset of AD; and the “VL” variant of this poly-T marker has been associated with increased mRNA expression of both TOMM40 and APOE in APOE ε3/ε3 brain." |
| [[TOMM40]] | biolink:associated_with | [[TOMM40P1]] |  | "None of the pseudogene primer sets amplified TOMM40 cDNA except the primer set of P1 (Figure 1B, lane 2), which is likely due to the high homology between TOMM40 cDNA and P1." |
| [[TOMM40]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "On the contrary, TOMM40 mRNA showed significantly (p < 0.001, t-test) higher expression (≈2.5-fold) in AD compared to control when the IVS9 assay was used (Figure 4B)." |
| mRNA (CHEBI:33699; MESH:D012333) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "On the contrary, TOMM40 mRNA showed significantly (p < 0.001, t-test) higher expression (≈2.5-fold) in AD compared to control when the IVS9 assay was used (Figure 4B)." |
| mRNA (CHEBI:33699; MESH:D012333) | biolink:derives_from | pre-mRNA (CHEBI:139356; MESH:D012322) |  | "While the primary transcript (pre-mRNA) transcription level is expected to be only a fraction of the spliced mRNA transcription level, this proportion is likely retained consistently across samples obtained from same cell/tissue-types." |
| [[TOMM40]] | biolink:associated_with | SNCA (HGNC:11138) |  | "TOM40 protein levels are significantly reduced in brains of Parkinson’s disease patients and in α-Syn transgenic mice." |
| [[TOMM40]] | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "TOM40 protein levels are significantly reduced in brains of Parkinson’s disease patients and in α-Syn transgenic mice." |
| [[TOMM40]] | biolink:associated_with | ovarian cancer (MONDO:0008170; MESH:D010051) |  | "TOMM40 overexpression at both the transcriptional and translational levels in ovarian cancer has been shown to correlate with increased cell proliferation, migration, and invasion." |
| [[TOMM40]] | biolink:positively_correlated_with | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "These findings indicate that upregulation of TOMM40 RNA levels corresponds with mitochondrial dysfunction." |
| [[TOMM40]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "Such epidemiological data strongly support the idea that TOMM40 plays a direct role in cognition and healthy aging." |
| [[Hydrogen peroxide]] (MESH:D006861) | biolink:affects | [[TOMM40]] | direction=increased | "After H2O2 treatment, TOMM40 surrogate RNA levels were increased (≈1.2–1.5-fold higher than the untreated one, which corresponded with a decreased DNA copy number (≈20–60% of the untreated levels) and a decreased membrane potential (≈20–75% of the untreated one; Figure 6)." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Because age is the most important risk factor for AD, the combined biological consequences of TOMM40 and APOE may represent a molecular mechanism explaining the APOE locus’ strong genetic association with AD." |
| [[APOE]] | biolink:associated_with | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "Thus, the unique genomic arrangement of the TOMM40-APOE gene cluster raises a possibility that genetic variants of the APOE locus could relate indirectly to mitochondrial function through LD with TOMM40." |
| [[APOE rs429358]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "With biologically meaningful RNA measurements in hand, we further examined the relationship between TOMM40 RNA levels and some AD-associated genotypes in human PMB." |
| [[TOMM40 rs2075650]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The G allele of rs2075650 has been associated with a range of phenotypes including reduced longevity, reduced BMI, and increased low-density lipoprotein cholesterol, as well as an increased risk of AD." |
| [[TOMM40 rs10524523]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "With biologically meaningful RNA measurements in hand, we further examined the relationship between TOMM40 RNA levels and some AD-associated genotypes in human PMB." |
| [[TOMM40 rs741780]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "With biologically meaningful RNA measurements in hand, we further examined the relationship between TOMM40 RNA levels and some AD-associated genotypes in human PMB." |
| TOMM40 rs71352238 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "With biologically meaningful RNA measurements in hand, we further examined the relationship between TOMM40 RNA levels and some AD-associated genotypes in human PMB." |
| TOMM40 rs10119 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "With biologically meaningful RNA measurements in hand, we further examined the relationship between TOMM40 RNA levels and some AD-associated genotypes in human PMB." |
| [[Hydrogen peroxide]] (MESH:D006861) | biolink:contributes_to | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "After H2O2 treatment, TOMM40 surrogate RNA levels were increased (≈1.2–1.5-fold higher than the untreated one, which corresponded with a decreased DNA copy number (≈20–60% of the untreated levels) and a decreased membrane potential (≈20–75% of the untreated one; Figure 6)." |
| RNA (CHEBI:33697; MESH:D012313) | biolink:positively_correlated_with | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "These findings indicate that upregulation of TOMM40 RNA levels corresponds with mitochondrial dysfunction." |
| DNA (CHEBI:16991; MESH:D004247) | biolink:associated_with | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "After H2O2 treatment, TOMM40 surrogate RNA levels were increased (≈1.2–1.5-fold higher than the untreated one, which corresponded with a decreased DNA copy number (≈20–60% of the untreated levels) and a decreased membrane potential (≈20–75% of the untreated one; Figure 6)." |
| [[TOMM40 rs10524523]] | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "Evidence also suggested that the length of rs10524523 (poly-T) within intron 6 of the TOMM40 is linked to different levels of risk and age of onset of cognitive decline." |
| [[TOMM40 rs2075650]] | biolink:has_phenotype | Increased LDL cholesterol (HP:0003141) |  | "The G allele of rs2075650 has been associated with a range of phenotypes including reduced longevity, reduced BMI, and increased low-density lipoprotein cholesterol, as well as an increased risk of AD." |
| [[Hydrogen peroxide]] (MESH:D006861) | biolink:affects | RNA (CHEBI:33697; MESH:D012313) | direction=increased | "After H2O2 treatment, TOMM40 surrogate RNA levels were increased (≈1.2–1.5-fold higher than the untreated one, which corresponded with a decreased DNA copy number (≈20–60% of the untreated levels) and a decreased membrane potential (≈20–75% of the untreated one; Figure 6)." |
| [[Hydrogen peroxide]] (MESH:D006861) | biolink:affects | DNA (CHEBI:16991; MESH:D004247) | direction=decreased | "After H2O2 treatment, TOMM40 surrogate RNA levels were increased (≈1.2–1.5-fold higher than the untreated one, which corresponded with a decreased DNA copy number (≈20–60% of the untreated levels) and a decreased membrane potential (≈20–75% of the untreated one; Figure 6)." |
| [[TOMM40 rs2075650]] | biolink:associated_with | low-density lipoprotein cholesterol (CHEBI:47774; MESH:D008078) |  | "The G allele of rs2075650 has been associated with a range of phenotypes including reduced longevity, reduced BMI, and increased low-density lipoprotein cholesterol, as well as an increased risk of AD." |
| [[TOMM40 rs2075650]] | biolink:correlated_with | [[APOE rs429358]] |  | "The SNP rs2075650 located in intron 2 of TOMM40 has been considered a proxy of the SNP rs429358 that defines the ε4 allele of APOE." |
| [[TOMM40 rs10524523]] | biolink:correlated_with | [[APOE rs429358]] |  | "For rs10524523, we stratified the “S” and “VL” variants only, excluding the third variant “L”, which is linked specifically with the ε4 variant of rs429358 that was analyzed separately." |
| [[TOMM40]] | biolink:positively_correlated_with | [[APOE]] |  | "The consistent upregulation of both TOMM40 and APOE in AD brains makes the concept of co-regulation of these genes through the same topological associating domain even more appealing." |
| [[APOE rs429358]] | NOT biolink:associated_with | RNA (CHEBI:18273; MESH:D012313) |  | "Our genetic association analyses revealed no difference between TOMM40 RNA transcription levels with either APOE rs429358 variants (C/ε4+ vs. C/ε4−) or TOMM40 rs2075650 variants (G+ vs. G−), two SNPs that have been consistently linked to AD risk through GWAS studies." |
| [[TOMM40 rs2075650]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our genetic association analyses revealed no difference between TOMM40 RNA transcription levels with either APOE rs429358 variants (C/ε4+ vs. C/ε4−) or TOMM40 rs2075650 variants (G+ vs. G−), two SNPs that have been consistently linked to AD risk through GWAS studies." |
| [[TOMM40 rs2075650]] | NOT biolink:associated_with | RNA (CHEBI:18273; MESH:D012313) |  | "Our genetic association analyses revealed no difference between TOMM40 RNA transcription levels with either APOE rs429358 variants (C/ε4+ vs. C/ε4−) or TOMM40 rs2075650 variants (G+ vs. G−), two SNPs that have been consistently linked to AD risk through GWAS studies." |
| [[TOMM40 rs10524523]] | biolink:associated_with | RNA (CHEBI:18273; MESH:D012313) |  | "In the case of rs10524523, we observed a higher transcription level (lower ΔCT value) of TOMM40 RNA in the “S” variant when compared to the “VL” allele." |
| [[TOMM40 rs10524523]] | biolink:associated_with | mRNA (CHEBI:33699; MESH:D012333) |  | "This result is opposite to the study of Linnertz et al., who showed TOMM40 mRNA levels were lower in “S” homozygotes compared with “VL” homozygotes in the AD brain." |
| [[TOMM40 rs741780]] | biolink:associated_with | RNA (CHEBI:18273; MESH:D012313) |  | "On the contrary, the SNPs rs10527523 and rs741780 showed significant allelic differences associated with TOMM40 RNA transcription." |
| RNA (CHEBI:18273; MESH:D012313) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Increased TOMM40 RNA transcription associated with AD could lead to changes in mitochondrial protein import, which might affect maintenance of mitochondrial membrane potential and overall mitochondrial function." |
| DNA (CHEBI:16991; MESH:D004247) | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Studies have also shown that MtDNA levels were decreased by 30–50% in the frontal cortex of AD patients when compared to controls." |
| DNA (CHEBI:16991; MESH:D004247) | biolink:associated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Significant differences in this copy number have been reported across different brain regions, and these variations were more pronounced in patients affected by neurodegenerative disorders." |
| RNA (CHEBI:18273; MESH:D012313) | biolink:positively_correlated_with | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "Our analyses showed that the increased TOMM40 RNA levels are associated with a lower MtDNA copy number and a lower mitochondrial membrane potential, which together signified a decrease in mitochondrial function." |
| [[Mitochondrial dysfunction]] (MESH:D028361) | biolink:associated_with | mRNA (CHEBI:33699; MESH:D012333) |  | "This observation could be explained by a feedback response to restore mitochondria function via upregulation of TOMM40 mRNA." |
| DNA (CHEBI:16991; MESH:D004247) | biolink:biomarker_for | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "MtDNA copy number is a measure of the number of mitochondrial genomes per cell and is a proxy for mitochondrial function." |
| [[TOMM40]] | biolink:associated_with | [[Hydrogen peroxide]] (MESH:D006861) |  | "The fold change of H2O2-treated cells was compared to the untreated cells (set as baseline of 1.0)." |
| [[Hydrogen peroxide]] (MESH:D006861) | biolink:associated_with | RNA (CHEBI:33697; MESH:D012313) |  | "The fold change of H2O2-treated cells was compared to the untreated cells (set as baseline of 1.0)." |
| [[TOMM40 rs741780]] | biolink:associated_with | RNA (CHEBI:33697; MESH:D012313) |  | "The t-test p values are shown where significant associations with TOMM40 intron 6 poly-T SNP rs10524523 (p < 0.02) and intron 8 SNP rs741780 (p < 0.01) were detected." |
| [[Hydrogen peroxide]] (MESH:D006861) | biolink:associated_with | DNA (CHEBI:16991; MESH:D004247) |  | "The fold change of H2O2-treated cells was compared to the untreated cells (set as baseline of 1.0)." |
