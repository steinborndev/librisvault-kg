---
type: source
title: "SIRT3 loss lowers insulin-degrading enzyme in comorbid Alzheimer mice"
paper_title: "Sirt3 deficiency induced down regulation of insulin degrading enzyme in comorbid Alzheimer’s disease with metabolic syndrome"
domain: neuroscience
status: developing
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-000827
pmid: "36396721"
pmcid: "PMC9672095"
doi: "10.1038/s41598-022-23652-5"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9672095/"
sources: ["[[.raw/01M4P6MQYSE6B43W58CJFMRG6R/normalized.md]]"]
tags: [mouse-model, rna-seq, amyloid-degradation]
---

# SIRT3 loss lowers insulin-degrading enzyme in comorbid Alzheimer mice

A mouse study of how [[Metabolic syndrome]] and amyloid pathology meet in the brain. The authors profile brain RNA from wild-type, Sirt3-knockout, [[APP-PS1 mouse]] and APP/PS1/Sirt3-knockout animals, find that [[IDE]] (insulin-degrading enzyme) is among the genes pushed down by Sirt3 loss, and then test whether [[SIRT3]] activity sets IDE levels with a Western diet and with the NAD+ precursor [[Nicotinamide riboside]] (NR).

## Design

- Animals: global Sirt3-knockout mice, [[APP-PS1 mouse]] animals and the double mutant [[APP-PS1-Sirt3 knockout mouse]] (the comorbid Alzheimer model made earlier by the same group), plus wild-type controls. Details are on the model page.
- RNA-seq: cortical RNA from 8-month-old females (four groups, library prep with poly-A selection, about 25 million reads on an Illumina NextSeq 550, mapped to mm10 with TopHat, differential expression with DESeq2 at adjusted P below 0.05). The legends mention four per group, while the gene plots show three samples. Enrichment of the changed genes was run in the DAVID tool against KEGG and Gene Ontology.
- Western diet: 2-month-old male wild-type and Sirt3-knockout mice for 4 months, and 6-week-old wild-type and APP/PS1 males for 7 months, with SIRT3 and IDE read in cortex by Western blot and IDE in plasma by ELISA (six per group). Samples came from the authors' earlier diet studies.
- Activation: 7-month-old C57BL/6 males (six per group) on chow or chow with 0.4% NR for 3 months; cortical SIRT3, IDE, [[MME]] (neprilysin) and [[BACE1]] by Western blot, IDE activity by a fluorometric kit assay, plasma IDE by ELISA. Then [[BV2]] microglial cells and a SIRT3 shRNA version of them (SIRT3 cut by about 70%) were given 0.5, 1 or 2 mM NR for 24 or 48 h.
- Statistics: unpaired t test or one-way ANOVA with Tukey. RNA-seq data are deposited at GEO under GSE216081.

## Findings

- Expression landscape: the four groups separated clearly on a heat map, and Sirt3 deletion, amyloid pathology and the combination each altered many genes. In the comorbid line, enrichment pointed to metabolic, inflammatory, Alzheimer disease and insulin signalling pathways (for example 1599 genes in metabolic pathways, 381 in the amyloid pathway and 139 in insulin signalling out of 25,000).
- Inflammatory genes up with amyloid: serpin, [[CCL3]], [[CLEC7A]], [[TYROBP]] and [[C3]] rose; cystatin F ([[CST7]]) rose by about 50-fold, CCL3 about tenfold and [[ITGAX]] about fivefold, with [[CD83]] and TYROBP rising modestly. These did not rise further with Sirt3 loss, except C3, which was significantly higher in the comorbid brain than in APP/PS1 alone. Diacylglycerol kinase fell in both amyloid groups.
- IDE as the key downregulated hit: IDE expression fell by about 50% in Sirt3-knockout and APP/PS1/Sirt3-knockout brain.
- Western diet: brain IDE fell by 33% in Sirt3-knockout mice (the text says especially after diet) and plasma IDE by 48%; in APP/PS1 mice the diet cut brain SIRT3 and IDE by about 50% each, but plasma IDE only by 24%.
- NR in wild-type mice: cortical IDE up 65%, neprilysin up 47%, BACE1 down 46%, SIRT3 up 72%, IDE activity up 84% and plasma IDE up 52%.
- NR in cells: SIRT3 rose 78% in BV2 after 2 mM for 24 h; in SIRT3-silenced cells basal SIRT3 was 47% lower and NR raised it 64%; IDE rose in both, more in the silenced line (64%). By 48 h SIRT3 no longer rose and IDE rose only modestly, which the authors read as a steady state.
- Interpretation offered: lower SIRT3 in metabolic syndrome lowers IDE, which would impair both insulin clearance and amyloid-beta degradation, while SIRT3 activation lowers amyloid-beta production (less BACE1) and raises degradation (more IDE and neprilysin). The discussion proposes an indirect route to IDE through PGC-1α (PPARGC1A) and NRF1, and notes that IDE's many substrates make it a doubtful drug target itself.

## Why This Source Matters

It gives a concrete molecular link between a metabolic risk factor and amyloid handling: a SIRT3 deficit, which diet and the knockout both produce, lowers an enzyme that clears both insulin and amyloid-beta. It also moves the conversation from "metabolic syndrome adds to amyloid pathology" to a testable shared pathway, and it shows an orally given NAD+ precursor shifting three amyloid-relevant proteins in the right direction in healthy mice.

## Assessment

- IDE was measured as protein and activity, and the RNA-seq fall was shown on a gene plot; no mRNA validation by PCR is described, and the diet experiments reused samples from earlier studies in different mouse strains and sexes (males for diet and NR, females for RNA-seq).
- The NR experiments used wild-type mice only; no NR arm was run in APP/PS1 or the comorbid mouse, so effects on plaque load are inferred from enzyme levels, not measured.
- NR raises NAD+ for many NAD-dependent enzymes, not SIRT3 alone, and SIRT3 activity itself was not read out; the SIRT3 knock-down cell line shows IDE still rose without SIRT3, which weakens a strictly SIRT3-dependent reading.
- Plasma and cortical IDE are treated as linked, but the main source of plasma IDE is the liver, so the plasma figures may not report brain changes.
- The gene-level comparison between groups is shown for selected genes; the full lists are in the deposited data, not the text. The text has small numbering slips (for example four samples per group in the legends against three in the gene plots).

## Open Questions

- Does nicotinamide riboside lower plaque burden and raise IDE and neprilysin in APP/PS1 and APP/PS1/Sirt3-knockout mice (only wild-type mice were treated)?
- Does SIRT3 control IDE transcription through PPARGC1A and NRF1 (proposed in the discussion but not tested)?
- Is the IDE fall in the brain of Sirt3-knockout mice a neuronal, glial or vascular effect (whole cortex lysates were used)?
- Are SIRT3 and IDE also lower together in human Alzheimer brain with metabolic syndrome (only mouse tissue and a mouse cell line were studied)?

## Connections

- Entities: [[SIRT3]], [[IDE]], [[MME]], [[BACE1]], [[CCL3]], [[C3]], [[CST7]], [[CD83]], [[CLEC7A]], [[ITGAX]], [[TYROBP]], [[PRNP]], [[Nicotinamide riboside]]
- Diseases and traits: [[Metabolic syndrome]], [[Insulin resistance]], [[Alzheimer disease]], [[Neuroinflammation]], [[Mitochondrial dysfunction]]
- Models: [[APP-PS1-Sirt3 knockout mouse]], [[APP-PS1 mouse]], [[BV2]]
- Processes: [[Amyloid-beta clearance]], [[Amyloid-beta formation]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[SIRT3]] | biolink:affects | [[IDE]] | direction=increased | "Conversely, activation of SIRT3 by nicotinamide riboside in vivo and in vitro resulted in IDE upregulation." |
| [[SIRT3]] | biolink:affects | [[MME]] | direction=increased | "SIRT3 activation in vivo also increased the levels of neprilysin, another Aβ degrading enzyme and decreased the levels of BACE1 which generates Aβ peptide suggesting SIRT3’s role in amyloid plaque reduction." |
| [[SIRT3]] | biolink:affects | [[BACE1]] | direction=decreased | "SIRT3 activation in vivo also increased the levels of neprilysin, another Aβ degrading enzyme and decreased the levels of BACE1 which generates Aβ peptide suggesting SIRT3’s role in amyloid plaque reduction." |
| [[SIRT3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "SIRT3 may be a potential therapeutic target to treat AD." |
| [[SIRT3]] | biolink:causes | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "We have previously demonstrated that Sirt3 gene deletion leads to brain mitochondrial dysfunction and neuroinflammation." |
| [[SIRT3]] | biolink:causes | neuroinflammation (HP:0033429; MESH:D000090862) |  | "We have previously demonstrated that Sirt3 gene deletion leads to brain mitochondrial dysfunction and neuroinflammation." |
| [[SIRT3]] | biolink:contributes_to | [[Insulin resistance]] (MESH:D007333) |  | "We also reported that silencing of Sirt3 gene in APP/PS1 mice results in exacerbation of insulin resistance, neuroinflammation and β amyloid plaque deposition." |
| [[SIRT3]] | biolink:contributes_to | amyloid plaque deposition (MESH:D058225) |  | "We also reported that silencing of Sirt3 gene in APP/PS1 mice results in exacerbation of insulin resistance, neuroinflammation and β amyloid plaque deposition." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:affects | [[SIRT3]] | direction=increased | "Conversely, activation of SIRT3 by nicotinamide riboside in vivo and in vitro resulted in IDE upregulation." |
| [[IDE]] | biolink:regulates | INS (HGNC:6081) |  | "Following Sirt3 gene deletion, a key finding was the decreased expression of insulin-degrading enzyme (IDE), an enzyme that regulates the levels of insulin and Aβ peptides." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:regulates | [[IDE]] |  | "Following Sirt3 gene deletion, a key finding was the decreased expression of insulin-degrading enzyme (IDE), an enzyme that regulates the levels of insulin and Aβ peptides." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:affects | [[IDE]] | direction=increased | "Conversely, activation of SIRT3 by nicotinamide riboside in vivo and in vitro resulted in IDE upregulation." |
| [[MME]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=decreased | "SIRT3 activation in vivo also increased the levels of neprilysin, another Aβ degrading enzyme and decreased the levels of BACE1 which generates Aβ peptide suggesting SIRT3’s role in amyloid plaque reduction." |
| [[BACE1]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "SIRT3 activation in vivo also increased the levels of neprilysin, another Aβ degrading enzyme and decreased the levels of BACE1 which generates Aβ peptide suggesting SIRT3’s role in amyloid plaque reduction." |
| [[Metabolic syndrome]] (MESH:D024821) | biolink:associated_with | amyloid pathology (HP:0011034) |  | "Our findings provide a plausible mechanism linking metabolic syndrome and amyloid pathology." |
| [[SIRT3]] | biolink:contributes_to | [[Metabolic syndrome]] (MESH:D024821) |  | "One of the genetic risk factors is the downregulation of Sirt3 gene." |
| [[SIRT3]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The deposition of β amyloid plaques increased in terms of number and size because of Sirt3 gene deletion." |
| [[SIRT3]] | biolink:regulates | SOD2 (HGNC:11180) | direction=increased | "Targets of SIRT3 include metabolic enzymes, antioxidant enzyme SOD2, respiratory chain complexes and transcriptional coactivator PGC-1α, needed for mitochondrial biogenesis." |
| [[SIRT3]] | biolink:regulates | PPARGC1A (HGNC:9237) | direction=increased | "Targets of SIRT3 include metabolic enzymes, antioxidant enzyme SOD2, respiratory chain complexes and transcriptional coactivator PGC-1α, needed for mitochondrial biogenesis." |
| [[SIRT3]] | biolink:contributes_to | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "We examined the brain samples of Sirt3-/- mice, fed on western diet and observed downregulation of metabolic enzymes, peripheral and central insulin resistance, mitochondrial dysfunction and inflammasome formation leading to neuroinflammation." |
| [[SIRT3]] | biolink:contributes_to | neuroinflammation (HP:0033429; MESH:D000090862) |  | "We examined the brain samples of Sirt3-/- mice, fed on western diet and observed downregulation of metabolic enzymes, peripheral and central insulin resistance, mitochondrial dysfunction and inflammasome formation leading to neuroinflammation." |
| [[SIRT3]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=decreased | "The deposition of β amyloid plaques increased in terms of number and size because of Sirt3 gene deletion." |
| [[SIRT3]] | biolink:associated_with | Inflammation (MESH:D007249) |  | "SIRT3 belongs to sirtuin family consisting of seven members that play critical roles in longevity and inflammation." |
| Sirt3 single point mutation (variant) | biolink:causes | [[Metabolic syndrome]] (MESH:D024821) |  | "A single point mutation in human Sirt3 leads to reduced activity and MetS." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Therefore, to determine if metabolic syndrome in mid-life is a risk factor for AD, we generated a comorbid AD mouse model by deleting Sirt3 gene globally in APP/PS1 mice, an Alzheimer’s transgenic mouse model with amyloid pathology." |
| [[PSEN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Therefore, to determine if metabolic syndrome in mid-life is a risk factor for AD, we generated a comorbid AD mouse model by deleting Sirt3 gene globally in APP/PS1 mice, an Alzheimer’s transgenic mouse model with amyloid pathology." |
| amyloid pathology (HP:0011034) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Therefore, to determine if metabolic syndrome in mid-life is a risk factor for AD, we generated a comorbid AD mouse model by deleting Sirt3 gene globally in APP/PS1 mice, an Alzheimer’s transgenic mouse model with amyloid pathology." |
| DNA (CHEBI:16991; MESH:D004247) | biolink:derives_from | RNA (CHEBI:18273; MESH:D012313) |  | "After quality control, mRNA was purified, sheared into short fragments of ~ 200 bases and used as templates for cDNA synthesis, followed by library preparation." |
| [[SIRT3]] | biolink:negatively_correlated_with | [[C3]] |  | "However, the levels of complement protein C3 were elevated significantly more in comorbid AD mouse brain, compared to APP/PS1 mice, suggesting the role of Sirt3 downregulation." |
| [[SIRT3]] | biolink:negatively_correlated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "We had previously demonstrated that Sirt3 gene deletion-induced mitochondrial injury leads to inflammasome formation in the brain." |
| [[SIRT3]] | biolink:has_phenotype | Hyperinsulinemia (HP:0000842; MESH:D006946) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[SIRT3]] | biolink:has_phenotype | hypertriglyceridemia (HP:0002155; MESH:D015228) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[SIRT3]] | biolink:has_phenotype | Weight gain (HP:0004324; MESH:D015430) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[APP]] | biolink:has_phenotype | Hyperinsulinemia (HP:0000842; MESH:D006946) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[APP]] | biolink:has_phenotype | hypertriglyceridemia (HP:0002155; MESH:D015228) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[APP]] | biolink:has_phenotype | Weight gain (HP:0004324; MESH:D015430) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[PSEN1]] | biolink:has_phenotype | Hyperinsulinemia (HP:0000842; MESH:D006946) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[PSEN1]] | biolink:has_phenotype | hypertriglyceridemia (HP:0002155; MESH:D015228) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[PSEN1]] | biolink:has_phenotype | Weight gain (HP:0004324; MESH:D015430) |  | "These mice were characterized by hyperinsulinemia, hypertriglyceridemia and weight gain." |
| [[IDE]] | biolink:affects | insulin (CHEBI:5931; MESH:D007328) | direction=decreased | "A key hit among the downregulated genes because of Sirt3 gene deletion was insulin-degrading enzyme (IDE) which plays a regulatory role in insulin turnover as well as degradation of Aβ peptide." |
| [[IDE]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=decreased | "A key hit among the downregulated genes because of Sirt3 gene deletion was insulin-degrading enzyme (IDE) which plays a regulatory role in insulin turnover as well as degradation of Aβ peptide." |
| [[CCL3]] | biolink:positively_correlated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "As expected, many among the upregulated genes were inflammatory mediators including serpin, CCL3, Clec7a, Tyrobp and C3." |
| [[CCL3]] | biolink:positively_correlated_with | Amyloid deposition (HP:0011034; MESH:D058225) |  | "The levels of chemokine CCL3 and itgax, also known as CD11C were induced by ten and five-fold respectively (Fig. 3B)." |
| [[CLEC7A]] | biolink:positively_correlated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "As expected, many among the upregulated genes were inflammatory mediators including serpin, CCL3, Clec7a, Tyrobp and C3." |
| [[CLEC7A]] | biolink:positively_correlated_with | Amyloid deposition (HP:0011034; MESH:D058225) |  | "As expected, many among the upregulated genes were inflammatory mediators including serpin, CCL3, Clec7a, Tyrobp and C3." |
| [[TYROBP]] | biolink:positively_correlated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "As expected, many among the upregulated genes were inflammatory mediators including serpin, CCL3, Clec7a, Tyrobp and C3." |
| [[TYROBP]] | biolink:positively_correlated_with | Amyloid deposition (HP:0011034; MESH:D058225) |  | "As expected, many among the upregulated genes were inflammatory mediators including serpin, CCL3, Clec7a, Tyrobp and C3." |
| [[C3]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, the levels of complement protein C3 were elevated significantly more in comorbid AD mouse brain, compared to APP/PS1 mice, suggesting the role of Sirt3 downregulation." |
| [[C3]] | biolink:positively_correlated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "As expected, many among the upregulated genes were inflammatory mediators including serpin, CCL3, Clec7a, Tyrobp and C3." |
| [[C3]] | biolink:positively_correlated_with | Amyloid deposition (HP:0011034; MESH:D058225) |  | "As expected, many among the upregulated genes were inflammatory mediators including serpin, CCL3, Clec7a, Tyrobp and C3." |
| [[CST7]] | biolink:positively_correlated_with | Amyloid deposition (HP:0011034; MESH:D058225) |  | "Cystatin F was induced by ~ 50 fold by amyloid deposition." |
| [[ITGAX]] | biolink:positively_correlated_with | Amyloid deposition (HP:0011034; MESH:D058225) |  | "The levels of chemokine CCL3 and itgax, also known as CD11C were induced by ten and five-fold respectively (Fig. 3B)." |
| [[CD83]] | biolink:positively_correlated_with | Amyloid deposition (HP:0011034; MESH:D058225) |  | "CD83, a surface marker for matured dendritic cells and Tyrobp were induced modestly." |
| amyloid pathology (HP:0011034) | biolink:contributes_to | neuroinflammation (HP:0033429; MESH:D000090862) |  | "Amyloid pathology is also known to induce neuroinflammation." |
| NAD+ (CHEBI:15846; MESH:D009243) | biolink:affects | [[SIRT3]] | direction=increased | "SIRT3 is activated by nicotinamide adenine dinucleotide (NAD+)." |
| [[SIRT3]] | biolink:associated_with_decreased_likelihood_of | amyloid plaque deposition (MESH:D058225) |  | "Taken together, these findings support the role of SIRT3 in reducing amyloid plaque deposition through multiple pathways." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:affects | [[MME]] | direction=increased | "In the current study, treatment of wild type mice with NR resulted in the upregulation of Aβ degrading enzymes namely IDE (65%; P < 0.01), neprilysin (47%; P < 0.05)." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:affects | [[BACE1]] | direction=decreased | "In addition, the levels of BACE1 which generates Aβ decreased significantly (46%; P < 0.05; Fig. 6A,B)." |
| NAD+ (CHEBI:15846; MESH:D009243) | biolink:derives_from | [[Nicotinamide riboside]] (MESH:C018613) |  | "To increase the cellular content of NAD+ , its precursor, nicotinamide riboside (NR) is generally administered." |
| [[SIRT3]] | biolink:causes | [[Metabolic syndrome]] (MESH:D024821) |  | "Global silencing of Sirt3 gene is one of the approaches to induce MetS in animal models." |
| [[SIRT3]] | biolink:associated_with | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "Therefore, our findings suggest that Sirt3 deficiency as in MetS can exacerbate amyloid deposition in addition to interaction with AD through insulin resistance, mitochondrial dysfunction and neuroinflammation." |
| [[SIRT3]] | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "Therefore, our findings suggest that Sirt3 deficiency as in MetS can exacerbate amyloid deposition in addition to interaction with AD through insulin resistance, mitochondrial dysfunction and neuroinflammation." |
| [[SIRT3]] | biolink:associated_with | Amyloid pathology (MONDO:0019065) |  | "We observed modulation of genes in the metabolic and inflammatory pathways because of Sirt3 gene deletion, suggesting that MetS can interact with amyloid pathology in the brain." |
| [[SIRT3]] | biolink:contributes_to | Amyloid deposition (HP:0011034; MESH:D058225) |  | "Therefore, our findings suggest that Sirt3 deficiency as in MetS can exacerbate amyloid deposition in addition to interaction with AD through insulin resistance, mitochondrial dysfunction and neuroinflammation." |
| [[SIRT3]] | biolink:associated_with | [[Insulin resistance]] (MESH:D007333) |  | "Therefore, our findings suggest that Sirt3 deficiency as in MetS can exacerbate amyloid deposition in addition to interaction with AD through insulin resistance, mitochondrial dysfunction and neuroinflammation." |
| [[SIRT3]] | biolink:affects | [[CCL3]] | direction=decreased | "The chemokine CCL3 and complement protein C3 were induced significantly more in APP/PS1/Sirt3-/- mouse brain, compared to APP/PS1 mice, suggesting exacerbation of neuroinflammation in comorbid AD." |
| [[SIRT3]] | biolink:affects | [[C3]] | direction=decreased | "The chemokine CCL3 and complement protein C3 were induced significantly more in APP/PS1/Sirt3-/- mouse brain, compared to APP/PS1 mice, suggesting exacerbation of neuroinflammation in comorbid AD." |
| [[SIRT3]] | NOT biolink:affects | [[CST7]] |  | "However, the induction of cystatin F, CD83, Itgax and prion protein were comparable in APP/PS1 and APP/PS1/Sirt3-/- mouse brain sample." |
| [[SIRT3]] | NOT biolink:affects | [[CD83]] |  | "However, the induction of cystatin F, CD83, Itgax and prion protein were comparable in APP/PS1 and APP/PS1/Sirt3-/- mouse brain sample." |
| [[SIRT3]] | NOT biolink:affects | [[ITGAX]] |  | "However, the induction of cystatin F, CD83, Itgax and prion protein were comparable in APP/PS1 and APP/PS1/Sirt3-/- mouse brain sample." |
| [[SIRT3]] | NOT biolink:affects | [[PRNP]] |  | "However, the induction of cystatin F, CD83, Itgax and prion protein were comparable in APP/PS1 and APP/PS1/Sirt3-/- mouse brain sample." |
| [[Metabolic syndrome]] (MESH:D024821) | biolink:negatively_correlated_with | [[IDE]] |  | "Diet-induced MetS decreased SIRT3 and IDE in wild type as well as in Alzheimer’s background." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The upregulation of these genes seems to play significant roles in Aβ driven Alzheimer’s pathogenesis." |
| [[CCL3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The chemokine CCL3 and complement protein C3 were induced significantly more in APP/PS1/Sirt3-/- mouse brain, compared to APP/PS1 mice, suggesting exacerbation of neuroinflammation in comorbid AD." |
| [[C3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The chemokine CCL3 and complement protein C3 were induced significantly more in APP/PS1/Sirt3-/- mouse brain, compared to APP/PS1 mice, suggesting exacerbation of neuroinflammation in comorbid AD." |
| [[CST7]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The upregulation of these genes seems to play significant roles in Aβ driven Alzheimer’s pathogenesis." |
| [[CD83]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The upregulation of these genes seems to play significant roles in Aβ driven Alzheimer’s pathogenesis." |
| [[ITGAX]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "CD11C + microglia are known to be elevated in AD." |
| [[PRNP]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The upregulation of these genes seems to play significant roles in Aβ driven Alzheimer’s pathogenesis." |
| [[CCL3]] | biolink:biomarker_for | neuroinflammation (HP:0033429; MESH:D000090862) |  | "The chemokine CCL3 and complement protein C3 were induced significantly more in APP/PS1/Sirt3-/- mouse brain, compared to APP/PS1 mice, suggesting exacerbation of neuroinflammation in comorbid AD." |
| [[C3]] | biolink:biomarker_for | neuroinflammation (HP:0033429; MESH:D000090862) |  | "The chemokine CCL3 and complement protein C3 were induced significantly more in APP/PS1/Sirt3-/- mouse brain, compared to APP/PS1 mice, suggesting exacerbation of neuroinflammation in comorbid AD." |
| [[APP]] | biolink:associated_with | Amyloid pathology (MONDO:0019065) |  | "Subsequently, we generated a novel mouse model for comorbid AD, by silencing Sirt3 gene in APP/PS1 mice, an Alzheimer’s mouse model with amyloid pathology." |
| [[APP]] | biolink:has_phenotype | Amyloid deposition (HP:0011034; MESH:D058225) |  | "Subsequently, we generated a novel mouse model for comorbid AD, by silencing Sirt3 gene in APP/PS1 mice, an Alzheimer’s mouse model with amyloid pathology." |
| [[PSEN1]] | biolink:associated_with | Amyloid pathology (MONDO:0019065) |  | "Subsequently, we generated a novel mouse model for comorbid AD, by silencing Sirt3 gene in APP/PS1 mice, an Alzheimer’s mouse model with amyloid pathology." |
| [[PSEN1]] | biolink:has_phenotype | Amyloid deposition (HP:0011034; MESH:D058225) |  | "Subsequently, we generated a novel mouse model for comorbid AD, by silencing Sirt3 gene in APP/PS1 mice, an Alzheimer’s mouse model with amyloid pathology." |
| [[TYROBP]] | biolink:associated_with | Amyloid pathology (MONDO:0019065) |  | "Induction of some of the other genes may be a protective response to amyloid pathology." |
| SERPINA3 (HGNC:16) | biolink:associated_with | Amyloid pathology (MONDO:0019065) |  | "Induction of some of the other genes may be a protective response to amyloid pathology." |
| [[CLEC7A]] | biolink:associated_with | Amyloid pathology (MONDO:0019065) |  | "Induction of some of the other genes may be a protective response to amyloid pathology." |
| [[IDE]] | biolink:causes | [[Insulin resistance]] (MESH:D007333) |  | "IDE is involved in insulin homeostasis and its downregulation leads to insulin resistance." |
| [[IDE]] | biolink:affects | Insulin (CHEBI:145810; MESH:D007328) |  | "IDE is involved in insulin homeostasis and its downregulation leads to insulin resistance." |
| [[PRNP]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "Cellular production of neurotoxic Aβ is regulated by prion protein." |
| [[TYROBP]] | biolink:physically_interacts_with | [[TREM2]] |  | "Tyrobp is an adapter protein for TREM2 and it is considered as neuroprotective, Serpin3k plays an antioxidant role and Clec7a is a phagocytic marker in microglia." |
| [[SIRT3]] | biolink:associated_with_decreased_likelihood_of | amyloid plaques (MONDO:0010022; MESH:D058225) |  | "These findings suggest that SIRT3 activation can decrease Aβ generation by multiple mechanisms and explain the exacerbated amyloid plaque deposition observed in APP/PS1/Sirt3-/- mouse brain." |
| [[SIRT3]] | biolink:affects | PPARGC1A (HGNC:9237) | direction=increased | "Because Sirt3 induces the expression of PGC-1α, Sirt3 may play an indirect role in the transcription of IDE through a pathway involving PGC-1α and Nrf1." |
| [[Honokiol]] (MESH:C005499) | biolink:affects | [[SIRT3]] | direction=increased | "Honokiol, another activator of SIRT3 has been also shown to decrease BACE1 levels." |
| [[SIRT3]] | biolink:affects | STK11 (HGNC:11389) |  | "A network analysis based on 407 known substrates of SIRT3 has proposed a novel mechanism for SIRT3-induced BACE1 inhibition through SIRT3, LKB1, AMPK, CREB, PGC-1a, PPARG and BACE1." |
| [[IDE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Genetic variations in IDE have been shown to be associated with risk for late-onset AD." |
| [[IDE]] | biolink:physically_interacts_with | zinc (CHEBI:27363; MESH:D015032) |  | "IDE is a 110 kDa zinc metallo-endopeptidase that is known to degrade bioactive peptides including insulin, glucagon, amylin and Aβ peptide." |
| [[IDE]] | biolink:affects | glucagon (CHEBI:5391; MESH:D005934) | direction=decreased | "IDE is a 110 kDa zinc metallo-endopeptidase that is known to degrade bioactive peptides including insulin, glucagon, amylin and Aβ peptide." |
| [[IDE]] | biolink:affects | amylin (CHEBI:80342; MESH:D058228) | direction=decreased | "IDE is a 110 kDa zinc metallo-endopeptidase that is known to degrade bioactive peptides including insulin, glucagon, amylin and Aβ peptide." |
| Inositol phosphates (CHEBI:24846; MESH:D007295) | biolink:affects | [[IDE]] | direction=increased | "Inositol phosphates (InsPs) and phosphatdidyliinositol phosphates are potent activators of IDE." |
| phosphatidylinositol phosphates (CHEBI:28765; MESH:D018129) | biolink:affects | [[IDE]] | direction=increased | "Inositol phosphates (InsPs) and phosphatdidyliinositol phosphates are potent activators of IDE." |
| [[IDE]] | biolink:associated_with | varicella zoster virus infection (MONDO:0005700; MESH:D000073618) |  | "For example, IDE interacts with the glycoprotein (GE) from varicella zoster virus (VZV)." |
| [[IDE]] | biolink:physically_interacts_with | glucocorticoid receptor (HGNC:7978) |  | "The other non-proteolytic functions of IDE include interaction with glucocorticoid receptors and α-synuclein." |
| [[IDE]] | biolink:physically_interacts_with | SNCA (HGNC:11138) |  | "The other non-proteolytic functions of IDE include interaction with glucocorticoid receptors and α-synuclein." |
| SIRT4 (HGNC:14932) | biolink:physically_interacts_with | [[IDE]] |  | "SIRT4, another member of the sirtuin family has been shown to interact with IDE and this interaction appears to play a role in insulin secretion by β cells." |
| [[IDE]] | biolink:associated_with_decreased_likelihood_of | amyloid plaques (MONDO:0010022; MESH:D058225) |  | "Transgenic overexpression of IDE enhances the proteolysis of beta-amyloid and decrease plaque formation." |
| [[IDE]] | biolink:has_phenotype | [[Insulin resistance]] (MESH:D007333) |  | "These mice were also characterized by insulin resistance." |
| [[IDE]] | biolink:negatively_correlated_with | type 2 diabetes (MONDO:0005148; MESH:D003924) |  | "IDE expression decreases in a mouse model with AD and type 2 diabetes." |
| rosiglitazone (CHEBI:50122; MESH:D000077154) | biolink:affects | [[IDE]] | direction=increased | "IDE expression was restored following treatment with rosiglitazone and AICAR, activators of PPARɣ and AMPK." |
| AICAR (CHEBI:18406; MESH:C031143) | biolink:affects | [[IDE]] | direction=increased | "IDE expression was restored following treatment with rosiglitazone and AICAR, activators of PPARɣ and AMPK." |
| NRF1 (HGNC:7996) | biolink:regulates | [[IDE]] | direction=increased | "IDE promoter contains Nrf1 binding site." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:causes | amyloid plaques (MONDO:0010022; MESH:D058225) |  | "Aβ peptides released by the proteolytic action of α and β secretases on the transmembrane amyloid precursor protein (AAP), polymerize to generate Aβ oligomers, protofibrils and amyloid plaques." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:causes | neurotoxicity (MONDO:0005527) |  | "Excessive generations of Aβ oligomers and Aβ fibrils cause neurotoxicity in the AD brain." |
| [[BACE1]] | biolink:affects | [[APP]] |  | "Aβ peptides released by the proteolytic action of α and β secretases on the transmembrane amyloid precursor protein (AAP), polymerize to generate Aβ oligomers, protofibrils and amyloid plaques." |
| rosiglitazone (CHEBI:50122; MESH:D000077154) | biolink:affects | [[PPARG]] | direction=increased | "IDE expression was restored following treatment with rosiglitazone and AICAR, activators of PPARɣ and AMPK." |
| AICAR (CHEBI:18406; MESH:C031143) | biolink:affects | PRKAA1 (HGNC:9376) | direction=increased | "IDE expression was restored following treatment with rosiglitazone and AICAR, activators of PPARɣ and AMPK." |
| PPARGC1A (HGNC:9237) | biolink:regulates | [[PPARG]] |  | "A network analysis based on 407 known substrates of SIRT3 has proposed a novel mechanism for SIRT3-induced BACE1 inhibition through SIRT3, LKB1, AMPK, CREB, PGC-1a, PPARG and BACE1." |
| [[PPARG]] | biolink:regulates | [[BACE1]] | direction=decreased | "A network analysis based on 407 known substrates of SIRT3 has proposed a novel mechanism for SIRT3-induced BACE1 inhibition through SIRT3, LKB1, AMPK, CREB, PGC-1a, PPARG and BACE1." |
| PRKAA1 (HGNC:9376) | biolink:regulates | PPARGC1A (HGNC:9237) |  | "A network analysis based on 407 known substrates of SIRT3 has proposed a novel mechanism for SIRT3-induced BACE1 inhibition through SIRT3, LKB1, AMPK, CREB, PGC-1a, PPARG and BACE1." |
| STK11 (HGNC:11389) | biolink:regulates | PRKAA1 (HGNC:9376) |  | "A network analysis based on 407 known substrates of SIRT3 has proposed a novel mechanism for SIRT3-induced BACE1 inhibition through SIRT3, LKB1, AMPK, CREB, PGC-1a, PPARG and BACE1." |
| NRF1 (HGNC:7996) | biolink:associated_with | NFE2L2 (HGNC:7782) |  | "Nrf1, together with Nrf2, mediates the coordination between nuclear and mitochondrial genomes." |
| PPARGC1A (HGNC:9237) | biolink:regulates | NRF1 (HGNC:7996) | direction=increased | "Nrf1 in turn is induced by PGC-1α." |
| NRF1 (HGNC:7996) | biolink:affects | DNA (CHEBI:16991; MESH:D004247) | direction=increased | "It is also required for mitochondrial respiration, and mitochondrial DNA transcription and replication." |
| [[Honokiol]] (MESH:C005499) | biolink:affects | [[BACE1]] | direction=decreased | "Honokiol, another activator of SIRT3 has been also shown to decrease BACE1 levels." |
| [[IDE]] | biolink:affects | INS (HGNC:6081) | direction=decreased | "Inhibition of IDE activity with a small molecule, was shown to result in glucose intolerance suggesting a physiological role for IDE in insulin clearance." |
| [[IDE]] | biolink:contributes_to | type 2 diabetes (MONDO:0005148; MESH:D003924) |  | "Goto-Kakizaki rat model for T2D is characterized by altered insulin degradation due to mutations in IDE gene." |
| [[IDE]] | biolink:associated_with | diabetes (MONDO:0005015; MESH:D003920) |  | "An increase in plasma IDE activity has been reported in both types of diabetes." |
| [[IDE]] | biolink:causes | Glucose intolerance (HP:0001952; MESH:D018149) |  | "Mutations in IDE gene leads to glucose intolerance and hyperinsulinemia." |
| [[IDE]] | biolink:causes | Hyperinsulinemia (HP:0000842; MESH:D006946) |  | "Mutations in IDE gene leads to glucose intolerance and hyperinsulinemia." |
| Glucose (CHEBI:17234; MESH:D005947) | biolink:affects | INS (HGNC:6081) | direction=increased | "Constitutive insulin secretion is observed in IDE-KO mice, suggesting that IDE is required for the regulation of glucose-stimulated insulin secretion." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:treats | type 2 diabetes (MONDO:0005148; MESH:D003924) |  | "NR has been reported to reverse insulin resistance and glucose intolerance in a mouse model for type 2 diabetes." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Therefore, NR-based treatment can be considered for the treatment of AD with comorbidities." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:treats | Glucose intolerance (HP:0001952; MESH:D018149) |  | "NR has been reported to reverse insulin resistance and glucose intolerance in a mouse model for type 2 diabetes." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:treats | [[Insulin resistance]] (MESH:D007333) |  | "NR has been reported to reverse insulin resistance and glucose intolerance in a mouse model for type 2 diabetes." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:treats | neuroinflammation (HP:0033429; MESH:D000090862) |  | "NR has been shown to be effective in reducing neuroinflammation and improve cognition in Alzheimer’s mouse models." |
| [[Nicotinamide riboside]] (MESH:C018613) | biolink:treats | cognitive impairment (HP:0100543; MESH:D060825) |  | "NR has been shown to be effective in reducing neuroinflammation and improve cognition in Alzheimer’s mouse models." |
