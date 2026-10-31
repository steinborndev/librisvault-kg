---
type: source
title: "Dual function TREM2 stalk antibody 4D9 in mouse microglia and APP knock-in mice"
paper_title: "Enhancing protective microglial activities with a dual function TREM2 antibody to the stalk region"
domain: neuroscience
status: seed
created: 2026-10-10
updated: 2026-10-10
content_updated: 2026-10-10
address: c-000763
pmid: "32154671"
pmcid: "PMC7136959"
doi: "10.15252/emmm.201911227"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC7136959/"
sources: ["[[.raw/01M4KPFYFQ8RZ00J40RJZ95V3M/normalized.md]]"]
tags: [microglia, monoclonal-antibody, mouse-model, amyloid, secretase]
---

# Dual function TREM2 stalk antibody 4D9 in mouse microglia and APP knock-in mice

A preclinical study that tried to raise the activity of [[TREM2]] on microglia without blocking the α-secretases [[ADAM10]] and [[ADAM17]] as a whole. The authors raised rat monoclonal antibodies against the mouse TREM2 ectodomain, screened for ones that stabilise full-length receptor at the cell surface, and characterised the best, [[4D9 monoclonal antibody]], from epitope to a 10-day treatment of [[AppNL-G-F mouse]] animals. The antibody recognises mouse TREM2 only (no binding to human TREM2 or mouse [[TREM1]]), so all work is in mouse and in mouse-receptor-expressing human cells.

## Design

- Rats were immunised with the mouse TREM2 ectodomain (residues 19-171); cleavage by ADAM10/17 lies after His157 in the stalk. Hybridoma antibodies were screened for higher membrane TREM2 and lower soluble TREM2 in [[HEK293]] Flp-In cells stably expressing mouse TREM2 and its adaptor [[TYROBP]] (DAP12), with the broad metalloprotease inhibitor [[GM6001]] as positive control and an isotype antibody as negative control.
- 4D9 was then sequenced and put on an effectorless human IgG1 backbone (L234A, L235A, P329G) so Fc receptor effects would not confound myeloid cells; a monovalent Fab was made for comparison.
- Systems: HEK293 cells, bone marrow-derived macrophages (wild-type, Trem2 heterozygous and knockout), primary microglia, wild-type mice for pharmacokinetics and target engagement, and 6-month-old AppNL-G-F knock-in mice versus wild-type given 50 mg/kg intraperitoneally on days 0, 3, 6 and 9 and analysed on day 10.
- Methods used: epitope mapping with tiled stalk peptides, surface plasmon resonance, an electrochemiluminescence (Meso Scale Discovery) ELISA for membrane and soluble TREM2, a p-SYK AlphaLISA, a CellTiter-Glo survival assay, uptake assays and immunofluorescence. See [[CSF soluble TREM2 target engagement assay]].

## Findings

- **Epitope and affinity.** 4D9 binds a 9-residue stalk peptide (DAGDLWVPE) about 12 residues N-terminal of the cleavage site; monovalent K_D 68 pM by surface plasmon resonance; cell-binding EC50 0.29 nM for the antibody and 0.17 nM for the Fab; a stalk peptide competed 4D9 off the ectodomain with an EC50 of 1.3 μM.
- **Less shedding, more surface receptor.** In HEK293 cells 4D9 raised membrane TREM2 and lowered soluble TREM2 about as much as GM6001. Both the full antibody and the Fab blocked ADAM17 cutting of a stalk peptide in a test tube, so 4D9 appears to hinder access to the substrate. In cells only the bivalent antibody reduced shedding (EC50 2.3 nM; see [[TREM2 ectodomain shedding]]).
- **Agonism.** The full antibody, not the Fab, raised phospho-[[SYK]] dose-dependently and boosted signalling from anionic liposomes 2.3-fold. The authors conclude that both actions need bivalent binding, probably by cross-linking TREM2 on the membrane, and that protease inability to cut dimeric substrates may explain the shedding block.
- **Macrophages.** In bone marrow-derived macrophages 4D9 bound wild-type but not Trem2 knockout cells, increased membrane TREM2 and lowered soluble TREM2, and rescued survival after M-CSF withdrawal (EC50 1.7 nM; 1.5 nM in heterozygous cells, with a smaller effect than in wild-type).
- **Microglia.** 4D9 bound wild-type but not Trem2 knockout primary microglia, and raised the share of cells that had taken up myelin debris and Aβ(1-42), while uptake of E. coli particles did not change. See [[Phagocytosis]].
- **Pharmacokinetics and target engagement.** After 10 mg/kg intravenously the antibody cleared like a normal IgG; brain levels were far below plasma, in the single-digit nanomolar range. Near-complete saturation of cerebrospinal fluid soluble TREM2 was reached 24 h after a single 50 mg/kg dose, falling to about 50% bound by day 10; 10 mg/kg also saturated it at 24 h, more than half was bound at 1 mg/kg and none at 0.1 mg/kg or below. Total brain TREM2 rose dose-dependently at 50 and 100 mg/kg.
- **AppNL-G-F mice.** Cortical TREM2 immunostaining was higher in untreated knock-in than wild-type mice and rose further with 4D9 (not in wild-type), with unchanged microglia (IBA1) numbers. [[P2RY12]]-positive cells, a homeostatic marker, fell with 4D9, and the changes were seen around plaques. The authors read this as a push from homeostatic toward [[Disease-associated microglia]].
- **Amyloid.** Cortical plaque area (Mann-Whitney P = 0.0082) and coverage (P = 0.014) fell, mainly the diffuse plaque halo. Soluble but not insoluble [[Amyloid-beta]] fell by immunoblot, and soluble Aβ42 fell by ELISA (P = 0.026) while insoluble Aβ42 did not change significantly (P = 0.0877).

## Why This Source Matters

It is a worked example of raising TREM2 function by an antibody that does two things at once, protecting the receptor from cleavage and activating it, rather than by a general protease inhibitor that would also impair the non-amyloidogenic processing of [[APP]] and many other ADAM10/17 substrates. It also shows a clinically translatable readout, antibody-bound versus total soluble TREM2 in cerebrospinal fluid, for confirming that a TREM2 antibody reaches its target. The authors propose human antibodies of the same mechanism for [[Alzheimer disease]] and note that amyloid plaque clearance by anti-Aβ antibodies is TREM2-dependent, which suggests a combination with [[Anti-amyloid antibody therapy]] that might allow a lower anti-Aβ dose.

## Assessment

- Mouse-specific tool antibody, and the in vivo disease experiment is one model, one dose regimen and 6 to 7 animals per group; no power calculation was done, no specific randomisation procedure was used beyond random assignment to groups after genotyping, and samples were pseudo-anonymised.
- Plaque reduction after only 10 days is called surprising by the authors, who relate it to the diffuse plaques of this model; the fate of the engulfed Aβ is unknown.
- Brain exposure was low and target engagement needed high doses; the authors suggest blood-brain barrier shuttle technology.
- Whether soluble TREM2 has functions of its own, and what chronic TREM2 enhancement does to microglia over time, are left open by the authors. They also note that opposite microglial states, locked homeostatic with TREM2 loss and locked disease-associated with [[GRN]] loss, are both harmful.
- One outlier was excluded in the Fig 3B data by a ROUT test; otherwise no exclusions were stated. The animal work was approved by a biotechnology company's animal care committee as well as a German institute's, so a commercial interest in TREM2 antibodies is likely.

## Open Questions

- Does an antibody of this mechanism raise TREM2 signalling and lower plaque load in a model with dense plaques and at later ages (the work used diffuse-plaque AppNL-G-F mice at 6 months and a 10-day dose)?
- What is the fate of the Aβ taken up by microglia after TREM2 antibody treatment (the authors state it is unknown)?
- Is soluble TREM2 itself functional, so that lowering it with a shedding-blocking antibody could be harmful (the authors flag it as unresolved)?
- Can the dual mechanism be reproduced with an antibody that binds human TREM2 and crosses the blood-brain barrier (4D9 binds mouse TREM2 only and brain levels were low)?

## Connections

- Target and cleavage enzymes: [[TREM2]], [[ADAM10]], [[ADAM17]]; process page [[TREM2 ectodomain shedding]]
- Antibody and tool compounds: [[4D9 monoclonal antibody]], [[GM6001]]
- Signalling: [[TYROBP]], [[SYK]]
- Microglial state: [[Disease-associated microglia]], [[P2RY12]], [[Phagocytosis]], [[Microglial cell activation]]
- Model and read-outs: [[AppNL-G-F mouse]], [[HEK293]], [[Amyloid-beta]], [[CSF soluble TREM2 target engagement assay]]
- Related context: [[GRN]], [[Anti-amyloid antibody therapy]], [[Alzheimer disease]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[ADAM10]] | biolink:affects | [[TREM2]] | direction=decreased | "To enhance TREM2 activity, we sought to selectively increase the full‐length protein on the cell surface via reducing its proteolytic shedding by A Disintegrin And Metalloproteinase (i.e., α‐secretase) 10/17." |
| [[TREM2]] | biolink:affects | [[SYK]] | direction=increased | "Monoclonal antibody 4D9, which has a stalk region epitope close to the cleavage site, demonstrated dual mechanisms of action by stabilizing TREM2 on the cell surface and reducing its shedding, and concomitantly activating phospho‐SYK signaling." |
| [[TREM2]] | biolink:associated_with | [[APP]] |  | "4D9 stimulated survival of macrophages and increased microglial uptake of myelin debris and amyloid β‐peptide in vitro." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "This study describes the discovery and characterization of a novel TREM2 antibody, which induces protective microglial functions and provides a basis for the development of human antibodies with a similar mechanistic profile for treatment of Alzheimer's disease." |
| [[Amyloid-beta]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We therefore need to develop strategies to interfere with the amyloid cascade immediately after it has been initially triggered by Aβ and may become independent of its further de novo production." |
| [[TREM2]] | biolink:physically_interacts_with | [[TYROBP]] |  | "Full‐length TREM2, in association with DAP12, forms a heteromeric complex required to activate phospho‐SYK signaling (Colonna, 2003)." |
| [[TREM2]] | biolink:regulates | [[SYK]] | direction=increased | "Full‐length TREM2, in association with DAP12, forms a heteromeric complex required to activate phospho‐SYK signaling (Colonna, 2003)." |
| [[TREM2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among them, coding variants in the triggering receptor expressed on myeloid cells 2 (TREM2) increase the risk for late‐onset AD as much as the apolipoprotein ε4 allele (Guerreiro et al, 2013; Jonsson & Stefansson, 2013; Jonsson et al, 2013; Rayaprolu et al, 2013; Borroni et al, 2014; Cuyvers et al, 2014)." |
| [[GM6001]] (MESH:C078131) | biolink:affects | [[TREM2]] | direction=increased | "Immunoblot analysis of membrane fractions of HEK293 Flp‐In cells stably overexpressing both mouse TREM2 and mouse DAP12 upon treatment with 4D9 antibody reveals increased levels of membrane‐bound TREM2 similar to what can be achieved by ADAM protease inhibition using the GM6001 inhibitor." |
| [[TREM2]] | biolink:affects | cholesterol esters (CHEBI:17002; MESH:D002788) | direction=decreased | "Moreover, TREM2‐deficient microglia were shown to be overloaded with cholesterol esters (CEs) as well as other lipid species as a result of chronic phagocytic challenge of myelin debris induced by a cuprizone diet (Nugent et al, 2019), indicating that TREM2 is important for lipid processing in addition to phagocytosis." |
| [[TYROBP]] | biolink:regulates | [[SYK]] | direction=increased | "Full‐length TREM2, in association with DAP12, forms a heteromeric complex required to activate phospho‐SYK signaling (Colonna, 2003)." |
| [[GM6001]] (MESH:C078131) | biolink:directly_physically_interacts_with | [[ADAM10]] |  | "Immunoblot analysis of membrane fractions of HEK293 Flp‐In cells stably overexpressing both mouse TREM2 and mouse DAP12 upon treatment with 4D9 antibody reveals increased levels of membrane‐bound TREM2 similar to what can be achieved by ADAM protease inhibition using the GM6001 inhibitor." |
| [[GM6001]] (MESH:C078131) | biolink:directly_physically_interacts_with | [[ADAM17]] |  | "Immunoblot analysis of membrane fractions of HEK293 Flp‐In cells stably overexpressing both mouse TREM2 and mouse DAP12 upon treatment with 4D9 antibody reveals increased levels of membrane‐bound TREM2 similar to what can be achieved by ADAM protease inhibition using the GM6001 inhibitor." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Among them, coding variants in the triggering receptor expressed on myeloid cells 2 (TREM2) increase the risk for late‐onset AD as much as the apolipoprotein ε4 allele (Guerreiro et al, 2013; Jonsson & Stefansson, 2013; Jonsson et al, 2013; Rayaprolu et al, 2013; Borroni et al, 2014; Cuyvers et al, 2014)." |
| TREM2 R47H (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "TREM2 has been shown to be involved in lipid sensing, a function which is diminished by the AD‐associated TREM2 R47H variant (Wang et al, 2015)." |
| cuprizone (MESH:D003471) | biolink:affects | cholesterol esters (CHEBI:17002; MESH:D002788) | direction=increased | "Moreover, TREM2‐deficient microglia were shown to be overloaded with cholesterol esters (CEs) as well as other lipid species as a result of chronic phagocytic challenge of myelin debris induced by a cuprizone diet (Nugent et al, 2019), indicating that TREM2 is important for lipid processing in addition to phagocytosis." |
| [[TREM2]] | biolink:positively_correlated_with | [[MAPT]] |  | "Moreover, sTREM2 positively correlates with total tau and phospho‐tau but not with Aβ (Suarez‐Calvet et al, 2016b)." |
| [[TREM2]] | NOT biolink:positively_correlated_with | [[Amyloid-beta]] |  | "Moreover, sTREM2 positively correlates with total tau and phospho‐tau but not with Aβ (Suarez‐Calvet et al, 2016b)." |
| [[TREM2]] | biolink:biomarker_for | mild cognitive impairment (HP:0100543; MESH:D060825) |  | "Quantitative analyses of the cleaved sTREM2 ectodomain in the cerebrospinal fluid of patients with sporadic and autosomal dominant AD (ADAD) revealed enhanced levels at the mild cognitive impairment stage (Suarez‐Calvet et al, 2016b, 2019) and up to 5 years before the estimated onset of ADAD (Suarez‐Calvet et al, 2016a), respectively." |
| [[TREM2]] | biolink:negatively_correlated_with | [[Hippocampal atrophy]] |  | "Furthermore, high levels of CSF sTREM2 predict a better outcome of cognition and reduced hippocampal shrinkage in the Alzheimer's disease neuroimaging initiative cohort (Ewers et al, 2019)." |
| [[ADAM10]] | biolink:affects | [[Amyloid-beta]] | direction=decreased | "However, α‐secretase competes with the amyloidogenic pathway and limits Aβ production (Haass & Selkoe, 1993); therefore, its inhibition in AD would be not be efficacious." |
| [[Amyloid-beta]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Taken in combination with the observation that TREM2 loss of function increases AD risk, this suggests that enhancing TREM2 signaling represents a therapeutic strategy that is downstream of the initial Aβ‐mediated trigger of the amyloid cascade." |
| Fab (MESH:D007140) | biolink:directly_physically_interacts_with | [[TREM2]] |  | "Next, we generated Fab fragments of 4D9, which specifically bound cell‐surface TREM2 on HEK293 cells with an EC50 of 0.17 nM (Fig 2A)." |
| Immunoglobulin G (MESH:D007074) | NOT biolink:physically_interacts_with | [[TREM2]] |  | "A dose response demonstrated a cell binding EC50 of 0.29 nM, while an isotype control antibody did not show measurable binding (Fig 2A)." |
| anionic liposome (MESH:D008081) | biolink:affects | [[TREM2]] | direction=increased | "Furthermore, anionic liposome ligand (Shirotani et al, 2019) stimulated TREM2 signaling 2.3‐fold by full‐length 4D9 but not by 4D9 Fab or the isotype control (Fig 2E)." |
| Fab (MESH:D007140) | biolink:affects | [[ADAM17]] | direction=decreased | "In vitro ADAM17 sheddase activity is blocked by 4D9‐effectorless mAb and 4D9 Fab fragment but not an isotype control." |
| Fab (MESH:D007140) | NOT biolink:affects | [[SYK]] | direction=increased | "This revealed a dose‐dependent increase in p‐SYK upon addition of 4D9 but not 4D9 Fab to the culture media of the cells (Fig 2D)." |
| streptavidin (CHEBI:201453; MESH:D019809) | biolink:directly_physically_interacts_with | biotin (CHEBI:15956; MESH:D001710) |  | "Cell‐surface binding of biotinylated 4D9 was confirmed by FACS with fluorophore‐conjugated streptavidin detection and found to be statistically significant on BMDM differentiated from three wild‐type mice compared with an isotype control (Fig 3A)." |
| [[TREM2]] | biolink:associated_with | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) |  | "Thus, 4D9 enhances TREM2‐dependent functions in myeloid phagocytes of the periphery and the central nervous system." |
| [[TREM2]] | biolink:associated_with | Myelin (MESH:D009185) |  | "Thus, 4D9 enhances TREM2‐dependent functions in myeloid phagocytes of the periphery and the central nervous system." |
| [[APP]] | biolink:positively_correlated_with | [[TREM2]] |  | "Control‐treated APP knock‐in mice showed elevated TREM2 expression as compared to non‐transgenic C57BL6 mice (Fig 6B and C), reflecting a shift to a disease‐associated state (Krasemann et al, 2017)." |
| [[TREM2]] | biolink:negatively_correlated_with | [[P2RY12]] |  | "Moreover, increased TREM2 and decreased P2RY12 expression was specifically observed in areas where microglia apparently clustered around amyloid plaques (Fig 6B and E)." |
| [[TREM2]] | biolink:associated_with | Amyloid plaque (MESH:D058225) |  | "Moreover, increased TREM2 and decreased P2RY12 expression was specifically observed in areas where microglia apparently clustered around amyloid plaques (Fig 6B and E)." |
| [[Amyloid-beta]] | biolink:associated_with | Amyloid plaque (MESH:D058225) |  | "This was further confirmed by Western blot analysis of soluble and insoluble Aβ demonstrating that 4D9 treatment specifically results in a reduction in soluble but not insoluble Aβ (Fig 7F)." |
| [[P2RY12]] | biolink:negatively_correlated_with | Amyloid plaque (MESH:D058225) |  | "Moreover, increased TREM2 and decreased P2RY12 expression was specifically observed in areas where microglia apparently clustered around amyloid plaques (Fig 6B and E)." |
| [[APP]] | biolink:associated_with | AIF1 (HGNC:352) |  | "Quantification of cortical IBA1 staining shown in B." |
| [[APP]] | biolink:associated_with | [[P2RY12]] |  | "Quantification of P2RY12‐stained cells in the cortex shown in (E)." |
| [[APP]] | biolink:has_phenotype | Amyloid plaque (MESH:D058225) |  | "Overview of the cortex immunohistochemically stained for Aβ plaques in 6‐month‐old APP‐NL‐G‐F mice treated with isotype control (A) and 4D9 antibody (B)." |
| [[AppNL-G-F mouse]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Immunoblot analysis of soluble (DEA fraction, top) and insoluble Aβ levels (FA fraction, bottom) in brains of APP‐NL‐G‐F mice treated with either isotype control or 4D9 antibody." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | Amyloid plaque (MESH:D058225) |  | "Overview of the cortex immunohistochemically stained for Aβ plaques in 6‐month‐old APP‐NL‐G‐F mice treated with isotype control (A) and 4D9 antibody (B)." |
| [[AppNL-G-F mouse]] | biolink:has_phenotype | Amyloid plaque (MESH:D058225) |  | "Overview of the cortex immunohistochemically stained for Aβ plaques in 6‐month‐old APP‐NL‐G‐F mice treated with isotype control (A) and 4D9 antibody (B)." |
| [[TREM2]] | biolink:associated_with | [[GRN]] |  | "Strikingly, both opposite phenotypes are deleterious to brain health, and absence of either TREM2 or PGRN causes similar brain‑wide disturbances in energy metabolism as measured by FDG‑PET (Gotzl et al, 2019)." |
| [[TREM2]] | biolink:associated_with | Retinal degeneration (MONDO:0004580; MESH:D012162) |  | "Microgliosis is observed in numerous neurological disorders, and only recently evidence has been presented that TREM2‑dependent microglial functions appear to be protective in AD models (Ulland et al, 2017; Focke et al, 2019; Parhizkar et al, 2019), AD patients (Ewers et al, 2019), and models of retinal degeneration (O'Koren et al, 2019)." |
| TREM2 H157Y (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Additional evidence for the signaling capacity of full‑length TREM2 comes from the analysis of the AD‑associated p.TREM2 H157Y variant (Jiang et al, 2016) which increases shedding of TREM2 and concomitantly reduces TREM2‑dependent phagocytosis (Schlepckow et al, 2017), thus furthermore indicating that the amount of cell‑surface TREM2 correlates with microglial activity." |
| amyloid (MONDO:0019065; MESH:D058225) | biolink:associated_with | Amyloid-beta oligomers (CHEBI:132554) |  | "Since 4D9 appears to selectively reduce soluble Aβ associated with the plaque halo, one may even argue that antibody treatment reduces the amount of toxic Aβ oligomers liberated by amyloid plaques." |
| [[TREM2]] | biolink:associated_with | frontotemporal lobar degeneration (MESH:D057174) |  | "This may indicate that TREM2‐stimulating therapeutic approaches could be employed in a variety of different clinical syndromes including AD, frontotemporal lobar degeneration, amyotrophic lateral sclerosis, retinal degeneration, multiple sclerosis, and obesity‐associated metabolic syndromes." |
| [[TREM2]] | biolink:associated_with | amyotrophic lateral sclerosis (MONDO:0004976; MESH:D000690) |  | "This may indicate that TREM2‐stimulating therapeutic approaches could be employed in a variety of different clinical syndromes including AD, frontotemporal lobar degeneration, amyotrophic lateral sclerosis, retinal degeneration, multiple sclerosis, and obesity‐associated metabolic syndromes." |
| [[TREM2]] | biolink:associated_with | multiple sclerosis (MONDO:0005301; MESH:D009103) |  | "This may indicate that TREM2‐stimulating therapeutic approaches could be employed in a variety of different clinical syndromes including AD, frontotemporal lobar degeneration, amyotrophic lateral sclerosis, retinal degeneration, multiple sclerosis, and obesity‐associated metabolic syndromes." |
| [[TREM2]] | biolink:associated_with | [[Obesity]] (MESH:D009765) |  | "This may indicate that TREM2‐stimulating therapeutic approaches could be employed in a variety of different clinical syndromes including AD, frontotemporal lobar degeneration, amyotrophic lateral sclerosis, retinal degeneration, multiple sclerosis, and obesity‐associated metabolic syndromes." |
| [[TREM2]] | biolink:associated_with_decreased_likelihood_of | adipocyte hypertrophy (HP:0030759) |  | "In fact, recent work demonstrated TREM2‐dependent protective functions in lipid‐associated peripheral macrophages, showing effects on lipid uptake and metabolism that are important for the prevention of adipocyte hypertrophy under conditions of a high‐fat diet (Jaitin et al, 2019)." |
| [[TREM2]] | biolink:associated_with | amyloid (MONDO:0019065; MESH:D058225) |  | "A combinatorial treatment strategy may therefore boost amyloid clearance via enhancement of TREM2‐dependent microglial activity and thus enable lower dosing of the anti‐Aβ antibody." |
| aducanumab (CHEBI:755082; MESH:C000600266) | biolink:in_clinical_trials_for | [[Alzheimer disease]] (MESH:D000544) |  | "This may be specifically of interest in light of the recent findings that a clinical trial using the anti‐Aβ antibody aducanumab, though controversial, suggests that treatment may slow clinical decline of patients at the highest dose of the drug." |
| aducanumab (CHEBI:755082; MESH:C000600266) | biolink:directly_physically_interacts_with | [[APP]] |  | "This may be specifically of interest in light of the recent findings that a clinical trial using the anti‐Aβ antibody aducanumab, though controversial, suggests that treatment may slow clinical decline of patients at the highest dose of the drug." |
| aducanumab (CHEBI:755082; MESH:C000600266) | biolink:associated_with | amyloid (MONDO:0019065; MESH:D058225) |  | "A combinatorial treatment strategy may therefore boost amyloid clearance via enhancement of TREM2‐dependent microglial activity and thus enable lower dosing of the anti‐Aβ antibody." |
