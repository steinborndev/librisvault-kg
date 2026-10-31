---
type: source
title: "Amyloid-beta and tau-associated microglia profiles in Alzheimer brain snRNAseq"
paper_title: "Distinct amyloid-β and tau-associated microglia profiles in Alzheimer’s disease"
domain: neuroscience
status: developing
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-000782
pmid: "33609158"
pmcid: "PMC8043951"
doi: "10.1007/s00401-021-02263-w"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8043951/"
sources: ["[[.raw/01M4NRAVGR4V0GEN1T5010NDDE/normalized.md]]"]
tags: [microglia, single-cell, tau, human-brain]
---

# Amyloid-beta and tau-associated microglia profiles in Alzheimer brain snRNAseq

Single-nucleus RNA sequencing of 482,472 neuron- and oligodendrocyte-depleted nuclei from cortex of 10 [[Alzheimer disease]] donors and 8 non-demented controls. Of the seven cell types analysed, only microglia changed with disease, and they split into two disease-linked profiles: AD1 microglia, a phagocytic/activated state that tracks [[Amyloid-beta]] load, and AD2 microglia, a more homeostatic state that tracks phospho-[[MAPT]] (tau) load. See [[AD1 and AD2 microglia]].

## Design

- Donors and regions: 10 Alzheimer and 8 control donors from the Born-Bunge NeuroBiobank (Antwerp). Each donor contributed the occipital cortex (amyloid-beta with no or little tau in the Alzheimer donors) and the occipitotemporal cortex (fusiform gyrus; amyloid-beta plus tau). Five controls were free of both pathologies (CTR) and three had mild amyloid-beta only (CTR+). Grey matter only; RNA integrity number above 5.
- Nuclei: sorted as DAPI-positive, NEUN-negative, OLIG2-negative to enrich microglia, astrocytes and rarer types, then run on 10x Genomics Chromium 3' v3. NEUN-positive and OLIG2-positive fractions went to bulk QuantSeq as a depletion check. See [[Nuclei depletion for microglia enrichment]] and [[Single-nucleus RNA sequencing]].
- Analysis: Seurat integration and subclustering per cell type, logistic-regression differential expression with donor as latent variable, Chi-squared tests of subcluster distribution against donor group, Pearson correlation of subcluster share with amyloid-beta and phospho-tau load (ImageJ on 4G8 and AT8 stains), and [[Pseudotime trajectory analysis]] with Monocle3.
- Validation: immunofluorescence for [[P2RY12]], IBA1 and [[ITGAX]] in frontal cortex of 29 donors (Alzheimer, dementia with Lewy bodies, controls); GRID2 immunohistochemistry and IBA1/GRID2/tau triple labelling in a further set of control and Alzheimer donors.

## Findings

- Cell types: 12 clusters, of which seven were analysed. Microglia were about 40% of nuclei (n = 148,606) and astrocytes about 30% (n = 128,764); the rest were endothelial cells, CNS-associated macrophages, lymphocytes, mural cells and fibroblasts. Bulk RNAseq of the NEUN-positive and OLIG2-positive fractions showed no consistent Alzheimer-associated change.
- Only microglia changed: subcluster distribution was associated with donor group (control versus Alzheimer) in the occipital cortex (p = 0.01; occipitotemporal p = 0.07). Astrocytes differed by region but not by disease.
- Thirteen microglia subclusters. Subclusters 0, 1 and 5 were homeostatic (P2RY12, [[CX3CR1]]) and more abundant in controls. Subclusters 7, 9 and 10 formed AD1, enriched for ITGAX, LPL, [[GPNMB]], MYO1E and [[SPP1]]; subclusters 2, 3 and 6 formed AD2, enriched for homeostatic genes plus neuron-related genes such as [[GRID2]], ADGRB3 and DPP10. Smaller subclusters carried inflammatory (8, 11), stress (4) and proliferation (12) signatures.
- AD1 trajectory: pseudotime ordered 0, 1, 5, 7, 9, 10, with control microglia at the start and Alzheimer microglia at the end. Nearly all of the top 40 non-ribosomal DAM genes and the top 37 ARM genes rose along it, so AD1 resembles the mouse phagocytic/activated state ([[Disease-associated microglia]]). [[TREM2]] expression came before [[APOE]] along the trajectory, and [[CD163]] was confined to nuclei at the end. The AD2 trajectory was very short and showed no intermediate stages.
- In situ, P2RY12 and ITGAX immunoreactivity in microglia were inversely correlated across the 29 donors.
- Load correlations: AD1 share correlated strongly with amyloid-beta load in samples with amyloid-beta only, but not in samples that also had tau. In samples with both pathologies, AD2 share correlated with phospho-tau load. Homeostatic subclusters correlated negatively with amyloid-beta and/or tau load. The authors note that subcluster shares are relative, so a rise in AD2 can by itself remove the AD1 correlation.
- Expression differences: about 2000 differentially expressed genes for AD1 against homeostatic subclusters (subclusters 9 and 10 further from homeostasis than 7) and about 150 for AD2. AD1 terms were cell migration, phagocytosis and lipid localisation, and 'cellular response to amyloid-beta' in subclusters 9 and 10; AD2 terms were synapse organisation and axonogenesis. Few genes were shared between the two profiles.
- GRID2: the most enriched AD2 gene. GRID2-positive cells with microglia-like morphology were abundant in Alzheimer samples with tau, rare in controls and in amyloid-only samples, colocalised with IBA1 and with tau pathology, and were often seen in neuritic plaque-like structures.
- Genetic risk: of 63 GWAS Alzheimer risk genes expressed in the human microglia core profile, 15 were significantly enriched in AD1 and six moderately enriched in AD2.
- Against earlier unsorted snRNAseq studies that found 47 and 22 Alzheimer-associated microglial genes, the enrichment gave about 9000 microglia per donor and about 2500 differentially expressed genes.

## Why This Source Matters

It gives the first human snRNAseq split of disease-associated microglia by pathology type: an amyloid-linked state matching the mouse phagocytic/activated profile, and a separate tau-linked state, AD2, not described before and marked by GRID2. The finding that risk genes lie mainly in the amyloid-linked profile supports amyloid-driven microglia responses as upstream, while the AD2 state, with no complement signature and a near-homeostatic profile, raises the possibility of a supportive role tied to the pathology that tracks dementia severity. The data are deposited at Gene Expression Omnibus (GSE148822).

## Assessment

- Small cohort (10 Alzheimer donors, 8 controls) and one pair of cortical regions; AD2 is defined partly through the occipitotemporal region, where region and tau burden are confounded.
- The AD1/AD2 correlations use relative subcluster shares, which the authors acknowledge are dependent variables.
- The depletion design lowers power for neurons, oligodendrocytes and other depleted types, and grey matter only was sampled, so absence of change in astrocytes and other cells is weak evidence.
- Function of AD2 (neurotrophic or response to neuronal stress) is inferred from gene ontology terms and the missing complement signature; no functional test was made. GRID2 is also a Purkinje neuron gene, so the protein validation rests on microglia-like morphology and IBA1 colocalisation in tissue sections.
- Trajectory direction is computational, supported by the in situ P2RY12 and ITGAX inverse relationship.

## Open Questions

- What do AD2 microglia do in tau-bearing tissue, and are they neurotrophic, a response to dying neurons, or neither (inferred from gene ontology terms and absent complement genes; no functional experiment)?
- Does GRID2 protein in AD2 microglia affect synapses or neuronal signalling (only expression and localisation were shown)?
- Do AD1 and AD2 profiles appear in white matter and in other regions such as hippocampus (only cortical grey matter of two regions was sampled)?
- Does amyloid-beta load predict AD2 abundance in tau-free tissue, or does AD2 depend on tau itself (the occipital cortex had little tau and few AD2 nuclei, but region and tau are confounded)?

## Connections

- Microglial states: [[AD1 and AD2 microglia]], [[Disease-associated microglia]], [[Microglial cell activation]]
- Genes: [[TREM2]], [[APOE]], [[P2RY12]], [[CX3CR1]], [[ITGAX]], [[GPNMB]], [[SPP1]], [[CD163]], [[GRID2]], [[MAPT]]
- Pathology: [[Amyloid-beta]], [[Neurofibrillary tangle]]
- Methods: [[Single-nucleus RNA sequencing]], [[Nuclei depletion for microglia enrichment]], [[Pseudotime trajectory analysis]], [[Genome-wide association study]]
- Disease: [[Alzheimer disease]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[Alzheimer disease]] (MESH:D000544) | biolink:associated_with | [[MAPT]] |  | "Alzheimer’s disease (AD) is the most prevalent form of dementia and is characterized by abnormal extracellular aggregates of amyloid-β and intraneuronal hyperphosphorylated tau tangles and neuropil threads." |
| [[MAPT]] | biolink:associated_with | Amyloid plaques (MESH:D058225) |  | "Here, we performed snRNAseq on 482,472 nuclei from non-demented control brains and AD brains containing only amyloid-β plaques or both amyloid-β plaques and tau pathology." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Amyloid-β and tau-associated AD-changes were studied in single-nucleus transcriptomes by FACS sorting of DAPIpos nuclei from 10 AD and 8 non-demented controls, and processed on a 10× Genomics platform (Fig. 1a–c)." |
| [[P2RY12]] | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 0, 1 and 5 were more abundant in CTR than in AD samples and contained homeostatic microglia, as these cells were enriched for homeostasis markers, such as P2RY12 and CX3CR1." |
| [[CX3CR1]] | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 0, 1 and 5 were more abundant in CTR than in AD samples and contained homeostatic microglia, as these cells were enriched for homeostasis markers, such as P2RY12 and CX3CR1." |
| [[ITGAX]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| LPL (HGNC:6677) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| [[GPNMB]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| MYO1E (HGNC:7599) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| [[SPP1]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| [[GRID2]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 2, 3 and 6 were enriched for expression of homeostasis genes, such as CX3CR1 and P2RY12, but also enriched for several neuron-related genes, such as GRID2, ADGRB3 and DPP10." |
| ADGRB3 (HGNC:945) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 2, 3 and 6 were enriched for expression of homeostasis genes, such as CX3CR1 and P2RY12, but also enriched for several neuron-related genes, such as GRID2, ADGRB3 and DPP10." |
| DPP10 (HGNC:20823) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Subclusters 2, 3 and 6 were enriched for expression of homeostasis genes, such as CX3CR1 and P2RY12, but also enriched for several neuron-related genes, such as GRID2, ADGRB3 and DPP10." |
| TOP2A (HGNC:11989) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A small subcluster of microglia was enriched for expression of genes associated with proliferation, such as TOP2A and MKI67 (cluster 12), and these were also more abundant in AD samples than in CTRs (Fig. 2b–d, Fig S6c and d, and Table S3)." |
| MKI67 (HGNC:7107) | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A small subcluster of microglia was enriched for expression of genes associated with proliferation, such as TOP2A and MKI67 (cluster 12), and these were also more abundant in AD samples than in CTRs (Fig. 2b–d, Fig S6c and d, and Table S3)." |
| [[ITGAX]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| LPL (HGNC:6677) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| [[GPNMB]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| MYO1E (HGNC:7599) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| [[SPP1]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Subclusters 7, 9 and 10 were enriched for expression of genes detected in phagocytic/activated microglia derived from amyloid mouse models, including ITGAX, LPL, GPNMB, MYO1E and SPP1." |
| MYO1E (HGNC:7599) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Color-scale indicates pseudotime, subclusters and expression of CX3CR1 (homeostasis) and MYO1E (AD1)." |
| [[P2RY12]] | biolink:associated_with | AIF1 (HGNC:352) |  | "Left: Microglia expressing P2RY12 and IBA1, but not ITGAX." |
| [[P2RY12]] | biolink:negatively_correlated_with | [[ITGAX]] |  | "A significant inverse correlation between P2RY12 and ITGAX immunoreactivity in microglia was identified, which illustrates a consistent functional transformation of microglia in line with gene expression changes along the AD1-trajectory (Fig. 3h)." |
| AIF1 (HGNC:352) | biolink:associated_with | [[ITGAX]] |  | "Right: Microglia expressing IBA1 and ITGAX, but not P2RY12." |
| [[GRID2]] | biolink:associated_with | AIF1 (HGNC:352) |  | "f IBA1 (green), GRID2 (orange) and phospho-tau (magenta) colocalization in human AD brain tissue." |
| [[GRID2]] | biolink:associated_with | [[MAPT]] |  | "f IBA1 (green), GRID2 (orange) and phospho-tau (magenta) colocalization in human AD brain tissue." |
| CACNA1A (HGNC:1388) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Moreover, the GO term ‘cellular response to amyloid-beta’ was significantly enriched in subclusters 9 and 10, in line with our finding that AD1 microglia abundance is associated with amyloid-β load (CACNA1A, NAMPT, TREM2) (Fig. S7b, Table S8)." |
| [[NAMPT]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Moreover, the GO term ‘cellular response to amyloid-beta’ was significantly enriched in subclusters 9 and 10, in line with our finding that AD1 microglia abundance is associated with amyloid-β load (CACNA1A, NAMPT, TREM2) (Fig. S7b, Table S8)." |
| [[TREM2]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Moreover, the GO term ‘cellular response to amyloid-beta’ was significantly enriched in subclusters 9 and 10, in line with our finding that AD1 microglia abundance is associated with amyloid-β load (CACNA1A, NAMPT, TREM2) (Fig. S7b, Table S8)." |
| [[GRID2]] | biolink:positively_correlated_with | [[MAPT]] |  | "Immunofluorescent triple labelling for GRID2, IBA1 and tau on enthorinal allocortex and temporal isocortex of 8 CTR and 12 AD donors showed that GRID2 cells were abundant in AD samples with increasing amounts of tau pathology and localized to regions with tau pathology (Fig. 4f, S8c–f)." |
| [[ITGAX]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| [[GPNMB]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| FLT1 (HGNC:3763) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| COLEC12 (HGNC:16016) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| MSR1 (HGNC:7376) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| AXL (HGNC:905) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| [[SPP1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| LPL (HGNC:6677) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| [[PPARG]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicates that AD1-microglia were associated with ‘cell migration’ (ITGAX, GPNMB and FLT1), ‘phagocytosis’ (COLEC12, MSR1, AXL) and ‘lipid localization’ (SPP1, LPL, PPARG)." |
| CACNA1A (HGNC:1388) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, the GO term ‘cellular response to amyloid-beta’ was significantly enriched in subclusters 9 and 10, in line with our finding that AD1 microglia abundance is associated with amyloid-β load (CACNA1A, NAMPT, TREM2) (Fig. S7b, Table S8)." |
| [[NAMPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, the GO term ‘cellular response to amyloid-beta’ was significantly enriched in subclusters 9 and 10, in line with our finding that AD1 microglia abundance is associated with amyloid-β load (CACNA1A, NAMPT, TREM2) (Fig. S7b, Table S8)." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, the GO term ‘cellular response to amyloid-beta’ was significantly enriched in subclusters 9 and 10, in line with our finding that AD1 microglia abundance is associated with amyloid-β load (CACNA1A, NAMPT, TREM2) (Fig. S7b, Table S8)." |
| [[GRID2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "GRID2 expressing cells had a microglia-like morphology, and were abundantly present in AD samples with tau pathology but rarely identified in CTR and AD samples without tau pathology (Fig. 4e, Fig S8a and b)." |
| ADGRB3 (HGNC:945) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicated that AD2 microglia possibly have neurotrophic functions, such as ‘synapse organization’ (GRID2, ADGRB3, GPM6A) and ‘axonogenesis’ (UNC5C, SLIT2, NRXN1) (Fig. S7d, Table S8)." |
| GPM6A (HGNC:4460) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicated that AD2 microglia possibly have neurotrophic functions, such as ‘synapse organization’ (GRID2, ADGRB3, GPM6A) and ‘axonogenesis’ (UNC5C, SLIT2, NRXN1) (Fig. S7d, Table S8)." |
| UNC5C (HGNC:12569) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicated that AD2 microglia possibly have neurotrophic functions, such as ‘synapse organization’ (GRID2, ADGRB3, GPM6A) and ‘axonogenesis’ (UNC5C, SLIT2, NRXN1) (Fig. S7d, Table S8)." |
| SLIT2 (HGNC:11086) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicated that AD2 microglia possibly have neurotrophic functions, such as ‘synapse organization’ (GRID2, ADGRB3, GPM6A) and ‘axonogenesis’ (UNC5C, SLIT2, NRXN1) (Fig. S7d, Table S8)." |
| NRXN1 (HGNC:8008) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Gene ontology analysis indicated that AD2 microglia possibly have neurotrophic functions, such as ‘synapse organization’ (GRID2, ADGRB3, GPM6A) and ‘axonogenesis’ (UNC5C, SLIT2, NRXN1) (Fig. S7d, Table S8)." |
| [[GRID2]] | biolink:associated_with | Neuritic plaques (HP:0100256; MESH:D058225) |  | "Also, GRID2pos microglia were often observed in (neuritic) plaque-like structures, indicating that this microglial subtype was associated with tau pathology (Figure S8b, g and h)." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In our AD1-microglia trajectory, TREM2 expression was detected prior to APOE (Figs. 3e and 4c), suggesting a similar response to amyloid-β." |
| [[CD163]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Indeed, in our AD1-microglia trajectory, CD163 is significantly differentially expressed and exclusively enriched in nuclei at the end of the AD1-trajectory (Fig. 3d, Table S3, S5, S6)." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[MAPT]] |  | "This finding is in line with a recent mouse study of Sierksma et al. (2020), where it was shown that the genetic risk of AD is functionally associated with the microglia response to amyloid-β pathology and not to phospho-tau pathology, suggesting that amyloid-β pathology is upstream of tau pathology." |
| [[APOE]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "In our AD1-microglia trajectory, TREM2 expression was detected prior to APOE (Figs. 3e and 4c), suggesting a similar response to amyloid-β." |
| [[CD163]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Recently, Nguyen et al. (2020) showed that CD163 is nearly exclusively present in amyloid-associated microglia." |
| [[Amyloid-beta]] (MESH:D016229) | NOT biolink:correlated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The AD2-microglia phenotype could be of great interest for future studies, as the degree of tau pathology correlates with the degree of dementia in AD donors, whereas the degree of amyloid-β does not." |
| [[MAPT]] | biolink:positively_correlated_with | Dementia (MONDO:0001627; MESH:D003704) |  | "The AD2-microglia phenotype could be of great interest for future studies, as the degree of tau pathology correlates with the degree of dementia in AD donors, whereas the degree of amyloid-β does not." |
| [[TREM2]] | biolink:associated_with | [[APOE]] |  | "In our AD1-microglia trajectory, TREM2 expression was detected prior to APOE (Figs. 3e and 4c), suggesting a similar response to amyloid-β." |
| [[GRID2]] | biolink:directly_physically_interacts_with | glutamate (CHEBI:16015; MESH:D018698) |  | "GRID2 is a glutamate receptor, in the cerebellum also expressed by Purkinje neurons." |
