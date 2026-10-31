---
type: source
title: "Circulating microRNA biomarkers for Alzheimer disease by database mining"
paper_title: "Systematic Search for Novel Circulating Biomarkers Associated with Extracellular Vesicles in Alzheimer's Disease: Combining Literature Screening and Database Mining Approaches"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000179
pmid: "34683087"
pmcid: "PMC8538213"
doi: "10.3390/jpm11100946"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8538213/"
sources: ["[[.raw/01M4DY94J6ADJT7H5GCS780HD7/normalized.md]]"]
tags: [biomarker, microrna]
---

# Circulating microRNA biomarkers for Alzheimer disease by database mining

A computational prioritisation of microRNAs (miRNAs) that could serve as blood-based markers of [[Alzheimer disease]]. The authors cross two public resources, one of experimentally validated miRNA-target interactions and one of disease-associated miRNAs, with a literature list of miRNAs carried in [[Extracellular vesicle]] cargo, and then rank each candidate by the kind of sample in which it was seen. No new wet-lab measurements were made.

## Design

- Approach 1 (vesicle route): a PubMed search for original articles from November 2014 to the end of February 2021 using the keywords Alzheimer's disease, extracellular vesicle and miRNA gave 144 unique vesicle-associated miRNAs from 68 publications. These were joined to 105 genes previously linked to Alzheimer risk or biomarker levels in genome-wide studies, and enriched for interactions in miRTarBase.
- Approach 2 (phenotype route): every miRNA annotated to Alzheimer disease in the Human microRNA Disease Database (115 unique after de-duplication) was joined to all target genes in miRTarBase. See [[MicroRNA-target interaction databases]].
- Prioritisation: the 169 unique miRNAs from the disease database were graded by where the original papers saw them: Alzheimer patient samples (very strong), Alzheimer animal or cell models (strong), non-Alzheimer models (possible), or in silico prediction only (potential). Original papers were then read for the specific interactions reported. Overlap between categories was drawn as a Venn diagram.

## Findings

- The vesicle list and the disease-database list shared only six miRNAs: miR-29c, miR-136-3p, miR-16-2, miR-132-5, miR-331-5p and miR-485-5p. The vesicle route gave 215 interactions and the disease-database route 942.
- Four interactions were common to both routes: miR-375 with [[APH1B]], miR-107 with [[CDC42SE2]], miR-375 with [[CELF2]] and miR-107 with [[IL6]]. These make [[MIR375]] and [[MIR107]] the leading vesicle-linked candidates.
- Of 169 miRNAs, 88 were very strong candidates: 61 (36.1%) seen in body fluids and 27 (16%) in brain tissue, with 14 in both. A further 28 were strong candidates (22 animal, 6 cell models), 40 possible candidates (30 cell, 10 animal non-Alzheimer models) and 13 only predicted in silico. Only [[MIR34A]] appeared in all four categories.
- Of 84 unique interactions curated from the papers, 7 (8.3%) were experimentally validated in body fluids of patients and 34 (40.5%) in Alzheimer brain tissue; 19 were found in Alzheimer animal models and 7 in Alzheimer cell cultures, with 17 in non-Alzheimer cell cultures and 12 in non-Alzheimer animal models.
- The seven body-fluid interactions, each confirmed with reporter assay, RT-qPCR and Western blot, were miR-193b with [[APP]] ([[MIR193B]]), miR-29c with [[BACE1]] and with a DNMT3 methyltransferase ([[MIR29C]]), miR-613 with [[BDNF]] ([[MIR613]]), miR-206 with [[IGF1]] ([[MIR206]]), miR-128 with [[PPARG]], and miR-146a with [[TLR2]] ([[MIR146A]]). The miR-193b interaction with APP was also seen in vesicles.
- The authors single out six circulating candidates (miR-193b, miR-29c, miR-613, miR-206, miR-128, miR-146a) and two vesicle-related ones (miR-375, miR-107).

## Biological context given for the top targets

- APH1B is a subunit of the gamma-secretase complex that, with the presenilins and PEN2, cuts APP; its missense variant [[APH1B rs117618017]] is cited as a high-confidence risk variant. CELF2 is an RNA-binding protein involved in alternative splicing of [[TREM2]], and [[CELF2 rs201119]] is cited as raising risk.
- [[CDC42SE2 rs382216]] is cited as lowering risk in a genome-wide study, and [[IL6 rs1800796]] as raising risk in a meta-analysis; IL6 is raised in Alzheimer brain.
- The miR-146a coding-region variant [[MIR146A rs2910164]] is cited as a risk allele; miR-146a is raised in postmortem Alzheimer brain.

## Why This Source Matters

It supplies a ranked, evidence-graded shortlist of miRNA-target pairs that connects the established genetic risk genes of Alzheimer disease to candidate peripheral biomarkers, and it documents that vesicle-derived miRNA lists and disease-database miRNA lists barely overlap. That mismatch matters for any blood-test design, including the plasma miRNA panel of [[Fluorescent nanoparticle kit for early Alzheimer disease diagnosis]], where [[MIR34A]] is also a marker.

## Assessment

- The work is a database and literature synthesis: candidates are ranked by where they were reported, not by pooled effect sizes, and no statistical test of biomarker performance was run.
- The authors note that several studies found no significant difference in miR-146a, miR-107, miR-375 or miR-29c in cerebrospinal fluid or blood, that expression is usually reported relative to other miRNAs, and that cut-off values are rarely given.
- Vesicle-enriched miRNA sets can differ from total miRNA in a sample, and isolation methods differ between studies, so the vesicle list is heterogeneous.
- The miR-375 interactions with APH1B and CELF2 were confirmed in a gastric carcinoma sample, not in an Alzheimer sample.
- Searches were run on one date (25 March 2021) in two databases, so later entries are absent.

## Open Questions

- Do miR-375 and miR-107 bind APH1B, CELF2, CDC42SE2 and IL6 in neuron-derived vesicles from Alzheimer patients (the interactions were validated only in other tissues or cell models)?
- What plasma or cerebrospinal fluid cut-off values separate Alzheimer patients from controls for miR-193b, miR-29c, miR-613, miR-206, miR-128 and miR-146a (no study in the survey reported usable cut-offs)?
- Why do the vesicle-associated miRNA list and the Alzheimer-annotated miRNA list share only six miRNAs (differences in vesicle isolation method, or in study design, were not tested)?

## Connections

- Disease: [[Alzheimer disease]], with the stages [[Early-onset Alzheimer disease]], [[Late-onset Alzheimer disease]] and [[Mild cognitive impairment]] described in the background.
- miRNAs: [[MIR375]], [[MIR107]], [[MIR193B]], [[MIR29C]], [[MIR613]], [[MIR206]], [[MIR146A]], [[MIR34A]]
- Targets: [[APH1B]], [[CELF2]], [[CDC42SE2]], [[IL6]], [[APP]], [[BACE1]], [[BDNF]], [[IGF1]], [[PPARG]], [[TLR2]]
- Variants cited: [[APH1B rs117618017]], [[CELF2 rs201119]], [[CDC42SE2 rs382216]], [[IL6 rs1800796]], [[MIR146A rs2910164]]
- Concepts: [[Extracellular vesicle]], [[MicroRNA-target interaction databases]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[MIR375]] | biolink:regulates | [[APH1B]] |  | "Four common MTI were observed between EV-miRNAs and AD-associated miRNAs: hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6." |
| [[MIR107]] | biolink:regulates | [[CDC42SE2]] |  | "Four common MTI were observed between EV-miRNAs and AD-associated miRNAs: hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6." |
| [[MIR375]] | biolink:regulates | [[CELF2]] |  | "Four common MTI were observed between EV-miRNAs and AD-associated miRNAs: hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6." |
| [[MIR107]] | biolink:regulates | [[IL6]] |  | "Four common MTI were observed between EV-miRNAs and AD-associated miRNAs: hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6." |
| [[MIR375]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Four common MTI were observed between EV-miRNAs and AD-associated miRNAs: hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6." |
| [[MIR107]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Four common MTI were observed between EV-miRNAs and AD-associated miRNAs: hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6." |
| [[MAPT]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Decreased amyloid-β (Aβ1–42), increased total Tau (tTau), and phospho Tau (pTau) from CSF are used in clinical practice as suitable biomarkers to support AD diagnostics." |
| [[MAPT]] | biolink:biomarker_for | neurofibrillary tangles (HP:0002185) |  | "Detectable cerebrospinal fluid (CSF) proteins reflect cerebral accumulation of insoluble plaques and aggregation of neurofibrillary tangles (NFT), two major hallmarks of AD." |
| microRNA (MESH:D035683) | biolink:affects | messenger RNA (CHEBI:33699; MESH:D012333) | direction=decreased | "Upon binding primarily to the 3′ untranslated region of the messenger RNAs (mRNAs), miRNAs block the translation or lead to degradation of target mRNAs." |
| microRNA (MESH:D035683) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Circulating miRNAs and target genes bear great potential as AD-related biomarkers and could provide valuable insight into the cellular mechanisms of AD pathology." |
| microRNA (MESH:D035683) | biolink:contributes_to | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "miRNAs play an important role in neurodegenerative diseases." |
| amyloid-β (CHEBI:64645; MESH:D016229) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Decreased amyloid-β (Aβ1–42), increased total Tau (tTau), and phospho Tau (pTau) from CSF are used in clinical practice as suitable biomarkers to support AD diagnostics." |
| amyloid-β (CHEBI:64645; MESH:D016229) | biolink:biomarker_for | amyloid plaques (MESH:D058225) |  | "Detectable cerebrospinal fluid (CSF) proteins reflect cerebral accumulation of insoluble plaques and aggregation of neurofibrillary tangles (NFT), two major hallmarks of AD." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "AD-associated tau phosphoforms have been found in EVs isolated from AD patients." |
| amyloid beta (CHEBI:10545; MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Both amyloid and tau pathologies have been associated with neuronal-derived EVs." |
| microRNA (MESH:D035683) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Several case-control studies identified miRNAs enriched in EVs (EV-miRNAs) isolated from body fluids in AD patients." |
| [[MIR29C]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Only six miRNAs were common between both datasets: hsa-miR-29c, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p." |
| MIR136 (HGNC:31522) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Only six miRNAs were common between both datasets: hsa-miR-29c, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p." |
| MIR16-2 (HGNC:31546) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Only six miRNAs were common between both datasets: hsa-miR-29c, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p." |
| [[MIR132]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Only six miRNAs were common between both datasets: hsa-miR-29c, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p." |
| MIR331 (HGNC:31772) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Only six miRNAs were common between both datasets: hsa-miR-29c, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p." |
| MIR485 (HGNC:32067) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Only six miRNAs were common between both datasets: hsa-miR-29c, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p." |
| [[MIR34A]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Only one miRNA, hsa-mir-34a, was observed in all four categories." |
| [[MIR375]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "An overlap between the two approaches showed four common MTI, hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6, with the greatest potential as EV-miRNA circulating biomarkers (Table 1)." |
| [[MIR107]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "An overlap between the two approaches showed four common MTI, hsa-miR-375–APH1B, hsa-miR-107–CDC42SE2, hsa-miR-375–CELF2, and hsa-miR-107–IL6, with the greatest potential as EV-miRNA circulating biomarkers (Table 1)." |
| [[APH1B]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Combining EV-miRNAs from 68 publications with a list of 105 AD-related genes resulted in 215 specific MTI." |
| [[CELF2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Combining EV-miRNAs from 68 publications with a list of 105 AD-related genes resulted in 215 specific MTI." |
| [[CDC42SE2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Combining EV-miRNAs from 68 publications with a list of 105 AD-related genes resulted in 215 specific MTI." |
| [[IL6]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Combining EV-miRNAs from 68 publications with a list of 105 AD-related genes resulted in 215 specific MTI." |
| mRNAs (CHEBI:33699) | biolink:associated_with | neurodegenerative disorders (MONDO:0000001; MESH:D019636) |  | "EV cargo has been extensively studied in neurodegenerative disorders. Differentially expressed EVs enriched mRNAs and miRNAs in blood serum and CSF were reported (reviewed in)." |
| microRNA (MESH:D035683) | biolink:associated_with | neurodegenerative disorders (MONDO:0000001; MESH:D019636) |  | "EV cargo has been extensively studied in neurodegenerative disorders. Differentially expressed EVs enriched mRNAs and miRNAs in blood serum and CSF were reported (reviewed in)." |
| [[MIR29C]] | biolink:regulates | [[BACE1]] |  | "Using the HMDD, seven MTI (hsa-miR-193b–APP, hsa-miR-29c–BACE1, hsa-miR-613–BDNF, hsa-miR-29c–DNMT3, hsa-miR-206–IGF1, hsa-miR-128–PPARG, and hsa-miR-146a–TLR2) were observed in the body fluids of AD patients." |
| [[MIR193B]] | biolink:regulates | [[APP]] |  | "Using the HMDD, seven MTI (hsa-miR-193b–APP, hsa-miR-29c–BACE1, hsa-miR-613–BDNF, hsa-miR-29c–DNMT3, hsa-miR-206–IGF1, hsa-miR-128–PPARG, and hsa-miR-146a–TLR2) were observed in the body fluids of AD patients." |
| [[MIR613]] | biolink:regulates | [[BDNF]] |  | "Using the HMDD, seven MTI (hsa-miR-193b–APP, hsa-miR-29c–BACE1, hsa-miR-613–BDNF, hsa-miR-29c–DNMT3, hsa-miR-206–IGF1, hsa-miR-128–PPARG, and hsa-miR-146a–TLR2) were observed in the body fluids of AD patients." |
| [[MIR206]] | biolink:regulates | [[IGF1]] |  | "Using the HMDD, seven MTI (hsa-miR-193b–APP, hsa-miR-29c–BACE1, hsa-miR-613–BDNF, hsa-miR-29c–DNMT3, hsa-miR-206–IGF1, hsa-miR-128–PPARG, and hsa-miR-146a–TLR2) were observed in the body fluids of AD patients." |
| [[MIR146A]] | biolink:regulates | [[TLR2]] |  | "Using the HMDD, seven MTI (hsa-miR-193b–APP, hsa-miR-29c–BACE1, hsa-miR-613–BDNF, hsa-miR-29c–DNMT3, hsa-miR-206–IGF1, hsa-miR-128–PPARG, and hsa-miR-146a–TLR2) were observed in the body fluids of AD patients." |
| [[APH1B]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Therefore, APH1B was also proposed as an AD-risk locus." |
| [[PSEN1]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "APP, PS1, and PS2, encoded by APP, PSEN1, and PSEN2, are common causative genes for a familial, early-onset type of AD." |
| [[PSEN2]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "APP, PS1, and PS2, encoded by APP, PSEN1, and PSEN2, are common causative genes for a familial, early-onset type of AD." |
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "APP, PS1, and PS2, encoded by APP, PSEN1, and PSEN2, are common causative genes for a familial, early-onset type of AD." |
| [[APH1B rs117618017]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "APH1B missense variant rs117618017 was recently identified as a high-confidence AD risk variant." |
| [[TREM2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Multiple genetics studies revealed TREM2 as an important AD risk locus." |
| [[CELF2 rs201119]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, CELF2 rs201119 was associated with increased AD risk." |
| [[IL6]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Elevated IL6 levels have been observed in AD brain tissue." |
| [[CDC42SE2 rs382216]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "CDC42SE2 rs382216 was associated with decreased AD risk in a GWAS study." |
| [[IL6 rs1800796]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Recently, rs1800796 in IL6 has been associated with increased AD risk in a meta-analysis." |
| IL6R (HGNC:6019) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, multiple polymorphisms in gene coding for IL6 receptors (IL6R) were found in AD GWAS studies." |
| [[MIR193B]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Later on, the potential of hsa-miR-193b as an early diagnostic circulating biomarker was confirmed." |
| [[BACE1]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Since it has been discovered in CSF, the potential of BACE1 as an AD biomarker was extensively studied." |
| [[MIR29C]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Potential use of hsa-miR-29c as an AD circulating biomarker was further confirmed using RNA deep sequencing." |
| [[BDNF]] | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In AD brains, decreased BDNF levels have been reported." |
| [[MIR613]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "hsa-miR-613 as an interacting partner of BDNF was detected in the serum and CSF of AD patients and AD mouse models." |
| [[MIR375]] | biolink:associated_with | neurological disorders (MESH:D009422) |  | "The importance of hsa-miR-375 has also been studied in neurological disorders." |
| [[APH1B]] | biolink:physically_interacts_with | [[PSEN1]] |  | "Together with PS1/PS2 and PEN2, it is involved in cleavage of amyloid-precursor proteins (APP) in the amyloid cascade." |
| [[APH1B]] | biolink:physically_interacts_with | [[PSEN2]] |  | "Together with PS1/PS2 and PEN2, it is involved in cleavage of amyloid-precursor proteins (APP) in the amyloid cascade." |
| [[APH1B]] | biolink:physically_interacts_with | PSENEN (HGNC:30100) |  | "Together with PS1/PS2 and PEN2, it is involved in cleavage of amyloid-precursor proteins (APP) in the amyloid cascade." |
| [[APH1B]] | biolink:affects | [[APP]] |  | "Together with PS1/PS2 and PEN2, it is involved in cleavage of amyloid-precursor proteins (APP) in the amyloid cascade." |
| [[APH1B]] | biolink:causes | neurodegeneration (HP:0002180) |  | "Depletion of Aph1b in mice leads to a progressive neurodegenerative phenotype and indicates APH1B as a potential AD treatment target." |
| [[CELF2]] | biolink:regulates | [[TREM2]] |  | "CELF2 is an RNA-binding protein implicated in alternative splicing of TREM2." |
| [[PSEN1]] | biolink:affects | [[APP]] |  | "Together with PS1/PS2 and PEN2, it is involved in cleavage of amyloid-precursor proteins (APP) in the amyloid cascade." |
| [[PSEN2]] | biolink:affects | [[APP]] |  | "Together with PS1/PS2 and PEN2, it is involved in cleavage of amyloid-precursor proteins (APP) in the amyloid cascade." |
| PSENEN (HGNC:30100) | biolink:affects | [[APP]] |  | "Together with PS1/PS2 and PEN2, it is involved in cleavage of amyloid-precursor proteins (APP) in the amyloid cascade." |
| [[BACE1]] | biolink:affects | [[APP]] |  | "BACE1 is a secretase, mediating a two-step generation of Aβ through APP cleavage." |
| [[APP]] | biolink:affects | amyloid-β (CHEBI:64645; MESH:D016229) |  | "BACE1 is a secretase, mediating a two-step generation of Aβ through APP cleavage." |
| [[IL6]] | biolink:associated_with | neurodegeneration (HP:0002180) |  | "Multiple lines of evidence link IL6 with neurodegeneration." |
| [[TREM2]] | biolink:associated_with | amyloid-β (CHEBI:64645; MESH:D016229) |  | "TREM2 is a key player in the microglial response to increased amyloid burden." |
| [[TREM2]] | biolink:associated_with | inflammation (MESH:D007249) |  | "The effect of TREM2 in neuronal inflammation, present also in AD, has been extensively studied." |
| CDC42 (HGNC:1736) | biolink:regulates | [[CDC42SE2]] |  | "CDC42SE2 is a potential actin cytoskeleton modulator acting downstream of CDC42." |
| [[BACE1]] | biolink:affects | amyloid-β (CHEBI:64645; MESH:D016229) | direction=increased | "BACE1 is a secretase, mediating a two-step generation of Aβ through APP cleavage." |
| [[MIR146A]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Multiple studies proposed hsa-miR-146a as an AD circulating biomarker." |
| [[MIR146A rs2910164]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Increased AD risk effect of rs2910164 minor allele in the miR-146a coding region was reported." |
| [[TLR2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The activation of TLR2 induces neurodegeneration and cognitive deficit in AD murine models." |
| TLR2 polymorphisms (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Further evidence elucidated the role of immune system in AD development, including TLR2 polymorphisms associated with AD in Asian populations." |
| [[PPARG]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Upregulation of hsa-miR-128 lead to downregulation of PPARG in clinical AD samples and AD cell models." |
| PPARG polymorphisms (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, the effect of PPARG polymorphisms on AD risk and age of onset was evaluated." |
| [[IGF1]] | biolink:negatively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Decreases in serum levels of IGF1 have been linked to AD." |
| IGF1 polymorphism (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In terms of genetics, only one IGF1 polymorphism was associated with AD risk in the Chinese Han population." |
| [[MIR206]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Further studies confirmed the potential of hsa-miR-206 as a circulating AD biomarker." |
| MIR136 (HGNC:31522) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Although hsa-mir-34a, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p were proposed as AD biomarkers using both approaches, no significant MTI were identified." |
| MIR16-2 (HGNC:31546) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Although hsa-mir-34a, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p were proposed as AD biomarkers using both approaches, no significant MTI were identified." |
| [[MIR132]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Although hsa-mir-34a, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p were proposed as AD biomarkers using both approaches, no significant MTI were identified." |
| MIR331 (HGNC:31772) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Although hsa-mir-34a, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p were proposed as AD biomarkers using both approaches, no significant MTI were identified." |
| MIR485 (HGNC:32067) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Although hsa-mir-34a, hsa-miR-136-3p, hsa-miR-16-2, hsa-miR-132-5, hsa-miR-331-5p, and hsa-miR-485-5p were proposed as AD biomarkers using both approaches, no significant MTI were identified." |
| [[MIR146A]] | biolink:physically_interacts_with | [[TLR2]] |  | "An experimental interaction of hsa-miR-146a with TLR2 was reported." |
| [[MIR146A]] | biolink:associated_with | inflammation (MESH:D007249) |  | "The effect of hsa-miR-146a as a switch for reduced proinflammatory microglial phenotypes was proposed." |
| [[TLR2]] | biolink:causes | neurodegeneration (HP:0002180) |  | "The activation of TLR2 induces neurodegeneration and cognitive deficit in AD murine models." |
| [[TLR2]] | biolink:causes | cognitive deficit (HP:0001268; MESH:D060825) |  | "The activation of TLR2 induces neurodegeneration and cognitive deficit in AD murine models." |
| [[IGF1]] | biolink:biomarker_for | neurodegeneration (HP:0002180) |  | "The effects of IGF1 on cell survival, apoptosis, and stimulation of neurogenesis in the hippocampus can predict neurodegeneration, encompassing AD." |
| [[IGF1]] | biolink:associated_with | cognitive deficit (HP:0001268; MESH:D060825) |  | "IGF1 levels were associated with cognitive decline in diabetic patients." |
| [[PPARG]] | biolink:associated_with | glucose (CHEBI:17234; MESH:D005947) |  | "PPARG is a receptor involved in lipid and glucose metabolism." |
| [[PPARG]] | biolink:associated_with | amyloid-β (CHEBI:64645; MESH:D016229) |  | "Interaction of a neuroprotective agent with PPARG has been discussed, suggesting the importance of PPARG in Aβ formation during inflammation." |
| [[PPARG]] | biolink:associated_with | inflammation (MESH:D007249) |  | "Interaction of a neuroprotective agent with PPARG has been discussed, suggesting the importance of PPARG in Aβ formation during inflammation." |
| [[IGF1]] | biolink:associated_with | insulin resistance (HP:0000855; MESH:D007333) |  | "Insulin growth factor-1 (IGF1) is a hormonal regulator of insulin resistance in diabetes." |
| [[IGF1]] | biolink:associated_with | diabetes (MONDO:0005015) |  | "Insulin growth factor-1 (IGF1) is a hormonal regulator of insulin resistance in diabetes." |
| [[MIR206]] | biolink:associated_with | [[IGF1]] |  | "Upregulation of hsa-miR-206 in AD blood samples was linked to IGF1 and AD-related inflammation." |
| [[MIR206]] | biolink:associated_with | inflammation (MESH:D007249) |  | "Upregulation of hsa-miR-206 in AD blood samples was linked to IGF1 and AD-related inflammation." |
| [[MIR613]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "miRNAs hsa-miR-193b, hsa-miR-29c, hsa-miR-613, hsa-miR-206, hsa-miR-128, and hsa-miR-146a represent the most promising circulating AD biomarkers, while miRNAs hsa-miR-375 and hsa-miR-107 could be promising EV-related AD biomarkers." |
