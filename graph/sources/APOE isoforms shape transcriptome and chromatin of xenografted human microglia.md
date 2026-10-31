---
type: source
title: "APOE isoforms shape transcriptome and chromatin of xenografted human microglia"
paper_title: "The APOE isoforms differentially shape the transcriptomic and epigenomic landscapes of human microglia xenografted into a mouse model of Alzheimer’s disease"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000333
pmid: "40419479"
pmcid: "PMC12106835"
doi: "10.1038/s41467-025-60099-4"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC12106835/"
sources: ["[[.raw/01M4DY94PVC62SZH6CQR4CCEKY/normalized.md]]"]
tags: [microglia, transcriptomics, epigenomics, apoe-isoforms]
---

# APOE isoforms shape transcriptome and chromatin of xenografted human microglia

Human iPSC-derived microglia carrying a single APOE2, APOE3, APOE4 or no APOE allele were transplanted into the brains of [[AppNL-G-F mouse|AppNL-G-F]] amyloid mice and profiled at 12 months by RNA-seq and [[ATAC-seq]], to ask how the [[APOE]] isoform changes gene regulation in microglia responding to amyloid beta, independently of APOE made by mouse cells or by astrocytes.

## Design

- Model: [[Human microglia xenotransplantation model]]. Isogenic lines from the male BIONi010-C background (APOE e2/KO, e3/KO, e4/KO and KO/KO, from the European Bank for induced pluripotent Stem Cells) were differentiated by the MIGRATE protocol, and 500,000 precursors were injected bilaterally into postnatal day 4 pups of Rag2-/- Il2rg-/- hCSF1 knock-in AppNL-G-F mice after endogenous microglia were depleted with the CSF1R inhibitor BLZ945. Only male mice were used. Human microglia were sorted by FACS (CD11b and human CD45 positive) at 12 months.
- Sample sizes after quality control: ATAC-seq 16 mice (APOE2 5, APOE3 5, APOE4 4, APOE-KO 2) and RNA-seq 17 mice (APOE2 5, APOE3 4, APOE4 5, APOE-KO 3). Two knockout animals still expressed APOE and were excluded; only 3 of 5 knockout samples were kept.
- Analysis: DESeq2 for differential expression and differential accessibility with APOE3 as baseline plus a direct APOE4 versus APOE2 contrast (FDR < 0.05); rank-rank hypergeometric overlap against the knockout; [[Genome-wide association study]] enrichment by MAGMA gene set analysis (three Alzheimer GWAS) and stratified LD score regression; hypergeometric enrichment against the eight amyloid-responsive microglial states from single-cell sequencing of the same model; [[Weighted gene co-expression network analysis]] with GO enrichment; HOMER de novo motif analysis of the top 100 peaks.
- Validation: a separate in vitro [[Phagocytosis]] assay in iPSC-derived microglia of the same four genotypes using pHrodo E. coli particles and fluorescent human myelin (7 wells per genotype, one-way ANOVA with Bonferroni correction).

## Findings

- Versus APOE3, APOE2 microglia had 470 differentially expressed genes (282 up, 188 down) and APOE4 had 332 (170 up, 158 down); APOE4 versus APOE2 gave 1639 (751 up, 888 down). The knockout versus APOE3 gave 332 (126 up, 206 down). Differential accessibility was smaller: 40 regions for APOE2, 50 for APOE4, 72 for APOE4 versus APOE2, and 22 for the knockout. APOE expression itself was lower in APOE4 than in APOE2 or APOE3 microglia.
- Expression changes in APOE2 and APOE4 each overlapped the knockout signature (Spearman rho 0.55 and 0.34), most strongly for genes lowered in both, so part of each isoform effect looks like loss of APOE function; unique changes remained for each.
- Genes lowered in APOE4 and in the knockout, but not those in APOE2, were enriched for Alzheimer GWAS risk variants in one of three GWAS, which the authors read as support for a loss-of-function mechanism of APOE4. Open chromatin of the xenografted microglia was enriched for Alzheimer heritability but not for amyotrophic lateral sclerosis or autism heritability.
- [[CHCHD2]], a mitochondrial gene tied to cell migration and [[Parkinson disease]], was sharply lower in APOE4 and knockout microglia in both expression and promoter accessibility. [[ZNF248]] was higher in APOE4 and knockout microglia in both assays, and the authors note its opposite behaviour in TREM2 knockout versus R47H mutant microglia of another study ([[TREM2]]). [[TSPAN13]], linked to lipid accumulation in microglia, was higher in APOE4 and knockout.
- Genes lowered in APOE4 microglia were enriched in the HLA, ribosomal and disease-associated microglia states, and within the disease-associated state in negative regulation of TNF production. Cytokine genes [[CCL3]], [[CCL3L1]] and [[CCL4L2]] were higher in APOE4, while [[CXCL16]] was higher in APOE2. Regions more open in APOE4 than APOE2 were enriched for the motif of [[STAT2]], an interferon-signalling factor. The authors read this as a failure of APOE4 microglia to enter protective states and a shift towards a cytokine response.
- Opposite to a mouse study that saw more TNF-alpha in APOE4 microglia, TNF-family genes including [[TNFRSF25]] and [[TNFRSF21]] were higher in APOE2 (nine TNF-family genes versus APOE4); the authors say the pro- or anti-inflammatory meaning is context dependent and unresolved. See [[TNF]].
- Two co-expression modules were higher in APOE2: one for proliferation and [[Cell migration]] (higher than in APOE3 and APOE4) and one for immune responses, including complement activation and antibody-mediated immunity (higher than in APOE4). APOE2-up genes were over-represented among genes of phagocytic plaque-associated microglia, and in vitro APOE2 microglia took up more E. coli particles than every other genotype and a larger share took up myelin than APOE4 microglia; knockout microglia held very large amounts of intracellular myelin, which the authors take to suggest failed digestion.
- Regions more open in APOE2 microglia were enriched for the [[VDR]] motif, and VDR target genes from monocytes were over-represented among genes higher in APOE2; [[IL10RA]] was also higher in APOE2. The authors propose that APOE2 microglia are primed to respond to [[Vitamin D]] and its anti-inflammatory IL-10 route, and call VDR a candidate therapeutic handle.
- Expression and accessibility changes were broadly concordant at promoters across all contrasts.

## Why This Source Matters

It separates microglia-autonomous effects of the three human APOE isoforms from those of astrocytic or mouse APOE, in cells under real amyloid load, and shows with two independent genome-wide assays that APOE2 and APOE4 differ most in migration, phagocytosis, cytokine and interferon programmes. It adds a regulatory layer (open chromatin, a VDR motif) to what iPSC work on [[APOE p.R136S]] and brain RNA-seq by genotype had shown, and gives a concrete, testable route (vitamin D-VDR-IL-10) for the protective APOE2 phenotype.

## Assessment

- Group sizes are small (2 to 5 mice per genotype) and the knockout group is the weakest: only two animals went into ATAC-seq after exclusions. All mice were male and all cells came from one donor background, so isoform effects cannot be separated from clonal variation, and each microglial genotype carries only one APOE allele (e2/KO and so on).
- The study profiles one time point (12 months, extensive amyloid), so effects present before amyloid are invisible, as the authors state. Sorted bulk microglia average over plaque-associated and non-associated states.
- Differentially accessible regions were linked to genes by proximity only, and the VDR result rests on motif enrichment plus overlap with a monocyte target-gene list; VDR binding, vitamin D responsiveness and IL-10 signalling were not tested experimentally.
- The in vitro phagocytosis assay used cells without amyloid; the figure legend contains a mislabelled comparison ("E4 vs E4"), and the discussion cites Supplementary Data 1 for the TNF-family genes where the results cite Supplementary Data 2.
- The Alzheimer-heritability enrichment among APOE4-down genes was significant in only one of three GWAS.
- The mouse is immunodeficient (needed to avoid rejection), which the authors note may alter the microglial response.

## Open Questions

- Does vitamin D or a VDR agonist move APOE4 microglia towards the APOE2 expression state (the VDR link rests on motif enrichment and a monocyte target list, with no treatment experiment)?
- Does VDR actually occupy the APOE2-specific open chromatin regions in microglia (inferred from motif analysis only, not ChIP or CUT&RUN)?
- Are the isoform differences in migration and cytokine programmes already present before amyloid pathology (only 12-month AppNL-G-F brains were profiled)?
- Do the CHCHD2 and ZNF248 changes in APOE4 microglia have a functional effect on migration or lipid handling (reported as expression and accessibility changes only)?

## Connections

- Gene and isoforms: [[APOE]]; protective-variant microglia studied in iPSC co-culture: [[APOE Christchurch microglia protect neurons from Tau in iPSC models]]; related blood and brain RNA-seq by genotype: [[Blood and brain transcriptome of Alzheimer disease by APOE genotype]]
- Disease and microglia biology: [[Alzheimer disease]], [[Late-onset Alzheimer disease]], [[Neuroinflammation]], [[Phagocytosis]], [[Cell migration]]
- Genes: [[CHCHD2]], [[ZNF248]], [[TSPAN13]], [[VDR]], [[IL10RA]], [[STAT2]], [[CXCL16]], [[CCL3]], [[CCL3L1]], [[CCL4L2]], [[TNFRSF25]], [[TNFRSF21]], [[TREM2]], [[TNF]]; chemical: [[Vitamin D]]
- Methods and models: [[Human microglia xenotransplantation model]], [[ATAC-seq]], [[Weighted gene co-expression network analysis]], [[Genome-wide association study]], [[iPSC neuron-microglia co-culture and neuroimmune organoid models]], [[AppNL-G-F mouse]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "APOE is the strongest risk gene for late onset Alzheimer’s disease and its expression is upregulated in microglia in response to amyloid beta." |
| amyloid beta (CHEBI:64645; MESH:D016229) | biolink:affects | [[APOE]] | direction=increased | "APOE is the strongest risk gene for late onset Alzheimer’s disease and its expression is upregulated in microglia in response to amyloid beta." |
| [[APOE]] | biolink:associated_with | [[VDR]] |  | "Our results indicate that impaired microglial proliferation, migration and immune responses may contribute to the increased risk for late-onset AD in APOE4 carriers, while increased phagocytic capabilities and DNA-binding of the vitamin D receptor in APOE2 microglia may contribute to the isoform’s protective role." |
| [[APOE]] | biolink:affects | cholesterol (CHEBI:16113; MESH:D002784) |  | "APOE is involved in regulating cholesterol and other lipid transport across cells." |
| [[APOE]] | biolink:associated_with | [[MAPT]] |  | "Furthermore, APOE4 microglia are linked to dysregulated lipid metabolism, followed by tau phosphorylation." |
| [[APOE]] | biolink:affects | TGFB1 (HGNC:11766) | direction=increased | "Regarding immune responses, APOE4 microglia induce the signalling of transforming growth factor-β (TGF-β), a multifunctional cytokine." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | late-onset (HP:0003584) |  | "In this context, the major transcriptional response of microglia is the upregulation of APOE, the strongest late-onset AD risk gene." |
| amyloid beta (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Supporting this is the continued characterisation of different microglial phenotypes in AD, including those responsive to amyloid beta (Aβ) aggregates, a pathological hallmark of AD." |
| APOE2 (variant) | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In AD, APOE2 is thought to be protective, while APOE4 increases disease risk up to 12-fold in homozygous individuals of certain human populations." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In AD, APOE2 is thought to be protective, while APOE4 increases disease risk up to 12-fold in homozygous individuals of certain human populations." |
| [[AppNL-G-F mouse]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We use RNA- and ATAC-sequencing to profile gene expression and chromatin accessibility of human microglia xenotransplantated into the brains of male APPNL-G-F mice." |
| [[VDR]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our results indicate that impaired microglial proliferation, migration and immune responses may contribute to the increased risk for late-onset AD in APOE4 carriers, while increased phagocytic capabilities and DNA-binding of the vitamin D receptor in APOE2 microglia may contribute to the isoform’s protective role." |
| H3K27ac (CHEBI:85044) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "H3K27ac is dysregulated in the brains of individuals with AD, and microglial H3K27ac regions are strongly enriched for AD genetic risk." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | late-onset (HP:0003584) |  | "Our results indicate that impaired microglial proliferation, migration and immune responses may contribute to the increased risk for late-onset AD in APOE4 carriers, while increased phagocytic capabilities and DNA-binding of the vitamin D receptor in APOE2 microglia may contribute to the isoform’s protective role." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In support of the opposing roles of APOE2 and APOE4 in AD risk, the greatest differences were observed between these isoforms." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We transplanted iPSC-derived human microglia APOE2/0, APOE3/0, APOE4/0 and an APOE knockout (APOE-KO) into the brains of the AppNL-G-F mouse model of Alzheimer’s disease." |
| [[APP]] | biolink:affects | amyloid beta (CHEBI:64645; MESH:D016229) | direction=increased | "At 12 months, by which point Aβ pathology is extensive, microglia were isolated by FACS using human microglia-specific antibodies (CD11b + hCD45+, Fig. 1a)." |
| ITGAM (HGNC:6149) | biolink:associated_with | PTPRC (HGNC:9666) |  | "At 12 months, by which point Aβ pathology is extensive, microglia were isolated by FACS using human microglia-specific antibodies (CD11b + hCD45+, Fig. 1a)." |
| [[APOE]] | biolink:affects | [[TSPAN13]] | direction=increased | "A few genes were only significant in either APOE2 or APOE4, including TSPAN13, which was upregulated in APOE4 microglia and is associated with lipid accumulation in microglia." |
| [[APOE]] | biolink:affects | [[CHCHD2]] | direction=decreased | "For instance, CHCHD2, a mitochondrial gene involved in promoting cellular migration and implicated in Parkinson’s disease (PD), was significantly downregulated in APOE4 microglia when compared to both APOE3 (logFC = –7.8, p = 1.3e−11; Figs. 2b, 3c, Supplementary Data 2) and APOE2 (logFC = –7.4, p = 7.8e−11; Figs. 2c, 3c, Supplementary Data 2)." |
| [[APOE]] | biolink:affects | [[ZNF248]] | direction=increased | "Similarly, the zinc finger protein ZNF248 was upregulated in APOE4 microglia (APOE4 vs APOE3, logFC = 9, p = 5.1e−14; APOE4 vs APOE2, logFC = 7.9, p = 5.2e−19; Supplementary Data 2) and genomic regions in the vicinity of this gene had increased chromatin accessibility (APOE4 vs APOE3, logFC = 6.3, p = 2.3e−5; APOE4 vs APOE2, logFC = 6.6, p = 3.2e−5; Supplementary Data 4)." |
| [[TREM2]] | biolink:affects | [[CHCHD2]] | direction=decreased | "Interestingly, in an in vitro study investigating functional and transcriptional phenotypes of a TREM2 mutant and knockout in iPSC-derived microglia-like cells, ZNF248 was upregulated in the TREM2-KO, while CHCHD2 expression was reduced in the R47H mutant." |
| [[CHCHD2]] | biolink:associated_with | [[Parkinson disease]] (MESH:D010300) |  | "For instance, CHCHD2, a mitochondrial gene involved in promoting cellular migration and implicated in Parkinson’s disease (PD), was significantly downregulated in APOE4 microglia when compared to both APOE3 (logFC = –7.8, p = 1.3e−11; Figs. 2b, 3c, Supplementary Data 2) and APOE2 (logFC = –7.4, p = 7.8e−11; Figs. 2c, 3c, Supplementary Data 2)." |
| [[TREM2]] | biolink:affects | [[ZNF248]] | direction=increased | "Interestingly, in an in vitro study investigating functional and transcriptional phenotypes of a TREM2 mutant and knockout in iPSC-derived microglia-like cells, ZNF248 was upregulated in the TREM2-KO, while CHCHD2 expression was reduced in the R47H mutant." |
| [[APOE]] | biolink:affects | [[CCL3]] | direction=increased | "Since negative regulation of cytokine production refers to processes that inhibit cytokine production, the downregulation of these genes in APOE4 microglia suggests increased cytokine production in this isoform, which was confirmed in the gene expression data (Fig. 4c–f)." |
| [[APOE]] | biolink:affects | [[CCL3L1]] | direction=increased | "Since negative regulation of cytokine production refers to processes that inhibit cytokine production, the downregulation of these genes in APOE4 microglia suggests increased cytokine production in this isoform, which was confirmed in the gene expression data (Fig. 4c–f)." |
| [[APOE]] | biolink:affects | [[CCL4L2]] | direction=increased | "Since negative regulation of cytokine production refers to processes that inhibit cytokine production, the downregulation of these genes in APOE4 microglia suggests increased cytokine production in this isoform, which was confirmed in the gene expression data (Fig. 4c–f)." |
| [[APOE]] | biolink:affects | [[CXCL16]] | direction=increased | "Since negative regulation of cytokine production refers to processes that inhibit cytokine production, the downregulation of these genes in APOE4 microglia suggests increased cytokine production in this isoform, which was confirmed in the gene expression data (Fig. 4c–f)." |
| [[APOE]] | biolink:affects | [[TNF]] | direction=increased | "Conversely, where the authors found increased TNFα in APOE4 microglia, TNF family members, including TNFRSF25 and TNFRSF21, were upregulated in APOE2 microglia in our study." |
| [[APOE]] | biolink:affects | [[TNFRSF25]] | direction=increased | "Conversely, where the authors found increased TNFα in APOE4 microglia, TNF family members, including TNFRSF25 and TNFRSF21, were upregulated in APOE2 microglia in our study." |
| [[APOE]] | biolink:affects | [[TNFRSF21]] | direction=increased | "Conversely, where the authors found increased TNFα in APOE4 microglia, TNF family members, including TNFRSF25 and TNFRSF21, were upregulated in APOE2 microglia in our study." |
| [[APOE]] | biolink:associated_with | amyloid beta (CHEBI:64645; MESH:D016229) |  | "Such pathways are likely important for microglia being recruited towards the site of Aβ pathology and initiating its clearance, which in some cases, requires APOE." |
| [[APOE]] | biolink:associated_with | amyloid beta (CHEBI:64645; MESH:D016229) |  | "Mancuso and colleagues showed that in response to Aβ, APOE4 microglia shift to the CRM state rather than HLA." |
| [[APOE]] | biolink:associated_with | [[IL10RA]] |  | "Boxplot of gene expression profiles of IL-10RA." |
| [[APOE]] | biolink:associated_with | myelin (MESH:D009185) |  | "We also observed that APOE-KO microglia displayed very high amounts of intracellular myelin." |
| [[APOE]] | biolink:associated_with | demyelination (HP:0011096; MESH:D003711) |  | "This could indicate an impairment to digest the phagocytosed material, and is in line with previous studies showing lipid accumulation in ApoE−/− mouse microglia in models of demyelination." |
| APOE2 (variant) | biolink:associated_with | myelin (MESH:D009185) |  | "Additionally, a significantly higher proportion of APOE2-expressing microglia successfully took up myelin compared to APOE4-expressing microglia (Fig. 6d, e), as reported previously." |
| APOE2 (variant) | biolink:associated_with | amyloid plaques (MESH:D058225) |  | "Barplot showing the overrepresentation of genes upregulated in APOE2 microglia in differentially expressed genes (DEGs) in phagocytic microglia responsive to Aβ plaques." |
| [[VDR]] | biolink:associated_with | IL10 (HGNC:5962) |  | "Illustration showing a mechanism of anti-inflammatory microglia activation mediated through vitamin D and IL-10 signalling." |
| [[APOE]] | biolink:affects | [[VDR]] | direction=increased | "This confirms the expected downstream transcriptional response predicted by increased VDR binding in APOE2 microglia." |
| [[APOE]] | biolink:affects | [[IL10RA]] | direction=increased | "Consistent with this, in our data, the alpha subunit of the IL-10 receptor (IL-10RA) was significantly upregulated in APOE2 microglia (Fig. 7d)." |
| [[APOE]] | biolink:associated_with | [[STAT2]] |  | "Aside from the VDR enrichment, regions with increased chromatin accessibility in APOE4-expressing microglia when compared to APOE2 were enriched for STAT2, a TF involved in interferon response signalling." |
| [[APOE]] | biolink:associated_with | [[TREM2]] |  | "Although the authors argue that it is unlikely that such a limited number of genes, including ZNF248, could explain such vast phenotypic differences, the overlap between APOE4 microglia and TREM2 knockout microglia is interesting." |
| [[VDR]] | biolink:directly_physically_interacts_with | DNA (CHEBI:16991; MESH:D004247) |  | "Regions with increased accessibility in the APOE2 microglia were strongly enriched for the DNA binding motif of the vitamin D receptor (VDR; Fig. 7a), a ligand-inducible transcription factor (TF) and main mediator of vitamin D signalling." |
| IL10 (HGNC:5962) | biolink:directly_physically_interacts_with | [[IL10RA]] |  | "Consistent with this, in our data, the alpha subunit of the IL-10 receptor (IL-10RA) was significantly upregulated in APOE2 microglia (Fig. 7d)." |
| [[STAT2]] | biolink:physically_interacts_with | DNA (CHEBI:16991; MESH:D004247) |  | "Aside from the VDR enrichment, regions with increased chromatin accessibility in APOE4-expressing microglia when compared to APOE2 were enriched for STAT2, a TF involved in interferon response signalling." |
| [[ZNF248]] | biolink:associated_with | [[TREM2]] |  | "ZNF248 was one of only four differentially expressed genes with reduced expression in the knockout but increased expression in the mutant." |
| [[APOE]] | biolink:associated_with | ATP (CHEBI:15422; MESH:D000255) |  | "This is supported in previous studies which have shown that migration is decreased in APOE4 microglia-like cells, APOE4 microglia have reduced motility and responsiveness to ATP, a chemotactic cue of neuronal damage, and amyloid beta." |
| [[APOE]] | biolink:associated_with | demyelination (HP:0011096; MESH:D003711) |  | "Previously, APOE4 microglia were shown to downregulate their expression of cellular migration genes in response to demyelination, and pericytes derived from APOE4 carriers exhibited downregulation of genes associated with cellular migration." |
| APOE2 (variant) | biolink:affects | amyloid beta (CHEBI:64645; MESH:D016229) | direction=decreased | "This observation is in agreement with previous studies which report a lower accumulation of myelin debris in APOE2-TR mice, and increased clearance of Aβ from the interstitial fluid of mice expressing the APOE2 isoform" |
| amyloid beta (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[TNF]] |  | "For instance, in APOE2 microglia the upregulation of TNF family genes may be triggered by their migration towards and interaction with Aβ plaques." |
| [[CXCL16]] | biolink:associated_with | brain tumour (MONDO:0021211) |  | "However, this chemokine has been reported to drive microglia to an anti-inflammatory phenotype in brain tumours." |
| [[APOE]] | biolink:negatively_correlated_with | low levels of vitamin D (HP:0100512) |  | "It’s important to take into consideration APOE genotype, as some studies have shown that APOE4 carriers have higher vitamin D levels and therefore vitamin D supplementation may be more beneficial to non-carriers." |
| [[VDR]] | biolink:regulates | IL10 (HGNC:5962) | direction=increased | "Vitamin D, via the VDR, increases the expression of the anti-inflammatory cytokine IL-10." |
| IL10 (HGNC:5962) | biolink:regulates | SOCS3 (HGNC:19391) | direction=increased | "IL-10 then activates SOCS3 via the IL-10 receptor, and this mechanism suppresses the expression of pro-inflammatory cytokines." |
