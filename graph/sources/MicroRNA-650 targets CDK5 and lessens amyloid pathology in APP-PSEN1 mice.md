---
type: source
title: "MicroRNA-650 targets CDK5 and lessens amyloid pathology in APP-PSEN1 mice"
paper_title: "MicroRNA-650 Regulates the Pathogenesis of Alzheimer’s Disease Through Targeting Cyclin-Dependent Kinase 5"
domain: neuroscience
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001277
pmid: "36656459"
pmcid: "PMC10039829"
doi: "10.1007/s12035-023-03224-y"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC10039829/"
sources: ["[[.raw/01M4P89VANX2S5SH3J814SCR0Y/normalized.md]]"]
tags: [microrna, mouse-model, kinase]
---

# MicroRNA-650 targets CDK5 and lessens amyloid pathology in APP-PSEN1 mice

A full-text study from Emory University of one microRNA, [[MIR650]] (miR-650), in [[Alzheimer disease]]. The authors profiled microRNAs in post-mortem human brain, found miR-650 the most raised, tested whether it represses three Alzheimer genes ([[APOE]], [[PSEN1]] and [[CDK5]]) in cultured cells, and then raised it in the hippocampus of [[APP-PS1 mouse]] animals.

## Findings

- **Human brain.** TaqMan profiling of 204 mature microRNAs in superior frontal (Brodmann area 9) and paracalcarine (area 17) cortex from 16 controls and 18 Alzheimer cases (NIA/AA criteria, post-mortem interval up to 8 h, age 65 or older) found 17 raised in Alzheimer samples (p < 0.05). miR-650 was the most significant (p = 0.00236).
- **Processing.** Mature miR-650 was raised, but its primary and precursor transcripts were lower in Alzheimer cases (p < 0.01), which the authors read as altered conversion of primary to mature miR-650 (see [[miRNA processing]]). Mature miR-650 comes from the 5-prime strand of its precursor.
- **Targets.** TargetScan predicted miR-650 sites in the 3'-UTRs of APOE, PSEN1 and CDK5. In a dual-luciferase reporter assay in [[HEK293]]-type cells, miR-650 duplex (2.5 nM) lowered reporter activity for all three 3'-UTRs relative to a miR-572 negative control, and deleting the predicted site in each 3'-UTR abolished the effect (see [[miRNA binding]]).
- **In vivo.** An AAV carrying GFP-miR-650 was injected into the right dentate gyrus and an AAV-GFP control into the left dentate gyrus of 1-year-old APP/PSEN1 mice (APP Swedish plus PSEN1 Δexon 9). One month later the miR-650 side showed more miR-650, and CDK5 protein and transcript were lower (p < 0.01).
- **Pathology.** On the miR-650 side there were fewer beta-amyloid-immunoreactive plaques, lower [[Amyloid-beta]] by ELISA (kit for Aβ40; p < 0.05, n = 3), and more MAP2-positive cells in the dentate gyrus (p < 0.05, n = 3), which the authors take as relief of neuronal deficit (see [[Neuronal loss]]).
- **Conclusion drawn.** A miR-650 to CDK5 axis shapes Alzheimer pathology; the authors suggest miR-650 as a target for antisense oligonucleotide therapy. The CDK5/p25 complex hyperphosphorylates tau (see [[Tau hyperphosphorylation]]).

## Assessment

- The in vivo group is small: virus injection is described as n = 5 mice in the results text but quantification as n = 3 per group; only the CDK5 effect is shown in vivo, while APOE and PSEN1 were tested only in reporter assays.
- Each mouse is its own control (left versus right hippocampus), which removes between-animal variation but not a possible side effect of the two injections; the vector-matched GFP control is reasonable.
- No experiment ties the plaque and neuron changes to CDK5 itself (no CDK5 rescue or knockdown), and a lower PSEN1 or APOE could also contribute, so "through CDK5" is inferred. No tau phosphorylation, behaviour or cell-type data were reported.
- miR-650 is raised in Alzheimer brain yet its overexpression in mice is protective; the paper does not explain this, and an early compensatory rise is one possible reading. The brain-region effect and cell-type source of the rise are not shown.
- The Aβ ELISA kit named is for Aβ40 while the immunostaining used an Aβ1-42 antibody. The reporter assays are said to use HEK293 cells in the text while the 3'-UTRs were amplified from 293FT cells.
- Controls and cases came from a single archive (Emory ADRC); the age, sex and APOE genotype tables were not reproduced in the text available.

## Why This Source Matters

It is a worked example of a microRNA that is raised in Alzheimer brain, represses a tau kinase (CDK5) and, when raised further in an amyloid mouse, lowers plaque and amyloid load. It puts CDK5, a kinase usually studied for tau, upstream of amyloid pathology through a post-transcriptional route, and it names a candidate for antisense-oligonucleotide-style therapy.

## Open Questions

- Does miR-650 overexpression still lower plaques and raise neuron numbers when CDK5 is restored (no CDK5 rescue was done; the in vivo link rests on correlation of CDK5 loss with pathology)?
- Does miR-650 lower APOE and PSEN1 protein in mouse hippocampus, as it does in reporter assays (only CDK5 was measured in vivo)?
- Why is mature miR-650 raised in Alzheimer brain while its primary and precursor forms are lower (processing enzymes such as Drosha and Dicer were not measured)?
- Does AAV-miR-650 change tau phosphorylation or memory performance in APP/PSEN1 mice (neither was assessed)?
- Which brain cell types express the raised miR-650 in Alzheimer cortex (bulk tissue only was profiled)?

## Connections

- Genes: [[MIR650]], [[CDK5]], [[APOE]], [[PSEN1]], [[DICER1]]
- Model and cells: [[APP-PS1 mouse]], [[HEK293]]
- Process and activity: [[miRNA processing]], [[miRNA binding]]
- Phenotype and chemical: [[Neuronal loss]], [[Amyloid-beta]]
- Disease context: [[Alzheimer disease]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[MIR650]] | biolink:regulates | [[CDK5]] | direction=decreased | "Bioinformatic analysis predicted that miR-650 targets the expression of three AD-associated components: Apolipoprotein E (APOE), Presenilin 1 (PSEN1), and Cyclin-Dependent Kinase 5 (CDK5), and we have experimentally confirmed that miR-650 is able to significantly reduce the expression of APOE, PSEN1, and CDK5 in vitro." |
| [[MIR650]] | biolink:regulates | [[APOE]] | direction=decreased | "Bioinformatic analysis predicted that miR-650 targets the expression of three AD-associated components: Apolipoprotein E (APOE), Presenilin 1 (PSEN1), and Cyclin-Dependent Kinase 5 (CDK5), and we have experimentally confirmed that miR-650 is able to significantly reduce the expression of APOE, PSEN1, and CDK5 in vitro." |
| [[MIR650]] | biolink:regulates | [[PSEN1]] | direction=decreased | "Bioinformatic analysis predicted that miR-650 targets the expression of three AD-associated components: Apolipoprotein E (APOE), Presenilin 1 (PSEN1), and Cyclin-Dependent Kinase 5 (CDK5), and we have experimentally confirmed that miR-650 is able to significantly reduce the expression of APOE, PSEN1, and CDK5 in vitro." |
| [[MIR650]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Here, we show that the expression of microRNA 650 (miR-650) is altered in brains from AD patients." |
| [[CDK5]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Bioinformatic analysis predicted that miR-650 targets the expression of three AD-associated components: Apolipoprotein E (APOE), Presenilin 1 (PSEN1), and Cyclin-Dependent Kinase 5 (CDK5), and we have experimentally confirmed that miR-650 is able to significantly reduce the expression of APOE, PSEN1, and CDK5 in vitro." |
| [[CDK5]] | biolink:contributes_to | [[Neuronal loss]] |  | "For instance, inhibition of CDK5 appears to protect β-amyloid-induced neuronal cell death; treatment with therapeutic concentration of a glycogen synthase kinase inhibitor blocked the generation of β-amyloid peptides." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Bioinformatic analysis predicted that miR-650 targets the expression of three AD-associated components: Apolipoprotein E (APOE), Presenilin 1 (PSEN1), and Cyclin-Dependent Kinase 5 (CDK5), and we have experimentally confirmed that miR-650 is able to significantly reduce the expression of APOE, PSEN1, and CDK5 in vitro." |
| [[PSEN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Bioinformatic analysis predicted that miR-650 targets the expression of three AD-associated components: Apolipoprotein E (APOE), Presenilin 1 (PSEN1), and Cyclin-Dependent Kinase 5 (CDK5), and we have experimentally confirmed that miR-650 is able to significantly reduce the expression of APOE, PSEN1, and CDK5 in vitro." |
| [[BACE1]] | biolink:affects | [[APP]] |  | "The processing of amyloid precursor protein (APP) to Aβ is catalyzed by β-secretase and γ-secretase complex sequentially, and the resultant cleaved short forms of Aβ can then self-aggregate to form amyloid plaques." |
| [[MAPT]] | biolink:associated_with | neurofibrillary tangles (HP:0002185) |  | "Although the etiology of AD is still rather vague, multiple neuropathological hallmarks of AD have been characterized, including insoluble, extracellular aggregates of amyloid-β peptides (Aβ), named amyloid plaques, and intracellular accumulations of hyperphosphorylated microtubule-associated protein tau, named neurofibrillary tangles (NFTs), as well as neuronal loss." |
| DROSHA (HGNC:17904) | biolink:affects | RNA (CHEBI:33697; MESH:D012313) |  | "Transcribed primary miRNAs (pri-miRNAs) are processed by Drosha in the nucleus, and the resulting precursor miRNAs (pre-miRNAs) are exported to the cytoplasm where they are further processed by Dicer to generate mature miRNAs." |
| [[DICER1]] | biolink:affects | RNA (CHEBI:33697; MESH:D012313) |  | "Transcribed primary miRNAs (pri-miRNAs) are processed by Drosha in the nucleus, and the resulting precursor miRNAs (pre-miRNAs) are exported to the cytoplasm where they are further processed by Dicer to generate mature miRNAs." |
| [[BACE1]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "The processing of amyloid precursor protein (APP) to Aβ is catalyzed by β-secretase and γ-secretase complex sequentially, and the resultant cleaved short forms of Aβ can then self-aggregate to form amyloid plaques." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Although the etiology of AD is still rather vague, multiple neuropathological hallmarks of AD have been characterized, including insoluble, extracellular aggregates of amyloid-β peptides (Aβ), named amyloid plaques, and intracellular accumulations of hyperphosphorylated microtubule-associated protein tau, named neurofibrillary tangles (NFTs), as well as neuronal loss." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | [[Neuronal loss]] |  | "For instance, inhibition of CDK5 appears to protect β-amyloid-induced neuronal cell death; treatment with therapeutic concentration of a glycogen synthase kinase inhibitor blocked the generation of β-amyloid peptides." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:causes | amyloid plaques (HP:0100256; MESH:D058225) |  | "The processing of amyloid precursor protein (APP) to Aβ is catalyzed by β-secretase and γ-secretase complex sequentially, and the resultant cleaved short forms of Aβ can then self-aggregate to form amyloid plaques." |
| [[MIR650]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "MiR-650 stood out as the most significantly increased one among 17 miRNAs (p = 0.00236, Table 2)." |
| [[APOE]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Using bioinformatic analyses, we determined that miR-650, one of these altered miRNAs, was likely to bind to APOE, PSEN1, and CDK5, genes involved in AD pathogenesis." |
| [[PSEN1]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Using bioinformatic analyses, we determined that miR-650, one of these altered miRNAs, was likely to bind to APOE, PSEN1, and CDK5, genes involved in AD pathogenesis." |
| [[CDK5]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Using bioinformatic analyses, we determined that miR-650, one of these altered miRNAs, was likely to bind to APOE, PSEN1, and CDK5, genes involved in AD pathogenesis." |
| [[MIR650]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=decreased | "Over-expression of miR-650 could also ameliorate neuronal deficits in these AD mice as evidenced by a decrease in the number of plaques and decreased Aβ levels." |
| [[MIR650]] | biolink:negatively_correlated_with | amyloid plaques (HP:0100256; MESH:D058225) |  | "Over-expression of miR-650 could also ameliorate neuronal deficits in these AD mice as evidenced by a decrease in the number of plaques and decreased Aβ levels." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:positively_correlated_with | amyloid plaques (HP:0100256; MESH:D058225) |  | "Over-expression of miR-650 could also ameliorate neuronal deficits in these AD mice as evidenced by a decrease in the number of plaques and decreased Aβ levels." |
| [[PSEN1]] | biolink:associated_with | early onset Alzheimer disease (MESH:D000544) |  | "APP/PSEN1 double transgenic mice contain mutant forms of APP and PSEN1 that are associated with early onset AD." |
| [[APP]] | biolink:associated_with | early onset Alzheimer disease (MESH:D000544) |  | "APP/PSEN1 double transgenic mice contain mutant forms of APP and PSEN1 that are associated with early onset AD." |
| [[MIR650]] | biolink:regulates | ING4 (HGNC:19423) |  | "Several targets of miRNA-650 have been identified, including ING4, CDK1, AKT2, EBF3, and other factors." |
| [[MIR650]] | biolink:regulates | [[CDK1]] |  | "Several targets of miRNA-650 have been identified, including ING4, CDK1, AKT2, EBF3, and other factors." |
| [[MIR650]] | biolink:regulates | AKT2 (HGNC:392) |  | "Several targets of miRNA-650 have been identified, including ING4, CDK1, AKT2, EBF3, and other factors." |
| [[MIR650]] | biolink:regulates | EBF3 (HGNC:19087) |  | "Several targets of miRNA-650 have been identified, including ING4, CDK1, AKT2, EBF3, and other factors." |
| [[MIR650]] | biolink:associated_with | cancer (MONDO:0004992; MESH:D009369) |  | "Irregular expression of miR-650 has been well documented in multiple types of human cancer." |
| [[MIR650]] | biolink:associated_with | [[Neurodegeneration]] |  | "These results suggest miR-650 is actively involved in neurodegeneration through modulating CDK5." |
| [[MIR650]] | biolink:associated_with_decreased_likelihood_of | amyloid plaques (HP:0100256; MESH:D058225) |  | "By manipulating CDK5 expression via overexpression of miR-650 in an AD mouse model, we showed that reduced plaques and Aβ presence in the brain." |
| [[CDK5]] | biolink:physically_interacts_with | [[CDK5R1]] |  | "The CDK5/p25 complex hyperphosphorylates Tau and leads to irreversible cytoskeletal disruption of neuronal cells and induced neuronal cell death." |
| [[CDK5]] | biolink:affects | [[MAPT]] | direction=increased | "The CDK5/p25 complex hyperphosphorylates Tau and leads to irreversible cytoskeletal disruption of neuronal cells and induced neuronal cell death." |
| [[CDK5]] | biolink:associated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Previous studies have demonstrated that CDK5 activity is increased in several different neurodegenerative diseases including AD, animal models of amyotrophic lateral sclerosis (ALS) and Niemann Pick type C (NPC) disease." |
| [[CDK5]] | biolink:associated_with | amyotrophic lateral sclerosis (MONDO:0004976; MESH:D000690) |  | "Previous studies have demonstrated that CDK5 activity is increased in several different neurodegenerative diseases including AD, animal models of amyotrophic lateral sclerosis (ALS) and Niemann Pick type C (NPC) disease." |
| [[CDK5]] | biolink:associated_with | Niemann-Pick disease type C (MONDO:0018982; MESH:D052556) |  | "Previous studies have demonstrated that CDK5 activity is increased in several different neurodegenerative diseases including AD, animal models of amyotrophic lateral sclerosis (ALS) and Niemann Pick type C (NPC) disease." |
| [[CDK5]] | biolink:contributes_to | [[Neurodegeneration]] |  | "The CDK5/p25 complex hyperphosphorylates Tau and leads to irreversible cytoskeletal disruption of neuronal cells and induced neuronal cell death." |
| [[CDK5]] | biolink:positively_correlated_with | amyloid plaques (HP:0100256; MESH:D058225) |  | "By manipulating CDK5 expression via overexpression of miR-650 in an AD mouse model, we showed that reduced plaques and Aβ presence in the brain." |
| [[CDK5R1]] | biolink:affects | [[MAPT]] | direction=increased | "The CDK5/p25 complex hyperphosphorylates Tau and leads to irreversible cytoskeletal disruption of neuronal cells and induced neuronal cell death." |
| [[CDK5R1]] | biolink:contributes_to | [[Neurodegeneration]] |  | "The CDK5/p25 complex hyperphosphorylates Tau and leads to irreversible cytoskeletal disruption of neuronal cells and induced neuronal cell death." |
| antisense oligonucleotides (CHEBI:7754; MESH:D016376) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "On this regard, new methodological advances of AD therapy have developed short and synthetic antisense oligonucleotides (ASOs), that recognize target mRNA for posttranscriptional regulation to correct protein expression errors." |
| antisense oligonucleotides (CHEBI:7754; MESH:D016376) | biolink:physically_interacts_with | mRNA (CHEBI:33699; MESH:D012333) |  | "On this regard, new methodological advances of AD therapy have developed short and synthetic antisense oligonucleotides (ASOs), that recognize target mRNA for posttranscriptional regulation to correct protein expression errors." |
