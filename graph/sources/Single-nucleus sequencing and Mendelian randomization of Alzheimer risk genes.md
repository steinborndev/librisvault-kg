---
type: source
title: "Single-nucleus sequencing and Mendelian randomization of Alzheimer risk genes"
paper_title: "Integrative analysis of single-nucleus RNA sequencing and Mendelian randomization to explore novel risk genes for Alzheimer’s disease"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000237
pmid: "39560568"
pmcid: "PMC11575974"
doi: "10.1097/md.0000000000040551"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC11575974/"
sources: ["[[.raw/01M4DY94K9KFMNXW5P48NCCGN7/normalized.md]]"]
tags: [macrophage, eqtl, alzheimer-risk-locus, secondary-analysis]
---

# Single-nucleus sequencing and Mendelian randomization of Alzheimer risk genes

A secondary analysis of public data that asks which genes active in brain macrophages causally change the risk of [[Alzheimer disease]]. The authors clustered a published single-nucleus RNA sequencing dataset of dorsolateral prefrontal cortex (GEO series GSE243292), took the genes that differ in macrophages, and tested each one by [[Mendelian randomization]] using blood expression quantitative trait loci as the exposure and a large European Alzheimer [[Genome-wide association study]] as the outcome.

## Why This Source Matters

It shows how a cell-type-resolved expression screen can be used to shortlist candidates for a genetic causal test, instead of testing every gene in the genome. The seven genes it returns (one with a plausible neuronal role, six expressed mainly in macrophages) point at innate immunity in the brain, in line with the immune loci already known from GWAS. The causal claims are thin (see Assessment), so the result is best read as a candidate list.

## Design

- Expression data: ten samples from GSE243292, two control brains without amyloid or tau pathology and eight Alzheimer brains with both. Processing used Seurat 4.2.0 with filters of 200 to 4000 genes and under 5% mitochondrial reads per nucleus, Harmony batch correction, the top 2000 variable genes, 15 principal components and UMAP. See [[Single-nucleus RNA sequencing]].
- Exposure: eQTLGen cis-eQTL summary statistics (19,942 genes, 31,684 European-ancestry participants).
- Outcome: GWAS catalog study GCST90027158, 487,511 European-ancestry participants (39,106 cases, 46,828 by-proxy cases, 401,577 controls).
- Instruments: SNPs under a locus-wide threshold, clumped at R2 below 0.001 over a 10,000 kb window, keeping those at P below 5e-8. Inverse variance weighting was the main estimator, with weighted median and MR-Egger as supports and a leave-one-out check.
- Two-sided tests, P below .05, in R 4.2.0.

## Findings

- 23 clusters were annotated into eight cell groups: oligodendrocytes, oligodendrocyte precursor cells, astrocytes, macrophages, endothelial cells, glutamatergic neurons, neural stem cells and neurons. Macrophages made up a larger share of nuclei in the Alzheimer group than in controls, and 305 genes differed in them.
- Of these 305, seven had an inverse-variance-weighted causal estimate with P below .05. Estimates below one (lower Alzheimer risk with higher expression): [[CACNA2D3]] 0.938 (0.902 to 0.975), [[INPP5D]] 0.844 (0.802 to 0.888), [[RBM47]] 0.937 (0.891 to 0.985), [[TBXAS1]] 0.965 (0.934 to 0.998). Estimates above one (higher risk): [[EPB41L2]] 1.079 (1.029 to 1.130), [[MYO1F]] 1.083 (1.004 to 1.168), [[SSH2]] 1.049 (1.015 to 1.083).
- Leave-one-out analysis gave similar estimates after dropping each SNP, so no single variant drove any of the seven.
- Expression: INPP5D, MYO1F, RBM47 and TBXAS1 were low in all groups except macrophages. EPB41L2 and SSH2 were highest in macrophages with moderate signal in glutamatergic neurons. CACNA2D3 was mostly in glutamatergic neurons.
- The authors link the macrophage increase to amyloid-beta-activated macrophages releasing reactive oxygen species and cytokines such as [[IL1B]], TNF-alpha and [[IL6]], and cite myosin IF as a regulator of macrophage IL-1 beta release in a colitis model. See [[Neuroinflammation]].

## Assessment

- The eQTL exposure comes from blood, whereas the candidates were chosen from brain macrophage expression; whether the blood-derived genetic effect on expression holds in brain macrophages or microglia is assumed, not shown. No colocalisation test was run, so linkage of the instrument to a neighbouring causal variant is not excluded.
- Only the inverse-variance-weighted P value is reported, with no multiple-testing correction across 305 genes, no per-gene SNP counts, no MR-Egger intercept or weighted-median results in the text, and no heterogeneity statistics. Several estimates (MYO1F, TBXAS1, RBM47) sit near the P = .05 line.
- The cell-composition result rests on two control samples against eight Alzheimer samples, and the samples were stratified by APOE and TREM2 status, which could confound macrophage counts. The cell labelled macrophage is probably the brain-resident microglia or perivascular macrophage population, which marker annotation at this resolution cannot separate.
- The instrument threshold is stated twice with different values (1e-8 and 5e-8), and the discussion writes "SHH2" where SSH2 is meant.
- Participants were all of European ancestry, which the authors state limits generalisation. No functional validation was done.
- Some risk genes are already known at the locus level: INPP5D sits in a known Alzheimer GWAS region, so the new part is the cell-type context rather than the association.

## Open Questions

- Do the causal estimates for these seven genes hold when brain-derived or microglia-specific eQTL data replace blood eQTLs (the study used eQTLGen blood data only)?
- Does a colocalisation analysis support a shared causal variant between expression of each of the seven genes and Alzheimer risk (not run in the paper)?
- Is the rise in macrophage proportion in Alzheimer cortex reproduced in larger single-nucleus cohorts (the comparison used two control and eight Alzheimer samples)?
- Does reducing EPB41L2, MYO1F or SSH2 expression in macrophages or microglia change amyloid or inflammatory readouts (no functional experiment was done)?

## Connections

- Disease: [[Alzheimer disease]]
- Candidate genes: [[CACNA2D3]], [[INPP5D]], [[RBM47]], [[TBXAS1]], [[EPB41L2]], [[MYO1F]], [[SSH2]]
- Methods: [[Mendelian randomization]], [[Single-nucleus RNA sequencing]], [[Genome-wide association study]]
- Related immune and microglial biology: [[Neuroinflammation]], [[TREM2]], [[APOE]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[CACNA2D3]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among these genes, CACNA2D3, INPP5D, RBM47, and TBXAS1 were associated with a decreased risk of AD, whereas EPB41L2, MYO1F, and SSH2 were associated with an increased risk." |
| [[INPP5D]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among these genes, CACNA2D3, INPP5D, RBM47, and TBXAS1 were associated with a decreased risk of AD, whereas EPB41L2, MYO1F, and SSH2 were associated with an increased risk." |
| [[RBM47]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among these genes, CACNA2D3, INPP5D, RBM47, and TBXAS1 were associated with a decreased risk of AD, whereas EPB41L2, MYO1F, and SSH2 were associated with an increased risk." |
| [[TBXAS1]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among these genes, CACNA2D3, INPP5D, RBM47, and TBXAS1 were associated with a decreased risk of AD, whereas EPB41L2, MYO1F, and SSH2 were associated with an increased risk." |
| [[EPB41L2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among these genes, CACNA2D3, INPP5D, RBM47, and TBXAS1 were associated with a decreased risk of AD, whereas EPB41L2, MYO1F, and SSH2 were associated with an increased risk." |
| [[MYO1F]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among these genes, CACNA2D3, INPP5D, RBM47, and TBXAS1 were associated with a decreased risk of AD, whereas EPB41L2, MYO1F, and SSH2 were associated with an increased risk." |
| [[SSH2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among these genes, CACNA2D3, INPP5D, RBM47, and TBXAS1 were associated with a decreased risk of AD, whereas EPB41L2, MYO1F, and SSH2 were associated with an increased risk." |
| [[Alzheimer disease]] (MESH:D000544) | biolink:associated_with | amyloid-β (CHEBI:64645; MESH:D016229) |  | "Alzheimer’s disease (AD) is a specific, progressive, and irreversible neurodegenerative disorder of the brain, that exhibits several complex pathophysiological mechanisms, predominantly manifesting as aggregation of neurofibrillary tangles and amyloid-β plaques." |
| [[IL1B]] | biolink:contributes_to | neuronal injury (MONDO:0021178; MESH:D014947) |  | "In the brain, macrophages are activated in the presence of amyloid-β, and these activated macrophages produce neurotoxic substances that contribute to neuronal injury." |
| TNF (HGNC:11892) | biolink:contributes_to | neuronal injury (MONDO:0021178; MESH:D014947) |  | "In the brain, macrophages are activated in the presence of amyloid-β, and these activated macrophages produce neurotoxic substances that contribute to neuronal injury." |
| [[IL6]] | biolink:contributes_to | neuronal injury (MONDO:0021178; MESH:D014947) |  | "In the brain, macrophages are activated in the presence of amyloid-β, and these activated macrophages produce neurotoxic substances that contribute to neuronal injury." |
| amyloid-β (CHEBI:64645; MESH:D016229) | biolink:contributes_to | neuronal injury (MONDO:0021178; MESH:D014947) |  | "In the brain, macrophages are activated in the presence of amyloid-β, and these activated macrophages produce neurotoxic substances that contribute to neuronal injury." |
| reactive oxygen species (CHEBI:26523; MESH:D017382) | biolink:contributes_to | neuronal injury (MONDO:0021178; MESH:D014947) |  | "In the brain, macrophages are activated in the presence of amyloid-β, and these activated macrophages produce neurotoxic substances that contribute to neuronal injury." |
| [[EPB41L2]] | biolink:associated_with | cancer (MONDO:0004992; MESH:D009369) |  | "Mutations or dysregulation of EPB41L2 have been implicated in various diseases, including cancer and neurological disorders, reflecting its importance in cell function and integrity." |
| [[EPB41L2]] | biolink:associated_with | neurological disorder (MONDO:0005071; MESH:D009422) |  | "Mutations or dysregulation of EPB41L2 have been implicated in various diseases, including cancer and neurological disorders, reflecting its importance in cell function and integrity." |
| [[EPB41L2]] | biolink:contributes_to | neuroinflammation (HP:0033429; MESH:D000090862) |  | "The expression of these genes could potentially contribute to the excitotoxicity and neuroinflammation observed in the disease." |
| [[MYO1F]] | biolink:affects | [[IL1B]] | direction=increased | "Myo1F promotes the secretion of pro-inflammatory cytokines such as IL-1β in macrophages, contributing to epithelial damage in inflammatory conditions." |
| [[MYO1F]] | biolink:contributes_to | colitis (MONDO:0005292; MESH:D003092) |  | "In a colitis model, Myo1F deficiency led to reduced secretion of pro-inflammatory cytokines, decreased epithelial damage, improved disease activity, and enhanced tissue repair." |
| [[SSH2]] | biolink:contributes_to | neuroinflammation (HP:0033429; MESH:D000090862) |  | "The expression of these genes could potentially contribute to the excitotoxicity and neuroinflammation observed in the disease." |
