---
type: source
title: "CDK5R1-related subtypes and immune infiltrates in Alzheimer disease"
paper_title: "Identification of Two CDK5R1-Related Subtypes and Characterization of Immune Infiltrates in Alzheimer's Disease Based on an Integrated Bioinformatics Analysis"
domain: neuroscience
status: developing
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-001046
pmid: "36561735"
pmcid: "PMC9767738"
doi: "10.1155/2022/6766460"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9767738/"
sources: ["[[.raw/01M4P89V7HSPAFA27CC6CCKGWV/normalized.md]]"]
tags: [transcriptomics, biomarker, neuroinflammation]
---

# CDK5R1-related subtypes and immune infiltrates in Alzheimer disease

A 2022 bioinformatics study of public microarray data from post-mortem brain. It asks whether [[CDK5R1]], a gene of the [[Reelin signaling pathway]], is changed in [[Alzheimer disease]], then uses the genes that co-vary with CDK5R1 to split Alzheimer samples into two subtypes (C1 and C2) and compares their immune cell content. Everything rests on expression data; no experiment was done on cells, tissue or animals.

## Design

- Three Gene Expression Omnibus datasets: GSE48350 (173 normal and 80 Alzheimer samples, several brain regions), GSE1297 (9 normal, 7 severe Alzheimer; hippocampus) and GSE33000 (157 normal, 310 Alzheimer). Thirteen Reelin pathway genes came from MSigDB.
- The 80 Alzheimer samples of GSE48350 were split at the median CDK5R1 level into low and high groups and compared with limma (adjusted p below 0.05, absolute log fold change at least 1).
- [[Weighted gene co-expression network analysis]] on the same 80 samples gave 30 modules; the two modules most correlated with CDK5R1 were intersected with the differentially expressed genes (266 genes in all).
- [[Consensus clustering]] of those 266 genes (k-means, 100 repeats of 80% of samples) chose k = 2.
- Genes differing between the subtypes (adjusted p below 0.05, absolute log fold change at least 1.5) went to GO and KEGG enrichment and to [[Gene set variation analysis]]; immune cell fractions came from [[CIBERSORT immune cell deconvolution]]. Subtypes were compared with the Wilcoxon rank sum test.

## Findings

- CDK5R1 was lower in Alzheimer than normal samples in all three datasets. By region in GSE48350 it was lower in entorhinal cortex, hippocampus and superior frontal gyrus but not in postcentral gyrus.
- High versus low CDK5R1 gave 441 differentially expressed genes (334 down and 107 up in the low group). The strongest positive module (antiquewhite4) correlated with CDK5R1 at r = 0.69 and the strongest negative (darkseagreen4) at r = -0.62.
- The 80 samples fell into C1 (n = 39) and C2 (n = 41). The two subtypes differed in 244 genes (165 up and 79 down in C2), enriched for [[Synapse organization]], cation channel regulation, neurotransmitter transport, neuroactive ligand-receptor interaction and the GABAergic synapse ([[GABA signaling pathway]]).
- GSVA scored immune and signalling pathways (primary immunodeficiency, B cell receptor, Toll-like receptor, complement, innate immune response, WNT, JNK cascade, cell cycle, axon guidance) as lower in C2 than C1.
- Of ten Reelin pathway genes, [[CRK]], [[RELN]], [[STAT5A]], [[CDK5]], CDK5R1 and [[SH3KBP1]] were lower and [[DAB2IP]], [[LRP8]], [[DAB1]] and [[FYN]] higher in C2. For telling the subtypes apart the AUC was 0.911 for STAT5A, 0.844 for CDK5R1, 0.826 for FYN and 0.766 for CDK5.
- CIBERSORT estimates: plasma cells, follicular helper T cells and activated NK cells were higher in C2; [[Monocyte]] fractions, M2 macrophages, gamma delta T cells and activated dendritic cells were higher in C1. Individual Reelin genes correlated with particular cell types (for example RELN with monocytes and M2 macrophages, STAT5A positively with monocytes and negatively with plasma cells and activated NK cells), see [[Immune response]].

## Assessment

- The subtypes are defined by expression of one gene in 80 samples from one dataset and were not tested in the other two datasets, so whether C1 and C2 are stable disease subtypes is untested. Splitting at the median guarantees two groups.
- CIBERSORT fractions from bulk brain microarrays are estimates; the immune differences are associations, and the discussion's readings (for example that NK or M2 changes drive progression) come from other literature, not from this analysis.
- The AUC values separate the study's own subtypes, which were built from CDK5R1-related genes, so they are partly circular and say little about diagnosing Alzheimer disease. The authors give no correction or independent validation, and name small sample sizes and the lack of cell or animal work as limits.
- Brain region differences within GSE48350 were not modelled in the clustering, so regional composition may contribute to the split.

## Why This Source Matters

It links the reduced CDK5R1 level reported in Alzheimer brain to a [[Reelin signaling pathway]] gene signature and to immune cell composition, giving a hypothesis (a low-CDK5R1, immune-depleted C2 state) rather than a mechanism. CDK5R1 encodes the p35 activator of [[CDK5]], whose kinase activity is otherwise discussed in this field as a driver of [[Tau hyperphosphorylation]]; here the gene is lower, not higher, so the direction of the expression change and the protein-level activity story are not the same question.

## Open Questions

- Do the C1 and C2 subtypes replicate when the same clustering is applied to independent Alzheimer brain expression data such as GSE1297 and GSE33000 or RNA-seq cohorts (the study clustered only GSE48350)?
- Is the lower CDK5R1 transcript level in Alzheimer brain accompanied by lower p35 protein or CDK5 activity (the study measured mRNA only)?
- Do the CIBERSORT differences between subtypes reflect true immune infiltration or the neuronal loss and cell composition of each sample (bulk tissue, no single-cell reference)?

## Connections

- Disease: [[Alzheimer disease]]
- Genes: [[CDK5R1]], [[CDK5]], [[RELN]], [[LRP8]], [[FYN]], [[CRK]], [[STAT5A]], [[DAB1]], [[DAB2IP]], [[SH3KBP1]]
- Pathway and processes: [[Reelin signaling pathway]], [[Immune response]], [[Synapse organization]], [[GABA signaling pathway]]
- Methods: [[Weighted gene co-expression network analysis]], [[Consensus clustering]], [[CIBERSORT immune cell deconvolution]], [[Gene set variation analysis]]
- Cell type: [[Monocyte]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[CDK5R1]] | biolink:associated_with | [[RELN]] |  | "Cyclin-dependent kinase 5 regulatory subunit 1 (CDK5R1) is one of the key genes in the Reelin pathway, whose activity plays an important role in neuronal differentiation and migration during neurodevelopment and is involved in neurodegenerative diseases." |
| [[CDK5R1]] | biolink:regulates | [[MAPT]] | direction=increased | "It has been reported that CDK5R1 is an important regulator participating in the aberrant hyperphosphorylation of tau in AD." |
| [[CDK5R1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "CDK5R1 was downregulated in AD." |
| [[CDK5R1]] | biolink:associated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Cyclin-dependent kinase 5 regulatory subunit 1 (CDK5R1) is one of the key genes in the Reelin pathway, whose activity plays an important role in neuronal differentiation and migration during neurodevelopment and is involved in neurodegenerative diseases." |
| [[CDK5R1]] | biolink:contributes_to | intellectual disability (MONDO:0001071; MESH:D008607) |  | "The polymorphisms and mutations in CDK5R1 and CDK5 contributed to the onset of intellectual disability." |
| [[CDK5R1]] | biolink:contributes_to | [[Cognitive impairment]] (MESH:D060825) |  | "Suppression of CDK5R1 activity improved diabetes-related cognitive deficits." |
| [[RELN]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[RELN]] | biolink:contributes_to | epilepsy (MONDO:0005027; MESH:D004827) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[RELN]] | biolink:contributes_to | intellectual disability (MONDO:0001071; MESH:D008607) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[RELN]] | biolink:contributes_to | depression (MONDO:0002050) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[RELN]] | biolink:contributes_to | bipolar disorder (MONDO:0004985; MESH:D001714) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[RELN]] | biolink:contributes_to | schizophrenia (MONDO:0005090; MESH:D012559) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[RELN]] | biolink:contributes_to | autism (MONDO:0005260; MESH:D001321) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[RELN]] | biolink:contributes_to | lissencephaly (MONDO:0018838; MESH:D054082) |  | "The Reelin signaling pathway was involved in the pathogenesis of human brain diseases, including epilepsy, AD, mental retardation, depression, bipolar disorder, schizophrenia, autism, and lissencephaly." |
| [[CDK5]] | biolink:contributes_to | intellectual disability (MONDO:0001071; MESH:D008607) |  | "The polymorphisms and mutations in CDK5R1 and CDK5 contributed to the onset of intellectual disability." |
| [[MAPT]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Based on previous studies, the abnormal hyperphosphorylation of tau protein, neuroinflammation, mitochondrial cascade, oxidative stress, and deposition of amyloid β-protein are the primary pathogeneses of AD." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Based on previous studies, the abnormal hyperphosphorylation of tau protein, neuroinflammation, mitochondrial cascade, oxidative stress, and deposition of amyloid β-protein are the primary pathogeneses of AD." |
| [[CDK5R1]] | biolink:associated_with | Primary immunodeficiency (MONDO:0003778) |  | "Our findings indicated that CDK5R1-related genes were mainly enriched in primary immunodeficiency, B cell receptor signaling pathway, Toll-like receptor signaling pathway, complement and coagulation cascades, regulation of immune response, activation of the innate immune response, lymphocyte costimulation, WNT signaling pathway, regulation of JNK cascade, cell cycle, T cell differentiation in the thymus, negative regulation of exocytosis, and axon guidance (Figure 7(e)), and these pathways were inhibited in the C2 subgroup." |
| [[CRK]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| [[DAB2IP]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| [[DAB2IP]] | biolink:associated_with | renal cell carcinoma (MONDO:0005086; MESH:D002292) |  | "DAB2IP is one of the members of Ras GTPase superfamily implicated in the regulation of cell metastasis, apoptosis, and proliferation; it also has been associated with immune cell infiltrates in renal cell carcinoma." |
| [[LRP8]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| [[STAT5A]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| [[STAT5A]] | biolink:contributes_to | leukemia (MONDO:0005059; MESH:D007938) |  | "An increase of STAT5A expression plays a vital role in leukemia development." |
| [[CDK5]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| [[CDK5R1]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Our results showed the important role of CDK5R1 in the development and progression of AD and implied that the Reelin pathway-related genes may serve as potential markers for the diagnosis and treatment of AD patients." |
| miRNA (MESH:D035683) | biolink:regulates | [[CDK5R1]] |  | "The previous study has revealed that CDK5R1 implicated in AD pathogenesis is regulated by the miR-15/107 family of miRNAs, which is anomalously regulated in AD." |
| [[DAB1]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| [[FYN]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| [[FYN]] | biolink:associated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "FYN is an important regulator in neurodegenerative pathways." |
| [[FYN]] | biolink:associated_with | memory deficits (MESH:D008569) |  | "It has been reported that targeting FYN could rescue memory deficits in an AD mouse model." |
| [[SH3KBP1]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Ten Reelin pathway-related genes (CRK, DAB2IP, LRP8, RELN, STAT5A, CDK5, CDK5R1, DAB1, FYN, and SH3KBP1) may serve as potential diagnostic markers for AD patients." |
| miRNA (MESH:D035683) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The previous study has revealed that CDK5R1 implicated in AD pathogenesis is regulated by the miR-15/107 family of miRNAs, which is anomalously regulated in AD." |
