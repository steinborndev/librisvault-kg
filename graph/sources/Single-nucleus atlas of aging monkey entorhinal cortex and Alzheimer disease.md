---
type: source
title: "Single-nucleus atlas of aging monkey entorhinal cortex and Alzheimer disease"
paper_title: "Single‐cell analysis reveals transcriptomic reprogramming in aging primate entorhinal cortex and the relevance with Alzheimer's disease"
domain: neuroscience
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001198
pmid: "36165462"
pmcid: "PMC9649611"
doi: "10.1111/acel.13723"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9649611/"
sources: ["[[.raw/01M4P89V9D1G160AKHZ5N6FM4Z/normalized.md]]"]
tags: [aging, primate, single-cell, selective-vulnerability, transcriptomics]
---

# Single-nucleus atlas of aging monkey entorhinal cortex and Alzheimer disease

The entorhinal cortex is among the first cortical areas to lose neurons and to collect amyloid and tangles in [[Alzheimer disease]], yet it is much less studied than hippocampus or prefrontal cortex. This study profiles it by [[Single-nucleus RNA sequencing]] in young and aged cynomolgus monkeys (Macaca fascicularis), maps what changes with age in each cell type, and then overlays human Alzheimer datasets to ask which cells look most disease-prone. The brain region is described on [[Entorhinal cortex]].

## Design

- Entorhinal cortex from young (7 to 8 years) and aged (16 to 18 years) monkeys supplied by a commercial animal-tissue company; animals reported free of disease history and dead of natural causes. The number of animals per group is not stated in the text read (a supplementary table is cited).
- Aged tissue showed more senescence-associated beta-galactosidase staining (see [[Cellular senescence]]), more deposits stained with the pan-Aβ antibody 4G8 and lower neuronal density.
- Nuclei were isolated, sequenced on Illumina HiSeq X10 and mapped to the Macaca fascicularis 6.0 genome. After filtering (200 to 4000 genes, mitochondrial fraction at most 1.5%) 76,839 nuclei remained; Harmony corrected batch and Seurat 4.0 clustered them into 32 clusters merged into seven cell types.
- Age-related differential expression per cell type by Wilcoxon test (adjusted p below 0.05, absolute log fold change above 0.25); proportion changes by Dirichlet-multinomial regression; regulators by pySCENIC ([[SCENIC regulon analysis]]); ligand-receptor communication by CellPhoneDB; disease gene-set scores from the Aging Atlas resource.
- Human comparisons used published entorhinal snRNA-seq of Alzheimer brain (for Alzheimer differentially expressed genes), bulk transcriptomes of Alzheimer and non-Alzheimer entorhinal cortex, and published laser-capture proteomics of proteins co-localised with plaques (270) and tangles (543). Subpopulations were found with [[Scissor phenotype-guided subpopulation analysis]].
- Raw sequencing data are deposited in the Genome Sequence Archive under CRA006617.

## Findings

- **Cell types.** Excitatory neurons 48,687, inhibitory neurons 15,178, oligodendrocytes 5,859, oligodendrocyte precursor cells 2,283, astrocytes 2,066, microglia 2,047 and endothelial cells 719. No cell-type proportion differed significantly between young and aged animals.
- **Neurons are most affected.** The neuronal lineage had the most age-related differentially expressed genes, and aging-gene scores rose in several cell types, most in neurons. Synapse signalling pathways fell in every cell type. Aged excitatory neurons raised endoplasmic-reticulum protein folding and chemical homeostasis genes, oligodendrocytes and precursors raised neuronal projection organisation, and microglia raised inflammation pathways.
- **Individual genes.** An olfactomedin gene (written OLFM in the text) was the top upregulated gene in excitatory neurons, [[APOE]] rose in astrocytes and [[B2M]] in microglia.
- **Regulators.** [[FOXN3]] was the leading regulon behind microglial age changes (targets in lipid metabolism and immune processes); ZMAT4, POU2F1, CLK2, [[TCF4]], MEF2A and SOX6 led the neuronal changes (targets in synaptic transmission and brain development). CREM and MEIS2 were regulators of neuronal lineage identity and FLI1 of microglia, in the young reference map.
- **Communication.** Cell-cell interactions were globally fewer in aged tissue; interactions present only in aged tissue fell in neuroactive ligand-receptor, leukocyte migration and cell adhesion categories. Age-related differentially expressed genes overlapped significantly with published monkey hippocampus data in all cell types.
- **Disease gene sets.** Alzheimer gene-set scores were higher in all aged cell types; Parkinson, learning-disorder and memory-disorder scores rose in neurons. Cell-type-restricted risk genes included [[APOD]] (learning disorder, oligodendrocyte precursors), [[MAP2]] ([[Parkinson disease]], oligodendrocytes) and [[NPY]] (Alzheimer and memory disorder, neurons and oligodendrocytes).
- **Overlap with human Alzheimer brain.** 166 genes were differentially expressed both with age here and in human Alzheimer entorhinal cortex, mostly in neurons; the upregulated shared genes related to synaptic signalling and the downregulated to neurogenesis.
- **APP and MAPT.** [[APP]] and [[MAPT]] were detected in all cell types, with more positive cells among neurons. The share of positive cells did not change with age but expression per cell rose in most types, as did the expression of proteins that co-localise with plaques and [[Neurofibrillary tangle]]s. The authors conclude that higher expression, not more expressing cells, is the likelier driver of deposition.
- **Alzheimer-prone excitatory neurons.** Of 31,617 aged excitatory neurons (9 clusters), Scissor flagged 1,370 as Alzheimer-associated, chiefly from clusters 4, 0 and 5. They had 196 up and 16 down genes versus other neurons, with synaptic signalling and ATP metabolism raised, and the signature scored higher in Alzheimer patients than controls in an independent dataset.

## Why This Source Matters

It gives a cell-type-resolved view of normal aging in a primate region that Alzheimer pathology reaches first, and ties it to human Alzheimer expression data. The finding that [[APP]] and [[MAPT]] rise per cell in aging, with no change in the number of expressing cells, and the flagged excitatory-neuron subpopulation, speak to [[Regional vulnerability to Alzheimer pathology]] at the level of cell subtypes.

## Assessment

- Disease links are inferential: Alzheimer relevance rests on overlap with human gene lists and a bulk-guided algorithm, with no pathology measured in the same animals beyond Aβ staining, and the monkeys do not have Alzheimer disease.
- Animal number, sex and post-mortem interval are not given in the text; a small number of animals would limit the age contrast.
- Gene-set scores come from a curated resource and human-derived regulon references (hg19) were applied to macaque data.
- Nuclei carry mostly nuclear transcripts, which may under-read some immune and cytoplasmic signals.
- Scissor calls depend on the bulk dataset and the alpha of 0.01; the Alzheimer-associated neurons were not validated in tissue.

## Open Questions

- Which excitatory neuron type (layer, projection class) do the Scissor-flagged cells in clusters 4, 0 and 5 correspond to (not resolved in the text read; marker heatmap only in a figure)?
- Does the per-cell rise of APP and MAPT expression with age occur in human entorhinal cortex from cognitively normal elderly donors (shown here only in monkey)?
- Which olfactomedin gene is the top upregulated gene in aged excitatory neurons (written only as OLFM in the text)?
- Is the neuron-specific loss of synapse signalling genes in aged entorhinal cortex matched by synapse loss at protein level (only transcripts were measured)?

## Connections

- Method: [[Single-nucleus RNA sequencing]], [[SCENIC regulon analysis]], [[Scissor phenotype-guided subpopulation analysis]]
- Brain region: [[Entorhinal cortex]], [[Regional vulnerability to Alzheimer pathology]]
- Genes: [[APP]], [[MAPT]], [[APOE]], [[B2M]], [[FOXN3]], [[TCF4]], [[NPY]], [[APOD]], [[MAP2]]
- Diseases and processes: [[Alzheimer disease]], [[Parkinson disease]], [[Cellular senescence]], [[Neurofibrillary tangle]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[Alzheimer disease]] (MESH:D000544) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "In addition, entorhinal cortex is among the first cortical fields to accumulate formation of β‐amyloid (Aβ) and neurofibrillary tangles (NFTs) in AD brains (Huijbers et al., ; Knopman et al., )." |
| [[APP]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "The expression levels of APP and MAPT, which generate β‐amyloid (Aβ) and neurofibrillary tangles, respectively, were increased in most aged entorhinal cortex cell types." |
| [[MAPT]] | biolink:contributes_to | neurofibrillary tangles (HP:0002185) |  | "The expression levels of APP and MAPT, which generate β‐amyloid (Aβ) and neurofibrillary tangles, respectively, were increased in most aged entorhinal cortex cell types." |
| CREM (HGNC:2352) | biolink:associated_with | neurodegeneration (HP:0002180) |  | "For example, the regulons of CREM and MEIS2, which are involved in cell differentiation and neurodegeneration (Mantamadiotis et al., ), were crucial regulators for neuronal lineage differentiation (ExN/InN) (Figure 1f, Table S3)." |
| MEIS2 (HGNC:7001) | biolink:associated_with | neurodegeneration (HP:0002180) |  | "For example, the regulons of CREM and MEIS2, which are involved in cell differentiation and neurodegeneration (Mantamadiotis et al., ), were crucial regulators for neuronal lineage differentiation (ExN/InN) (Figure 1f, Table S3)." |
| FLI1 (HGNC:3749) | biolink:associated_with | inflammation (HP:0012647; MESH:D007249) |  | "The regulons of FLI1, which regulate inflammation‐associated genes (B. Chen et al., ), were identified as upstream regulators of microglia (Figure 1f, Table S3)." |
| [[APOE]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "APOE, which plays a role in lipid metabolism, Aβ aggregation, and tau damage (Yin & Wang, ), was up‐regulated in the astrocytes." |
| [[APOE]] | biolink:affects | [[MAPT]] |  | "APOE, which plays a role in lipid metabolism, Aβ aggregation, and tau damage (Yin & Wang, ), was up‐regulated in the astrocytes." |
| [[B2M]] | biolink:positively_correlated_with | inflammation (HP:0012647; MESH:D007249) |  | "B2M, which is a component of the MHC‐I molecule and accumulates during inflammation (Batista Muñoz et al., ), was up‐regulated in the microglia, thus suggesting elevated inflammation in the aged entorhinal cortex." |
| [[APP]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Several APP cleavage products are considered as potential contributors to AD, leading to neuronal dysfunction" |
| [[APP]] | biolink:contributes_to | senile plaques (HP:0100256; MESH:D058225) |  | "Thus, the elevated expression of APP and MAPT, rather than the number of positive cells expressing APP and MAPT, was likely the major cause of Aβ deposition and NFT formation in the aged entorhinal cortex." |
| [[MAPT]] | biolink:associated_with | tauopathy (MONDO:0005574; MESH:D024801) |  | "Hyperphosphorylated tau protein participates in the formation of NFTs, which characterize many neurodegenerative disorders, termed tauopathies" |
| [[MAPT]] | biolink:associated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Hyperphosphorylated tau protein participates in the formation of NFTs, which characterize many neurodegenerative disorders, termed tauopathies" |
| [[APOD]] | biolink:associated_with_increased_likelihood_of | [[Dementia with Lewy bodies]] (MESH:D020961) |  | "Notably, APOD, a specific risk gene of LD, showed dysregulated expression in OPCs, while MAP2, a specific risk gene for PD, showed dysregulated expression in oligodendrocytes." |
| [[MAP2]] | biolink:associated_with_increased_likelihood_of | [[Parkinson disease]] (MESH:D010300) |  | "Notably, APOD, a specific risk gene of LD, showed dysregulated expression in OPCs, while MAP2, a specific risk gene for PD, showed dysregulated expression in oligodendrocytes." |
| [[NPY]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "For example, NPY (co‐risk gene for AD and MD) showed abnormal expression in both neurons and oligodendrocytes." |
| [[NPY]] | biolink:associated_with_increased_likelihood_of | major depression (MONDO:0002009) |  | "For example, NPY (co‐risk gene for AD and MD) showed abnormal expression in both neurons and oligodendrocytes." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Several APP cleavage products are considered as potential contributors to AD, leading to neuronal dysfunction" |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | senile plaques (HP:0100256; MESH:D058225) |  | "Accumulated Aβ peptides are the main component of senile plaques and are derived from the proteolytic cleavage of the large glycoprotein amyloid precursor protein (APP)" |
| [[Amyloid-beta]] (MESH:D016229) | biolink:derives_from | glycoprotein (CHEBI:17089; MESH:D006023) |  | "Accumulated Aβ peptides are the main component of senile plaques and are derived from the proteolytic cleavage of the large glycoprotein amyloid precursor protein (APP)" |
| [[APP]] | biolink:associated_with | [[MAPT]] |  | "In our study, APP and MAPT gene expression levels, as well as their coexistence, were significantly increased in most cell types in the aged entorhinal cortex, which is likely an important inducement of early AD." |
| [[MAPT]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "In our study, APP and MAPT gene expression levels, as well as their coexistence, were significantly increased in most cell types in the aged entorhinal cortex, which is likely an important inducement of early AD." |
| adenosine triphosphate (CHEBI:15422; MESH:D000255) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, based on integration of bulk transcriptome data of AD, we identified ExNs subpopulations that are involved in synaptic signaling and ATP metabolic pathways are most highly associated with AD, which provide potential therapies for the diagnosis and treatment of AD." |
