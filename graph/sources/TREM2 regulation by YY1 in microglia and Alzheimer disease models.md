---
type: source
title: "TREM2 regulation by YY1 in microglia and Alzheimer disease models"
paper_title: "Regulation of TREM2 expression by transcription factor YY1 and its protective effect against Alzheimer’s disease"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000109
pmid: "37044212"
pmcid: "PMC10193014"
doi: "10.1016/j.jbc.2023.104688"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC10193014/"
sources: ["[[.raw/01M4DY94GKWQWQ78H9BCA80AZC/normalized.md]]"]
tags: [microglia, transcription-factor, neuroinflammation]
---

# TREM2 regulation by YY1 in microglia and Alzheimer disease models

A promoter-level study of what switches on [[TREM2]], the microglial receptor whose rare loss-of-function variants raise the risk of [[Alzheimer disease]]. The authors map the human TREM2 promoter, identify the transcription factor [[YY1]] as a binder of its core region, and show that knocking YY1 down lowers TREM2 in two mouse cell lines, while both proteins fall after inflammatory challenge and in an amyloid mouse model.

## Design

- Promoter mapping: a 983-bp stretch upstream of the transcription start site and a series of 5' deletions (pTREM2-A to G) were cloned into a firefly luciferase vector and read out against a co-transfected Renilla control in [[BV2]] microglial cells and [[HEK293]] cells. See [[Promoter mapping and transcription factor binding assays]].
- Factor identification: biotinylated promoter fragments (-370 to +33 versus -118 to +33) pulled down proteins from BV2 nuclear extract for mass spectrometry, intersected with predictions from the online tool PROMO.
- Binding confirmation: electrophoretic mobility shift assay (EMSA) with a 25-bp probe carrying the predicted element, with cold wild-type and mutant competitors, plus a combined EMSA and Western blot because no antibody worked for supershift or immunoprecipitation.
- Function: a mutant promoter reporter, shRNA silencing of YY1 followed by reporter and immunoblot readouts in BV2 and [[Neuro2a]] cells.
- Inflammation and disease models: BV2 cells treated overnight with 2 μg/ml [[Lipopolysaccharide]], and brain lysates from 3-4 month old [[APP-PS45 mouse]] animals against age- and sex-matched wild type (six per group). Statistics were one-way or two-way ANOVA and Student's t test.

## Findings

- Promoter activity: the longest fragments (-983 and -671 to +33) were about as active as empty vector; -580 to +33 gave a 2.7-fold rise and -370 to +33 (pTREM2-D) a 6.4-fold rise in BV2. Cutting further to -118 abolished activity. The authors infer a repressive element between -580 and -370 and a strong activating element between -370 and -118; HEK293 cells behaved similarly.
- YY1 as the binder: YY1 was the only transcription factor found by both the pull-down mass spectrometry and PROMO. Its predicted site (CCATCTG at -254 to -248) is found in a similar position in eight other species, which the authors take as evolutionary conservation.
- Binding in vitro: the wild-type probe formed a shifted complex with BV2 nuclear extract that was partly competed by a 1x and fully competed by a 5x excess of unlabeled probe; a mutant site (CCATCTG changed to GGGGCTG) did not compete. EMSA followed by Western blot placed YY1 in the shifted band. Longer upstream fragments pulled down YY1 about as well as -370 to +33, so their weak reporter activity is not explained by lost YY1 binding and may reflect other repressive elements.
- Function: mutating the site cut pTREM2-D activity by about 53%, and YY1 shRNA cut it by about 45%. Endogenous YY1 fell by only about 30% in BV2, with TREM2 protein falling by a similar amount; in Neuro2a, YY1 and TREM2 both fell by more than 70%.
- Inflammation and disease: LPS lowered both YY1 and TREM2 in BV2. In APP-PS45 brain, YY1 was about 39% and TREM2 about 49% lower than in wild type. Overexpressing YY1 in LPS-treated BV2 cells gave only marginal TREM2 recovery (data not shown, weak expression).
- Interpretation offered: microglial YY1 supports TREM2 expression, and keeping YY1 activity up could preserve TREM2 function against Alzheimer disease; YY1 is also reported to raise TREM2 indirectly through microRNA.

## Why This Source Matters

Genetics shows that losing TREM2 function raises Alzheimer risk, but little was known about what controls TREM2 expression in non-carriers. This paper offers a concrete regulatory handle, a conserved YY1 element in the TREM2 core promoter, and ties its loss to the two situations where TREM2 is known to fall (inflammation and amyloid pathology). It also frames lowered TREM2 as an expression problem as well as a coding-variant problem, which widens the set of people for whom the pathway could matter.

## Assessment

- The causal chain is shown only in part. Promoter mutation and shRNA knock-down link YY1 to TREM2 in cell lines, but the in vivo evidence is correlative (both proteins lower in one transgenic model), and the rescue by YY1 overexpression under LPS failed or was too weak to interpret.
- Direct occupancy of the native promoter in cells (for example by chromatin immunoprecipitation) was not shown; binding rests on in vitro pull-down and EMSA, and no antibody was usable for supershift.
- Knock-down in BV2 was modest (about 30%), and the human promoter was tested in mouse and human cell lines; the second knock-down line, Neuro2a, is a neuroblastoma rather than a microglial line. TREM2 mRNA was not reported, only protein and reporter activity.
- Whole-brain lysates from one transgenic line at one age mix cell types, so a microglial YY1 change is inferred rather than measured. The text also contains small inconsistencies in the fragment and lane numbering.

## Open Questions

- Does restoring YY1 selectively in microglia of an amyloid mouse model raise TREM2 and improve amyloid clearance (not tested; overexpression in BV2 was too weak to interpret)?
- Does YY1 occupy the TREM2 promoter in intact microglia, for example by chromatin immunoprecipitation (only in vitro pull-down and EMSA were used because no antibody worked for immunoprecipitation)?
- What are the repressive elements between -580 and -370 of the TREM2 promoter, and which factors bind them?
- Is the fall in YY1 in Alzheimer brain a cause or a consequence of inflammation and amyloid pathology (both proteins were only measured together at one time point)?

## Connections

- Entities: [[TREM2]], [[YY1]], [[Lipopolysaccharide]]; cell and animal models [[BV2]], [[Neuro2a]], [[HEK293]], [[APP-PS45 mouse]].
- Disease context: [[Alzheimer disease]]; TREM2 is cleaved by [[ADAM10]] and [[ADAM17]] to soluble TREM2, and its microglial functions include phagocytosis of amyloid beta from [[APP]] (see [[Amyloid-beta formation]]).
- Method: [[Promoter mapping and transcription factor binding assays]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[YY1]] | biolink:regulates | [[TREM2]] | direction=increased | "shRNA-mediated YY1 silencing significantly reduced the activity of the TREM2 minimal promoter and TREM2 protein levels in the microglial cell line BV2 and the neuroblastoma Neuro2A." |
| [[TREM2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "TREM2 encoding the transmembrane receptor protein TREM2 is a risk gene of Alzheimer’s disease (AD), and the impairment of TREM2 functions in microglia due to mutations in TREM2 may significantly increase the risk of AD by promoting AD pathologies." |
| [[TREM2]] | biolink:directly_physically_interacts_with | TYROBP (HGNC:12449) |  | "Upon its binding with extracellular ligands on the plasma membrane, TREM2 initiates downstream signaling cascades through its cytoplasmic binding protein TYROBP (or DAP12) and is as such involved in a variety of cellular functions." |
| [[ADAM10]] | biolink:affects | [[TREM2]] |  | "TREM2 can be cleaved by ADAM10 and ADAM17 in the extracellular/intraluminal domain to release the C terminally truncated soluble TREM2 (sTREM2) into the interstitial or cerebrospinal fluid in the brain." |
| [[ADAM17]] | biolink:affects | [[TREM2]] |  | "TREM2 can be cleaved by ADAM10 and ADAM17 in the extracellular/intraluminal domain to release the C terminally truncated soluble TREM2 (sTREM2) into the interstitial or cerebrospinal fluid in the brain." |
| TNF (HGNC:11892) | biolink:affects | [[TREM2]] | direction=decreased | "In vitro studies in microglial cells demonstrated that the expression of TREM2 is decreased by proinflammatory agents such as TNFα, IL1β, IFNγ, and lipopolysaccharide (LPS) (, )." |
| IL1B (HGNC:5992) | biolink:affects | [[TREM2]] | direction=decreased | "In vitro studies in microglial cells demonstrated that the expression of TREM2 is decreased by proinflammatory agents such as TNFα, IL1β, IFNγ, and lipopolysaccharide (LPS) (, )." |
| IFNG (HGNC:5438) | biolink:affects | [[TREM2]] | direction=decreased | "In vitro studies in microglial cells demonstrated that the expression of TREM2 is decreased by proinflammatory agents such as TNFα, IL1β, IFNγ, and lipopolysaccharide (LPS) (, )." |
| [[Lipopolysaccharide]] (MESH:D008070) | biolink:affects | [[TREM2]] | direction=decreased | "In vitro studies in microglial cells demonstrated that the expression of TREM2 is decreased by proinflammatory agents such as TNFα, IL1β, IFNγ, and lipopolysaccharide (LPS) (, )." |
| [[YY1]] | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, we found that the levels of TREM2 and YY1 were both downregulated in lipopolysaccharide-treated BV2 cells and in the brain of AD model mice." |
| [[Lipopolysaccharide]] (MESH:D008070) | biolink:affects | [[YY1]] | direction=decreased | "Furthermore, we found that the levels of TREM2 and YY1 were both downregulated in lipopolysaccharide-treated BV2 cells and in the brain of AD model mice." |
| [[YY1]] | biolink:directly_physically_interacts_with | DNA (CHEBI:16991; MESH:D004247) |  | "By luciferase assay, DNA pull-down, and in silico predictions, we identified Yin Yang 1(YY1) as a binding protein of the minimal promoter of the TREM2 gene, and the binding was further confirmed by EMSA and DNA pull-down assay." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The extracellular neuritic plaque with the amyloid protein (Aβ) as the major component and intracellular fibrillary tangle formed by the aggregation of hyperphosphorylated tau protein are the characteristic neuropathologies of AD." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The extracellular neuritic plaque with the amyloid protein (Aβ) as the major component and intracellular fibrillary tangle formed by the aggregation of hyperphosphorylated tau protein are the characteristic neuropathologies of AD." |
| TREM2 p.Arg47His (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The carriers of the best characterized p.Arg47His in TREM2 are 2.83 times more prone to AD, although the association is only confirmed in European population." |
| [[APP]] | biolink:associated_with | neuritic plaque (MESH:D058225) |  | "The extracellular neuritic plaque with the amyloid protein (Aβ) as the major component and intracellular fibrillary tangle formed by the aggregation of hyperphosphorylated tau protein are the characteristic neuropathologies of AD." |
| [[YY1]] | biolink:physically_interacts_with | DNA (CHEBI:16991; MESH:D004247) |  | "Different DNA fragments 5′ to the transcriptional starting site of TREM2 were used to pull-down YY1 in nuclear extracts." |
| [[YY1]] | biolink:physically_interacts_with | oligonucleotides (CHEBI:7754; MESH:D009841) |  | "Lane 2 indicates a shifted DNA–protein complex band formed by incubation of BV2 nuclear extract and labeled YY1 probe." |
| biotin (CHEBI:15956; MESH:D001710) | biolink:directly_physically_interacts_with | streptavidin (CHEBI:201453; MESH:D019809) |  | "F, before and after incubation of probes and streptavidin magnetic beads, the amounts of probes were measured by agarose gel to verify the binding efficiency, and the beads were used for YY1 pull-down from nuclear extract as in (G)." |
| [[TREM2]] | biolink:affects | [[APP]] | direction=decreased | "Our results suggested that YY1 may directly promote TREM2 expression in microglia, which in turn enhances the clearance of Aβ, suppresses the immune responses, and maintains the cell homeostasis of microglia." |
| [[TREM2]] | biolink:negatively_correlated_with | neuroinflammation (HP:0033429; MESH:D007249) |  | "In microglia, the major cell type in the brain to express TREM2, TREM2 participates in multiple cellular functions such as mediating the phagocytosis of Aβ, suppressing the inflammatory, and orchestrating lipid metabolism." |
| [[YY1]] | biolink:affects | [[APP]] | direction=increased | "Some studies suggested that YY1 in neurons may increase Aβ by regulating the expression of proteins directly and indirectly involved in Aβ production." |
| [[YY1]] | biolink:negatively_correlated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Moreover, YY1 was also found to be reduced in the brains of patients with other neurodegenerative disease." |
| [[YY1]] | biolink:negatively_correlated_with | neuroinflammation (HP:0033429; MESH:D007249) |  | "We found that YY1 in BV2 is decreased by LPS, a condition to simulate neuroinflammation that is common for almost all neurodegenerative diseases." |
| [[Lipopolysaccharide]] (MESH:D008070) | biolink:causes | neuroinflammation (HP:0033429; MESH:D007249) |  | "It has been well established that TREM2 in microglia is downregulated by the inflammation eliciting agent LPS (, )." |
| TREM2 sequence variants (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The mutations/SNPs in TREM2 correlated to AD may blunt some of these functions and as such increase the risk of AD." |
