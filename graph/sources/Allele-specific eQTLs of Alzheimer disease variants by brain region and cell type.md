---
type: source
title: "Allele-specific eQTLs of Alzheimer disease variants by brain region and cell type"
paper_title: "Allele-specific analysis reveals exon- and cell-type-specific regulatory effects of Alzheimer’s disease-associated genetic variants"
domain: neuroscience
status: developing
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000468
pmid: "35436980"
pmcid: "PMC9016079"
doi: "10.1038/s41398-022-01913-1"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9016079/"
sources: ["[[.raw/01M4DY94SJSRPT383DPQ5DGHPC/normalized.md]]"]
tags: [alzheimer-risk-locus, eqtl, allele-specific-expression, gene-expression, cell-type-resolution]
---

# Allele-specific eQTLs of Alzheimer disease variants by brain region and cell type

An allele-specific eQTL (aseQTL) study of 33 common late-onset [[Alzheimer disease]] GWAS SNPs in four brain regions, six neural cell types from single-nucleus data, sorted microglia and classical monocytes. It introduces the [[Hierarchical Poisson mixed model]] and finds that 24 of the 33 loci (72.7%) affect allelic expression of a local gene in at least one brain region, often only in one region, one exon or one cell type.

## Design

- 33 independent European-ancestry GWAS SNPs with minor allele frequency above 5% (31 outside APOE plus the [[APOE rs429358]] and [[APOE rs7412]] variants that define ε4 and ε2), tested against exonic SNPs of genes with a transcription start within 500 kb; 2432 haplotypes were examined.
- Bulk RNA-seq, about 2500 samples: prefrontal cortex (882), posterior cingulate cortex (572) and head of caudate nucleus (747) from ROSMAP, and temporal cortex (317) from MayoRNAseq. Single-nucleus data: more than 240,000 prefrontal nuclei from 71 ROSMAP subjects; microglia power was raised with seven microglia-specific single-nucleus samples and ten sorted-cell bulk samples. Monocytes: CD14+CD16- classical monocytes, 336 usable samples.
- Reads were realigned with WASP to remove mapping bias, imputed genotypes with quality above 0.96 were used to limit phasing errors, and single-nucleus counts were collapsed to unique molecular identifiers.
- Each significant signal was sorted into three classes by linkage disequilibrium with the exonic proxy SNP and by whether the proxy SNP was itself more strongly associated: class one (GWAS SNP stronger, 53 associations in 19 genes), class two (proxy stronger but in high linkage disequilibrium, 17 associations) and class three (proxy much stronger, weak linkage in the whole sample, so likely an artefact of correlation in double-heterozygous people).

## Findings

- Region-level: 367 significant associations (FDR below 0.05) across 24 loci and 87 genes; most were consistent across regions, some region-specific. Three associations are new: [[APH1B rs117618017]] with [[CA12]] in the caudate nucleus, rs113260531 with [[CHRNE]] in the prefrontal cortex and caudate, and [[CASS4 rs6014724]] with [[CASS4]] in the caudate.
- Region-dependent effects: rs113260531-A lowered [[RABEP1]] in prefrontal and temporal cortex but raised it elsewhere; [[CLU rs7982]] (tagging [[CLU rs4236673]]) affected [[CLU]] only in the temporal cortex; [[CR1 rs2093760]] and rs442495 were strong aseQTLs of [[CR1]] and [[ADAM10]] in the temporal cortex, where those genes are expressed.
- Exon-specific effects: [[CD33 rs3865444]] acted only at exon 2 of [[CD33]], confirming a splicing effect also seen in monocytes; for [[APOE]], the ε4 allele raised exon 2 expression measured at [[APOE rs440446]] but lowered exon 4 of the major transcript, because of linkage with a minor transcript.
- ε4 lowers APOE expression in all four regions, and the effect persisted when only unaffected controls were analysed, so it is not a consequence of diagnosis. The authors argue astrocytes, the main APOE-expressing neural cell, are the likely source, and note that APOE is reported higher in microglia of patients.
- No interaction of any of the 367 aseQTLs with age at death (85 or less versus above), sex or Alzheimer diagnosis after correction.
- Single-nucleus level: of 499 tests (28 SNPs, 118 genes), 11 were significant for rs1859788 and rs3740688 with [[PILRB]], [[TRIM4]] and [[MTCH2]], but all were class three and the SNPs were not genotype-level eQTLs. Genotype-level eQTLs: rs2093760 with CR1 in oligodendrocytes, and rs6931277 with [[HLA-DOB]] in excitatory neurons and [[HLA-DQA2]] in microglia.
- Microglia: seven significant associations in six genes ([[BIN1]], [[ITGAM]], [[FCER1G]], [[MS4A7]], [[ATXN3]], [[ABCA7]]); BIN1, FCER1G and ABCA7 overlapped the tissue-level hits. Genotype-level microglial eQTLs also included [[ADAMTS4 rs4575098]] with [[ADAMTS4]] and rs867611 with [[PICALM]].
- Monocytes: 14 significant associations from six SNPs in nine genes, mostly immune genes ([[CD33]], [[MS4A6A]], [[SPI1]], [[HLA-DQB1]], [[FCER1G]]); the MS4A6A signal from rs2081545 matched the caudate nucleus, and rs6931277 also acted on HLA-DQB1.
- Several signals (CLU, BIN1, CD33, PTK2B, B4GALT3, CASTOR3, ADAMTS4) were missing from gene-level brain eQTL catalogues but matched exon-level, transcript-level or splicing QTLs, so allele-specific analysis uncovers effects that gene-level data blur; see also [[Expression quantitative trait locus analysis]].

## Assessment

- Strengths: a formal power comparison by simulation, a cross-region and cross-cell-type design with two replication-style comparisons (monocytes and microglia), and explicit handling of mapping bias, phasing quality and linkage artefacts.
- Limits stated by the authors: 3'-biased single-nucleus reads leave most exonic SNPs unmeasured, the single-nucleus and microglia samples are small (seven to ten extra microglia samples, 71 cortical subjects), and class two and class three signals cannot separate the GWAS SNP from a linked exonic SNP. Only common European-ancestry SNPs were tested.
- The single-nucleus aseQTLs for PILRB, TRIM4 and MTCH2 are explained as linkage artefacts, so the cell-type resolution of the allele-specific method is mainly shown by genotype-level eQTLs (CR1, HLA genes).

## Open Questions

- Does the CR1 missense variant rs2296160 or a regulatory effect of the GWAS SNP rs2093760 drive the oligodendrocyte and temporal cortex signal (the two variants are in near-complete linkage, so statistics alone cannot separate them)?
- Is lower APOE expression with the ε4 allele driven by astrocytes, and is the higher APOE in microglia of patients regulated differently (microglia were only a tiny fraction of the nuclei sequenced)?
- Do the microglial allele-specific associations in BIN1, ITGAM, FCER1G, MS4A7, ATXN3 and ABCA7 replicate in a larger microglia dataset (the analysis pooled only 17 microglia-enriched samples and the strongest signals rested on double-heterozygous people)?
- Would long-read single-nucleus sequencing recover the allele-specific signals missed by 3' read coverage (suggested by the authors but not tested)?

## Why This Source Matters

It shows, with a method that is more powerful than the beta-binomial standard, that Alzheimer GWAS signals frequently act on one exon, one brain region or one cell type, and it separates credible regulatory effects from artefacts of linkage in double-heterozygous people. It also supplies a direct, control-only demonstration that the ε4 allele reduces APOE expression independently of disease.

## Connections

- Method: [[Hierarchical Poisson mixed model]], [[Expression quantitative trait locus analysis]], [[Single-nucleus RNA sequencing]], [[Genome-wide association study]]
- Disease: [[Alzheimer disease]], [[Late-onset Alzheimer disease]]
- Genes with new or confirmed signals: [[APOE]], [[CD33]], [[CR1]], [[CLU]], [[BIN1]], [[ADAM10]], [[MS4A6A]], [[ABCA7]], [[CHRNE]], [[CA12]], [[CASS4]], [[PILRB]], [[FCER1G]], [[HLA-DQB1]], [[HLA-DQA2]], [[HLA-DOB]]
- Related locus study: [[Non-coding risk haplotypes at the APOE locus in Alzheimer disease]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, except for a few exonic variants in, e.g., APOE and TREM2, most of these identified signals are in non-coding regions and thus present difficulties in elucidating their causal pathways in neuropathology and pinpointing the genes, cell types, and brain regions mediating their associations with LOAD." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, except for a few exonic variants in, e.g., APOE and TREM2, most of these identified signals are in non-coding regions and thus present difficulties in elucidating their causal pathways in neuropathology and pinpointing the genes, cell types, and brain regions mediating their associations with LOAD." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we conducted an analysis of allele-specific expression quantitative trait loci (aseQTLs) for 33 AD-associated variants in four brain regions and seven cell types using ~3000 bulk RNA-seq samples and >0.25 million single nuclei." |
| [[CR1 rs2093760]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we conducted an analysis of allele-specific expression quantitative trait loci (aseQTLs) for 33 AD-associated variants in four brain regions and seven cell types using ~3000 bulk RNA-seq samples and >0.25 million single nuclei." |
| [[CLU rs7982]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we conducted an analysis of allele-specific expression quantitative trait loci (aseQTLs) for 33 AD-associated variants in four brain regions and seven cell types using ~3000 bulk RNA-seq samples and >0.25 million single nuclei." |
| [[CD33 rs3865444]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we conducted an analysis of allele-specific expression quantitative trait loci (aseQTLs) for 33 AD-associated variants in four brain regions and seven cell types using ~3000 bulk RNA-seq samples and >0.25 million single nuclei." |
| [[CD33]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Because many AD-associated SNPs are located in or near genes specifically expressed in microglia or monocytes (e.g., TREM2 and CD33), we further evaluated the regulatory effects in these two cell types using both cell-sorting bulk RNA-seq and snRNA-seq data." |
| [[BIN1 rs6733839]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "e An example of combining evidence from both the ASE and the genotype-level expression to improve the power for detecting the association between the AD-associated SNP rs6733839 and BIN1." |
| [[APOE rs429358]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We specifically focused on 33 independent (except for the APOE ε4 and APOE ε2 variants encoded by the minor alleles of rs429358 and rs7412, respectively) AD-associated common SNPs (defined as a minor allele frequency (MAF) > 5%) in the European population reported or replicated in large-scale GWAS and meta-analyses (Fig. 1a)." |
| [[APOE rs7412]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We specifically focused on 33 independent (except for the APOE ε4 and APOE ε2 variants encoded by the minor alleles of rs429358 and rs7412, respectively) AD-associated common SNPs (defined as a minor allele frequency (MAF) > 5%) in the European population reported or replicated in large-scale GWAS and meta-analyses (Fig. 1a)." |
| RABEP1 rs113260531 (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "These observations suggest that the regulatory effects of certain AD-associated SNPs are region-dependent." |
| [[CLU rs4236673]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "rs7982 (chr8:27462481), in almost complete LD with the AD GWAS locus rs4236673, was significantly (p = 1E-50) associated with the ASE of CLU only in the TC, but not even nominally significant in the other regions (Fig. 1c, Table S1)." |
| [[CR1 rs2093760]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "These observations suggest that the regulatory effects of certain AD-associated SNPs are region-dependent." |
| ADAM10 rs442495 (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "These observations suggest that the regulatory effects of certain AD-associated SNPs are region-dependent." |
| [[BIN1 rs6733839]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "These observations suggest that the regulatory effects of certain AD-associated SNPs are region-dependent." |
| [[CLU rs7982]] | biolink:correlated_with | [[CLU rs4236673]] |  | "rs7982 (chr8:27462481), in almost complete LD with the AD GWAS locus rs4236673, was significantly (p = 1E-50) associated with the ASE of CLU only in the TC, but not even nominally significant in the other regions (Fig. 1c, Table S1)." |
| [[APOE rs429358]] | biolink:correlated_with | [[APOE rs440446]] |  | "A further investigation reveals that the APOE ε4 variant is in mild LD with rs440446, which is located in another transcript (ENST00000434152) of APOE (Fig. 2c)." |
| [[APOE rs429358]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "For example, we observed that the APOE ε4 allele (rs429358-C), the leading genetic risk factor, was associated with elevated expression of exon 2 measured at rs440446 (Fig. 2a), but with reduced expression of exon 4 of APOE (Fig. 2b)." |
| [[CR1 rs2093760]] | biolink:correlated_with | [[CR1 rs2296160]] |  | "The only exception is the missense variant rs2296160, which was in nearly complete LD (r = 0.995) with rs2093760 and very strongly (p = 8.95E-16) associated with the ASE (Table S1, Fig. 3c)." |
| [[CLU rs4236673]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "These AD GWAS SNPs were in almost complete LD with the exonic SNPs used for measuring the ASE." |
| [[ADAMTS4 rs4575098]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "These AD GWAS SNPs were in almost complete LD with the exonic SNPs used for measuring the ASE." |
| rs59735493 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "These AD GWAS SNPs were in almost complete LD with the exonic SNPs used for measuring the ASE." |
| rs442495 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "These AD GWAS SNPs were in almost complete LD with the exonic SNPs used for measuring the ASE." |
| [[CLU rs4236673]] | biolink:correlated_with | rs9331888 (variant) |  | "The AD GWAS SNP rs4236673 is in almost complete LD with rs7982 and mild LD with rs9331888 (Table S1)." |
| [[CLU rs4236673]] | biolink:correlated_with | [[CLU rs7982]] |  | "The AD GWAS SNP rs4236673 is in almost complete LD with rs7982 and mild LD with rs9331888 (Table S1)." |
| [[CLU rs4236673]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "The AD GWAS SNP rs4236673 is in almost complete LD with rs7982 and mild LD with rs9331888 (Table S1)." |
| rs1859788 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Specifically, the AD GWAS SNP rs1859788 was associated with the allelic imbalance of PILRB in excitatory and inhibitory neurons, astrocytes, and oligodendrocytes." |
| rs3740688 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We identified 11 significant associations (FDR p < 0.05) between two AD-associated SNPs and the ASE of three genes, including PILRB, TRIM4, and MTCH2 (Table S3)." |
| rs1859788 (variant) | biolink:correlated_with | chr7:99965285 (variant) |  | "rs1859788 was in complete LD with the two exonic SNPs only in the double-heterozygous subjects, but the correlation was low in the whole sample (r = ~0.2)." |
| rs1859788 (variant) | biolink:correlated_with | chr7:99955364 (variant) |  | "rs1859788 was in complete LD with the two exonic SNPs only in the double-heterozygous subjects, but the correlation was low in the whole sample (r = ~0.2)." |
| [[CD33 rs3865444]] | biolink:associated_with | rs2455069 (variant) |  | "Similar to the results in the region-specific analysis, rs3865444 was associated with the ASE of the second exon of CD33 measured at chr19:51728641 (rs2455069) and chr19:51728477 (rs12459419) in monocytes (p = 4.52E-12 and 2.05E-6) (Fig. 6a), confirming that this AD-associated SNP is an sQTL of exon 2 reported in." |
| [[CD33 rs3865444]] | biolink:associated_with | [[CD33 p.A14V]] |  | "Similar to the results in the region-specific analysis, rs3865444 was associated with the ASE of the second exon of CD33 measured at chr19:51728641 (rs2455069) and chr19:51728477 (rs12459419) in monocytes (p = 4.52E-12 and 2.05E-6) (Fig. 6a), confirming that this AD-associated SNP is an sQTL of exon 2 reported in." |
| [[ADAMTS4 rs4575098]] | biolink:correlated_with | [[FCER1G rs11421]] |  | "As another example, rs4575098, an AD-associated SNP located in the UTR of ADAMTS4, was in moderate LD (r = 0.59) with an exonic variant rs11421, located in the 5’ UTR of FCER1G, which was itself a significant aseQTL of FCER1G (Fig. 6c)." |
| rs2081545 (variant) | biolink:associated_with | rs7232 (variant) |  | "The association between rs2081545 and MS4A6A was observed in two of the exons measured at rs7232 and rs12453." |
| rs2081545 (variant) | biolink:associated_with | rs12453 (variant) |  | "The association between rs2081545 and MS4A6A was observed in two of the exons measured at rs7232 and rs12453." |
| [[CD33 rs3865444]] | biolink:correlated_with | [[CD33 p.A14V]] |  | "The almost complete LD between the promoter variant rs3865444 and the exonic variant rs12459419 makes it challenging to determine the causal variant." |
| [[APOE]] | biolink:affects | mRNA (CHEBI:33699; MESH:D012333) | direction=decreased | "These results corroborate previous findings of lower mRNA and protein levels of APOE in ε4 carriers." |
| [[CR1]] | biolink:correlated_with | [[APOE]] |  | "Genes in the complement system are abundantly expressed in microglia and are co-expressed with APOE." |
| [[CR1 rs2093760]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "More research is needed to elucidate which functional consequence of this haplotype is the primary factor contributing to the risk of LOAD." |
| [[CR1 rs2296160]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "More research is needed to elucidate which functional consequence of this haplotype is the primary factor contributing to the risk of LOAD." |
