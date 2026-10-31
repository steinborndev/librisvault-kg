---
type: source
title: "Predictive gene expression signatures of Alzheimer disease in six brain regions"
paper_title: "Predictive gene expression signatures for Alzheimer's disease using post-mortem brain tissue"
domain: neuroscience
status: developing
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-001030
pmid: "41113932"
pmcid: "PMC12528040"
doi: "10.3389/fnagi.2025.1591946"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC12528040/"
sources: ["[[.raw/01M4P89V7CZP0E1HXMSZ12826Y/normalized.md]]"]
tags: [transcriptomics, biomarker, drug-candidate, postmortem-brain]
---

# Predictive gene expression signatures of Alzheimer disease in six brain regions

A Frontiers in Aging Neuroscience (2025) analysis of bulk RNA-seq from post-mortem brain. For each of six regions affected at different stages of [[Alzheimer disease]], the authors took the differentially expressed genes between control and Alzheimer samples, turned them into a predictive signature with ASSIGN, checked the predicted "AD activity" against pathology and clinical measures, and then used the signatures to ask why some regions are more vulnerable and which drugs might reverse them. The concepts are in [[Predictive gene expression signatures with ASSIGN]], [[Regional vulnerability to Alzheimer pathology]] and [[Connectivity Map analysis]].

## Design

- Counts came from the AMP-AD RNAseq Harmonization study, see [[AMP-AD brain RNAseq cohorts]]: 632 dorsolateral prefrontal cortex (DLPFC) samples from ROSMAP; 160 parahippocampal gyrus (PHG), 187 inferior frontal gyrus (IFG) and 191 superior temporal gyrus (STG) samples from the Mount Sinai Brain Bank; 262 temporal cortex (TCX) and 261 cerebellum (CER) samples from the Mayo Clinic study.
- GSE104687 (Aging, Dementia and Traumatic Brain Injury study; 98 TCX and 94 hippocampus FPKM samples) served as the only external validation set.
- Control and Alzheimer groups were defined per region from CERAD plaque scores, [[Braak staging]] and study-specific diagnoses; DESeq2 gave differentially expressed genes (adjusted p at most 0.05, region-specific log2 fold change cut-offs), after batch correction with sva.
- Predicted activity (0 to 1) was compared with Braak stage, CERAD score, Thal phase, cognitive diagnosis, Clinical Dementia Rating, MMSE (DLPFC) and mean plaque density (PHG, IFG, STG). A binomial GLM per region added age at death, sex, [[APOE]] genotype and race; fit was judged by McFadden pseudo-R2 and leave-one-out cross-validated AUC.
- Overlap of signature genes between regions, GeneMANIA co-expression networks with CytoHubba hub genes, g:Profiler enrichment ([[Gene set enrichment analysis]]), MCODE modules and [[ClueGO functional network analysis]] described the processes involved.

## Findings

- Differentially expressed genes were most numerous in the early-affected PHG (176; 154 up, 22 down), then STG (127), CER (55), TCX (53), DLPFC (53) and IFG (44).
- Predicted AD activity differed significantly between controls and severe Alzheimer cases in every region on the pathology and clinical measures (Table 1). Plaque density correlated positively with activity in PHG (Pearson r = 0.560), IFG (r = 0.566) and STG (r = 0.387).
- In the external set the PHG signature separated control from severe Alzheimer hippocampi across all measures; the TCX signature showed higher activity in cases but not significantly so.
- Signature predictions were the strongest predictors of Alzheimer status in every region except TCX (n = 23 after filtering, perfect separation by APOE genotype). PHG had a very strong model fit; cross-validated AUCs ranged from 0.729 to 0.995.
- Male sex was associated with lower odds of Alzheimer status in PHG, CER and IFG, significantly so only in IFG. APOE e3/e4 raised the odds relative to e2/e3 in DLPFC (OR 9.58) and CER (OR 27.9).
- [[S100A4]] was up in all six regions. Five genes appeared in five regions: [[ANGPT2]] and LINC03082 up, [[CRH]], LINC01007 and [[PPEF1]] down. Fourteen genes appeared in four regions, with [[KCNE4]], [[GEM]], [[HSPA1A]], [[SPN]], LINC01736 and [[CD44]] up and FRMPD2B and [[NEUROD6]] down. CRH, ANGPT2, S100A4 and PPEF1 were also hub genes.
- Extracellular matrix terms (matrix, external encapsulating structure, collagen-containing matrix) were up in every region; see [[Extracellular matrix organization]]. Neuropeptide hormone activity and hormonal signalling were down in every region except cerebellum.
- PHG was dominated by neuroinflammatory terms and STG by immune effector terms; in TCX glutamate decarboxylase activity was down while collagen fibril organization was up; CER showed immune and inflammatory terms including [[TLR4]] upregulation. PHG formed six MCODE clusters (score 7.8) versus two in DLPFC (score 4.2); STG had 663 enriched pathways against 22 in DLPFC.
- Connectivity Map queries returned FGFR inhibitors in all regions except PHG and CER, with [[Orantinib]] the shared compound; 17 compounds were common to TCX, STG, IFG and DLPFC; bromodomain inhibitors were common to TCX, STG and DLPFC, and knockdown of [[BRD2]] and [[BRD4]] reversed the signature. PHG returned two compounds and CER six, with no shared classes.

## Why This Source Matters

It pairs region-by-region expression signatures with pathology- and cognition-based validation, so the gene lists are tied to Braak, CERAD and diagnosis rather than only to a case-control label, and it points to a small set of recurrent genes ([[S100A4]], [[CRH]], [[ANGPT2]]) and two themes (matrix remodelling up, hormone signalling down) shared by all regions. The drug leads are hypotheses from signature matching, not tested compounds.

## Assessment

- All tissue is end-stage post-mortem, so early changes are inferred from regional order, not observed; the authors say so.
- Only PHG and TCX could be validated externally, and TCX failed; four of six signatures have no independent replication.
- Region differences in gene counts may reflect the cohort, sample size and the region-specific fold change thresholds (chosen to optimise prediction) as much as biology, since regions come from three different studies.
- The TCX model rests on 23 samples with perfect separation, so its odds ratios and intervals are unusable.
- The reported interval for the IFG male-sex odds ratio (OR 0.092, interval 15.9 to 1.49 x 10^4) does not contain the point estimate; the table was not available to resolve this.
- Interpretive claims (CRH loss weakens neuroinflammation control, S100A4 causes matrix stiffening, cerebellar resistance from preserved hormones) are discussion, not tested here. Drug matches rely on Connectivity Map scores only, and blood-brain barrier penetration of FGFR and bromodomain inhibitors is flagged as limiting.
- Supplementary tables with the full gene lists were not part of the text read.

## Open Questions

- Does downregulation of [[CRH]] precede cortical amyloid and tau pathology in longitudinal or early-stage brain tissue (the study used post-mortem, mostly late-stage samples)?
- Can the region signatures be detected in blood-derived RNA to predict Alzheimer status (the authors propose it but tested only brain tissue)?
- Do the signatures of the superior temporal gyrus, inferior frontal gyrus, dorsolateral prefrontal cortex and cerebellum replicate in an independent cohort (only the parahippocampal gyrus and temporal cortex signatures had a matching external set)?
- Does [[Orantinib]] or knockdown of [[BRD4]] reverse the matrix and hormone signatures in human neurons or in an Alzheimer mouse model (matches come from Connectivity Map scores alone)?
- Why is the cerebellum the exception for hormone signalling and [[CRH]] downregulation (offered as preserved endocrine signalling, without direct evidence)?

## Connections

- Disease: [[Alzheimer disease]]
- Genes: [[S100A4]], [[ANGPT2]], [[CRH]], [[CD44]], [[PPEF1]], [[NEUROD6]], [[HSPA1A]], [[KCNE4]], [[GEM]], [[SPN]], [[APOE]], [[TLR4]], [[BRD2]], [[BRD4]]
- Compound: [[Orantinib]]
- Process: [[Extracellular matrix organization]]
- Methods: [[Predictive gene expression signatures with ASSIGN]], [[Connectivity Map analysis]], [[ClueGO functional network analysis]], [[Gene set enrichment analysis]], [[AMP-AD brain RNAseq cohorts]]
- Topics: [[Regional vulnerability to Alzheimer pathology]], [[Braak staging]], [[Drug repurposing]], [[Neuroinflammation]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Alzheimer’s Disease (AD) is a progressive neurodegenerative disorder characterized by amyloid-beta (Aβ) plaques and tau protein aggregates in the brain." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Alzheimer’s Disease (AD) is a progressive neurodegenerative disorder characterized by amyloid-beta (Aβ) plaques and tau protein aggregates in the brain." |
| [[S100A4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Notably, S100A4 was consistently upregulated across all regions, while CRH expression was downregulated except in the cerebellum." |
| [[CRH]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Notably, S100A4 was consistently upregulated across all regions, while CRH expression was downregulated except in the cerebellum." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Additionally, findings underscored the influence of APOE genotype (e3/e4) and sex on disease progression." |
| APOE e3/e4 genotype (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Additionally, findings underscored the influence of APOE genotype (e3/e4) and sex on disease progression." |
| [[Orantinib]] (MESH:C412603) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Drug repurposing analysis identified FGFR inhibitors, specifically orantinib and bromodomain inhibitors, as promising therapeutic candidates." |
| APOE e3/e4 (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In later-affected regions, APOE e3/e4 significantly increased AD likelihood compared to e2/e3 in DLPFC (OR = 9.58, 95% CI [1.89, 56.5], p < 0.01) and CER (OR = 27.9, 95% CI [14.4, 1.30 × 103], p < 0.05)." |
| Neurofibrillary tangles (HP:0002185) | biolink:associated_with | [[MAPT]] |  | "Specifically, we assessed the biological relevance of our gene expression signatures with postmortem neuropathological measures, including Braak staging—which captures the distribution and severity of neurofibrillary tangles composed of hyperphosphorylated tau—and CERAD scores, which quantify the density of neuritic amyloid plaques." |
| [[ANGPT2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Additionally, five genes were found across five of the six regions including upregulation of ANGPT2, LINC03082, and downregulation of CRH, LINC01007, and PPEF1, suggesting their significant but less ubiquitous involvement." |
| LINC03082 (HGNC:56676) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Additionally, five genes were found across five of the six regions including upregulation of ANGPT2, LINC03082, and downregulation of CRH, LINC01007, and PPEF1, suggesting their significant but less ubiquitous involvement." |
| LINC01007 (HGNC:48973) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Additionally, five genes were found across five of the six regions including upregulation of ANGPT2, LINC03082, and downregulation of CRH, LINC01007, and PPEF1, suggesting their significant but less ubiquitous involvement." |
| [[PPEF1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Additionally, five genes were found across five of the six regions including upregulation of ANGPT2, LINC03082, and downregulation of CRH, LINC01007, and PPEF1, suggesting their significant but less ubiquitous involvement." |
| [[KCNE4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| [[GEM]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| [[HSPA1A]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| [[SPN]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| LINC01736 (HGNC:52524) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| [[CD44]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| FRMPD2B (HGNC:16843) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| [[NEUROD6]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Next, fourteen other genes were found across four of the six brain regions with upregulation of KCNE4, GEM, HSPA1A, SPN, LINC01736, CD44 and downregulation of FRMPD2B and NEUROD6 (Figure 3; Supplementary Table 10)." |
| [[BRD2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "While no specific bromodomain inhibitor was identified, knockdown of bromodomain targets like BRD2 and BRD4 reversed the AD expression captured in our signatures, suggesting their potential to reverse AD-specific effects in the TCX, STG and DLPFC." |
| [[BRD4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "While no specific bromodomain inhibitor was identified, knockdown of bromodomain targets like BRD2 and BRD4 reversed the AD expression captured in our signatures, suggesting their potential to reverse AD-specific effects in the TCX, STG and DLPFC." |
| collagen (CHEBI:3815; MESH:D003094) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Despite this, extracellular matrix (ECM)-related processes were consistently upregulated across all regions, particularly in the extracellular matrix, external encapsulating structure, and collagen-containing ECM." |
| [[TLR4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Finally, the CER showed heightened immune and inflammatory responses, including Toll-like receptor 4 upregulation, potentially driving increased chemotaxis and angiogenesis regulation (Supplementary Figure 4; Supplementary Table 13F)." |
| [[TLR4]] | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "Finally, the CER showed heightened immune and inflammatory responses, including Toll-like receptor 4 upregulation, potentially driving increased chemotaxis and angiogenesis regulation (Supplementary Figure 4; Supplementary Table 13F)." |
| [[MAPT]] | biolink:associated_with | neurodegeneration (HP:0002180) |  | "This aligns with their role as some of the first sites of Aβ and tau accumulation along with neurodegeneration." |
| [[CRH]] | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "Additional work has also reported widespread CRH loss alongside glial overactivation and depletion of immune-regulatory neuropeptides in the parahippocampal and temporal cortices, mirroring the inflammatory profiles we observed in these same regions." |
| [[APOE]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Meanwhile, genetic predisposition played a larger role in DLPFC and CER, where APOE genotype significantly influenced development of AD supporting previous studies." |
| APOE e4 (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Specifically, APOE e3/e4 carriers showed a heightened risk of AD compared to e2/e3, particularly in CER, where genetic influence appeared even more pronounced." |
| [[Alzheimer disease]] (MESH:D000544) | biolink:negatively_correlated_with | glutamate (CHEBI:16015; MESH:D018698) |  | "In contrast, the TCX, a mid-affected region in AD, exhibited limited dysregulation, primarily marked by downregulation of glutamate decarboxylase activity, consistent with decreased GABA and glutamate levels in AD patients." |
| [[Alzheimer disease]] (MESH:D000544) | biolink:negatively_correlated_with | GABA (CHEBI:16865; MESH:D005680) |  | "In contrast, the TCX, a mid-affected region in AD, exhibited limited dysregulation, primarily marked by downregulation of glutamate decarboxylase activity, consistent with decreased GABA and glutamate levels in AD patients." |
| APOE e4 (variant) | biolink:positively_correlated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "This supports APOE e4 association with increased amyloid accumulation and neuroinflammatory responses in later-affected cortical and cerebellar regions." |
| APOE e4 (variant) | biolink:positively_correlated_with | amyloid (MESH:D000682) |  | "This supports APOE e4 association with increased amyloid accumulation and neuroinflammatory responses in later-affected cortical and cerebellar regions." |
| [[Orantinib]] (MESH:C412603) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Notably, FGFR inhibitors like orantinib, linked to TCX, STG, IFG, and DLPFC, target FGF signaling to potentially restore ECM integrity and reduce inflammation, aligning with disruptions observed in these regions." |
| [[S100A4]] | biolink:affects | collagen (CHEBI:3815; MESH:D003094) | direction=increased | "This dysregulation likely leads to excessive collagen deposition, resulting in extracellular stiffening negatively impacting synaptic plasticity and compromising BBB integrity." |
| [[S100A4]] | biolink:contributes_to | rigidity (HP:0002063) |  | "This dysregulation likely leads to excessive collagen deposition, resulting in extracellular stiffening negatively impacting synaptic plasticity and compromising BBB integrity." |
| [[ANGPT2]] | biolink:contributes_to | inflammation (MESH:D007249) |  | "Studies suggest ANGPT2 is linked to vascular dysfunction in AD, contributing to BBB breakdown, inflammation, and impaired blood flow." |
| [[CRH]] | biolink:associated_with | neuroinflammatory responses (HP:0033429) |  | "Given the role of CRH in stress adaptation and neuronal resilience, its downregulation suggests a weakened ability to regulate neuroinflammatory responses, leaving neurons more vulnerable to degeneration." |
| [[CRH]] | biolink:associated_with | hypothalamic atrophy (HP:0025058) |  | "This aligns with findings that HPA axis dysfunction in AD disrupts stress-response mechanisms, leading to hypothalamic atrophy causing increased susceptibility of amyloid-β accumulation." |
| [[CRH]] | biolink:contributes_to | neurodegeneration (HP:0002180) |  | "Given the role of CRH in stress adaptation and neuronal resilience, its downregulation suggests a weakened ability to regulate neuroinflammatory responses, leaving neurons more vulnerable to degeneration." |
| rigidity (HP:0002063) | biolink:associated_with | [[MAPT]] |  | "Ultimately, dysregulation in these processes further exacerbate disease progression by impairing the clearance of Aβ and tau aggregates due to increased matrix rigidity." |
| hypothalamic atrophy (HP:0025058) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "This aligns with findings that HPA axis dysfunction in AD disrupts stress-response mechanisms, leading to hypothalamic atrophy causing increased susceptibility of amyloid-β accumulation." |
| rigidity (HP:0002063) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Ultimately, dysregulation in these processes further exacerbate disease progression by impairing the clearance of Aβ and tau aggregates due to increased matrix rigidity." |
| collagen (CHEBI:3815; MESH:D003094) | biolink:contributes_to | rigidity (HP:0002063) |  | "This dysregulation likely leads to excessive collagen deposition, resulting in extracellular stiffening negatively impacting synaptic plasticity and compromising BBB integrity." |
| [[Orantinib]] (MESH:C412603) | biolink:treats | inflammation (MESH:D007249) |  | "Notably, FGFR inhibitors like orantinib, linked to TCX, STG, IFG, and DLPFC, target FGF signaling to potentially restore ECM integrity and reduce inflammation, aligning with disruptions observed in these regions." |
