---
type: source
title: "Common BACE2 polymorphisms and CSF amyloid in APOE ε4 non-carriers"
paper_title: "Common BACE2 Polymorphisms are Associated with Altered Risk for Alzheimer’s Disease and CSF Amyloid Biomarkers in APOE ε4 Non-Carriers"
domain: neuroscience
status: developing
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001327
pmid: "31270419"
pmcid: "PMC6610620"
doi: "10.1038/s41598-019-45896-4"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC6610620/"
sources: ["[[.raw/01M4P89VBDQVH7S8SE47JARM24/normalized.md]]"]
tags: [secretase, biomarker, eqtl]
---

# Common BACE2 polymorphisms and CSF amyloid in APOE ε4 non-carriers

A four-part genetic and cell study of [[BACE2]], the close relative of [[BACE1]] that cuts [[APP]] at the β site weakly, at an α-like site, and at a "θ-secretase" site inside the [[Amyloid-beta]] domain, and that can also degrade Aβ. The authors tested whether common variants at the BACE2 locus on chromosome 21 change risk of [[Late-onset Alzheimer disease]], whether they track CSF Aβ1-42, whether they act through BACE2 expression, and whether raising BACE2 lowers secreted Aβ in cells.

## Why This Source Matters

Neither exome sequencing nor genome-wide scans had reported common or rare BACE1 or BACE2 variants as altering Alzheimer risk. This study finds a nominal, [[APOE]]-dependent signal at BACE2 in a neuropathology-confirmed cohort, links the same SNP region to CSF Aβ1-42 and to BACE2 mRNA, and shows in a neuroblastoma line that BACE2 overexpression lowers Aβ40 and Aβ42. It is hypothesis-generating rather than conclusive (see Assessment), but it matters for BACE inhibitor programmes, which cross-react with BACE2, and for rodent models that rely on the BACE1-preferring Swedish APP mutation.

## Design

- Discovery: the [[TGenII neuropathology cohort]], 1599 European-ancestry subjects over 65 at death (1014 pathologically verified cases, 585 controls); people with other neurological disease, stroke, cerebrovascular disease or Lewy bodies were excluded. Genotyped on the Affymetrix SNP 6.0 array.
- Replication of the biomarker arm: the [[Alzheimer's Disease Neuroimaging Initiative]] (ADNI), clinically diagnosed Alzheimer disease, [[Mild cognitive impairment]] and cognitively normal subjects, genotyped on the Illumina Human610-Quad chip; CSF Aβ1-42 analysed by linear regression.
- A 5 Mb region around BACE2 (hg19 chr21:40-45 Mb) was imputed with IMPUTE2 from 1000 Genomes phase 1. SNPs with minor allele frequency below 1% or genotyping rate below 95% were dropped. Logistic models used the first two ADMIXTURE population-structure vectors, sex and APOE ε4 dose (0, 1 or 2 alleles) with an APOE interaction term. Bonferroni correction was described in the methods for independent SNPs (r2 below 0.80).
- Expression: cortex array expression data from TGenII control donors only, three BACE2 probes, tested as an [[Expression quantitative trait locus analysis]].
- Cell work: Sleeping Beauty transposon BACE2 overexpression in [[BE2-M17]] neuroblastoma cells, which express BACE2 at under 0.5 FPKM, with ELISA of Aβ1-40 and Aβ1-42 in the medium after 72 hours.

## Findings

- Case-control in all subjects: the top SNP was [[BACE2 rs8134992]] (uncorrected p = 0.00136). With an APOE interaction term the top SNP was [[BACE2 rs2898441]] (p = 0.0267); with population structure and sex added it was [[BACE2 rs9978431]] (p = 0.0249). Splitting by APOE showed the locus signal only in ε4 non-carriers.
- CADD scores of the associated SNPs did not exceed 15, so none is predicted to change protein function directly.
- CSF Aβ1-42 in ADNI: association in the AD group (strongest [[BACE2 rs2837994]], p = 0.000183) and the MCI group (strongest [[BACE2 rs9980146]], p = 0.0207), again only in ε4 non-carriers and not in cognitively normal controls. See [[Decreased amyloid beta 42 peptide CSF concentration]].
- eQTL: all three BACE2 probes showed variant-expression associations in control cortex that were modified by APOE status. [[BACE2 rs2012050]] (p = 0.0425), also significant for CSF Aβ1-42 in ADNI MCI, was linked in ε4 non-carriers with the T/T genotype to lower BACE2 expression and higher CSF Aβ1-42.
- Overexpressing BACE2 lowered Aβ1-40 and Aβ1-42 in the culture medium (box plots only; no values or test statistic are given in the text).

## Interpretation offered

The authors read the data as BACE2 variants altering Aβ generation or clearance through BACE2 expression, with the APOE dependence possibly arising because BACE2 is high in neurons and glia and may rise with gliosis as disease progresses. They argue that BACE2 inhibition, an off-target effect of BACE1 inhibitors, is unlikely to be desirable given BACE2's Aβ-degrading activity (citing earlier work that raising BACE2 activity may be therapeutic), and that Swedish-mutation rodent models may under-represent BACE2 biology.

## Assessment

- Every headline p-value is uncorrected and nominal (0.0425 to 0.00136 in TGenII; 0.0207 to 0.000183 in ADNI); the text reports no SNP that survives the Bonferroni correction it describes, and the number of independent SNPs tested is not stated.
- The APOE-stratified signal comes from post-hoc splitting after interaction p-values near 0.025, and ADNI group sizes, effect sizes and the direction of the case-control effect are not given in the text; the full results sit in supplementary tables.
- Different SNPs top each analysis, so the claim of one consistent locus rests on proximity ("same region"), not on a shared lead variant; only rs2012050 bridges the eQTL and CSF analyses.
- Direction is hard to read: higher CSF Aβ1-42 usually means less brain deposition, while lower BACE2 expression should mean less Aβ degradation; the authors call the pairing "in agreement" with BACE2 degrading Aβ without resolving this.
- eQTL used control cortex only, the cell experiment used a single line with near-absent baseline BACE2, and the overexpression readout has no quantification in the text. Neither shows that the associated SNPs act on BACE2 in disease.
- The abstract and highlights say the risk effect is preferential to ε4 non-carriers; ε4 carriers, being fewer, may simply have less power.

## Open questions

- Does the BACE2 locus association with Alzheimer disease in APOE ε4 non-carriers survive multiple-testing correction and replicate in an independent large cohort such as the Alzheimer's Disease Genetics Consortium (the study reports only uncorrected p-values)?
- Which allele of the lead BACE2 SNPs raises or lowers Alzheimer risk, and in which direction does BACE2 expression move with disease status (the text gives direction only for rs2012050 and only in controls)?
- Does a lower BACE2 expression genotype lead to more or less amyloid deposition by amyloid PET or neuropathology, given that CSF Aβ1-42 was higher in the lower-expression group?
- Why would the BACE2 effect depend on APOE ε4 status (not tested mechanistically; only a gliosis-related speculation is offered)?
- Does BACE2 overexpression lower Aβ by θ-secretase cleavage of APP or by degrading Aβ itself, and by how much (no values are reported in the text)?

## Connections

- Gene and locus: [[BACE2]], variants [[BACE2 rs8134992]], [[BACE2 rs2898441]], [[BACE2 rs9978431]], [[BACE2 rs2837994]], [[BACE2 rs9980146]], [[BACE2 rs2012050]]
- Modifier of risk: [[APOE]]; disease: [[Alzheimer disease]]; stage: [[Mild cognitive impairment]]
- Related amyloid-handling genes: [[BACE1]], [[IDE]], [[ADAM10]], [[ADAM17]], [[PSEN1]], [[PSEN2]]
- Cohorts and methods: [[TGenII neuropathology cohort]], [[Alzheimer's Disease Neuroimaging Initiative]], [[Expression quantitative trait locus analysis]]
- Cell model: [[BE2-M17]]
- Biomarker: [[Decreased amyloid beta 42 peptide CSF concentration]]
- Related therapy context: [[APP-selective BACE1 inhibitor FAH65 from a phenytoin screening hit]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[BACE2]] | biolink:affects | [[APP]] |  | "Finally, it is clear that the homologue of BACE1, BACE2 can also cleave both APP and amyloid beta (Aβ)." |
| [[BACE2]] | biolink:genetically_interacts_with | [[APOE]] |  | "These findings suggest that genetic variation at the BACE2 locus modifies AD risk for those individuals who don’t carry the ε4 variant of APOE." |
| [[BACE2]] | biolink:associated_with | [[BACE1]] |  | "Fluhrer et al. demonstrated that the cleavage of APP via BACE2 results in production of soluble APP-α and reduced production of amyloidogenic species suggesting that APP metabolism by BACE2 acts in an opposing fashion to BACE1 in cells that express both enzymes." |
| [[BACE2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In this study, we report that common single nucleotide polymorphism (SNP) variation in BACE2 is associated with altered AD risk in apolipoprotein E gene (APOE) epsilon 4 variant (ε4) non-carriers." |
| [[BACE2]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Due to this finding we sought to understand the possible genetic risk contributed by the BACE2 locus to the development of late-onset Alzheimer’s disease (AD)." |
| [[BACE2]] | biolink:associated_with | [[Down syndrome]] (MESH:D004314) |  | "Although two studies, one in the Finnish population and one in Down syndrome, have both implicated BACE2 in disease, to date neither exome sequencing or genome-wide association studies have reported common or rare pathogenic variability in either BACE1 or BACE2 as altering risk for disease." |
| [[BACE2]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=decreased | "Lastly, Abdul-Hay et al. demonstrated that BACE2 can degrade Aβ with an efficiency second only to insulin degrading enzyme (IDE)." |
| [[BACE2]] | biolink:affects | Amyloid-beta 1-42 (MESH:C075222) | direction=decreased | "Lastly, overexpression of BACE2 in vitro resulted in decreased Aβ1-40 and Aβ1-42 fragments in a cell line model of Aβ production." |
| [[BACE2]] | biolink:affects | Amyloid-beta 1-40 (MESH:C078592) | direction=decreased | "Lastly, overexpression of BACE2 in vitro resulted in decreased Aβ1-40 and Aβ1-42 fragments in a cell line model of Aβ production." |
| [[BACE1]] | biolink:affects | [[APP]] |  | "It is known that BACE2 can cleave APP at the β-secretase site (albeit with much lower efficiency than BACE1) and near the α-secretase site as well." |
| [[ADAM10]] | biolink:affects | [[APP]] |  | "More recently, reduced function variants of both ADAM10 and ADAM17, the enzymes involved in the alternate α-secretase cleavage of APP, have been shown to increase the risk of AD as well." |
| [[ADAM17]] | biolink:affects | [[APP]] |  | "More recently, reduced function variants of both ADAM10 and ADAM17, the enzymes involved in the alternate α-secretase cleavage of APP, have been shown to increase the risk of AD as well." |
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Classically, the causative mutations were in APP itself and in the presenilin genes – PSEN1 and 2." |
| [[APP]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "The amyloid (Aβ) hypothesis of Alzheimer’s disease (AD) has primarily been driven by the observation that genetic variability that alters amyloid precursor protein (APP) metabolism increases de position of Aβ." |
| [[PSEN1]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Classically, the causative mutations were in APP itself and in the presenilin genes – PSEN1 and 2." |
| [[PSEN1]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "Aβ is generated by the sequential actions of β-secretase (BACE1) and γ-secretase, of which the presenilins are the major component." |
| [[PSEN2]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Classically, the causative mutations were in APP itself and in the presenilin genes – PSEN1 and 2." |
| [[PSEN2]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "Aβ is generated by the sequential actions of β-secretase (BACE1) and γ-secretase, of which the presenilins are the major component." |
| [[BACE1]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "Aβ is generated by the sequential actions of β-secretase (BACE1) and γ-secretase, of which the presenilins are the major component." |
| [[ADAM10]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "More recently, reduced function variants of both ADAM10 and ADAM17, the enzymes involved in the alternate α-secretase cleavage of APP, have been shown to increase the risk of AD as well." |
| [[ADAM17]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "More recently, reduced function variants of both ADAM10 and ADAM17, the enzymes involved in the alternate α-secretase cleavage of APP, have been shown to increase the risk of AD as well." |
| [[IDE]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=decreased | "Lastly, Abdul-Hay et al. demonstrated that BACE2 can degrade Aβ with an efficiency second only to insulin degrading enzyme (IDE)." |
| [[Alzheimer disease]] (MESH:D000544) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "The amyloid (Aβ) hypothesis of Alzheimer’s disease (AD) has primarily been driven by the observation that genetic variability that alters amyloid precursor protein (APP) metabolism increases de position of Aβ." |
| [[BACE2]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "CSF Aβ1-42 levels are associated with BACE2 locus SNPs in AD and MCI Individuals from the ADNI cohort who are APOE ε4 non-carriers." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "These association results, in a well characterized neuropathology-confirmed cohort, suggest that there are common SNPs within the BACE2 locus that alter AD risk preferentially in individuals who do not carry the APOE ε4 genetic risk for the disease." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "These association results, in a well characterized neuropathology-confirmed cohort, suggest that there are common SNPs within the BACE2 locus that alter AD risk preferentially in individuals who do not carry the APOE ε4 genetic risk for the disease." |
| [[BACE2 rs8134992]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The SNP rs8134992 was identified as the most significant with an uncorrected p-value of 0.00136." |
| [[BACE2 rs2898441]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "This yielded a significant association at rs2898441 with an uncorrected p-value of 0.0267." |
| [[BACE2 rs9978431]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "This resulted in rs9978431 as the SNP with the most significant p-value at 0.0249." |
| [[BACE2 rs2837994]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "The strongest associated SNPs (rs2837994 in AD at p = 0.000183 and rs9980146 in MCI at p = 0.0207, both uncorrected) were located in the same region as defined above for the BACE2 genetic association." |
| [[BACE2 rs9980146]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "The strongest associated SNPs (rs2837994 in AD at p = 0.000183 and rs9980146 in MCI at p = 0.0207, both uncorrected) were located in the same region as defined above for the BACE2 genetic association." |
| [[BACE2]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Collectively, this work supports previous analyses suggesting that genetic variability in BACE2 alters mRNA expression and plays a role in AD." |
| [[BACE2]] | biolink:associated_with | Gliosis (HP:0002171; MESH:D005911) |  | "This means that with the gliosis inherent in the AD disease process, BACE2 expression may become more pronounced as the disease progresses." |
| Swedish APP mutation (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Indeed, this has wide reaching implications 1) for assessment of BACE inhibition in AD treatment, and 2) in the interpretation of AD rodent models where the Swedish (“BACE1 preferring”) mutation is used to model the disease." |
| [[BACE2 rs2012050]] | biolink:associated_with | Amyloid-beta 1-42 (MESH:C075222) |  | "APOE ε4 non-carriers of the minor allele of rs2012050 demonstrate lower BACE2 gene expression and also higher CSF Aβ1-42 levels (Fig. 4)." |
| [[BACE2 rs2012050]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "SNP rs2012050 is associated with altered BACE2 gene expression and Aβ1-42 CSF levels." |
