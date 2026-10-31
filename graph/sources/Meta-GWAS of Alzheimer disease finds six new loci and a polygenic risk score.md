---
type: source
title: "Meta-GWAS of Alzheimer disease finds six new loci and a polygenic risk score"
paper_title: "Common variants in Alzheimer’s disease and risk stratification by polygenic risk scores"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000164
pmid: "34099642"
pmcid: "PMC8184987"
doi: "10.1038/s41467-021-22491-8"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8184987/"
sources: ["[[.raw/01M4DY94HTZ5GHZERAAWN6WKXZ/normalized.md]]"]
tags: [gwas, polygenic-risk-score, alzheimer-risk-locus]
---

# Meta-GWAS of Alzheimer disease finds six new loci and a polygenic risk score

A genome-wide meta-analysis of 467,623 European-ancestry individuals (409,435 in discovery, 58,190 in replication) that adds six variants at five loci to the genetic map of [[Alzheimer disease]], and then uses all 39 genome-wide significant variants outside [[APOE]] in a [[Polygenic risk score]] to stratify risk and age at onset. The study is a [[Genome-wide association study]] meta-analysis from the GR@ACE, EADB and related consortia.

## Design

- Discovery combined three datasets by fixed-effects inverse-variance-weighted meta-analysis: GR@ACE/DEGESCO (6331 cases, 6055 controls, genotyped on a Spanish biobank array and imputed to the Haplotype Reference Consortium panel), the International Genomics of Alzheimer's Project stage 1 and 2 summary statistics (up to 30,344 cases and 52,427 controls), and a UK Biobank by-proxy analysis built from parental dementia history (27,696 maternal and 14,338 paternal cases).
- Replication: 16 independent cohorts (19,087 cases, 39,101 controls), largely from the European Alzheimer's Disease Biobank project. All 384 variants with suggestive association (p < 10^-5) within 200 kb of a sentinel SNP were tested.
- Functional annotation used FUMA (positional, eQTL and chromatin-interaction mapping); lead SNPs were clumped (r2 < 0.001, 250 kb).
- The 39-variant PRS was validated in an independent set of 676 clinically diagnosed and 332 autopsy-confirmed cases against 1386 controls, then used for risk stratification in GR@ACE. Percentile boundaries were set in controls aged 55 or younger to limit survival bias.

## Findings

### New loci

- Discovery gave 36 independent genome-wide significant variants in 35 regions; four regions were new. Case-control and by-proxy effect estimates correlated highly (R2 = 0.994). Genomic inflation (lambda median 1.08) was attributed to polygenicity rather than population structure (LD score regression intercept 1.036).
- After replication, six variants at five loci were new: [[APP rs2154481]] (intronic, protective, OR 0.95), two missense variants in [[SHARPIN]] ([[SHARPIN p.S17F]], OR 1.14; [[SHARPIN p.P294S]], OR 1.13; not in linkage disequilibrium with each other), [[PRKD3 rs876461]] near [[PRKD3]] and [[NDUFAF7]] (OR 1.07), [[CHRNE rs72835061]] in the 3' UTR of [[CHRNE]] (OR 1.09) and [[PLCG2 rs3935877]] (protective, OR 0.92).
- Three further loci were strengthened or confirmed: a second common [[PLCG2]] variant, a stop-gain variant in [[IL34]] and a variant near [[HS3ST1]]. Two suggestive loci, ELK2AP and SPPL2A, did not replicate.
- Of the known genetic variance, the 30 previously described loci were said to explain about 31%, leaving most of it uncharacterised.

### Mechanistic hints

- The protective APP variant lies in a 295 bp DNase-hypersensitive region and is an eQTL for APP mRNA and an antisense transcript. The authors cite functional evidence that a linkage block of 13 SNPs including it increases binding of the transcription factor TFCP2 and enhancer activity, and propose that slightly higher lifelong APP expression protects, with a U-shaped (hormesis) response as one way to square this with APP duplications causing [[Early-onset Alzheimer disease]] and with worsening cognition under beta-secretase inhibitors. They also raise protective APP fragments as an alternative.
- SHARPIN was previously proposed as a candidate gene; a rare missense variant (p.Gly186Arg) mislocalised the protein and weakened NF-κB activation, so the two common missense variants may act through immune signalling.
- The CHRNE risk allele raises CHRNE expression in brain and other tissues (GTEx p = 2.1 x 10^-13), a possible hypermorph that would put cholinergic signalling back into prevention thinking.

### Polygenic risk score

- The PRS gave an odds ratio of 1.30 per standard deviation for clinically diagnosed and 1.38 for autopsy-confirmed cases in the validation set; adding sub-significant variants did not improve it. It held in the presence of concomitant brain pathology (84% of autopsied cases had at least one, 48.8% more than one), in both sexes (OR 1.33 males, 1.32 females), and in early-onset (OR 1.58) and late-onset disease (OR 1.29); see [[Late-onset Alzheimer disease]].
- In GR@ACE (12,386 individuals) the PRS gave OR 1.27 per standard deviation (p = 7.3 x 10^-39). The top 2% had 3.0-fold higher risk than the bottom 2%. Within each APOE genotype group the top-versus-bottom PRS odds ratio was about 2.0 to 2.7, with no PRS-by-APOE interaction on risk (p = 0.76).
- The extreme groups, APOE ε4ε4 with highest PRS versus APOE ε2ε2/ε2ε3 with lowest PRS, differed 16.2-fold in risk and 9 years in median age at onset.
- Age at onset differed by PRS only among [[APOE]] ε4 carriers: 4 years in heterozygotes (81 versus 77 years) and 5.5 years in homozygotes (78.5 versus 73 years). ε4 heterozygotes with the highest PRS looked like ε4 homozygotes in risk and onset age, and a Cox model showed a PRS-APOE interaction on onset (p = 0.021).
- The authors suggest trials that enrich for ε4 homozygotes could widen entry to high-PRS ε4 heterozygotes, about 1% of controls, and that PRS could help interpret trial results because it shifts age at onset.

## Why This Source Matters

It supplies the common-variant side of [[Alzheimer disease]] genetics alongside the rare familial genes [[APP]], [[PSEN1]] and [[PSEN2]]: the protective intronic APP variant argues that APP production or processing matters in sporadic as well as familial disease, and the SHARPIN, PLCG2 and CHRNE signals point to immune and cholinergic biology. The PRS results show that polygenic burden adds to APOE genotype, mainly by moving age at onset in ε4 carriers, which is a concrete rule for enrolling pre-symptomatic participants in prevention trials.

## Assessment

- All samples are of European ancestry, so the 39-variant score may not transfer to other ancestries; the authors say validation in other populations is needed.
- GR@ACE controls are younger than cases and some may still develop disease, which the authors treat as making risk estimates conservative.
- Cases from the UK Biobank are by-proxy (parental dementia) rather than directly diagnosed, though the sensitivity analysis without them gave nearly identical effects.
- The causal gene at the PRKD3/NDUFAF7 locus is not resolved, and the functional readings for APP, SHARPIN and CHRNE rest on public eQTL data and prior reports, not on experiments in this study.
- A correction to the paper was published in 2023 (doi 10.1038/s41467-023-36192-x); its content was not available in the text read. The supplementary tables were also not available, so allele-level details beyond the main text are not recorded here.

## Open Questions

- Does the protective APP intronic variant rs2154481 change APP expression or the balance of amyloid beta and protective APP fragments in human brain (the study relies on public eQTL data and prior transcription-factor assays)?
- Do the two SHARPIN missense variants alter NF-κB signalling or linear ubiquitination the way the rare p.Gly186Arg variant does (no functional test was done)?
- Which gene at the PRKD3/NDUFAF7 locus mediates the risk association (the variant lies between two genes and no expression evidence was shown)?
- Does the 39-variant Alzheimer polygenic risk score keep its odds ratio and its effect on age at onset in APOE ε4 carriers of non-European ancestry (all cohorts here were European)?
- Does the elevated CHRNE expression linked to the risk allele reflect altered cholinergic receptor function in the brain (only GTEx expression data were used)?

## Connections

- Disease: [[Alzheimer disease]], [[Early-onset Alzheimer disease]], [[Late-onset Alzheimer disease]]
- Genes: [[APP]], [[PSEN1]], [[PSEN2]], [[APOE]], [[SHARPIN]], [[CHRNE]], [[PLCG2]], [[PRKD3]], [[NDUFAF7]], [[IL34]], [[HS3ST1]]
- Variants: [[APP rs2154481]], [[SHARPIN p.S17F]], [[SHARPIN p.P294S]], [[PRKD3 rs876461]], [[CHRNE rs72835061]], [[PLCG2 rs3935877]], [[APOE rs429358]]
- Methods: [[Genome-wide association study]], [[Polygenic risk score]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Thus far, multiple loci associated with Alzheimer’s disease (AD) have been described next to causal mutations in two subunits of γ-secretases, membrane-embedded aspartyl complexes (PSEN1, PSEN2 genes), and the gene encoding one target protein of these proteases, the amyloid precursor protein gene (APP)." |
| [[CHRNE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we add six variants associated with Alzheimer’s disease risk (near APP, CHRNE, PRKD3/NDUFAF7, PLCG2 and two exonic variants in the SHARPIN gene)." |
| [[PRKD3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we add six variants associated with Alzheimer’s disease risk (near APP, CHRNE, PRKD3/NDUFAF7, PLCG2 and two exonic variants in the SHARPIN gene)." |
| [[NDUFAF7]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we add six variants associated with Alzheimer’s disease risk (near APP, CHRNE, PRKD3/NDUFAF7, PLCG2 and two exonic variants in the SHARPIN gene)." |
| [[PLCG2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we add six variants associated with Alzheimer’s disease risk (near APP, CHRNE, PRKD3/NDUFAF7, PLCG2 and two exonic variants in the SHARPIN gene)." |
| [[SHARPIN]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we add six variants associated with Alzheimer’s disease risk (near APP, CHRNE, PRKD3/NDUFAF7, PLCG2 and two exonic variants in the SHARPIN gene)." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The most prominent locus, APOE, was detected almost 30 years ago using linkage techniques." |
| APOE ɛ4 (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "However, only carriers of causal mutations (APP, PSEN1, and PSEN2) and the APOE ɛ4 allele are considered high risk, while other common and rare genetic variants are ignored." |
| [[PSEN1]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Thus far, multiple loci associated with Alzheimer’s disease (AD) have been described next to causal mutations in two subunits of γ-secretases, membrane-embedded aspartyl complexes (PSEN1, PSEN2 genes), and the gene encoding one target protein of these proteases, the amyloid precursor protein gene (APP)." |
| [[PSEN2]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Thus far, multiple loci associated with Alzheimer’s disease (AD) have been described next to causal mutations in two subunits of γ-secretases, membrane-embedded aspartyl complexes (PSEN1, PSEN2 genes), and the gene encoding one target protein of these proteases, the amyloid precursor protein gene (APP)." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "a Manhattan plot of overall meta-analysis for genome-wide association in Alzheimer’s disease highlighting in pink the loci associated with AD in this study (PRKD3/NDUFAF7, SHARPIN, CHRNE, PLCG2, and APP)." |
| [[IL34]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our analysis also strengthened the evidence of association with AD for three additional genomic loci including an association with a variant in PLCG2 (rs3935877, MAF = 0.13, OR = 0.92 [0.90–0.95], p = 6.9 × 10−9, Fig. 2d), and confirmed another common variant in PLCG2, a stop gain mutation in IL-34 and a variant near HS3ST1 (Table 1, Supplementary Fig. 3 and Supplementary Data 2, 3)." |
| [[HS3ST1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Our analysis also strengthened the evidence of association with AD for three additional genomic loci including an association with a variant in PLCG2 (rs3935877, MAF = 0.13, OR = 0.92 [0.90–0.95], p = 6.9 × 10−9, Fig. 2d), and confirmed another common variant in PLCG2, a stop gain mutation in IL-34 and a variant near HS3ST1 (Table 1, Supplementary Fig. 3 and Supplementary Data 2, 3)." |
| ELK2AP (HGNC:3323) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We were not able to replicate two loci (ELK2AP and SPPL2A regions) that showed suggestive association with AD (p < 1 × 10−7 in discovery)." |
| SPPL2A (HGNC:30227) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We were not able to replicate two loci (ELK2AP and SPPL2A regions) that showed suggestive association with AD (p < 1 × 10−7 in discovery)." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Using this strategy, we identified a genome-wide significant (GWS) association (p < 5 × 10−8) for 36 independent genetic variants in 35 genomic regions (the APOE region contains signals for ɛ4 and ɛ2)." |
| APOE ε2 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Using this strategy, we identified a genome-wide significant (GWS) association (p < 5 × 10−8) for 36 independent genetic variants in 35 genomic regions (the APOE region contains signals for ɛ4 and ɛ2)." |
| [[APP rs2154481]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In APP, we identified a common (MAF = 0.46) intronic variant associated with a reduced risk of AD (rs2154481, OR = 0.95 [0.94–0.96], p = 1.39 × 10−11, Fig. 2f)." |
| [[SHARPIN p.S17F]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Both missense variants increased AD risk (p.Ser17Phe, MAF = 0.085, OR = 1.14 [1.10–1.18], p = 9.6 × 10−13 and p.Pro294Ser, MAF = 0.052, OR = 1.13 [1.09–1.18], p = 1.0 × 10−9, Fig. 2b)." |
| [[SHARPIN p.P294S]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Both missense variants increased AD risk (p.Ser17Phe, MAF = 0.085, OR = 1.14 [1.10–1.18], p = 9.6 × 10−13 and p.Pro294Ser, MAF = 0.052, OR = 1.13 [1.09–1.18], p = 1.0 × 10−9, Fig. 2b)." |
| [[PRKD3 rs876461]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "A variant close to the genes PRKD3 and NDUFAF7 (rs876461, MAF = 0.143) emerged as the most significant variant in the region after the combined analysis (OR = 1.07 [1.05–1.09], p = 1.3 × 10−9, Fig. 2c)." |
| [[CHRNE rs72835061]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "In the 3’-UTR region of CHRNE (Cholinergic Receptor Nicotinic Epsilon Subunit), rs72835061 (MAF = 0.085) was associated with a 1.09-fold increased risk of AD (95% CI [1.06–1.11], p = 1.5 × 10−10, Fig. 2e)." |
| [[PLCG2 rs3935877]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Our analysis also strengthened the evidence of association with AD for three additional genomic loci including an association with a variant in PLCG2 (rs3935877, MAF = 0.13, OR = 0.92 [0.90–0.95], p = 6.9 × 10−9, Fig. 2d), and confirmed another common variant in PLCG2, a stop gain mutation in IL-34 and a variant near HS3ST1 (Table 1, Supplementary Fig. 3 and Supplementary Data 2, 3)." |
| [[SHARPIN p.S17F]] | NOT biolink:correlated_with | [[SHARPIN p.P294S]] |  | "In SHARPIN (SHANK Associated RH Domain Interactor) gene, we found two missense mutations (rs34173062/p.Ser17Phe and rs34674752/p.Pro294Ser) that are in linkage equilibrium (R2 = 1.3 × 10−6, D′ = 0.014, p = 0.96)." |
| Common variants (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "For common variants, we selected only signals firmly replicated in large meta-GWAS (Lambert et al., Kunkle et al., Jun et al., Sims et al., Jansen et al. and present study)." |
| Rare variants (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "For rare variants, we only selected those variants widely replicated excluding those loci presenting conflicting results." |
| Single nucleotide polymorphism (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "we constructed a weighted PRS based on the 39 genetic variants (excluding APOE genotypes) that showed GWS evidence of association with AD (see Methods, Fig. 4 and Supplementary Data 5)." |
| Single nucleotide polymorphism (variant) | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "Our analysis revealed that the effect of the PRS was the same in both sexes (Fig. 4c) and was consistent with both early-onset (onset before 65 years; OR = 1.58, 95% CI [1.22–2.05], p = 5.8 × 10−4) as well as with late-onset AD (onset later than 85 years; OR = 1.29, 95% CI [1.10–1.51], p = 1.5 × 10−3)." |
| Single nucleotide polymorphism (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Our analysis revealed that the effect of the PRS was the same in both sexes (Fig. 4c) and was consistent with both early-onset (onset before 65 years; OR = 1.58, 95% CI [1.22–2.05], p = 5.8 × 10−4) as well as with late-onset AD (onset later than 85 years; OR = 1.29, 95% CI [1.10–1.51], p = 1.5 × 10−3)." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Finally, we compared the risk extremes and found a 16.2-fold (95% CI [8.84–29.5], p = 1.5 × 10−19) increased risk for the highest-PRS group (APOE ɛ4ɛ4) compared with the lowest-PRS group (APOE ɛ2ɛ2/ɛ2ɛ3; Supplementary Data 8)." |
| APOE ε2 (variant) | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Comparisons of the highest and lowest-PRS percentiles with respect to the APOE genotype groups: a difference was found between highest ɛ2ɛ2/ɛ2ɛ3 carriers vs. lowest ɛ3ɛ3 carriers (OR = 0.51 [0.34–0.75], p = 7.8 × 10−4)" |
| [[APP]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Our results directly support APP production or processing as a causal pathway not only in familial AD but in common sporadic AD." |
| [[SHARPIN]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Two independent missense mutations in SHARPIN increased the AD risk." |
| SHARPIN p.Gly186Arg (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "SHARPIN was previously proposed as an AD candidate gene, and functional analysis of a rare missense variant (NM_030974.3:p.Gly186Arg) resulted in the aberrant cellular localization of the variant protein and attenuated the activation of NF-κB, a central mediator of inflammatory and immune responses." |
| beta-amyloid (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "These signals reinforce that AD is a complex disease in which amyloid processing and immune response play key roles." |
| TFCP2 (HGNC:11748) | biolink:regulates | [[APP]] | direction=increased | "Functional evidence supports a modified APP transcription as an LD block of 13 SNPs within the APP locus (including rs2154481) increased the TFCP2 transcription factor avidity to its binding site and increased the enhancer activity of this specific intronic region." |
| [[APP]] | biolink:causes | Early-onset Alzheimer disease (MESH:D000544) |  | "Still, this seems counterintuitive as duplications of the gene lead to early-onset AD." |
| [[SHARPIN]] | biolink:affects | NFKB1 (HGNC:7794) | direction=decreased | "SHARPIN was previously proposed as an AD candidate gene, and functional analysis of a rare missense variant (NM_030974.3:p.Gly186Arg) resulted in the aberrant cellular localization of the variant protein and attenuated the activation of NF-κB, a central mediator of inflammatory and immune responses." |
