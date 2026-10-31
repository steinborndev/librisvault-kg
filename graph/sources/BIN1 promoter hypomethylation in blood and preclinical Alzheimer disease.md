---
type: source
title: "BIN1 promoter hypomethylation in blood and preclinical Alzheimer disease"
paper_title: "Association between methylation of BIN1 promoter in peripheral blood and preclinical Alzheimer’s disease"
domain: neuroscience
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001269
pmid: "33531457"
pmcid: "PMC7854626"
doi: "10.1038/s41398-021-01218-9"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC7854626/"
sources: ["[[.raw/01M4P89VAFEFP6ZRQRGY16TRYZ/normalized.md]]"]
tags: [epigenetics, biomarker, cohort]
---

# BIN1 promoter hypomethylation in blood and preclinical Alzheimer disease

Cross-sectional study of 814 northern Han Chinese adults without objective cognitive impairment from the [[Chinese Alzheimer's Biomarker and LifestylE cohort]] (484 cognitively normal, 330 with [[Subjective cognitive decline]]). [[DNA methylation]] of the [[BIN1]] promoter in peripheral blood was measured by [[MethylTarget sequencing]] across six CpG-island regions (BIN1_01 to BIN1_06) and tested against preclinical status and cerebrospinal fluid markers.

## Design

- CSF [[Amyloid-beta]] 42, total tau and phosphorylated tau (181) were measured by Innotest ELISA; participants were called positive on a tertile rule: Aβ42 in the lowest third (A+, at most 120.71 pg/mL), p-tau in the top third (T+, at least 39.15 pg/mL), t-tau in the top third (N+, at least 184.19 pg/mL). See [[ATN framework]].
- [[APOE]] genotype came from rs7412 and rs429358 by SNaPshot.
- Regressions were adjusted for age, sex, education, APOE ε4 status and assay variation; Bonferroni correction was applied.

## Findings

- Participants with subjective cognitive decline had lower BIN1 promoter methylation than cognitively normal participants (p = 8.47 x 10^-6), and the A+ group lower than the A- group (p = 0.0060). Methylation fell stepwise from ATN stage 0 to stage 2 (stage 2 versus stage 0, p = 0.0079). Those with subjective decline and positive Aβ42 had the lowest values (p < 0.0001 against cognitively normal A-).
- The difference sat only in region BIN1_01 (p = 1.63 x 10^-5), not in BIN1_02 to BIN1_06.
- Discrimination was weak: AUROC 0.5918 (cognitively normal versus subjective decline) and 0.6448 (cognitively normal A- versus subjective decline A+), with heavy overlap.
- In all participants, lower methylation went with lower CSF Aβ42 (p = 0.0008; see [[Decreased amyloid beta 42 peptide CSF concentration]]) and higher p-tau/Aβ42 (p = 0.0001) and t-tau/Aβ42 (p < 0.0001), but not with p-tau or t-tau alone.
- These associations held in the subjective decline subgroup and not in the cognitively normal subgroup. Only there was lower methylation also tied to higher CSF p-tau (p = 0.0028; see [[Increased CSF phosphorylated tau concentration]]) and t-tau (p = 0.0130; see [[Increased CSF total tau concentration]]), and the tau links survived adjustment for Aβ42.
- Adjusting for an APOE ε4 by methylation interaction left the Aβ42 and ratio associations intact; the interaction itself had a modest effect on p-tau (p = 0.0195). Effects looked larger in ε4 carriers (122 of 814) but the sample was small. A negative methylation to p-tau link appeared only in carriers.
- Two promoter SNPs with minor allele frequency above 0.05, [[BIN1 rs58402148]] (0.13) and [[BIN1 rs17014923]] (0.10), were not linked to preclinical status or CSF markers but were strongly linked to methylation (p < 0.0001); adding them changed nothing. Blood cell counts and sample storage time also did not change the results.
- Methylation was unrelated to sex, APOE ε4 status or age.

## Why This Source Matters

It moves BIN1 methylation, previously reported in autopsy brain, into blood and into the preclinical stage, and ties it to amyloid and tau readouts independent of the known risk SNPs and APOE. The authors argue epigenetic control, which is more plastic than sequence variation, could make BIN1 a more tractable target. The signal is modest at the individual level, so it is a risk-association finding rather than a diagnostic test.

## Assessment

- Cross-sectional, so direction and timing cannot be inferred; the authors call for longitudinal cohorts.
- Blood BIN1 expression was not measured alongside methylation, so the functional consequence of hypomethylation is inferred from earlier work.
- CSF positivity used cohort tertiles rather than clinical cut-offs, and the single-centre northern Han sample limits generalisation.
- The associations were absent in cognitively normal participants and only subjective decline showed them; the p-tau/APOE interaction was uncorrected for multiple testing and borderline.
- The authors' wording that this is the first such finding rests on their own literature search.

## Open Questions

- Does BIN1 promoter hypomethylation in blood predict conversion from subjective cognitive decline to mild cognitive impairment or dementia (the study is cross-sectional)?
- Does BIN1_01 hypomethylation in blood raise BIN1 mRNA or protein levels in the same individuals (expression was not measured together with methylation)?
- Is the BIN1 methylation and CSF Aβ42 association replicated in non-Han cohorts (only northern Han Chinese participants were studied)?
- Does the BIN1 by APOE ε4 interaction on CSF p-tau hold in a larger sample of ε4 carriers (only 122 carriers were available)?

## Connections

- Disease: [[Alzheimer disease]], [[Late-onset Alzheimer disease]], [[Subjective cognitive decline]]
- Genes: [[BIN1]], [[APOE]], [[MAPT]]
- Variants: [[BIN1 rs58402148]], [[BIN1 rs17014923]]
- Markers: [[Decreased amyloid beta 42 peptide CSF concentration]], [[Increased CSF phosphorylated tau concentration]], [[Increased CSF total tau concentration]]
- Methods: [[MethylTarget sequencing]], [[DNA methylation]], [[ATN framework]]
- Cohort: [[Chinese Alzheimer's Biomarker and LifestylE cohort]]
- A network study of GWAS and methylation also placed BIN1 in its top module: [[Network-based integration of Alzheimer GWAS and DNA methylation finds BIN1 and GNAS module]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[BIN1]] | biolink:negatively_correlated_with | [[MAPT]] |  | "In addition, hypomethylation of BIN1 promoter was also accompanied by increased CSF p-tau (p = 0.0028) and t-tau (p = 0.0130) in the SCD subgroup, which was independent of CSF Aβ42." |
| [[BIN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our study is the first to find a robust association between hypomethylation of BIN1 promoter in peripheral blood and preclinical AD." |
| [[BIN1]] | biolink:associated_with_increased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "The bridging integrator 1 (BIN1) gene is the second most important susceptibility gene for late-onset Alzheimer’s disease (LOAD) after apolipoprotein E (APOE) gene." |
| [[BIN1]] | biolink:associated_with | [[Subjective cognitive decline]] |  | "Results showed that SCD participants with significant AD biological characteristics had lower methylation levels of BIN1 promoter, even after correcting for covariates." |
| [[BIN1]] | biolink:associated_with | [[Decreased amyloid beta 42 peptide CSF concentration]] |  | "Hypomethylation of BIN1 promoter were associated with decreased CSF Aβ42 (p = 0.0008), as well as increased p-tau/Aβ42 (p = 0.0001) and t-tau/Aβ42 (p < 0.0001) in total participants." |
| [[BIN1]] | biolink:positively_correlated_with | Amyloid beta 42 (CHEBI:64647; MESH:C075222) |  | "Hypomethylation of BIN1 promoter were associated with decreased CSF Aβ42 (p = 0.0008), as well as increased p-tau/Aβ42 (p = 0.0001) and t-tau/Aβ42 (p < 0.0001) in total participants." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| [[APP]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| [[APP]] | biolink:associated_with_increased_likelihood_of | Early-onset Alzheimer disease (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| [[PSEN1]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| [[PSEN1]] | biolink:associated_with_increased_likelihood_of | Early-onset Alzheimer disease (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| [[PSEN2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| [[PSEN2]] | biolink:associated_with_increased_likelihood_of | Early-onset Alzheimer disease (MESH:D000544) |  | "Initial studies have identified some classical susceptibility genes, including amyloid precursor protein (APP), presenilin genes 1 and 2 (PSEN1, PSEN2) for early-onset AD (EOAD), and apolipoprotein E (APOE) for late-onset AD (LOAD)." |
| Single nucleotide polymorphism (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "This association between genetic mutations in BIN1 and AD susceptibility was also verified by our previous study on a large Han Chinese cohort." |
| Single nucleotide polymorphism (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Subsequent genome-wide association studies identified a major susceptibility locus for LOAD on the bridging integrator 1 (BIN1) gene, which was located on chromosome 2q14.3 and was currently identified as the second most important susceptibility gene in LOAD after APOE." |
| [[BIN1]] | NOT biolink:associated_with | [[APOE]] |  | "In addition, there was no significant difference in methylation level of BIN1 promoter between different genders (p = 0.0741) and different APOE ɛ4 status (p = 0.2891), and no correlation was found between methylation levels of BIN1 promoter and age (p = 0.4445)." |
| [[BIN1]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "In an ATN biological construct, the A+ subgroup had significantly lower methylation levels of BIN1 promoter than the A− subgroup (p = 0.0060) (Fig. 1D–F)." |
| [[BIN1]] | biolink:associated_with | CpG (CHEBI:167896; MESH:C015772) |  | "In support of this result, some nearby differential methylation CpG sites were found in BIN1_01 region (Additional file 4)." |
| [[APOE]] | NOT biolink:associated_with | [[Subjective cognitive decline]] |  | "As predicted, frequency of positive APOE ε4 status showed an increasing trend in SCD subgroup (CN: 13.84%, SCD: 16.67%), although not statistically significant." |
| [[Subjective cognitive decline]] | NOT biolink:associated_with | [[MAPT]] |  | "No significant difference was found in levels of CSF p-tau (p = 0.1727) and t-tau (p = 0.0710) between two subgroups." |
| [[Subjective cognitive decline]] | biolink:negatively_correlated_with | Aβ42 (CHEBI:64647) |  | "As for CSF biomarkers, SCD subgroup had lower levels of Aβ42 (p = 0.0004) and higher levels of p-tau/Aβ42 (p < 0.0001) and t-tau/Aβ42 (p < 0.0001) compared with CN subgroup." |
| [[BIN1]] | biolink:negatively_correlated_with | [[Subjective cognitive decline]] |  | "Results still showed that lower methylation levels of BIN1 promoter were associated with SCD or SCD+ (p < 0.05) (Fig. 2)." |
| [[BIN1]] | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Results still showed that lower methylation levels of BIN1 promoter were associated with SCD or SCD+ (p < 0.05) (Fig. 2)." |
| [[BIN1]] | biolink:positively_correlated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Lower methylation levels of BIN1 promoter were significantly associated with decreased levels of CSF Aβ42 (β = 20.1268, p = 0.0008) as well as increased levels of CSF p-tau/Aβ42 (β = −23.8708, p = 0.0001) and t-tau/Aβ42 (β = −24.5219, p < 0.0001)." |
| [[BIN1]] | biolink:associated_with | [[APOE]] |  | "Though the interaction (BIN1×APOE) was not significantly associated with the changes of CSF Aβ42, t-tau, and t-tau/Aβ42 (p > 0.01), it had moderate influences on the level of CSF p-tau (p = 0.0195) and p-tau/Aβ42 (p = 0.0857) (Table 3)." |
| [[BIN1]] | biolink:associated_with | [[MAPT]] |  | "Results showed that methylation levels of BIN1 promoter were still significantly associated with CSF Aβ42, p-tau/Aβ42, and t-tau/Aβ42 in these models." |
| [[MAPT]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "The main finding of our study was that hypomethylation of BIN1 promoter might increase the risk of preclinical AD and be associated with more severe pathological changes of CSF AD core biomarkers in elderly adults without objective cognitive impairment." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "These results suggested that, in our study, SCD participants had preclinical AD characteristics." |
| [[Subjective cognitive decline]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Firstly, consistent with previous studies, our analysis of the participant characteristics showed that though the SCD participants in our study did not have an objective cognitive impairment, they had obvious changes in CSF AD core biomarkers (especially Aβ-related biomarkers)." |
| [[BIN1 rs58402148]] | NOT biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Though we did not find their associations with preclinical AD susceptibility and CSF AD core biomarkers (p > 0.05), they showed significant associations with methylation levels of BIN1 promoter (p < 0.0001) (Additional file 7)." |
| [[BIN1 rs17014923]] | NOT biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Though we did not find their associations with preclinical AD susceptibility and CSF AD core biomarkers (p > 0.05), they showed significant associations with methylation levels of BIN1 promoter (p < 0.0001) (Additional file 7)." |
| [[BIN1 rs58402148]] | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Though we did not find their associations with preclinical AD susceptibility and CSF AD core biomarkers (p > 0.05), they showed significant associations with methylation levels of BIN1 promoter (p < 0.0001) (Additional file 7)." |
| [[BIN1 rs17014923]] | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Though we did not find their associations with preclinical AD susceptibility and CSF AD core biomarkers (p > 0.05), they showed significant associations with methylation levels of BIN1 promoter (p < 0.0001) (Additional file 7)." |
| [[BIN1 rs58402148]] | NOT biolink:associated_with | [[Subjective cognitive decline]] |  | "Though we did not find their associations with preclinical AD susceptibility and CSF AD core biomarkers (p > 0.05), they showed significant associations with methylation levels of BIN1 promoter (p < 0.0001) (Additional file 7)." |
| [[BIN1 rs17014923]] | NOT biolink:associated_with | [[Subjective cognitive decline]] |  | "Though we did not find their associations with preclinical AD susceptibility and CSF AD core biomarkers (p > 0.05), they showed significant associations with methylation levels of BIN1 promoter (p < 0.0001) (Additional file 7)." |
| [[BIN1]] | biolink:associated_with | Mild cognitive impairment (MESH:D060825) |  | "Consistent with our results, a recent study of differential methylation in peripheral blood between cognitively normal people and patients with AD or MCI found some differentially methylated loci near BIN1 gene." |
| [[BIN1]] | biolink:directly_physically_interacts_with | [[MAPT]] |  | "As for tau-related pathology, besides affecting the endocytosis of tau protein, BIN1 protein can also directly bind to a proline-rich domain in tau by SH3 domain, suggesting that increased expression of BIN1 protein exacerbates tau-related pathology." |
| [[BIN1]] | biolink:affects | [[APP]] |  | "Specifically, as for Aβ-related pathology, BIN1 protein was thought to be involved in endocytosis, which could serve as a pathway that leads to APP production and release." |
| [[BIN1]] | biolink:affects | mRNA (CHEBI:33699; MESH:D012333) |  | "Overall, both brain and peripheral blood evidences suggested that the expression of the BIN1 gene changed, indirectly supporting hypothesis that altered methylation of BIN1 may contribute to the occurrence and development of AD by regulating the expression of RNA or protein." |
| [[BIN1]] | biolink:affects | RNA (CHEBI:33697; MESH:D012313) |  | "Overall, both brain and peripheral blood evidences suggested that the expression of the BIN1 gene changed, indirectly supporting hypothesis that altered methylation of BIN1 may contribute to the occurrence and development of AD by regulating the expression of RNA or protein." |
| [[BIN1]] | biolink:directly_physically_interacts_with | Proline (CHEBI:17203; MESH:D011392) |  | "As for tau-related pathology, besides affecting the endocytosis of tau protein, BIN1 protein can also directly bind to a proline-rich domain in tau by SH3 domain, suggesting that increased expression of BIN1 protein exacerbates tau-related pathology." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Overall, from the above studies, it was not difficult to see that BIN1 protein was involved in the pathological changes of AD and the mechanisms of its influences on Aβ and tau pathology were significantly different." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Overall, from the above studies, it was not difficult to see that BIN1 protein was involved in the pathological changes of AD and the mechanisms of its influences on Aβ and tau pathology were significantly different." |
| mRNA (CHEBI:33699; MESH:D012333) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In fact, as for human brain tissue, both BIN1 mRNA and protein levels were altered in AD patients." |
| [[APOE]] | biolink:associated_with | [[MAPT]] |  | "However, it was worth noting that a modest effect of interaction between APOE ɛ4 status and methylation levels was also found in our study, especially for the CSF p-tau levels." |
