---
type: source
title: "APOE Christchurch microglia protect neurons from Tau in iPSC models"
paper_title: "Microglial APOE3 Christchurch protects neurons from Tau pathology in a human iPSC-based model of Alzheimer’s disease"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000140
pmid: "39612244"
pmcid: "PMC11753789"
doi: "10.1016/j.celrep.2024.114982"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC11753789/"
sources: ["[[.raw/01M4DY94HC9BASA28AWPS2Z2A5/normalized.md]]"]
tags: [microglia, tau, ipsc, neuroinflammation]
---

# APOE Christchurch microglia protect neurons from Tau in iPSC models

A mechanistic test of whether the rare [[APOE p.R136S]] variant (APOE3 Christchurch, APOECh) is itself responsible for the delayed onset of [[Alzheimer disease]] seen in a Colombian carrier of the [[PSEN1 p.E280A]] mutation, using human induced pluripotent stem cell (hiPSC) models. The authors ask whether microglia carrying the variant protect neurons from Tau pathology, and through which pathway.

## Design

- Cells: isogenic APOE3 and APOECh iPSC pairs, made by CRISPR-Cas9 editing of control lines, a pair from the Jackson Laboratory, and a pair derived from two members of the Paisa PSEN1 E280A kindred (one homozygous for APOECh with the PSEN1 mutation corrected, one APOE3/E3 with the mutation corrected). Microglia were differentiated through CD43-positive haematopoietic progenitors with an IL-34, TGF-β1 and M-CSF cocktail. Neurons came from wild-type and CRISPR-engineered PSEN1 E280A mutant iPSCs.
- Models: 2D neuron-microglia co-cultures (neurons to microglia 5:2, 10 days) and 3D brain organoids into which microglia were introduced at day 50 and analysed 20 days later; see [[iPSC neuron-microglia co-culture and neuroimmune organoid models]].
- Challenges: pHrodo-labelled human fetal synaptosomes for phagocytosis, synthetic amyloid beta 42 (500 nM), conditioned medium from wild-type or PSEN1 mutant neurons (with or without the gamma-secretase inhibitor [[DAPT]]), Tau oligomers immunoprecipitated with antibody T22 from Alzheimer postmortem cortex, and synaptosomes from Alzheimer postmortem brain (ADHS).
- Readouts: RNA sequencing of CD11b-purified microglia with GO and KEGG enrichment, qRT-PCR, lipid droplet staining (LipidSpot), lipid peroxidation (BODIPY 581/591 C11), phagocytosis index, phosphorylated Tau (AT8) by immunostaining and detergent-fractionated western blot, and multi-electrode array recordings of neuronal network activity.
- Perturbations: doxycycline-inducible [[TFRC]] knock-in, the ferroptosis inhibitor [[Liproxstatin-1]], pemetrexed (Alimta) and folic acid for the folate pathway, the phagocytosis inhibitor cytochalasin D, and an APOE mimetic peptide spanning residues 133-149 ([[APOE mimetic peptide]]).
- Statistics: one- or two-way ANOVA with Tukey's test, or unpaired t test; significance at p < 0.05.

## Findings

- With PSEN1 mutant neurons, APOE3 microglia had a markedly lower synaptosome phagocytosis index than APOECh microglia and a higher [[IL1B]] induction; with wild-type neurons the two genotypes did not differ.
- RNA sequencing of microglia co-cultured with mutant neurons: genes up in APOECh microglia mapped to [[Phagocytosis]], lipid particles, folic acid and amyloid beta binding; genes down mapped to inflammatory response, apoptosis, [[Ferroptosis]], ion homeostasis and Alzheimer pathways. By qRT-PCR, [[ACSL1]], [[TFRC]] and [[SAT1]] were higher in APOE3 than APOECh microglia, whereas [[ANXA3]], [[CD93]] and [[SLC11A1]] were higher in APOECh microglia.
- Amyloid beta 42, or medium from PSEN1 mutant neurons, induced ACSL1, increased [[Lipid droplet]] number and raised [[Lipid peroxidation]] and TFRC in APOE3 microglia but not in APOECh microglia. Medium from DAPT-treated mutant neurons had no such effect, tying the signal to amyloid beta production. Expression of [[TREM2]] and ITGAX (disease-associated microglia markers) did not differ between genotypes after amyloid beta 42.
- Amyloid beta 42 lowered phagocytosis and cell viability in APOE3 but not APOECh microglia; Liproxstatin-1 rescued viability and, in co-culture with mutant neurons, phagocytosis in APOE3 microglia, while pemetrexed and folic acid did not. Inducing TFRC lowered phagocytosis in microglia of both genotypes.
- Tau oligomers left less residual oligomer in APOECh than APOE3 co-cultures with mutant neurons (no genotype difference with wild-type neurons). Both ADHS and oligomer challenge raised phosphorylated [[MAPT]] (Tau) in soluble and insoluble fractions of neurons with APOE3 microglia, less so with APOECh microglia; cytochalasin D raised neuronal phospho-Tau under both genotypes, consistent with phagocytosis limiting its spread.
- ADHS cut neuronal network activity on multi-electrode arrays with APOE3 microglia (more strongly for mutant neurons), whereas activity was largely preserved with APOECh microglia, for wild-type as well as mutant neurons.
- The APOE mimetic peptide brought lipid droplet number and lipid peroxidation in amyloid-beta-treated APOE3 microglia down to APOECh levels, prevented the phagocytosis loss, and lowered the share of phospho-Tau positive neurons after ADHS.
- In brain organoids, day-70 PSEN1 mutant organoids carried more phospho-Tau than wild type, and APOECh microglia lowered phospho-Tau in mutant organoids more than APOE3 microglia did.
- The authors conclude that APOECh acts causally and cell-autonomously in microglia: by resisting amyloid-beta-driven lipid droplet formation, lipid peroxidation and ferroptosis, the microglia keep phagocytosing and so limit Tau spread.

## Why This Source Matters

It supplies a human cell-based causal test of a protective variant first described in a single patient, and ties it to a specific microglial pathway (lipid droplets, [[Lipid peroxidation]], [[Ferroptosis]], [[Phagocytosis]]) rather than to amyloid load, which was high in the carrier. It also shows a pharmacological way to mimic the effect in APOE3 cells, which makes APOE-receptor interaction and microglial lipid metabolism concrete drug targets, and it provides a reusable platform for comparing other APOE alleles.

## Assessment

- The variant's effect is shown in iPSC-derived cells and organoids, not in human brain tissue from carriers; the authors state this as a limit.
- Replicates are few: many panels use three iPSC lines, four organoids or three technical repeats, and some counts are images from three lines rather than independent experiments. Only one clone was used per isogenic line.
- The text and figure legends give different numbers of CRISPR-edited isogenic pairs (two in the text, three in the legend) and different liproxstatin-1 doses (1 μM in methods, 2 μM in the legend); the legend values were not resolved.
- Ferroptosis is inferred from lipid peroxidation, TFRC and SAT1 expression and rescue by one inhibitor; iron content and other ferroptosis markers were not measured. Amyloid beta 42 added at 500 nM is a synthetic stand-in for the amyloid environment.
- How the mimetic peptide works, and whether it acts on neurons, microglia or their interface, is not shown.
- Two authors are co-inventors on a patent application on APOE Christchurch therapeutics, and one co-founded a company developing therapies inspired by protected cases.

## Open Questions

- Do microglia from human APOE Christchurch carriers show the same resistance to lipid droplet formation and ferroptosis in postmortem brain (the study used engineered iPSC models only)?
- Does the APOE mimetic peptide spanning residues 133-149 act on neurons, on microglia or at their interface (not tested)?
- Do the rare APOE3-Jacksonville (V236E) and APOE4 R251G variants and the common APOE2, APOE3 and APOE4 alleles differ in microglial lipid droplet formation and ferroptosis in the same co-culture platform (proposed in the discussion, not yet done)?
- Is reduced binding of APOE Christchurch to heparan sulfate proteoglycans the receptor-level cause of the microglial resistance to amyloid beta 42 (cited from earlier work, not tested here)?

## Connections

- Variants: [[APOE p.R136S]], [[PSEN1 p.E280A]]; genes: [[APOE]], [[PSEN1]], [[MAPT]], [[TREM2]], [[ACSL1]], [[TFRC]], [[SAT1]], [[ANXA3]], [[CD93]], [[SLC11A1]], [[IL1B]]
- Processes and components: [[Ferroptosis]], [[Lipid peroxidation]], [[Phagocytosis]], [[Lipid droplet]]
- Chemicals: [[Liproxstatin-1]], [[DAPT]], [[APOE mimetic peptide]]
- Diseases: [[Alzheimer disease]], [[Early-onset Alzheimer disease]], [[Neurofibrillary tangle]]
- Method: [[iPSC neuron-microglia co-culture and neuroimmune organoid models]]
- Related microglial work: [[TREM2 regulation by YY1 in microglia and Alzheimer disease models]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APOE]] | biolink:affects | [[MAPT]] | direction=decreased | "We show that APOECh microglia are resistant to Aβ-induced lipid peroxidation and ferroptosis and therefore preserve the phagocytic activity and promote pTau clearance, providing mechanistic insights into the neuroprotective role of APOE3Ch microglia." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The ε4 allele of APOE is the strongest genetic risk factor for AD." |
| [[APOE]] | biolink:associated_with_decreased_likelihood_of | neurofibrillary tangles (HP:0002185) |  | "Sun et al. demonstrate that APOE3 Christchurch microglia protect neurons from Aβ-induced Tau pathology by regulating lipid peroxidation and phagocytosis." |
| [[APOE]] | biolink:physically_interacts_with | cholesterol (CHEBI:16113; MESH:D002784) |  | "Apolipoprotein E (APOE) is a major cholesterol carrier that mediates lipid transport in the brain." |
| [[PSEN1]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Familial AD (fAD) is a rare form of AD that is primarily caused by genetic mutations in three genes: the amyloid precursor protein (APP) gene, presenilin 1 (PSEN1) gene, and presenilin 2 (PSEN2) gene." |
| [[PSEN1]] | biolink:causes | familial Alzheimer disease (MONDO:0100087) |  | "Familial AD (fAD) is a rare form of AD that is primarily caused by genetic mutations in three genes: the amyloid precursor protein (APP) gene, presenilin 1 (PSEN1) gene, and presenilin 2 (PSEN2) gene." |
| [[PSEN1]] | biolink:contributes_to | amyloid plaques (HP:0100256; MESH:D058225) |  | "Mutations of PSEN1 and PSEN2 genes affect the function of γ-secretase complex, which is responsible for the cleavage of the APP protein and releasing Aβ peptides, leading to increased ratio of Aβ42/Aβ40, which contributes to the formation of amyloid plaques." |
| [[PSEN1]] | biolink:affects | amyloid-beta (CHEBI:64645; MESH:D016229) | direction=increased | "Mutations of PSEN1 and PSEN2 genes affect the function of γ-secretase complex, which is responsible for the cleavage of the APP protein and releasing Aβ peptides, leading to increased ratio of Aβ42/Aβ40, which contributes to the formation of amyloid plaques." |
| [[PSEN2]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Familial AD (fAD) is a rare form of AD that is primarily caused by genetic mutations in three genes: the amyloid precursor protein (APP) gene, presenilin 1 (PSEN1) gene, and presenilin 2 (PSEN2) gene." |
| [[PSEN2]] | biolink:causes | familial Alzheimer disease (MONDO:0100087) |  | "Familial AD (fAD) is a rare form of AD that is primarily caused by genetic mutations in three genes: the amyloid precursor protein (APP) gene, presenilin 1 (PSEN1) gene, and presenilin 2 (PSEN2) gene." |
| [[PSEN2]] | biolink:contributes_to | amyloid plaques (HP:0100256; MESH:D058225) |  | "Mutations of PSEN1 and PSEN2 genes affect the function of γ-secretase complex, which is responsible for the cleavage of the APP protein and releasing Aβ peptides, leading to increased ratio of Aβ42/Aβ40, which contributes to the formation of amyloid plaques." |
| [[PSEN2]] | biolink:affects | amyloid-beta (CHEBI:64645; MESH:D016229) | direction=increased | "Mutations of PSEN1 and PSEN2 genes affect the function of γ-secretase complex, which is responsible for the cleavage of the APP protein and releasing Aβ peptides, leading to increased ratio of Aβ42/Aβ40, which contributes to the formation of amyloid plaques." |
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Familial AD (fAD) is a rare form of AD that is primarily caused by genetic mutations in three genes: the amyloid precursor protein (APP) gene, presenilin 1 (PSEN1) gene, and presenilin 2 (PSEN2) gene." |
| [[APP]] | biolink:causes | familial Alzheimer disease (MONDO:0100087) |  | "Familial AD (fAD) is a rare form of AD that is primarily caused by genetic mutations in three genes: the amyloid precursor protein (APP) gene, presenilin 1 (PSEN1) gene, and presenilin 2 (PSEN2) gene." |
| [[APOE p.R136S]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "A recent study found that the APOE3 Christchurch (APOECh) variant could delay AD progression." |
| [[PSEN1 p.E280A]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, researchers found that an individual harboring the PSEN1 E280A mutation from the Paisa PSEN1 E280A kindred showed delayed onset of AD as shown by the limited development of Tau pathology despite the presence of excess amyloid plaques." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The ε4 allele of APOE is the strongest genetic risk factor for AD." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Although the US Food and Drug Administration (FDA) has approved aducanumab and Leqembi as disease-modifying treatments for AD by targeting β-amyloid (Aβ), their impact on long-term disease progression remains to be watched." |
| aducanumab (CHEBI:755082; MESH:C000600266) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Although the US Food and Drug Administration (FDA) has approved aducanumab and Leqembi as disease-modifying treatments for AD by targeting β-amyloid (Aβ), their impact on long-term disease progression remains to be watched." |
| lecanemab (CHEBI:755918; MESH:C000612089) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Although the US Food and Drug Administration (FDA) has approved aducanumab and Leqembi as disease-modifying treatments for AD by targeting β-amyloid (Aβ), their impact on long-term disease progression remains to be watched." |
| [[PSEN1 p.E280A]] | biolink:associated_with | amyloid plaques (HP:0100256; MESH:D058225) |  | "Recently, researchers found that an individual harboring the PSEN1 E280A mutation from the Paisa PSEN1 E280A kindred showed delayed onset of AD as shown by the limited development of Tau pathology despite the presence of excess amyloid plaques." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:contributes_to | amyloid plaques (HP:0100256; MESH:D058225) |  | "Mutations of PSEN1 and PSEN2 genes affect the function of γ-secretase complex, which is responsible for the cleavage of the APP protein and releasing Aβ peptides, leading to increased ratio of Aβ42/Aβ40, which contributes to the formation of amyloid plaques." |
| [[APOE p.R136S]] | biolink:associated_with_decreased_likelihood_of | neurofibrillary tangles (HP:0002185) |  | "Sun et al. demonstrate that APOE3 Christchurch microglia protect neurons from Aβ-induced Tau pathology by regulating lipid peroxidation and phagocytosis." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:contributes_to | neurofibrillary tangles (HP:0002185) |  | "Sun et al. demonstrate that APOE3 Christchurch microglia protect neurons from Aβ-induced Tau pathology by regulating lipid peroxidation and phagocytosis." |
| aducanumab (CHEBI:755082; MESH:C000600266) | biolink:directly_physically_interacts_with | amyloid-beta (CHEBI:64645; MESH:D016229) |  | "Although the US Food and Drug Administration (FDA) has approved aducanumab and Leqembi as disease-modifying treatments for AD by targeting β-amyloid (Aβ), their impact on long-term disease progression remains to be watched." |
| lecanemab (CHEBI:755918; MESH:C000612089) | biolink:directly_physically_interacts_with | amyloid-beta (CHEBI:64645; MESH:D016229) |  | "Although the US Food and Drug Administration (FDA) has approved aducanumab and Leqembi as disease-modifying treatments for AD by targeting β-amyloid (Aβ), their impact on long-term disease progression remains to be watched." |
| [[APOE]] | biolink:affects | [[IL1B]] | direction=decreased | "Moreover, APOE3 microglia co-cultured with PSEN1 mutant neurons exhibited elevated neuroinflammatory response as revealed by a higher induction of IL-1β than that in APOECh microglia co-cultured with PSEN1 mutant neurons (Figure S2C)." |
| [[APOE]] | biolink:affects | [[ACSL1]] | direction=decreased | "We detected substantially elevated expression of ACSL1, a gene encoding a key enzyme for lipid droplet biogenesis, in APOE3 microglia compared to APOECh microglia when co-cultured with PSEN1 mutant neurons (Figure 2E)." |
| [[APOE]] | biolink:affects | [[TFRC]] | direction=decreased | "Notably, TFRC and SAT1 exhibited increased expression levels in APOE3 microglia compared to APOECh microglia that were co-cultured with PSEN1 mutant neurons (Figure 2F)." |
| [[APOE]] | biolink:affects | [[SAT1]] | direction=decreased | "Notably, TFRC and SAT1 exhibited increased expression levels in APOE3 microglia compared to APOECh microglia that were co-cultured with PSEN1 mutant neurons (Figure 2F)." |
| [[APOE]] | biolink:affects | [[ANXA3]] | direction=increased | "Conversely, phagocytosis-related genes, such as ANXA3, CD93, and SLC11A1, displayed elevated expression levels in APOECh microglia compared to APOE3 microglia when co-cultured with PSEN1 mutant neurons (Figure 2G)." |
| [[APOE]] | biolink:affects | [[CD93]] | direction=increased | "Conversely, phagocytosis-related genes, such as ANXA3, CD93, and SLC11A1, displayed elevated expression levels in APOECh microglia compared to APOE3 microglia when co-cultured with PSEN1 mutant neurons (Figure 2G)." |
| [[APOE]] | biolink:affects | [[SLC11A1]] | direction=increased | "Conversely, phagocytosis-related genes, such as ANXA3, CD93, and SLC11A1, displayed elevated expression levels in APOECh microglia compared to APOE3 microglia when co-cultured with PSEN1 mutant neurons (Figure 2G)." |
| [[APOE]] | biolink:associated_with | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "Moreover, APOE3 microglia co-cultured with PSEN1 mutant neurons exhibited elevated neuroinflammatory response as revealed by a higher induction of IL-1β than that in APOECh microglia co-cultured with PSEN1 mutant neurons (Figure S2C)." |
| [[APOE p.R136S]] | biolink:associated_with | [[PSEN1 p.E280A]] |  | "To determine if the APOECh variant can protect neurons from the neuropathology induced by the PSEN1 E280A mutation, we generated a PSEN1 E280A mutant iPSC line by CRISPR-Cas9 editing (Figure 1D)." |
| [[APOE p.R136S]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "To elucidate the role of APOECh variant in the pathogenesis of AD, we generated two isogenic APOECh iPSC lines from two control APOE3 (E3) iPSC lines by CRISPR-Cas9 editing and obtained a pair of isogenic APOECh and APOE3 iPSC lines from the Jackson laboratory (Figures 1A, 1B, and S1; Tables S1 and S2)." |
| [[APOE p.R136S]] | biolink:negatively_correlated_with | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "In conclusion, our observation indicates that APOECh microglia display significantly enhanced phagocytic activity and reduced inflammatory response compared to APOE3 microglia when co-cultured with PSEN1 mutant neurons, suggesting that APOECh microglia may be more resilient to toxic environments and better equipped to maintain their phagocytic function." |
| [[IL1B]] | biolink:biomarker_for | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "Moreover, APOE3 microglia co-cultured with PSEN1 mutant neurons exhibited elevated neuroinflammatory response as revealed by a higher induction of IL-1β than that in APOECh microglia co-cultured with PSEN1 mutant neurons (Figure S2C)." |
| [[TFRC]] | biolink:affects | iron (CHEBI:35136; MESH:D007501) | direction=increased | "In the ferroptosis pathway (Figure 2D), transferrin receptor protein 1 (TFRC) facilitates iron transport into the cell, while SAT1 contributes to lipid peroxidation through the regulation of ALOX15 expression." |
| [[SAT1]] | biolink:regulates | ALOX15 (HGNC:433) | direction=increased | "In the ferroptosis pathway (Figure 2D), transferrin receptor protein 1 (TFRC) facilitates iron transport into the cell, while SAT1 contributes to lipid peroxidation through the regulation of ALOX15 expression." |
| [[PSEN1]] | biolink:affects | [[ACSL1]] | direction=increased | "Because PSEN1 E280A mutant neurons produce more Aβ42 than WT neurons, the elevated expression of ACSL1 in APOE3 microglia co-cultured with PSEN1 mutant but not WT neurons prompted us to investigate the role of Aβ42 in the induction of ACSL1 expression." |
| [[PSEN1]] | biolink:affects | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Because PSEN1 E280A mutant neurons produce more Aβ42 than WT neurons, the elevated expression of ACSL1 in APOE3 microglia co-cultured with PSEN1 mutant but not WT neurons prompted us to investigate the role of Aβ42 in the induction of ACSL1 expression." |
| [[PSEN1 p.E280A]] | biolink:affects | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Because PSEN1 E280A mutant neurons produce more Aβ42 than WT neurons, the elevated expression of ACSL1 in APOE3 microglia co-cultured with PSEN1 mutant but not WT neurons prompted us to investigate the role of Aβ42 in the induction of ACSL1 expression." |
| [[APOE]] | biolink:associated_with | [[ACSL1]] |  | "Indeed, treatment with Aβ42 induced ACSL1 expression in APOE3 but not APOECh microglia (Figure S3A)." |
| [[APOE]] | biolink:associated_with | [[TFRC]] |  | "Furthermore, we detected elevated expression of TFRC, an important regulator of ferroptosis, in Aβ42-treated APOE3 but not APOECh microglia (Figures 3H and 3I)." |
| Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | biolink:affects | [[ACSL1]] | direction=increased | "Indeed, treatment with Aβ42 induced ACSL1 expression in APOE3 but not APOECh microglia (Figure S3A)." |
| Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | biolink:affects | [[TFRC]] | direction=increased | "Furthermore, we detected elevated expression of TFRC, an important regulator of ferroptosis, in Aβ42-treated APOE3 but not APOECh microglia (Figures 3H and 3I)." |
| cytochalasin D (CHEBI:529996; MESH:D015638) | biolink:affects | [[MAPT]] | direction=increased | "Moreover, treatment of the N-MG co-cultures with the phagocytosis inhibitor cytochalasin D (cytoD) led to dramatically increased pTau level in neurons co-cultured with either APOE3 or APOECh microglia (Figures S5E and S5F), suggesting that the reduced pTau level in neurons co-cultured with APOECh microglia could be due to the enhanced phagocytosis capacity of APOECh microglia." |
| [[APOE]] | biolink:affects | [[MAPT]] | direction=decreased | "These results indicate that APOECh microglia are more effective at clearing oTau compared to APOE3 microglia." |
| [[APOE p.R136S]] | biolink:affects | [[MAPT]] | direction=decreased | "These results indicate that APOECh microglia are more effective at clearing oTau compared to APOE3 microglia." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We prepared oTau from postmortem brain tissues of patients with AD (Figures S5A and S5B) and introduced them into N-MG co-cultures to serve as a source of the pathological Tau." |
| Tau oligomer (CHEBI:132554) | biolink:contributes_to | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "This process of Tau oligomerization is believed to be a critical factor for initiating neuronal loss and cognitive impairment observed in neurodegenerative disorders." |
| Tau oligomer (CHEBI:132554) | biolink:contributes_to | neuronal loss (HP:0002529) |  | "This process of Tau oligomerization is believed to be a critical factor for initiating neuronal loss and cognitive impairment observed in neurodegenerative disorders." |
| Tau oligomer (CHEBI:132554) | biolink:contributes_to | cognitive impairment (HP:0100543; MESH:D060825) |  | "This process of Tau oligomerization is believed to be a critical factor for initiating neuronal loss and cognitive impairment observed in neurodegenerative disorders." |
| [[MAPT]] | biolink:contributes_to | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "Moreover, treatment with oTau enhanced the inflammatory response in APOE3 microglia co-cultured with both WT and PSEN1 mutant neurons, with more dramatic increase in APOE3 microglia co-cultured with PSEN1 mutant neurons." |
| [[APOE]] | biolink:associated_with_decreased_likelihood_of | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "In contrast, APOECh microglia were resistant to oTau-induced inflammatory response (Figure S5G)." |
| [[APOE p.R136S]] | biolink:associated_with_decreased_likelihood_of | Neuroinflammation (HP:0033429; MESH:D000090862) |  | "In contrast, APOECh microglia were resistant to oTau-induced inflammatory response (Figure S5G)." |
| [[APOE]] | biolink:physically_interacts_with | heparan sulfate proteoglycans (CHEBI:24499; MESH:D019812) |  | "It has been shown that the protective effect of APOECh is partly due to its reduced affinity for heparan sulfate proteoglycans (HSPG) or other cellular receptors for APOE." |
| [[APOE]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Many genetic risk factors associated with late-onset AD are highly or specifically expressed in microglia." |
| [[APOE]] | biolink:associated_with | defective phagocytosis (MONDO:0024627) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[APOE p.R136S]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The recent discovery of an association between the presence of an APOECh variant and delayed onset of cognitive impairment reinforces the potential of developing disease-modifying therapies for AD by targeting APOE." |
| [[APOE p.R136S]] | biolink:associated_with_decreased_likelihood_of | cognitive impairment (HP:0100543; MESH:D060825) |  | "The recent discovery of an association between the presence of an APOECh variant and delayed onset of cognitive impairment reinforces the potential of developing disease-modifying therapies for AD by targeting APOE." |
| [[APOE p.R136S]] | biolink:associated_with_decreased_likelihood_of | defective phagocytosis (MONDO:0024627) |  | "In this study, we found that PSEN1 E280A mutant neurons reduced the phagocytic capacity of APOE3 microglia substantially, whereas APOECh microglia are resistant." |
| [[PSEN1]] | biolink:affects | [[MAPT]] | direction=increased | "At day 70 of organoid development, we observed significantly higher levels of pTau in PSEN1 mutant brain organoids compared to WT brain organoids (Figures 7B and 7C)." |
| [[PSEN1]] | biolink:contributes_to | defective phagocytosis (MONDO:0024627) |  | "In this study, we found that PSEN1 E280A mutant neurons reduced the phagocytic capacity of APOE3 microglia substantially, whereas APOECh microglia are resistant." |
| [[PSEN1 p.E280A]] | biolink:contributes_to | defective phagocytosis (MONDO:0024627) |  | "In this study, we found that PSEN1 E280A mutant neurons reduced the phagocytic capacity of APOE3 microglia substantially, whereas APOECh microglia are resistant." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, when we added oTau derived from brain tissues from patients with AD to the N-MG co-cultures, we observed substantially less residual oTau in PSEN1 mutant neurons co-cultured with APOECh microglia than in neurons co-cultured with APOE3 microglia." |
| [[MAPT]] | biolink:causes | neurodegeneration (HP:0002180) |  | "It has been shown that oTau are neurotoxic and can induce neurodegeneration." |
| [[TREM2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[TREM2]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Many genetic risk factors associated with late-onset AD are highly or specifically expressed in microglia." |
| [[TREM2]] | biolink:associated_with | defective phagocytosis (MONDO:0024627) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[CLU]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[CLU]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Many genetic risk factors associated with late-onset AD are highly or specifically expressed in microglia." |
| [[CLU]] | biolink:associated_with | defective phagocytosis (MONDO:0024627) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[ABCA7]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[ABCA7]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Many genetic risk factors associated with late-onset AD are highly or specifically expressed in microglia." |
| [[ABCA7]] | biolink:associated_with | defective phagocytosis (MONDO:0024627) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| GRN (HGNC:4601) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| GRN (HGNC:4601) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Many genetic risk factors associated with late-onset AD are highly or specifically expressed in microglia." |
| GRN (HGNC:4601) | biolink:associated_with | defective phagocytosis (MONDO:0024627) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[CD33]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[CD33]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Many genetic risk factors associated with late-onset AD are highly or specifically expressed in microglia." |
| [[CD33]] | biolink:associated_with | defective phagocytosis (MONDO:0024627) |  | "Many AD risk genes (i.e., APOE, CLU, ABCA7, GRN, TREM2, and CD33) have been linked to microglia phagocytosis." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, this study opens up a promising path for screening potential drugs for AD by targeting APOE and its downstream pathways, including suppressing lipid droplet formation, lipid peroxidation, and ferroptosis, and enhancing phagocytosis in microglia." |
| [[Amyloid-beta]] | biolink:affects | [[MAPT]] | direction=increased | "In this study, we have shown that microglial APOE3Ch can protect neurons from Aβ-induced Tau pathology and impaired neural network activity by reducing lipid droplet-mediated ferroptosis and enhancing phagocytosis in microglia using human iPSC-based 2D N-MG co-culture and 3D neuroimmune organoid models." |
| [[APOE p.R136S]] | biolink:affects | heparan sulfate proteoglycans (CHEBI:24499; MESH:D019812) | direction=decreased | "It has been shown that the protective effect of APOECh is partly due to its reduced affinity for HSPG or other cellular receptors for APOE." |
| Doxycycline (CHEBI:50845; MESH:D004318) | biolink:affects | [[TFRC]] | direction=increased | "Doxycycline (Dox) was used to induced TFRC overexpression in TFRC KI MG." |
| [[APOE]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "APOECh MG protects neurons from AD insult" |
| Aβ42 (MESH:C075222) | biolink:affects | [[TFRC]] | direction=increased | "(H and I) Aβ42 induces ferroptosis gene expression in E3 but not Ch MG." |
| [[DAPT]] (MESH:C048518) | biolink:affects | Aβ42 (MESH:C075222) | direction=decreased | "(K) Blocking Aβ42 production in neurons rescues the phagocytic defect in E3 MG." |
| [[APOE]] | biolink:affects | Lipid peroxide (MESH:D008054) | direction=decreased | "(C and D) An APOE mimetic peptide decreases Aβ-induced lipid peroxidation in E3 MG." |
| [[PSEN1]] | biolink:associated_with | [[MAPT]] |  | "(C) Quantification of the percentage of pTau+ areas in WT and PSEN1 Mut BOs. n = 4 organoids." |
| [[Amyloid-beta]] | biolink:affects | Lipid peroxide (MESH:D008054) | direction=increased | "(C and D) An APOE mimetic peptide decreases Aβ-induced lipid peroxidation in E3 MG." |
