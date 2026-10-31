---
type: source
title: "6-Gingerol from ginger screened for Alzheimer disease by docking and dynamics"
paper_title: "Screening of Active Substances Regulating Alzheimer’s Disease in Ginger and Visualization of the Effectiveness on 6-Gingerol Pathway Targets"
domain: pharmacology
status: developing
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001236
pmid: "38397589"
pmcid: "PMC10888025"
doi: "10.3390/foods13040612"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC10888025/"
sources: ["[[.raw/01M4P89VA1XK3DB0VJ6NG3A0ET/normalized.md]]"]
tags: [herbal-medicine, natural-product, in-silico, drug-target]
---

# 6-Gingerol from ginger screened for Alzheimer disease by docking and dynamics

A computational screen of the constituents of [[Zingiber officinale]] (ginger) for [[Alzheimer disease]]. Public databases give ginger compounds and Alzheimer-related genes; their overlap is analysed by enrichment and a protein interaction network, one compound, [[6-Gingerol]], is chosen with the help of a small [[PC12]] cell test, and its binding to four proteins is checked by [[Molecular docking]] and 100 ns [[Molecular dynamics simulation]]. It is an example of [[Network pharmacology with multi-omics for herbal medicines]] without the omics half.

## Design

- Compound and target sets: the TCMSP database (queried 10 May 2023) gave 143 ginger ingredients with oral bioavailability of at least 30%; the drug-likeness cut-off of 0.18 was deliberately dropped to keep more compounds. These map to 298 predicted drug targets.
- Disease targets: 1088 Alzheimer genes from GeneCards (protein-coding, relevance score above 15), OMIM and DisGeNET (gene-disease score above 0.3). The overlap with the drug targets is 95 "key targets".
- Enrichment: Gene Ontology and KEGG enrichment of the 95 targets with clusterProfiler (adjusted p below 0.05), networks drawn in Cytoscape.
- Interaction network: STRING at medium confidence 0.4 gave a network of 95 nodes and 958 edges; the five best-connected nodes were called hub genes.
- Cell test: [[PC12]] cells (rat) were exposed to amyloid-beta 1-42 (10 μM for 24 h chosen from a concentration series) with or without 6-gingerol, and viability was read with the CCK-8 kit.
- Docking: CB-Dock2 (AutoDock Vina engine) of 6-gingerol against 16 proteins; the top three by Vina score plus the hub gene CASP3 went on to GROMACS 2022.3 (Amber99sb-ildn force field, TIP3P water, 300 K, 1 bar, 100 ns, 2 fs steps), read as RMSD, RMSF, radius of gyration, hydrogen bonds and Gibbs free energy landscapes.

## Findings

- Ginger compounds hit 95 of the 1088 Alzheimer genes. The 898 biological process, 31 cellular component, 106 molecular function and 142 KEGG terms were led by response to xenobiotic stimulus, [[Oxidative stress]], response to toxic substance, lipid and atherosclerosis, and diabetic cardiomyopathy. The authors tie the first terms to metal and acid exposure that causes amyloid deposition in mice, and the lipid terms to [[APOE]] status and lipid-raft changes in early disease.
- The compound-target network (191 nodes, 444 edges) puts 6-gingerol on 16 key targets: [[ACHE]], ADRB2, [[BAX]], [[BCL2]], [[CASP3]], CASP9, ESR1, JUN, [[MMP2]], [[MMP9]], PPARG, [[PTGS2]], RELA, SLC6A2, SLC6A3 and SLC6A4.
- Hub genes by degree: [[ALB]], [[ACTB]], [[GAPDH]], [[CASP3]] and [[CAT]].
- 6-Gingerol was picked for follow-up on three grounds: the network result, the authors' earlier laboratory identification of characteristic ginger compounds, and published work on it. In PC12 cells injured with amyloid-beta 1-42 it gave "a certain improvement" in viability; no numbers or concentrations are given in the text.
- Lowest docking energies of 6-gingerol: [[MMP2]] -8.7, [[ACHE]] -8.3, [[PTGS2]] -7.9 and [[CASP3]] -6.0 kcal/mol (the first three were the best of the 16). Contacts are listed residue by residue: for ACHE, hydrogen bonds with Ser203, Gly122, Tyr337, Tyr124 and Trp86 and pi stacking with Trp86, Phe338 and Tyr341; for CASP3, hydrogen bonds with His277, Lys224, Leu223 and Asp228; for MMP2, hydrogen bonds with Arg462, Gly389, Ile395, Ala393 and Pro394; for PTGS2, a single hydrogen bond with Leu531.
- All four complexes stayed together over 100 ns. Complex RMSD settled near 0.24-0.26 nm (ACHE), 0.3-0.4 nm (CASP3), 0.42-0.46 nm (MMP2) and 0.22-0.24 nm (PTGS2); the hydrogen-bond maximum was 5, 4, 6 and 3 respectively, with 1-4 persisting through the run. Low-energy basins in the free energy landscapes sat at radius of gyration 2.305-2.33 nm for ACHE, 1.80-1.83 for CASP3, 2.77-2.83 for MMP2 and 2.81-2.85 for PTGS2.
- The authors read this as 6-gingerol possibly acting on cholinesterase metabolism, apoptosis, protease and prostaglandin routes in Alzheimer disease, and call for cell and animal experiments.

## Why This Source Matters

It documents a low-cost pipeline of the kind now common for food and herbal ingredients: databases to targets, targets to a hub-gene list, then docking and dynamics. For this subject it nominates a ginger compound and four candidate protein targets for [[Alzheimer disease]], all of them classical players (cholinergic transmission, [[Apoptosis]], matrix proteolysis, [[Neuroinflammation]] through prostaglandins). The only wet-lab evidence is one viability assay, so the paper is a hypothesis generator rather than evidence that 6-gingerol works.

## Assessment

- Binding evidence is in silico only. Vina scores of -6.0 to -8.7 kcal/mol for a flexible small molecule are modest and say little about real affinity; CASP3, kept as the "hub gene" for dynamics, has the weakest docking score. One 100 ns run per complex without replicates, and no control ligand (a known inhibitor docked the same way), leaves nothing to compare the numbers against.
- Hub genes ALB, ACTB, GAPDH and CAT are abundant, heavily studied proteins that dominate any STRING degree ranking; their rank is more likely to reflect literature density than Alzheimer relevance. The paper does not discuss this.
- The choice of 6-gingerol rests partly on the group's earlier unpublished-in-this-paper screening and on literature, not on the network alone; 6-gingerol is one of 143 compounds and no other compound was tested for comparison.
- The cell experiment is thinly reported: the text gives no gingerol concentrations, no viability percentages and no statistics, and the methods paragraph mentions imidacloprid and acetamiprid, which are unrelated to the study and look like text carried over from another paper. PC12 cells are from rat, while the targets docked are presumably human structures.
- Internal inconsistencies in the dynamics: the quoted mean radius of gyration for ACHE (2.32-3.34 nm) overlaps poorly with its energy basin (2.305-2.33 nm); for PTGS2 the steady value (2.46-2.48 nm) lies outside the basin (2.81-2.85 nm); and the ligand RMSD for PTGS2 (about 0.8 nm) is far above the protein's, which argues for a mobile ligand rather than a firmly bound one. A drug named "Restigmine" is probably rivastigmine, and the hub gene appears once as "GADPH".
- The 1088 disease genes were built from three databases with different thresholds; the 95-gene overlap shows ginger targets are disease-associated, but many genes of any large set will be, so no background comparison was made.

## Open Questions

- Does 6-gingerol at defined concentrations raise viability of amyloid-beta 1-42 injured PC12 cells, and by how much (the text reports only a qualitative improvement without concentrations or statistics)?
- Does 6-gingerol inhibit or bind acetylcholinesterase, MMP2, PTGS2 or caspase-3 in a biochemical assay (only docking and 100 ns simulations were run)?
- Would a known inhibitor of acetylcholinesterase such as donepezil, docked and simulated the same way, score better or worse than 6-gingerol (no reference ligand was included)?
- Are ALB, ACTB, GAPDH and CAT still hub genes when the protein interaction network is built from a random set of 95 genes (no background control was run)?
- Does oral 6-gingerol reach the brain at concentrations near those used in cells (the study does not address pharmacokinetics)?

## Connections

- Compound: [[6-Gingerol]]; plant: [[Zingiber officinale]]
- Targets docked and simulated: [[ACHE]], [[MMP2]], [[PTGS2]], [[CASP3]]; hub genes [[ALB]], [[ACTB]], [[GAPDH]], [[CAT]]
- Disease context: [[Alzheimer disease]], [[Amyloid-beta]], [[Apoptosis]], [[Oxidative stress]]
- Methods: [[Network pharmacology with multi-omics for herbal medicines]], [[Molecular docking]], [[Molecular dynamics simulation]]; cell model [[PC12]]
- Related drug context: the paper opens with the 2023 full approval of lecanemab, see [[Anti-amyloid antibody therapy]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| Ginger (CHEBI:753433) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Ginger has been reported to potentially treat Alzheimer’s disease (AD), but the specific compounds responsible for this biological function and their mechanisms are still unknown." |
| [[6-Gingerol]] (MESH:C007845) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "The findings indicate that 6-Gingerol exhibits strong binding ability to these disease targets, suggesting its potential role in regulating AD at the molecular level, as well as in abnormal cholinesterase metabolism and cell apoptosis, among other related regulatory pathways." |
| [[ALB]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The TCMSP, GeneCards, OMIM, and DisGeNET databases were utilized to obtain 95 cross-targets related to ginger’s active ingredients and AD as key targets." |
| [[ACTB]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The TCMSP, GeneCards, OMIM, and DisGeNET databases were utilized to obtain 95 cross-targets related to ginger’s active ingredients and AD as key targets." |
| [[GAPDH]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The TCMSP, GeneCards, OMIM, and DisGeNET databases were utilized to obtain 95 cross-targets related to ginger’s active ingredients and AD as key targets." |
| [[CASP3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The TCMSP, GeneCards, OMIM, and DisGeNET databases were utilized to obtain 95 cross-targets related to ginger’s active ingredients and AD as key targets." |
| [[CAT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The TCMSP, GeneCards, OMIM, and DisGeNET databases were utilized to obtain 95 cross-targets related to ginger’s active ingredients and AD as key targets." |
| [[ACHE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The findings indicate that 6-Gingerol exhibits strong binding ability to these disease targets, suggesting its potential role in regulating AD at the molecular level, as well as in abnormal cholinesterase metabolism and cell apoptosis, among other related regulatory pathways." |
| [[MMP2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The findings indicate that 6-Gingerol exhibits strong binding ability to these disease targets, suggesting its potential role in regulating AD at the molecular level, as well as in abnormal cholinesterase metabolism and cell apoptosis, among other related regulatory pathways." |
| [[PTGS2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The findings indicate that 6-Gingerol exhibits strong binding ability to these disease targets, suggesting its potential role in regulating AD at the molecular level, as well as in abnormal cholinesterase metabolism and cell apoptosis, among other related regulatory pathways." |
| [[MAPT]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Based on previous findings, scientists have proposed several popular hypotheses that may induce the development of AD: the hypothesis of Aβ cascade, microtubule-associated protein tau protein (Tau) hyperphosphorylation, cholinergic hypothesis, neuroinflammation, oxidative stress, and metal ions." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "β-amyloid peptide (Aβ) is the main component of Amyloid plaques and plays an important role in the pathophysiological process of AD." |
| DNA (CHEBI:16991; MESH:D004247) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, lipid peroxidation and mitochondrial DNA oxidation have also been observed in the brains of individuals with AD." |
| [[6-Gingerol]] (MESH:C007845) | biolink:derives_from | Ginger (CHEBI:753433) |  | "Based on the results of network pharmacology and cell experiments, 6-Gingerol was selected as the active ingredient for further investigation." |
| Ginger (CHEBI:753433) | biolink:associated_with | Oxidative stress (HP:0025464) |  | "A functional enrichment analysis revealed that the pathways in which ginger’s active substances may be involved in regulating AD include response to exogenous stimuli, response to oxidative stress, response to toxic substances, and lipid metabolism, among others." |
| [[6-Gingerol]] (MESH:C007845) | biolink:directly_physically_interacts_with | [[CASP3]] |  | "Molecular docking was performed between 6-Gingerol and its 16 key targets, and the top three proteins with the strongest binding affinities (ACHE, MMP2, and PTGS2) were chosen for molecular dynamics analysis together with the CASP3 protein as the HUB gene." |
| [[6-Gingerol]] (MESH:C007845) | biolink:directly_physically_interacts_with | [[ACHE]] |  | "Molecular docking was performed between 6-Gingerol and its 16 key targets, and the top three proteins with the strongest binding affinities (ACHE, MMP2, and PTGS2) were chosen for molecular dynamics analysis together with the CASP3 protein as the HUB gene." |
| [[6-Gingerol]] (MESH:C007845) | biolink:directly_physically_interacts_with | [[MMP2]] |  | "Molecular docking was performed between 6-Gingerol and its 16 key targets, and the top three proteins with the strongest binding affinities (ACHE, MMP2, and PTGS2) were chosen for molecular dynamics analysis together with the CASP3 protein as the HUB gene." |
| [[6-Gingerol]] (MESH:C007845) | biolink:directly_physically_interacts_with | [[PTGS2]] |  | "Molecular docking was performed between 6-Gingerol and its 16 key targets, and the top three proteins with the strongest binding affinities (ACHE, MMP2, and PTGS2) were chosen for molecular dynamics analysis together with the CASP3 protein as the HUB gene." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | Amyloid plaques (MONDO:0019065; MESH:D058225) |  | "β-amyloid peptide (Aβ) is the main component of Amyloid plaques and plays an important role in the pathophysiological process of AD." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "The accumulation of Aβ can lead to oxidative stress reactions and activate inflammatory pathways in the primary neurons in the body." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:causes | Neurotoxicity (MONDO:0005527) |  | "Oxidative stress and inflammatory response are closely related to Aβ-induced neurotoxicity." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:affects | Reactive oxygen species (CHEBI:26523; MESH:D017382) | direction=increased | "For example, experiments in vitro/vivo have shown that Aβ has the potential to elevate the levels of reactive oxygen species (ROS)." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | Oxidative stress (HP:0025464) |  | "The accumulation of Aβ can lead to oxidative stress reactions and activate inflammatory pathways in the primary neurons in the body." |
| Lecanemab (CHEBI:755918; MESH:C000612089) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "After the continuous efforts of researchers, on 6 July 2023, the Food and Drug Administration (FDA) in the United States fully authorized the usage of Leqembi (Lecanemab), an AD treatment drug developed by BIIB." |
| Ginger (CHEBI:753433) | biolink:treats | Headache (HP:0002315; MESH:D006261) |  | "In traditional Eastern medicine, ginger is recognized for its ability to alleviate headACHEs, nausea, and colds." |
| Ginger (CHEBI:753433) | biolink:treats | Nausea (HP:0002018; MESH:D009325) |  | "In traditional Eastern medicine, ginger is recognized for its ability to alleviate headACHEs, nausea, and colds." |
| Ginger (CHEBI:753433) | biolink:treats | Common cold (MONDO:0005709; MESH:D003139) |  | "In traditional Eastern medicine, ginger is recognized for its ability to alleviate headACHEs, nausea, and colds." |
| Ginger (CHEBI:753433) | biolink:treats | Rheumatoid arthritis (MONDO:0008383; MESH:D001172) |  | "Modern medicine has also utilized ginger in the treatment of various diseases such as rheumatoid arthritis, atherosclerosis, ulcers, and depression." |
| Ginger (CHEBI:753433) | biolink:treats | Atherosclerosis (MONDO:0005311; MESH:D050197) |  | "Modern medicine has also utilized ginger in the treatment of various diseases such as rheumatoid arthritis, atherosclerosis, ulcers, and depression." |
| Ginger (CHEBI:753433) | biolink:treats | Ulcer (MONDO:0043839; MESH:D014456) |  | "Modern medicine has also utilized ginger in the treatment of various diseases such as rheumatoid arthritis, atherosclerosis, ulcers, and depression." |
| Ginger (CHEBI:753433) | biolink:treats | Depression (MONDO:0002050) |  | "Modern medicine has also utilized ginger in the treatment of various diseases such as rheumatoid arthritis, atherosclerosis, ulcers, and depression." |
| Ginger (CHEBI:753433) | biolink:treats | Neurotoxicity (MONDO:0005527) |  | "Some studies suggest that the active ingredients present in ginger may have the potential to alleviate Aβ-induced neurotoxicity by modulating oxidative stress and inflammatory pathways." |
| Allicin (CHEBI:28411; MESH:C006452) | biolink:derives_from | Garlic (CHEBI:753431) |  | "Furthermore, many herbal medicines and functional agricultural products (or food) contain bioactive phytochemical substances with strong antioxidant potential, such as Allicin in garlic, Capsaicin in pepper, Curcumin, and Gingerol in ginger." |
| Ginger (CHEBI:753433) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The visual network diagram offers a more intuitive representation of the role of ginger in regulating AD and its associated metabolic pathways." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Genetic and environmental factors are associated with AD, such as the carrying status of Apolipoprotein E (APOE) and lipid transporters, and dietary lipid content." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | ADRB2 (HGNC:286) |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[BAX]] |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[BCL2]] |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | CASP9 (HGNC:1511) |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[ESR1]] |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | JUN (HGNC:6204) |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[MMP9]] |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[PPARG]] |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[RELA]] |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | SLC6A2 (HGNC:11048) |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | SLC6A3 (HGNC:11049) |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[SLC6A4]] |  | "The CB-Dock2 platform was used for molecular docking analysis to evaluate the binding affinity between 6-Gingerol and various proteins including ACHE, ADRB2, BAX, BCL2, CASP3, CASP9, ESR1, JUN, MMP2, MMP9, PPARG, PTGS2, RELA, SLC6A2, SLC6A3, and SLC6A4." |
| Rivastigmine (CHEBI:8874; MESH:D000068836) | biolink:directly_physically_interacts_with | [[ACHE]] |  | "Restigmine, a drug targeting ACHE, is considered as one of the treatment options for AD." |
| [[ACHE]] | biolink:associated_with | Necrosis (MESH:D009336) |  | "There are also numerous reports linking changes in lipid metabolism, live cells, apoptotic cells, and the distribution of necrotic brain cells to the activity of acetylcholinesterase in serum and brain." |
| [[CASP3]] | biolink:affects | [[MAPT]] |  | "Research has shown that CASP3 is involved in the cleavage of β-amyloid protein, as well as Tau protein and presenilin protein (PS1, PS2), which are closely associated with AD." |
| [[CASP3]] | biolink:affects | [[PSEN1]] |  | "Research has shown that CASP3 is involved in the cleavage of β-amyloid protein, as well as Tau protein and presenilin protein (PS1, PS2), which are closely associated with AD." |
| [[CASP3]] | biolink:affects | [[PSEN2]] |  | "Research has shown that CASP3 is involved in the cleavage of β-amyloid protein, as well as Tau protein and presenilin protein (PS1, PS2), which are closely associated with AD." |
| Crocin (MESH:C029036) | biolink:affects | [[CASP3]] | direction=decreased | "Crocin significantly reduces CASP3 protein expression in cell models of Alzheimer’s disease, offering promising potential for treating the disease by decreasing the cell apoptosis rate and alleviating mitochondrial dysfunction." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Research has shown that CASP3 is involved in the cleavage of β-amyloid protein, as well as Tau protein and presenilin protein (PS1, PS2), which are closely associated with AD." |
| [[PSEN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Research has shown that CASP3 is involved in the cleavage of β-amyloid protein, as well as Tau protein and presenilin protein (PS1, PS2), which are closely associated with AD." |
| [[PSEN2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Research has shown that CASP3 is involved in the cleavage of β-amyloid protein, as well as Tau protein and presenilin protein (PS1, PS2), which are closely associated with AD." |
| Rivastigmine (CHEBI:8874; MESH:D000068836) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Restigmine, a drug targeting ACHE, is considered as one of the treatment options for AD." |
| Acetylcholine (CHEBI:15355; MESH:D000109) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Impaired lipid metabolism, which is associated with decreased acetylcholine levels and alterations in phospholipid metabolism, is a key characteristic of AD." |
| Crocin (MESH:C029036) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Crocin significantly reduces CASP3 protein expression in cell models of Alzheimer’s disease, offering promising potential for treating the disease by decreasing the cell apoptosis rate and alleviating mitochondrial dysfunction." |
| Crocin (MESH:C029036) | biolink:treats | [[Mitochondrial dysfunction]] (MESH:D028361) |  | "Crocin significantly reduces CASP3 protein expression in cell models of Alzheimer’s disease, offering promising potential for treating the disease by decreasing the cell apoptosis rate and alleviating mitochondrial dysfunction." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[ACHE]] |  | "The molecular simulation and MD results confirmed that 6-Gingerol may be regulated by ACHE, MMP2, PTGS2, and CASP3 in improving the progression of AD." |
| [[6-Gingerol]] (MESH:C007845) | biolink:physically_interacts_with | [[CASP3]] |  | "The molecular simulation and MD results confirmed that 6-Gingerol may be regulated by ACHE, MMP2, PTGS2, and CASP3 in improving the progression of AD." |
| [[MMP2]] | biolink:affects | [[MAPT]] | direction=decreased | "This suggests that the accumulation of MMP2 in neurofibrillary tangles may be a protective response aimed at reducing the production of toxic truncated tau species in the brains of individuals with AD." |
| [[MMP2]] | biolink:associated_with | Neurofibrillary tangles (HP:0002185) |  | "This suggests that the accumulation of MMP2 in neurofibrillary tangles may be a protective response aimed at reducing the production of toxic truncated tau species in the brains of individuals with AD." |
| [[MMP2]] | biolink:associated_with | zinc (CHEBI:27363; MESH:D015032) |  | "Matrix Metalloproteinase-2 (MMP2) is a zinc-dependent protease that primarily targets extracellular matrix proteins." |
| [[PTGS2]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Elevated levels of PTGS2/COX-2 and PGs play a role in the development of AD." |
| [[PTGS2]] | biolink:affects | prostaglandins (CHEBI:26333; MESH:D011453) | direction=increased | "Prostaglandin-endoperoxide synthase 2 (PTGS2), also referred to as cyclooxygenase 2 (COX-2), is an enzyme that acts as the rate-limiting factor in the synthesis of prostaglandins (PGs)." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "AD is characterized by the buildup of Aβ protein and tau hyperphosphorylation, and the relevant mechanisms and pathways may include neuroinflammation, oxidative stress, synaptic plasticity, neurotoxicity, autophagy, and apoptosis." |
| prostaglandins (CHEBI:26333; MESH:D011453) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Elevated levels of PTGS2/COX-2 and PGs play a role in the development of AD." |
| Ginger (CHEBI:753433) | biolink:associated_with | Atherosclerosis (MONDO:0005311; MESH:D050197) |  | "The pathways in which the active substances in ginger may be involved in regulating AD include response to exogenous stimuli, response to oxidative stress, toxic substance reactions, lipids and atherosclerosis, diabetic cardiomyopathy, etc." |
| Ginger (CHEBI:753433) | biolink:associated_with | Diabetic cardiomyopathy (MESH:D058065) |  | "The pathways in which the active substances in ginger may be involved in regulating AD include response to exogenous stimuli, response to oxidative stress, toxic substance reactions, lipids and atherosclerosis, diabetic cardiomyopathy, etc." |
