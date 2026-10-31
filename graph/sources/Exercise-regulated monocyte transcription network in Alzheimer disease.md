---
type: source
title: "Exercise-regulated monocyte transcription network in Alzheimer disease"
paper_title: "Exercise Modifies the Transcriptional Regulatory Features of Monocytes in Alzheimer’s Patients: A Multi-Omics Integration Analysis Based on Single Cell Technology"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000286
pmid: "35592698"
pmcid: "PMC9110789"
doi: "10.3389/fnagi.2022.881488"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9110789/"
sources: ["[[.raw/01M4DY94NG421AHVHRGTHKBAJD/normalized.md]]"]
tags: [monocyte, exercise, transcription-factor, secondary-analysis, blood-biomarker]
---

# Exercise-regulated monocyte transcription network in Alzheimer disease

A bioinformatic study that mines three public GEO datasets to ask how physical exercise might protect against [[Alzheimer disease]] through circulating monocytes. Single-cell data from blood of Alzheimer patients and controls (GSE181279) give the cell types, cell-cell signalling and transcription factor regulons; a pre- versus post-exercise blood dataset (GSE51835) shows which genes exercise moves; and a large Alzheimer case-control blood expression set (GSE140831) tests whether the resulting gene panel predicts disease. The panel the authors keep is called the ERADMT gene set (exercise-regulated Alzheimer-disease monocyte transcription): [[APP]], [[CCR1]], [[TNF]], [[ATF3]], [[KLF4]], [[HES4]] and [[MAFB]].

## Why This Source Matters

It is an example of stacking a single-cell atlas, a bulk before-and-after contrast and a case-control cohort to nominate a small regulator-to-ligand network, here with a lifestyle intervention as the "perturbation". It puts [[APP]], the best-known Alzheimer gene, into a blood monocyte setting rather than a neuronal one, and names transcription factors (ATF3, KLF4, HES4, MAFB) not usually discussed for Alzheimer disease. The causal and clinical claims outrun the design (see Assessment), so it is a hypothesis-generating candidate list, not evidence that exercise acts through these genes.

## Design

- Single-cell data: 36,849 peripheral blood nucleated cells from three amyloid-PET-positive Alzheimer patients over 60 and two age-matched cognitively normal controls (GSE181279). Seurat quality control (cells with at least 200 genes, under 10 mitochondrial genes), UMAP, SingleR annotation corrected with marker genes; 17 clusters annotated as T-cell subsets, NK cells, B cells and CD14+ and CD16+ monocytes. See [[Single-cell RNA sequencing]].
- Exercise contrast: GSE51835, mononuclear cells from 12 individuals before and after 20 minutes of exercise (24 samples; described as bulk RNA-seq but run on an Affymetrix microarray). limma gave 1,811 differentially expressed genes.
- Case-control set: GSE140831, circulating blood expression from 204 Alzheimer patients and 530 controls, used only for the prediction models.
- Cell communication: CellPhoneDB and CellChat on the single-cell data, with CellChat pathways MIF, GALECTIN, TNF, IL16, ANNEXIN and RESISTIN.
- Regulators: SCENIC regulon analysis with regulon specificity scores and entropy-based clustering of transcription factors into modules M1 to M9; see [[SCENIC regulon analysis]]. Monocle2 pseudotime on the monocytes. GO and KEGG enrichment with clusterProfiler.
- Prediction: a neural network on the seven genes to tell pre- from post-exercise samples; random forest and support vector machine models, a nomogram, calibration and decision curves to tell Alzheimer from control blood.

## Findings

- Monocyte numbers did not differ between Alzheimer and control blood (CD14+ and CD16+ proportions), so the authors read any monocyte difference as transcriptional. CD14+ and CD16+ monocytes signalled to other cells through all six CellChat pathways.
- The 1,811 exercise-responsive genes were enriched for response to lipopolysaccharide, p53-mediated signalling, ubiquitin ligase and nuclear transcription factor complexes, histone methylation binding, and the FOXO, natural killer cytotoxicity and Th17 differentiation pathways. 57 (CD14+) and 39 (CD16+) monocyte genes were differentially expressed in Alzheimer blood.
- Of 32 key ligand-receptor pairs, four genes also responded to exercise: [[TNF]], [[CCR1]], [[APP]] and [[AREG]]. TNF, CCR1 and APP were higher after exercise (p < 0.05); AREG is not carried into the later network.
- The top monocyte regulators intersected with Alzheimer differential expression gave [[MAFB]], [[HES4]] and [[FOSL1]]. These three characterise module M4, which is enriched in both monocyte types and in terms for myeloid and lymphocyte differentiation, muscle development and transcriptional repression.
- Intersecting the 17 M4 transcription factors with the exercise genes left [[ATF3]], [[BCL3]], [[KLF4]] and [[NFIL3]]. Sankey (regulon-to-target) diagrams link them to APP, CCR1 and TNF; the final text states that ATF3 positively regulates TNF and KLF4 positively regulates CCR1, and names ATF3, MAFB, HES4 and KLF4 as the candidate regulators of TNF, CCR1 and APP. BCL3, NFIL3 and FOSL1 drop out of the seven-gene panel.
- Pseudotime placed the ERADMT genes on the state 1 branch, enriched in CD14+ monocytes, from which the authors conclude that exercise acts mainly through CD14+ monocytes.
- The seven genes correlated positively with one another in single-cell and exercise data. A neural network on them separated pre- from post-exercise samples (ROC given in figures, no AUC in the text). In GSE140831 the correlation was positive except that APP was negatively correlated with ATF3 and HES4; the random forest beat the support vector machine on AUC, and a nomogram was well calibrated.
- APP expression and its ratio in CD14+ monocytes were higher in Alzheimer patients, which the authors take as a hint that monocyte APP contributes to amyloid deposition.

## Assessment

- The title says exercise changes monocytes of Alzheimer patients, but the exercise dataset is a 20-minute bout in 12 individuals who are not stated to have Alzheimer disease; no Alzheimer patient was studied before and after an exercise programme. Acute response is read as chronic prevention.
- Single-cell power is small (three patients, two controls), with no per-donor statistics described and Alzheimer-versus-control differences tested on pseudo-bulk of cells from so few donors.
- The seven-gene panel was chosen by intersecting the same datasets in which it is then tested, and no hold-out or independent cohort is reported for the random forest, support vector machine or nomogram, so its "risk marker" performance is probably optimistic; AUC values are not given in the text. The same applies to the neural network for exercise adherence, which only separates pre- from post-exercise samples of a single acute experiment.
- SCENIC here only recovers positively correlated regulator-target links, as the authors note, and Sankey diagrams are inferred from co-expression, so "regulates" is correlation. APP is higher after exercise and higher in Alzheimer monocytes, which does not sit comfortably with exercise being protective; the discussion does not resolve this.
- Several wording slips: the exercise dataset is called bulk RNA-seq and microarray; in the figure legend for correlations it is called GSE181279; KLF4 is written "KFL4" in places; the pseudotime conclusion is stated twice in the discussion. Claims of first-time findings for ATF3, KLF4 and HES4 in exercise are not backed by a literature search in the text.
- The authors state that experimental validation and clinical studies are needed.

## Open Questions

- Is the ERADMT gene panel (APP, CCR1, TNF, ATF3, KLF4, HES4, MAFB) still predictive of Alzheimer disease in an independent blood expression cohort not used to select it?
- Do monocytes from Alzheimer patients after a chronic exercise programme (not a single 20-minute bout) show the same shifts in ATF3, KLF4 and TNF (the exercise data came from 12 individuals, not described as patients)?
- Does ATF3 or KLF4 knock-down in human CD14+ monocytes change TNF or CCR1 expression, as the co-expression regulons predict (no wet-lab test was done)?
- Why is APP higher in monocytes both after exercise and in Alzheimer disease, and what does monocyte APP contribute to amyloid deposition (the study only infers this from expression)?

## Connections

- Disease: [[Alzheimer disease]]
- ERADMT genes: [[APP]], [[CCR1]], [[TNF]], [[ATF3]], [[KLF4]], [[HES4]], [[MAFB]]
- Other genes with findings: [[AREG]], [[BCL3]], [[NFIL3]], [[FOSL1]]
- Methods: [[Single-cell RNA sequencing]], [[SCENIC regulon analysis]], [[Gene set enrichment analysis]]
- Related immune biology: [[Neuroinflammation]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[TNF]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "TNF, CCR1, APP, and AREG, the key ligand-receptor-related genes, were found to be differentially expressed between exercise-treated and AD patients." |
| [[CCR1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "TNF, CCR1, APP, and AREG, the key ligand-receptor-related genes, were found to be differentially expressed between exercise-treated and AD patients." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "TNF, CCR1, APP, and AREG, the key ligand-receptor-related genes, were found to be differentially expressed between exercise-treated and AD patients." |
| [[AREG]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "TNF, CCR1, APP, and AREG, the key ligand-receptor-related genes, were found to be differentially expressed between exercise-treated and AD patients." |
| [[MAFB]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Among the identified TFs, MAFB, HES4, and FOSL1 were found to be differentially expressed in AD." |
| [[HES4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Among the identified TFs, MAFB, HES4, and FOSL1 were found to be differentially expressed in AD." |
| [[FOSL1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Among the identified TFs, MAFB, HES4, and FOSL1 were found to be differentially expressed in AD." |
| [[MAPT]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "In terms of pathogenesis, it is thought to be caused by extracellular amyloid β-protein (Aβ) deposition and tau hyperphosphorylation." |
| amyloid β-protein (CHEBI:64645; MESH:D016229) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "In terms of pathogenesis, it is thought to be caused by extracellular amyloid β-protein (Aβ) deposition and tau hyperphosphorylation." |
| [[TNF]] | biolink:associated_with | [[CCR1]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[TNF]] | biolink:associated_with | [[APP]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[MAFB]] | biolink:regulates | [[TNF]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[HES4]] | biolink:regulates | [[TNF]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[ATF3]] | biolink:regulates | [[TNF]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[KLF4]] | biolink:regulates | [[TNF]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[CCR1]] | biolink:associated_with | [[APP]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[MAFB]] | biolink:regulates | [[CCR1]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[HES4]] | biolink:regulates | [[CCR1]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[ATF3]] | biolink:regulates | [[CCR1]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[KLF4]] | biolink:regulates | [[CCR1]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[MAFB]] | biolink:regulates | [[APP]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[HES4]] | biolink:regulates | [[APP]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[ATF3]] | biolink:regulates | [[APP]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[KLF4]] | biolink:regulates | [[APP]] |  | "And ATF3, MAFB, HES4, and KLF4 that were identified in M4 clusters may be the TFs that regulate TNF, CCR1, and APP in exercise prescription." |
| [[MAFB]] | biolink:associated_with | [[HES4]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[MAFB]] | biolink:associated_with | [[FOSL1]] |  | "Moreover, the M4 cluster to which MAFB, HES4, and FOSL1 belonged was defined as the signature cluster for AD phenotype." |
| [[MAFB]] | biolink:associated_with | [[ATF3]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[MAFB]] | biolink:associated_with | [[KLF4]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[HES4]] | biolink:associated_with | [[FOSL1]] |  | "Moreover, the M4 cluster to which MAFB, HES4, and FOSL1 belonged was defined as the signature cluster for AD phenotype." |
| [[HES4]] | biolink:associated_with | [[ATF3]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[HES4]] | biolink:associated_with | [[KLF4]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| [[ATF3]] | biolink:associated_with | [[KLF4]] |  | "After that, APP, CCR1, TNF, ATF3, KLF4, HES4, and MAFB formed a regulatory network in the ERADMT gene set, and all of them were mechanistically linked." |
| CD14 (HGNC:1628) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The proportions of CD14+ and CD16+ monocytes were not significantly different between the AD and NC groups." |
| FCGR3A (HGNC:3619) | NOT biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The proportions of CD14+ and CD16+ monocytes were not significantly different between the AD and NC groups." |
| CD14 (HGNC:1628) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A total of 57 and 39 DEGs were associated with AD at the single-cell level in CD14+ and CD16+ monocytes, respectively (Supplementary Figure 2C)." |
| FCGR3A (HGNC:3619) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A total of 57 and 39 DEGs were associated with AD at the single-cell level in CD14+ and CD16+ monocytes, respectively (Supplementary Figure 2C)." |
| [[MAFB]] | biolink:regulates | [[AREG]] |  | "Sankey maps were drawn based on the results of previous SCENIC analyses to reveal transcriptional regulators that may regulate TNF, CCR1, APP, and AREG (Figure 6D)." |
| [[HES4]] | biolink:regulates | [[AREG]] |  | "Sankey maps were drawn based on the results of previous SCENIC analyses to reveal transcriptional regulators that may regulate TNF, CCR1, APP, and AREG (Figure 6D)." |
| [[FOSL1]] | biolink:regulates | [[TNF]] |  | "Sankey maps were drawn based on the results of previous SCENIC analyses to reveal transcriptional regulators that may regulate TNF, CCR1, APP, and AREG (Figure 6D)." |
| [[FOSL1]] | biolink:regulates | [[CCR1]] |  | "Sankey maps were drawn based on the results of previous SCENIC analyses to reveal transcriptional regulators that may regulate TNF, CCR1, APP, and AREG (Figure 6D)." |
| [[FOSL1]] | biolink:regulates | [[APP]] |  | "Sankey maps were drawn based on the results of previous SCENIC analyses to reveal transcriptional regulators that may regulate TNF, CCR1, APP, and AREG (Figure 6D)." |
| [[FOSL1]] | biolink:regulates | [[AREG]] |  | "Sankey maps were drawn based on the results of previous SCENIC analyses to reveal transcriptional regulators that may regulate TNF, CCR1, APP, and AREG (Figure 6D)." |
| [[ATF3]] | biolink:positively_correlated_with | [[KLF4]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[ATF3]] | biolink:positively_correlated_with | [[HES4]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[ATF3]] | biolink:positively_correlated_with | [[MAFB]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[ATF3]] | biolink:associated_with | CD14 (HGNC:1628) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[ATF3]] | biolink:associated_with | FCGR3A (HGNC:3619) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[ATF3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The transcription factors ATF3, BCL3, KLF4, and NFIL3 were the key TFs regulated by AD and exercise." |
| [[BCL3]] | biolink:regulates | [[APP]] |  | "Subsequently, the sankey diagram demonstrated the key ligands or receptors (APP, CCR1, and TNF) that may be regulated by the co-differentially expressed transcription factors (ATF3, BCL3, KLF4, and NFIL3; Figure 7C)." |
| [[BCL3]] | biolink:regulates | [[CCR1]] |  | "Subsequently, the sankey diagram demonstrated the key ligands or receptors (APP, CCR1, and TNF) that may be regulated by the co-differentially expressed transcription factors (ATF3, BCL3, KLF4, and NFIL3; Figure 7C)." |
| [[BCL3]] | biolink:regulates | [[TNF]] |  | "Subsequently, the sankey diagram demonstrated the key ligands or receptors (APP, CCR1, and TNF) that may be regulated by the co-differentially expressed transcription factors (ATF3, BCL3, KLF4, and NFIL3; Figure 7C)." |
| [[BCL3]] | biolink:associated_with | CD14 (HGNC:1628) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[BCL3]] | biolink:associated_with | FCGR3A (HGNC:3619) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[BCL3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The transcription factors ATF3, BCL3, KLF4, and NFIL3 were the key TFs regulated by AD and exercise." |
| [[KLF4]] | biolink:positively_correlated_with | [[HES4]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[KLF4]] | biolink:positively_correlated_with | [[MAFB]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[KLF4]] | biolink:associated_with | CD14 (HGNC:1628) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[KLF4]] | biolink:associated_with | FCGR3A (HGNC:3619) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[KLF4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The transcription factors ATF3, BCL3, KLF4, and NFIL3 were the key TFs regulated by AD and exercise." |
| [[NFIL3]] | biolink:regulates | [[APP]] |  | "Subsequently, the sankey diagram demonstrated the key ligands or receptors (APP, CCR1, and TNF) that may be regulated by the co-differentially expressed transcription factors (ATF3, BCL3, KLF4, and NFIL3; Figure 7C)." |
| [[NFIL3]] | biolink:regulates | [[CCR1]] |  | "Subsequently, the sankey diagram demonstrated the key ligands or receptors (APP, CCR1, and TNF) that may be regulated by the co-differentially expressed transcription factors (ATF3, BCL3, KLF4, and NFIL3; Figure 7C)." |
| [[NFIL3]] | biolink:regulates | [[TNF]] |  | "Subsequently, the sankey diagram demonstrated the key ligands or receptors (APP, CCR1, and TNF) that may be regulated by the co-differentially expressed transcription factors (ATF3, BCL3, KLF4, and NFIL3; Figure 7C)." |
| [[NFIL3]] | biolink:associated_with | CD14 (HGNC:1628) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[NFIL3]] | biolink:associated_with | FCGR3A (HGNC:3619) |  | "The key transcription factors were predominantly expressed in CD14+ and CD16+ monocytes." |
| [[NFIL3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The transcription factors ATF3, BCL3, KLF4, and NFIL3 were the key TFs regulated by AD and exercise." |
| [[APP]] | biolink:positively_correlated_with | [[CCR1]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[APP]] | biolink:positively_correlated_with | [[TNF]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[APP]] | biolink:associated_with | CD14 (HGNC:1628) |  | "Furthermore, ERADMT gene set was concentrated in the state 1 branch of the pseudo-temporal track and enriched in CD14+ monocyte." |
| [[CCR1]] | biolink:positively_correlated_with | [[TNF]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[CCR1]] | biolink:associated_with | CD14 (HGNC:1628) |  | "Furthermore, ERADMT gene set was concentrated in the state 1 branch of the pseudo-temporal track and enriched in CD14+ monocyte." |
| [[TNF]] | biolink:associated_with | CD14 (HGNC:1628) |  | "Furthermore, ERADMT gene set was concentrated in the state 1 branch of the pseudo-temporal track and enriched in CD14+ monocyte." |
| [[HES4]] | biolink:positively_correlated_with | [[MAFB]] |  | "The results were similar to those of the SCENIC analysis, i.e., The expression of genes in the ERADMT gene set was positively correlated with each other’s expression." |
| [[HES4]] | biolink:associated_with | CD14 (HGNC:1628) |  | "Furthermore, ERADMT gene set was concentrated in the state 1 branch of the pseudo-temporal track and enriched in CD14+ monocyte." |
| [[MAFB]] | biolink:associated_with | CD14 (HGNC:1628) |  | "Furthermore, ERADMT gene set was concentrated in the state 1 branch of the pseudo-temporal track and enriched in CD14+ monocyte." |
| [[APP]] | biolink:negatively_correlated_with | [[ATF3]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[APP]] | biolink:positively_correlated_with | [[KLF4]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[APP]] | biolink:negatively_correlated_with | [[HES4]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[APP]] | biolink:positively_correlated_with | [[MAFB]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[APP]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "ERADMT gene set, as a set of genes in the regulatory network, is a potential risk marker for AD development and an indicator for the assessment of exercise therapy adherence in AD patients." |
| [[CCR1]] | biolink:positively_correlated_with | [[ATF3]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[CCR1]] | biolink:positively_correlated_with | [[KLF4]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[CCR1]] | biolink:positively_correlated_with | [[HES4]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[CCR1]] | biolink:positively_correlated_with | [[MAFB]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[CCR1]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "ERADMT gene set, as a set of genes in the regulatory network, is a potential risk marker for AD development and an indicator for the assessment of exercise therapy adherence in AD patients." |
| [[TNF]] | biolink:positively_correlated_with | [[ATF3]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[TNF]] | biolink:positively_correlated_with | [[KLF4]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[TNF]] | biolink:positively_correlated_with | [[HES4]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[TNF]] | biolink:positively_correlated_with | [[MAFB]] |  | "Correlation analysis based on the GSE140831 dataset suggested that the expression in the ERADMT gene set was positively correlated with each other, except for APP, which was negatively correlated with ATF3 and HES4 (Supplementary Figure 4A)." |
| [[TNF]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "ERADMT gene set, as a set of genes in the regulatory network, is a potential risk marker for AD development and an indicator for the assessment of exercise therapy adherence in AD patients." |
| [[ATF3]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "ERADMT gene set, as a set of genes in the regulatory network, is a potential risk marker for AD development and an indicator for the assessment of exercise therapy adherence in AD patients." |
| [[KLF4]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "ERADMT gene set, as a set of genes in the regulatory network, is a potential risk marker for AD development and an indicator for the assessment of exercise therapy adherence in AD patients." |
| [[FOSL1]] | biolink:positively_correlated_with | [[HES4]] |  | "The expression of transcription factors in each module had a substantial positive connection, and FOSL1, HES4, and MAFB identified the genes in the M4 module as a possible cluster of transcriptional regulators linked to the start of Alzheimer’s disease." |
| [[HES4]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "ERADMT gene set, as a set of genes in the regulatory network, is a potential risk marker for AD development and an indicator for the assessment of exercise therapy adherence in AD patients." |
| [[FOSL1]] | biolink:positively_correlated_with | [[MAFB]] |  | "The expression of transcription factors in each module had a substantial positive connection, and FOSL1, HES4, and MAFB identified the genes in the M4 module as a possible cluster of transcriptional regulators linked to the start of Alzheimer’s disease." |
| [[MAFB]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "ERADMT gene set, as a set of genes in the regulatory network, is a potential risk marker for AD development and an indicator for the assessment of exercise therapy adherence in AD patients." |
| [[APP]] | biolink:contributes_to | amyloid deposition (HP:0011034; MESH:D058225) |  | "APP is significantly upregulated in CD14+ monocytes of AD patients, indicating that APP may be a key cause of amyloid deposition." |
| [[CCR1]] | biolink:directly_physically_interacts_with | CCL3 (HGNC:10627) |  | "CCR1 is a receptor for CCL3." |
| [[TNF]] | biolink:directly_physically_interacts_with | TNFRSF1B (HGNC:11917) |  | "TNF is a ligand for TNFRSF1B, TNFRSF1A, NOTCH and FAS." |
| [[TNF]] | biolink:directly_physically_interacts_with | TNFRSF1A (HGNC:11916) |  | "TNF is a ligand for TNFRSF1B, TNFRSF1A, NOTCH and FAS." |
| [[TNF]] | biolink:directly_physically_interacts_with | FAS (HGNC:11920) |  | "TNF is a ligand for TNFRSF1B, TNFRSF1A, NOTCH and FAS." |
| [[ATF3]] | biolink:contributes_to | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "ATF3 can also promote the progression of neurodegenerative diseases." |
| [[ATF3]] | biolink:associated_with | sciatic nerve injury (MONDO:0021178; MESH:D014947) |  | "Treadmill exercise can promote sciatic nerve injury regeneration through ATF3 upregulation." |
| [[KLF4]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "However, in a recent study, KFL4 was found to be associated with the onset of dementia, which is consistent with our findings." |
| [[HES4]] | biolink:associated_with | Huntington disease (MONDO:0007739; MESH:D006816) |  | "Epigenetic dysregulation of HES4 may be closely associated with the development of Huntington’s disease in the nervous system." |
| APP mutations (variant) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "APP mutations cause AD." |
| amyloid β-protein (CHEBI:64645; MESH:D016229) | biolink:associated_with | amyloid deposition (HP:0011034; MESH:D058225) |  | "Amyloid hypothesis shows that secretases cleave APP to form toxic amyloid-B (AB) peptides and plaques, thus causing AD." |
