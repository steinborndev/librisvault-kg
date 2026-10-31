---
type: source
title: "Blood and brain transcriptome of Alzheimer disease by APOE genotype"
paper_title: "Blood and brain transcriptome analysis reveals APOE genotype-mediated and immune-related pathways involved in Alzheimer disease"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000274
pmid: "35139885"
pmcid: "PMC8830081"
doi: "10.1186/s13195-022-00975-z"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8830081/"
sources: ["[[.raw/01M4DY94MFP1784WD3JA6XG21H/normalized.md]]"]
tags: [transcriptomics, blood-biomarker, cerebrovascular, neuroinflammation]
---

# Blood and brain transcriptome of Alzheimer disease by APOE genotype

A joint analysis of RNA sequencing from blood (112 neuropathologically confirmed [[Alzheimer disease]] cases, 67 controls) and prefrontal cortex (344 cases, 232 controls) in the Religious Orders Study and Rush Memory and Aging Project (ROSMAP), run in the total sample and within [[APOE]] genotype groups (ε2/ε3, ε3/ε3, ε3/ε4). Pathways and co-expression networks from the combined data were then tested against vascular injury proteins in a second brain cohort, to ask how the ε4 allele might act on the blood-brain barrier.

## Design

- Blood RNA-seq came from 614 ROSMAP participants in three sequencing batches; 179 had a neuropathological diagnosis (NIA-Reagan criteria, Braak and CERAD scores). Brain RNA-seq covered 576 samples with RNA integrity number and post-mortem interval; 140 people contributed both tissues.
- Differential expression used VOOM and LIMMA per tissue (blood stratified by batch, then meta-analysed with METAL); blood and brain Z-scores were merged with O'Brien's method (R package CUMP). Transcriptome-wide significance was P < 3.3 × 10^-6.
- [[Gene set enrichment analysis]] used MSigDB hallmark sets on the combined ranking per genotype group. [[Weighted gene co-expression network analysis]] found brain modules, tested their preservation in blood, and used Ingenuity Pathway Analysis to build subnetworks of Alzheimer-associated genes.
- Cell-type expression was read from a blood single-cell dataset (about 2400 cells, dendritic cells and monocytes only) and from prefrontal-cortex [[Single-nucleus RNA sequencing]] of 48 ROSMAP brains.
- Vascular injury proteins ([[ICAM1]], [[VCAM1]] and serum amyloid A) were measured by Meso Scale V-PLEX in dorsolateral prefrontal cortex lysate, and 107 top-ranked genes were tested against them in 208 Framingham Heart Study / Boston University brains (threshold P < 4.67 × 10^-4).

## Findings

- No gene reached transcriptome-wide significance in the total sample. Of 64 expressed genes from a large GWAS list, five were nominally significant in the combined data; [[INPP5D]] (up) and [[HLA-DQA1]] (down) were nominal in both blood and brain with the same direction, and [[BCKDK]], [[TSPOAP1]] and [[SIGLEC11]] passed correction in brain only.
- Within genotype groups, [[PIGHP1]] was upregulated in ε2/ε3 (combined blood and brain) and [[FRAS1]] downregulated in ε3/ε4 (blood only). [[C4A]], [[C4B]] and [[HSPA2]] were moderately raised in ε2/ε3 brain, not blood.
- Cell type: [[HLA-DQA1]] and [[INPP5D]] were most expressed in blood dendritic cells and monocytes; INPP5D was the only one of the group expressed in brain, specifically in microglia.
- Pathways: 21 hallmark pathways were significant in at least one genotype group; ten in ε3/ε4, six unique to it (apoptosis, estrogen response late, hypoxia, IL6/JAK/STAT3 signaling, inflammatory response, p53). Allograft rejection, interferon gamma response, peroxisome and TNFA signaling via NFKB were enriched for upregulated Alzheimer genes in ε3/ε4 and downregulated ones in ε2/ε3 and ε3/ε3, with almost no shared leading-edge genes ([[HLA-DRA]], CD74 and KYNU were the exceptions across pairs of groups).
- Of 92 leading-edge genes in those four pathways, 21 were associated with at least one vascular injury protein: 11 with serum amyloid A, 13 with VCAM-1, and only [[TRIP10]] and [[FOSL1]] with ICAM-1.
- Four brain networks were preserved in blood. The light green network had a higher eigengene in ε4 carriers (P = 4.7 × 10^-3) and was enriched for Alzheimer-associated genes; it contains [[NFKBIA]] (five of nine significant KEGG pathways), HLA-DRA, INPP5D and C4B. Within its 17-gene subnetwork, [[VASP]] and C4B were associated with the vascular injury proteins.
- Overall, 23 genes from pathways and networks were associated with at least one vascular injury trait.

## Why This Source Matters

It is a rare same-person comparison of blood and brain transcriptomes by APOE genotype, and it points to genes in innate immune and NF-κB signalling whose expression tracks markers of [[Blood-brain barrier dysfunction]] differently in ε4 carriers and non-carriers. This supports blood expression as a route to brain-relevant biology, though the blood groups are small.

## Assessment

- Blood genotype groups were small (ε3/ε4 analysed only in one sequencing batch) and the blood data had strong batch effects, handled by per-batch meta-analysis.
- RNA integrity was unavailable for blood; the blood single-cell reference covers only dendritic cells and monocytes.
- Vascular injury proteins were measured in brain homogenate from a different cohort than the expression used for discovery, and the links to barrier function rest on associations, not experiments.
- Co-expression modules are statistical; the authors check biological coherence with pathway subnetworks and call for experimental follow-up.

## Open Questions

- Do the ε4-specific pathway directions (up in ε3/ε4, down in non-carriers) replicate in a larger, independently sequenced blood cohort (ROSMAP ε3/ε4 blood was analysed from one batch only)?
- Does altered expression of VASP or C4B change blood-brain barrier integrity in an experimental model carrying APOE ε4 (only correlations with ICAM-1, VCAM-1 and serum amyloid A were tested)?
- Which blood cell types other than dendritic cells and monocytes carry the APOE-dependent signal (no single-cell reference was available for them)?

## Connections

- Genes: [[APOE]], [[INPP5D]], [[HLA-DQA1]], [[PIGHP1]], [[FRAS1]], [[C4B]], [[C4A]], [[HSPA2]], [[BCKDK]], [[TSPOAP1]], [[SIGLEC11]], [[VASP]], [[ICAM1]], [[VCAM1]], [[TRIP10]], [[FOSL1]], [[HLA-DRA]], [[NFKBIA]]
- Methods: [[Gene set enrichment analysis]], [[Weighted gene co-expression network analysis]], [[Single-nucleus RNA sequencing]]
- Concepts: [[Blood-brain barrier dysfunction]], [[Neuroinflammation]], [[Cerebral amyloid angiopathy]]
- Disease: [[Alzheimer disease]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Apolipoprotein E (APOE) genotype is the strongest genetic risk factor for late-onset AD and the ε4 allele has been recently associated with BBB dysfunction leading to cognitive decline." |
| [[APOE]] | biolink:associated_with | [[Cerebral amyloid angiopathy]] (MESH:D016657) |  | "Both ε2 and ε4 are significantly associated with the risk of CAA." |
| [[INPP5D]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We observed differentially expressed genes with P < 0.05 in both brain and blood for established AD genes INPP5D (upregulated) and HLA-DQA1 (downregulated)." |
| [[HLA-DQA1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We observed differentially expressed genes with P < 0.05 in both brain and blood for established AD genes INPP5D (upregulated) and HLA-DQA1 (downregulated)." |
| [[PIGHP1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PIGHP1 and FRAS1 were differentially expressed at the transcriptome-wide level (P < 3.3 × 10−6) within ε2/ε3 and ε3/ε4 groups, respectively." |
| [[FRAS1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PIGHP1 and FRAS1 were differentially expressed at the transcriptome-wide level (P < 3.3 × 10−6) within ε2/ε3 and ε3/ε4 groups, respectively." |
| [[IFNG]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Four pathways (allograft rejection, interferon gamma response, peroxisome, and TNFA signaling via NFKB) were enriched for AD upregulated genes in the ε3/ε4 group and AD downregulated genes in subjects lacking ε4." |
| TNF (HGNC:11892) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Four pathways (allograft rejection, interferon gamma response, peroxisome, and TNFA signaling via NFKB) were enriched for AD upregulated genes in the ε3/ε4 group and AD downregulated genes in subjects lacking ε4." |
| [[MAPT]] | biolink:correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "For example, plasma phosphorylated tau levels are highly correlated with neurodegenerative disorders and AD pathology." |
| [[MAPT]] | biolink:correlated_with | neurodegenerative disorder (MONDO:0005559; MESH:D019636) |  | "For example, plasma phosphorylated tau levels are highly correlated with neurodegenerative disorders and AD pathology." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Heterozygosity of the APOE ε4 allele confers a 3–4-fold increase of AD risk and ε4 homozygotes have a 10–12-fold increased likelihood of a clinical diagnosis of AD among persons of European ancestry." |
| APOE ε2 (variant) | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "By contrast, among clinically and neuropathologically confirmed AD cases and controls of European ancestry, a single copy of the APOE ε2 allele is associated with 0.61-fold decreased risk and ε2 homozygotes have an 0.87-fold reduced risk for AD compared to individuals with the ε3/ε3 genotype." |
| [[APOE]] | biolink:associated_with | [[Cerebral amyloid angiopathy]] (MESH:D016657) |  | "Both ε2 and ε4 are significantly associated with the risk of CAA." |
| APOE ε2 (variant) | biolink:associated_with | [[Cerebral amyloid angiopathy]] (MESH:D016657) |  | "Both ε2 and ε4 are significantly associated with the risk of CAA." |
| [[APOE]] | biolink:contributes_to | cognitive decline (HP:0001268; MESH:D060825) |  | "Apolipoprotein E (APOE) genotype is the strongest genetic risk factor for late-onset AD and the ε4 allele has been recently associated with BBB dysfunction leading to cognitive decline." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Previous whole transcriptome-wide studies from autopsied brains demonstrate that the classical complement cascade and tau phosphorylation are linked to AD in an APOE genotype-specific manner." |
| SPDYE3 (HGNC:35462) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The expression of five of these 64 genes (HLA-DQA1, INPP5D, SPDYE3, TSPOAP1, and SIGLEC11) were nominally significant (P < 0.05) in the analysis of the combined blood and brain data (Table 2, Supplemental Table 4, Supplementary Fig. 2)." |
| [[TSPOAP1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Differentially expressed genes (DEGs) after multiple testing correction at P < 6.4 × 10−4 were evident only in the brain for BCKDK (P = 5.1 × 10−4, Padj = 0.04), TSPOAP1 (P = 2.6 × 10−4, Padj = 0.02), and SIGLEC11 (P = 1.6 × 10−4, Padj = 0.01)." |
| [[SIGLEC11]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Differentially expressed genes (DEGs) after multiple testing correction at P < 6.4 × 10−4 were evident only in the brain for BCKDK (P = 5.1 × 10−4, Padj = 0.04), TSPOAP1 (P = 2.6 × 10−4, Padj = 0.02), and SIGLEC11 (P = 1.6 × 10−4, Padj = 0.01)." |
| [[BCKDK]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Differentially expressed genes (DEGs) after multiple testing correction at P < 6.4 × 10−4 were evident only in the brain for BCKDK (P = 5.1 × 10−4, Padj = 0.04), TSPOAP1 (P = 2.6 × 10−4, Padj = 0.02), and SIGLEC11 (P = 1.6 × 10−4, Padj = 0.01)." |
| [[PIGHP1]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PIGHP1 was significantly upregulated in AD cases in the combined brain and blood samples in the ε2/ε3 group (Z = 4.67, P = 3.1×10−6, Padj = 0.05), a pattern predominated by the evidence in the brain but also apparent in the blood (Table 3, Supplementary Figs. 2, 3a)." |
| [[FRAS1]] | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Among ε3/ε4 subjects, the expression of FRAS1 was significantly downregulated in AD cases in blood only (Z = −4.66, P = 3.2 × 10−6, P adj = 0.05) (Supplementary Fig. 3b)." |
| [[C4A]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Among genes previously associated with AD among ε2/ε3 subjects, C4A, C4B, and HSPA2 were moderately (P < 10−3) upregulated in the brain but not blood from AD ROSMAP Study participants in the ε2/ε3 subgroup and total sample (Supplemental Table 5)." |
| [[C4B]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Among genes previously associated with AD among ε2/ε3 subjects, C4A, C4B, and HSPA2 were moderately (P < 10−3) upregulated in the brain but not blood from AD ROSMAP Study participants in the ε2/ε3 subgroup and total sample (Supplemental Table 5)." |
| [[HSPA2]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Among genes previously associated with AD among ε2/ε3 subjects, C4A, C4B, and HSPA2 were moderately (P < 10−3) upregulated in the brain but not blood from AD ROSMAP Study participants in the ε2/ε3 subgroup and total sample (Supplemental Table 5)." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Previous whole transcriptome-wide studies from autopsied brains demonstrate that the classical complement cascade and tau phosphorylation are linked to AD in an APOE genotype-specific manner." |
| [[APOE]] | biolink:associated_with | [[HLA-DRA]] |  | "Leading-edge genes in the same pathway shared by different APOE genotypes included HLA-DRA in allograft rejection, CD74 in interferon gamma response, and KYNU in TNFA signaling via NFKB." |
| [[APOE]] | biolink:associated_with | CD74 (HGNC:1697) |  | "Leading-edge genes in the same pathway shared by different APOE genotypes included HLA-DRA in allograft rejection, CD74 in interferon gamma response, and KYNU in TNFA signaling via NFKB." |
| [[APOE]] | biolink:associated_with | KYNU (HGNC:6469) |  | "Leading-edge genes in the same pathway shared by different APOE genotypes included HLA-DRA in allograft rejection, CD74 in interferon gamma response, and KYNU in TNFA signaling via NFKB." |
| [[APOE]] | biolink:associated_with | [[IFNG]] |  | "Pathways for allograft rejection, interferon gamma response, peroxisome, and TNFA signaling via NFKB were enriched for upregulated AD genes in the ε3/ε4 group but for downregulated AD genes in the ε2/ε3 and ε3/ε3 groups." |
| [[APOE]] | biolink:associated_with | TNF (HGNC:11892) |  | "Pathways for allograft rejection, interferon gamma response, peroxisome, and TNFA signaling via NFKB were enriched for upregulated AD genes in the ε3/ε4 group but for downregulated AD genes in the ε2/ε3 and ε3/ε3 groups." |
| [[APOE]] | biolink:associated_with | [[IL6]] |  | "Six pathways were significantly and uniquely enriched in the ε3/ε4 subgroup including apoptosis, estrogen response late, hypoxia, il6/jak/stat3 signaling, inflammatory response, and p53 pathway." |
| [[APOE]] | biolink:associated_with | [[STAT3]] |  | "Six pathways were significantly and uniquely enriched in the ε3/ε4 subgroup including apoptosis, estrogen response late, hypoxia, il6/jak/stat3 signaling, inflammatory response, and p53 pathway." |
| [[APOE]] | biolink:associated_with | TP53 (HGNC:11998) |  | "Six pathways were significantly and uniquely enriched in the ε3/ε4 subgroup including apoptosis, estrogen response late, hypoxia, il6/jak/stat3 signaling, inflammatory response, and p53 pathway." |
| [[APOE]] | biolink:associated_with | hypoxia (MESH:D000860) |  | "Six pathways were significantly and uniquely enriched in the ε3/ε4 subgroup including apoptosis, estrogen response late, hypoxia, il6/jak/stat3 signaling, inflammatory response, and p53 pathway." |
| [[TRIP10]] | biolink:associated_with | [[ICAM1]] |  | "The expression of only two genes, TRIP10 and FOSL1, which are both involved in signaling via NFKB, was significantly associated with ICAM-1 levels." |
| [[FOSL1]] | biolink:associated_with | [[ICAM1]] |  | "The expression of only two genes, TRIP10 and FOSL1, which are both involved in signaling via NFKB, was significantly associated with ICAM-1 levels." |
| [[INPP5D]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Expression of INPP5D and HLA-DQA-1 was significantly greater in both blood and brain from individuals with AD compared to controls." |
| [[INPP5D]] | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "INPP5D is highly expressed in microglia and encodes the protein SHIP1 which has been implicated in many neuroinflammatory processes." |
| [[HLA-DQA1]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Expression of INPP5D and HLA-DQA-1 was significantly greater in both blood and brain from individuals with AD compared to controls." |
| [[FRAS1]] | biolink:has_phenotype | cognitive decline (HP:0001268; MESH:D060825) |  | "FRAS1 was significantly downregulated in AD compared to controls in blood from ε3/ε4 AD individuals and a recent study showed that FRAS1 knockdown mice were impaired in memory and learning behaviors." |
| [[NFKBIA]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "One of these genes, NFKBIA, is a leading-edge gene from the signaling via NFKB pathway and was involved in five out of nine significant KEGG pathways and two out of four hallmark pathways in the light green network (Table 4, Supplementary Table 8)." |
| [[HLA-DRA]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "HLA-DRA is involved in six of the nine significant KEGG pathways and the allograft rejection hallmark pathway in the light green network and is a leading-edge gene in the allograft rejection pathway identified in the ε3/ε3 and ε3/ε4 groups." |
| [[C4A]] | biolink:associated_with | [[ICAM1]] |  | "Specifically, VASP expression was significantly associated with levels of ICAM-1 (P = 3.7 × 10−4, Padj = 0.04) and SAA (P = 1.0 × 10−4, Padj = 0.01) and C4B expression was significantly associated with levels of ICAM-1 (P = 1.3 × 10−5, Padj = 1.4 × 10−3), SAA (P = 1.6 × 10−4, Padj = 0.02), and VCAM-1 (P = 7.0 × 10−6, Padj = 7.6 × 10−4)." |
| [[C4A]] | biolink:associated_with | [[VCAM1]] |  | "Specifically, VASP expression was significantly associated with levels of ICAM-1 (P = 3.7 × 10−4, Padj = 0.04) and SAA (P = 1.0 × 10−4, Padj = 0.01) and C4B expression was significantly associated with levels of ICAM-1 (P = 1.3 × 10−5, Padj = 1.4 × 10−3), SAA (P = 1.6 × 10−4, Padj = 0.02), and VCAM-1 (P = 7.0 × 10−6, Padj = 7.6 × 10−4)." |
| [[C4A]] | biolink:associated_with | Staphylococcus aureus infection (MONDO:0005545; MESH:D013203) |  | "C4B, which is upregulated in the brain from AD cases compared to controls in the ε2/ε3 group (Supplementary Table 5), was included in the light green network pathways involved in Staphylococcus aureus infection and systemic lupus erythematosus." |
| [[C4A]] | biolink:associated_with | systemic lupus erythematosus (MONDO:0007915; MESH:D008180) |  | "C4B, which is upregulated in the brain from AD cases compared to controls in the ε2/ε3 group (Supplementary Table 5), was included in the light green network pathways involved in Staphylococcus aureus infection and systemic lupus erythematosus." |
| [[C4A]] | biolink:associated_with | vascular injury (MONDO:0021178; MESH:D057772) |  | "Two of the 17 subnetwork genes in the significant pathways enriched for AD genes in the light green network (Supplementary Table 10) were significantly associated with the level of at least one of the three vascular injury proteins after multiple testing correction (Fig. 3d)." |
| [[VASP]] | biolink:associated_with | [[ICAM1]] |  | "Specifically, VASP expression was significantly associated with levels of ICAM-1 (P = 3.7 × 10−4, Padj = 0.04) and SAA (P = 1.0 × 10−4, Padj = 0.01) and C4B expression was significantly associated with levels of ICAM-1 (P = 1.3 × 10−5, Padj = 1.4 × 10−3), SAA (P = 1.6 × 10−4, Padj = 0.02), and VCAM-1 (P = 7.0 × 10−6, Padj = 7.6 × 10−4)." |
| [[VASP]] | biolink:associated_with | vascular injury (MONDO:0021178; MESH:D057772) |  | "Two of the 17 subnetwork genes in the significant pathways enriched for AD genes in the light green network (Supplementary Table 10) were significantly associated with the level of at least one of the three vascular injury proteins after multiple testing correction (Fig. 3d)." |
| [[APOE]] | biolink:associated_with | cognitive decline (HP:0001268; MESH:D060825) |  | "A recent study showed that APOE ε4 carriers exhibit BBB dysfunction and cognitive decline independent of AD pathology." |
| [[IFNG]] | biolink:affects | [[APOE]] | direction=decreased | "The inflammatory cytokine interferon gamma has been shown to impact directly brain endothelium to cause BBB breakdown and can inhibit ApoE production in macrophages." |
| [[VASP]] | biolink:associated_with | [[APOE]] |  | "We identified VASP and C4B in an APOE genotype-specific co-expressed gene network in the brain that was reproduced in the blood, and the expression of these genes was significantly associated with levels of multiple vascular damage proteins." |
| [[C4B]] | biolink:associated_with | [[APOE]] |  | "The pattern of C4B expression in the brain is dependent on the APOE genotype, and dysregulation of the complement system can cause or exacerbate BBB dysfunction." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We identified four pathways (allograft rejection, interferon gamma response, peroxisome, and TNFA signaling via NFKB) containing gene sets that, with respect to AD, were significantly upregulated in the blood and brain from ε4 carriers and other gene sets from the same pathways that were downregulated in individuals without ε4." |
| [[APOE]] | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "The TNFA via NFKB signaling pathway has been implicated in BBB dysfunction, and the TNFA and NFKB pathways have been independently associated with increased neuroinflammation related to APOE ε4." |
| [[TRIP10]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "TRIP10 was previously included in an AD network derived from multi-omic integration and FOSL-1 was identified in conjunction with PIAS1, a protein associated with AD and inflammatory response." |
| PIAS1 (HGNC:2752) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "TRIP10 was previously included in an AD network derived from multi-omic integration and FOSL-1 was identified in conjunction with PIAS1, a protein associated with AD and inflammatory response." |
| [[VASP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Additionally, VASP has been recently implicated in a microglial network in AD." |
| TNF (HGNC:11892) | biolink:associated_with | NF-kappa B (HGNC:7794) |  | "The TNFA via NFKB signaling pathway has been implicated in BBB dysfunction, and the TNFA and NFKB pathways have been independently associated with increased neuroinflammation related to APOE ε4." |
| TNF (HGNC:11892) | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "The TNFA via NFKB signaling pathway has been implicated in BBB dysfunction, and the TNFA and NFKB pathways have been independently associated with increased neuroinflammation related to APOE ε4." |
| [[FOSL1]] | biolink:associated_with | TNF (HGNC:11892) |  | "Our study showed that FOSL1 and TRIP10 were among the genes enriched in the TNFA via the NFKB pathway, and their expression was associated with ICAM-1." |
| [[TRIP10]] | biolink:associated_with | TNF (HGNC:11892) |  | "Our study showed that FOSL1 and TRIP10 were among the genes enriched in the TNFA via the NFKB pathway, and their expression was associated with ICAM-1." |
| NF-kappa B (HGNC:7794) | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "The TNFA via NFKB signaling pathway has been implicated in BBB dysfunction, and the TNFA and NFKB pathways have been independently associated with increased neuroinflammation related to APOE ε4." |
| [[FOSL1]] | biolink:associated_with | NF-kappa B (HGNC:7794) |  | "Our study showed that FOSL1 and TRIP10 were among the genes enriched in the TNFA via the NFKB pathway, and their expression was associated with ICAM-1." |
| [[TRIP10]] | biolink:associated_with | NF-kappa B (HGNC:7794) |  | "Our study showed that FOSL1 and TRIP10 were among the genes enriched in the TNFA via the NFKB pathway, and their expression was associated with ICAM-1." |
| [[ICAM1]] | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "ICAM-1 is a cytokine involved in the regulation of the BBB, and increased ICAM-1 level has been associated with BBB damage and neuroinflammation." |
| [[C4B]] | biolink:associated_with | [[ICAM1]] |  | "We identified VASP and C4B in an APOE genotype-specific co-expressed gene network in the brain that was reproduced in the blood, and the expression of these genes was significantly associated with levels of multiple vascular damage proteins." |
| [[VASP]] | biolink:associated_with | [[VCAM1]] |  | "We identified VASP and C4B in an APOE genotype-specific co-expressed gene network in the brain that was reproduced in the blood, and the expression of these genes was significantly associated with levels of multiple vascular damage proteins." |
| [[C4B]] | biolink:associated_with | [[VCAM1]] |  | "We identified VASP and C4B in an APOE genotype-specific co-expressed gene network in the brain that was reproduced in the blood, and the expression of these genes was significantly associated with levels of multiple vascular damage proteins." |
| [[FOSL1]] | biolink:associated_with | PIAS1 (HGNC:2752) |  | "TRIP10 was previously included in an AD network derived from multi-omic integration and FOSL-1 was identified in conjunction with PIAS1, a protein associated with AD and inflammatory response." |
| [[VASP]] | biolink:correlated_with | [[C4B]] |  | "We identified VASP and C4B in an APOE genotype-specific co-expressed gene network in the brain that was reproduced in the blood, and the expression of these genes was significantly associated with levels of multiple vascular damage proteins." |
