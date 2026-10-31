---
type: source
title: "ZnO-osthol nanoparticles protect APP-overexpressing neuroblastoma cells"
paper_title: "Inhibition of Glycogen Synthase Kinase and the Neuroprotective Function of Conjugated ZnO-Osthol Nanoparticles in Alzheimer's Disease"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000322
pmid: "39281976"
pmcid: "PMC11401704"
doi: "10.1155/2022/1401995"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC11401704/"
sources: ["[[.raw/01M4DY94PG2B25AXFWEJ8NRBTS/normalized.md]]"]
tags: [apoptosis, microrna, nanoparticle]
---

# ZnO-osthol nanoparticles protect APP-overexpressing neuroblastoma cells

An in vitro study of whether the plant coumarin [[Osthol]], conjugated to [[Zinc oxide]] nanoparticles, protects human neuroblastoma cells from toxicity caused by overexpressed amyloid precursor protein, a cellular model of [[Alzheimer disease]]. The authors propose that osthol raises the microRNA [[MIR132]], acts on the Wnt/β-catenin pathway and so preserves synaptic proteins.

## Design

- Nanoparticles: zinc oxide nanoparticles were made by Nd:YAG laser ablation of zinc oxide pellets in deionized water and checked by X-ray diffraction and transmission electron microscopy (spherical, mean 35 nm). Pulsing purified osthol with the zinc oxide gave conjugates of about 149 nm by TEM, with an osthol grain size of 65 nm by X-ray diffraction.
- Cell model: [[BE2-M17]] human neuroblastoma cells were transduced with a lentiviral [[APP]] vector (empty vector as control). Amyloid beta 1-42 protein by western blot and APP transcript by RT-PCR confirmed the model from the third day after transduction. Osthol was applied at 50 μM from a DMSO stock.
- Read-outs: cell viability by CCK-8, apoptosis by annexin V-FITC/propidium iodide flow cytometry, miR-132 and pathway transcripts by RT-qPCR, and proteins by western blot. Results are given as mean ± SD with Student's t test or analysis of variance, P < 0.05 taken as significant.

## Findings

- APP overexpression lowered cell viability and raised [[Apoptosis]] in BE2-M17 cells; zinc oxide-osthol restored viability and reduced apoptosis.
- APP transduction lowered miR-132, and osthol treatment raised it above empty-vector cells.
- The synaptic proteins [[SYN1]] (synapsin-1), [[SYP]] (synaptophysin) and [[DLG4]] (PSD-95) fell in APP-overexpressing cells and were restored by zinc oxide-osthol. An anti-miR-132 inhibitor lowered synapsin-1, and zinc oxide-osthol reversed that effect.
- Western blot and RT-qPCR of [[CDH13]], [[GSK3B]], phosphorylated GSK-3β and phosphorylated [[CTNNB1]] (β-catenin) showed lower levels after zinc oxide-osthol than in APP-overexpressing controls. The authors read this as osthol engaging [[Wnt signaling pathway]] control of GSK-3β, upstream of the tau hyperphosphorylation that builds [[Neurofibrillary tangle]], and conclude that osthol is a candidate Alzheimer drug.

## Why This Source Matters

It links a natural coumarin and a metal-oxide carrier to a miR-132 and GSK-3β/β-catenin account of synapse protection in an amyloid precursor protein cell model, adding a pharmacological angle to the [[MIR132]] literature, where the microRNA is otherwise studied as a marker or mediator. As evidence it is a single-cell-line, hypothesis-generating study rather than a demonstration of a mechanism or a treatment effect.

## Assessment

- The abstract and conclusion say osthol "inhibits APP expression" through miR-132, but the cells express APP from a lentiviral construct and no experiment shows APP or amyloid beta falling after treatment; the direct evidence is on viability, apoptosis, synaptic proteins and pathway markers.
- The methods describe osthol alone at 50 μM in the cell work, while the headline compound is the zinc oxide-osthol conjugate; the text does not say which preparation each assay used, nor report osthol-only or zinc oxide-only controls, so the contribution of the nanoparticle carrier is not separated.
- The Wnt/β-catenin story is internally inconsistent. The abstract says osthol triggers Wnt/β-catenin signalling, yet the results report lower GSK-3β, phospho-GSK-3β and phospho-β-catenin, and the discussion credits "miRNA-377 and miRNA-107" rather than miR-132 for rescuing synapse loss. No Wnt reporter or β-catenin activity assay is described.
- CDH13 enters the results without introduction, the figure legends give an anti-miR-132 and RT-qPCR readout for protein results, and one legend reads P < 0.055; several temperatures and units in the methods are corrupted (for example 370°C), so the text read here cannot be taken as a protocol.
- Only one cell line was used, with no primary neurons, animals or nanoparticle toxicity or uptake data, although zinc oxide nanoparticles are themselves cytotoxic in some systems.

## Open Questions

- Does zinc oxide-osthol, osthol alone or zinc oxide alone restore viability in APP-overexpressing BE2-M17 cells (the text reports no single-component controls)?
- Does osthol-driven miR-132 upregulation lower amyloid beta 1-42 or APP protein in APP-overexpressing neuronal cells (no such measurement is reported)?
- Is the effect on GSK-3β and β-catenin dependent on miR-132, tested by miR-132 inhibition together with a Wnt activity reporter (only synapsin-1 was tested with the inhibitor)?
- Do zinc oxide-osthol nanoparticles protect synapses in primary neurons or in an Alzheimer mouse model at a dose that avoids zinc oxide toxicity (only a neuroblastoma line was used)?

## Connections

- Disease context: [[Alzheimer disease]], [[Neurofibrillary tangle]], [[Apoptosis]], [[Wnt signaling pathway]]
- Compounds: [[Osthol]], [[Zinc oxide]]
- Model: [[BE2-M17]]
- Genes: [[APP]], [[MIR132]], [[MIR107]], [[GSK3B]], [[CTNNB1]], [[SYP]], [[DLG4]], [[SYN1]], [[CDH13]], [[MAPT]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The key reason was that by upregulating miR-132, osthol could inhibit APP expression to prevent AD from occurring." |
| Amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "A critical factor in the cause and progression of Alzheimer's disease (AD) is the growth of β-amyloid peptide (Aβ) in the brain." |
| [[Osthol]] (MESH:C046627) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "We conclude from our observations that osthol is a potential drug for the treatment of a neurodegenerative disease, Alzheimer's." |
| [[Zinc oxide]] (MESH:D015034) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "In the current study, by inducing APP vector in human BE (2)-M17 cells, we established a cellular model of AD and investigated the protective effect of osthol (7-methoxy-8-3-methyl-2-butenyl-2H-1-benzopyran-2-one)-zinc oxide nanoparticles." |
| Zinc (CHEBI:27363; MESH:D015032) | biolink:in_clinical_trials_for | [[Alzheimer disease]] (MESH:D000544) |  | "Initial studies of zinc supplementation in patients with AD who were ultimately not completed due to adverse events were initially performed by Constantinidis and subsequently suggested by Burnet, who hypothesized that supplementation with zinc might prevent or delay the onset of dementia." |
| Nanoparticles (CHEBI:50803) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "In the current study, by inducing APP vector in human BE (2)-M17 cells, we established a cellular model of AD and investigated the protective effect of osthol (7-methoxy-8-3-methyl-2-butenyl-2H-1-benzopyran-2-one)-zinc oxide nanoparticles." |
| [[MIR132]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The key reason was that by upregulating miR-132, osthol could inhibit APP expression to prevent AD from occurring." |
| [[CTNNB1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The dysregulation of the GSK-3β substrate and the level of β-catenin in AD is influenced by neuron death, growth, and differentiation." |
| [[GSK3B]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "AD pathogenesis is caused by GSK, referred to as glycogen synthase kinase, which is a negative Wnt signal transduction pathway controller." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The signaling pathway of phosphoinositide 3-kinase (PI3K)/AKT appears to be important for AD because it promotes tau protein hyperphosphorylation." |
| PIK3CA (HGNC:8975) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The signaling pathway of phosphoinositide 3-kinase (PI3K)/AKT appears to be important for AD because it promotes tau protein hyperphosphorylation." |
| AKT1 (HGNC:391) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The signaling pathway of phosphoinositide 3-kinase (PI3K)/AKT appears to be important for AD because it promotes tau protein hyperphosphorylation." |
| Aluminum chloride (CHEBI:30114; MESH:D000077410) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "ALCL3-induced Alzheimer's disease in mice has been prevented by Osthol which is regulated via PI3K/AKT signalling pathway and the PI3K/AKT signaling pathway." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[APP]] | direction=decreased | "The key reason was that by upregulating miR-132, osthol could inhibit APP expression to prevent AD from occurring." |
| [[MIR132]] | biolink:regulates | [[APP]] | direction=decreased | "The key reason was that by upregulating miR-132, osthol could inhibit APP expression to prevent AD from occurring." |
| Amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:affects | [[DLG4]] | direction=decreased | "In rat hippocampal neurons, soluble Aβ therapy has been reported to significantly reduce the amount of these proteins (PSD-95, SYP, and synapsin-1)." |
| Amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:affects | [[SYP]] | direction=decreased | "In rat hippocampal neurons, soluble Aβ therapy has been reported to significantly reduce the amount of these proteins (PSD-95, SYP, and synapsin-1)." |
| Amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:affects | [[SYN1]] | direction=decreased | "In rat hippocampal neurons, soluble Aβ therapy has been reported to significantly reduce the amount of these proteins (PSD-95, SYP, and synapsin-1)." |
| [[Osthol]] (MESH:C046627) | biolink:physically_interacts_with | [[Zinc oxide]] (MESH:D015034) |  | "The osthol-conjugated zinc oxide nanoparticles could significantly increase cell viability by inhibiting cell apoptosis." |
| [[Osthol]] (MESH:C046627) | biolink:physically_interacts_with | Nanoparticles (CHEBI:50803) |  | "The osthol-conjugated zinc oxide nanoparticles could significantly increase cell viability by inhibiting cell apoptosis." |
| [[Osthol]] (MESH:C046627) | biolink:treats | Neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "We conclude from our observations that osthol is a potential drug for the treatment of a neurodegenerative disease, Alzheimer's." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[DLG4]] | direction=increased | "Osthol treatment has also prevented synaptic proteins such as postsynaptic density-95 (PSD-95), synaptophysin (SYP), and synapsin-1 from decreasing in APP-induced BE (2)-M17 cells." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[SYP]] | direction=increased | "Osthol treatment has also prevented synaptic proteins such as postsynaptic density-95 (PSD-95), synaptophysin (SYP), and synapsin-1 from decreasing in APP-induced BE (2)-M17 cells." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[SYN1]] | direction=increased | "Osthol treatment has also prevented synaptic proteins such as postsynaptic density-95 (PSD-95), synaptophysin (SYP), and synapsin-1 from decreasing in APP-induced BE (2)-M17 cells." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[MIR132]] | direction=increased | "In addition, the expression of miR-132 was significantly upregulated by osthol by triggering the Wnt/β-catenin signaling pathway." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[CTNNB1]] | direction=increased | "In addition, the expression of miR-132 was significantly upregulated by osthol by triggering the Wnt/β-catenin signaling pathway." |
| [[Osthol]] (MESH:C046627) | biolink:affects | PIK3CA (HGNC:8975) |  | "ALCL3-induced Alzheimer's disease in mice has been prevented by Osthol which is regulated via PI3K/AKT signalling pathway and the PI3K/AKT signaling pathway." |
| [[Osthol]] (MESH:C046627) | biolink:affects | AKT1 (HGNC:391) |  | "ALCL3-induced Alzheimer's disease in mice has been prevented by Osthol which is regulated via PI3K/AKT signalling pathway and the PI3K/AKT signaling pathway." |
| [[Osthol]] (MESH:C046627) | biolink:treats | Neoplasm (MONDO:0005070; MESH:D009369) |  | "Osthol (OST, 7-methoxy-8-isopentenoxycoumarin, C15H16O3) (Figure 1) is a natural coumarin derived from Cnidium monnieri (L.) Cusson, recently used by several researchers, and has attracted a great range of attention due to its wide range of pharmacological attributes, such as anti-oxidative stress, anti-inflammatory, anti-tumor, and anti-apoptotic activities." |
| Zinc (CHEBI:27363; MESH:D015032) | biolink:treats | Dementia (MONDO:0001627; MESH:D003704) |  | "Initial studies of zinc supplementation in patients with AD who were ultimately not completed due to adverse events were initially performed by Constantinidis and subsequently suggested by Burnet, who hypothesized that supplementation with zinc might prevent or delay the onset of dementia." |
| [[GSK3B]] | biolink:contributes_to | Cognitive impairment (HP:0100543; MESH:D060825) |  | "Accumulated evidence has shown that active GSK-3β can lead to aberrant tau phosphorylation in neurons and neurofibrillary tangle accumulation, ultimately impairing learning and memory." |
| [[GSK3B]] | biolink:contributes_to | Neurofibrillary tangles (HP:0002185) |  | "Accumulated evidence has shown that active GSK-3β can lead to aberrant tau phosphorylation in neurons and neurofibrillary tangle accumulation, ultimately impairing learning and memory." |
| [[CTNNB1]] | biolink:regulates | [[MIR132]] | direction=increased | "In addition, the expression of miR-132 was significantly upregulated by osthol by triggering the Wnt/β-catenin signaling pathway." |
| [[GSK3B]] | biolink:regulates | [[CTNNB1]] |  | "AD pathogenesis is caused by GSK, referred to as glycogen synthase kinase, which is a negative Wnt signal transduction pathway controller." |
| [[GSK3B]] | biolink:affects | [[MAPT]] | direction=increased | "Accumulated evidence has shown that active GSK-3β can lead to aberrant tau phosphorylation in neurons and neurofibrillary tangle accumulation, ultimately impairing learning and memory." |
| PIK3CA (HGNC:8975) | biolink:regulates | [[GSK3B]] |  | "The major roles in mediating neurogenesis are well known for glycogen synthase kinase-3β (GSK-3β), an important downstream target of the PI3K/AKT signaling pathway." |
| AKT1 (HGNC:391) | biolink:regulates | [[GSK3B]] |  | "The major roles in mediating neurogenesis are well known for glycogen synthase kinase-3β (GSK-3β), an important downstream target of the PI3K/AKT signaling pathway." |
| PIK3CA (HGNC:8975) | biolink:affects | [[MAPT]] | direction=increased | "The signaling pathway of phosphoinositide 3-kinase (PI3K)/AKT appears to be important for AD because it promotes tau protein hyperphosphorylation." |
| AKT1 (HGNC:391) | biolink:affects | [[MAPT]] | direction=increased | "The signaling pathway of phosphoinositide 3-kinase (PI3K)/AKT appears to be important for AD because it promotes tau protein hyperphosphorylation." |
| PIK3CA (HGNC:8975) | biolink:associated_with | AKT1 (HGNC:391) |  | "The major roles in mediating neurogenesis are well known for glycogen synthase kinase-3β (GSK-3β), an important downstream target of the PI3K/AKT signaling pathway." |
| [[Zinc oxide]] (MESH:D015034) | biolink:affects | [[MIR132]] | direction=increased | "These findings showed that zinc oxide-osthol could play a neuroprotective role in the APP-induced BE (2)-M17cells by upregulation of miR-132 and inhibition of CDH13, GSK-3β, p-GSK-3β, and p-β-catenin protein expressions." |
| [[Zinc oxide]] (MESH:D015034) | biolink:affects | [[CTNNB1]] | direction=decreased | "These findings showed that zinc oxide-osthol could play a neuroprotective role in the APP-induced BE (2)-M17cells by upregulation of miR-132 and inhibition of CDH13, GSK-3β, p-GSK-3β, and p-β-catenin protein expressions." |
| [[Zinc oxide]] (MESH:D015034) | biolink:affects | [[SYN1]] | direction=increased | "The decrease in synapsin-1 attenuated and restored protein expression when treated with zinc oxide-osthol." |
| [[Zinc oxide]] (MESH:D015034) | biolink:affects | [[DLG4]] | direction=increased | "In contrast to the control group, zinc oxide-osthol significantly increased the protein expressions of SYP and PSD-95 in APP-induced BE (2)-M17 cells (Figure 6)." |
| [[Zinc oxide]] (MESH:D015034) | biolink:affects | [[SYP]] | direction=increased | "In contrast to the control group, zinc oxide-osthol significantly increased the protein expressions of SYP and PSD-95 in APP-induced BE (2)-M17 cells (Figure 6)." |
| [[Zinc oxide]] (MESH:D015034) | biolink:affects | [[CDH13]] | direction=decreased | "These findings showed that zinc oxide-osthol could play a neuroprotective role in the APP-induced BE (2)-M17cells by upregulation of miR-132 and inhibition of CDH13, GSK-3β, p-GSK-3β, and p-β-catenin protein expressions." |
| [[Zinc oxide]] (MESH:D015034) | biolink:affects | [[GSK3B]] | direction=decreased | "These findings showed that zinc oxide-osthol could play a neuroprotective role in the APP-induced BE (2)-M17cells by upregulation of miR-132 and inhibition of CDH13, GSK-3β, p-GSK-3β, and p-β-catenin protein expressions." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[CDH13]] | direction=decreased | "These findings showed that zinc oxide-osthol could play a neuroprotective role in the APP-induced BE (2)-M17cells by upregulation of miR-132 and inhibition of CDH13, GSK-3β, p-GSK-3β, and p-β-catenin protein expressions." |
| [[Osthol]] (MESH:C046627) | biolink:affects | [[GSK3B]] | direction=decreased | "These findings showed that zinc oxide-osthol could play a neuroprotective role in the APP-induced BE (2)-M17cells by upregulation of miR-132 and inhibition of CDH13, GSK-3β, p-GSK-3β, and p-β-catenin protein expressions." |
| [[APP]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "The successful construction of the AD cellular model in which APP performs its role as a neurotoxic oligomer was suggested in these findings (Figure 4)." |
| [[MAPT]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Although Aβ plays a critical role in AD, as is known, growing evidence has shown that aberrant tau phosphorylation and oligomerization are likely to be crucial to the disease process." |
| [[APP]] | biolink:affects | [[MIR132]] | direction=decreased | "Compared with the control group, it can be shown that APP transduction inhibited miR-132 expression in BE (2)-M17 cells." |
| [[MIR132]] | biolink:affects | [[SYN1]] | direction=increased | "Anti-miR-132 significantly reduced synapsin-1 protein expressions, while zinc oxide-osthol treatment reversed the effect of the miR-132 inhibitor in BE (2)-M17 cells overexpressed with APP." |
| [[MAPT]] | biolink:contributes_to | Neurofibrillary tangles (HP:0002185) |  | "Abnormal hyperphosphorylated tau protein is made up of NFTs." |
| [[MAPT]] | biolink:causes | Memory impairment (HP:0002354) |  | "Cytoskeletal destabilization, apoptotic cells, and eventually memory dysfunction can result from these hyperphosphorylated tau proteins." |
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "AD is a complex disease predominantly caused by APP that causes Aβ-neurotoxicity; Aβ accumulation contributes to a decline in cognition in patients with AD." |
| [[APP]] | biolink:causes | neurotoxicity (MONDO:0005527) |  | "AD is a complex disease predominantly caused by APP that causes Aβ-neurotoxicity; Aβ accumulation contributes to a decline in cognition in patients with AD." |
| [[APP]] | biolink:affects | [[DLG4]] | direction=decreased | "Osthol treatment has also prevented synaptic proteins such as postsynaptic density-95 (PSD-95), synaptophysin (SYP), and synapsin-1 from decreasing in APP-induced BE (2)-M17 cells." |
| [[APP]] | biolink:affects | [[SYP]] | direction=decreased | "Osthol treatment has also prevented synaptic proteins such as postsynaptic density-95 (PSD-95), synaptophysin (SYP), and synapsin-1 from decreasing in APP-induced BE (2)-M17 cells." |
| [[APP]] | biolink:affects | [[SYN1]] | direction=decreased | "Osthol treatment has also prevented synaptic proteins such as postsynaptic density-95 (PSD-95), synaptophysin (SYP), and synapsin-1 from decreasing in APP-induced BE (2)-M17 cells." |
| Nanoparticles (CHEBI:50803) | biolink:affects | [[CTNNB1]] | direction=decreased | "In addition, zinc oxide-osthol plays a critical role in minimizing its downstream impact through miRNA-377 upregulation and downregulation of GSK-3β, p-GSK-iβ, and p-β-catenin signaling pathways in cells overexpressed with APP." |
| Nanoparticles (CHEBI:50803) | biolink:affects | [[GSK3B]] | direction=decreased | "In addition, zinc oxide-osthol plays a critical role in minimizing its downstream impact through miRNA-377 upregulation and downregulation of GSK-3β, p-GSK-iβ, and p-β-catenin signaling pathways in cells overexpressed with APP." |
| Nanoparticles (CHEBI:50803) | biolink:affects | MIR377 (HGNC:31870) | direction=increased | "In addition, zinc oxide-osthol plays a critical role in minimizing its downstream impact through miRNA-377 upregulation and downregulation of GSK-3β, p-GSK-iβ, and p-β-catenin signaling pathways in cells overexpressed with APP." |
| MIR377 (HGNC:31870) | biolink:regulates | [[CTNNB1]] |  | "Our findings showed that miRNA-377 and miRNA-107 overexpression could save Aβ 1-42-induced synapse loss by targeting the signaling pathway for GSK-3β, p-GSK-3β, and p-β-catenin." |
| [[MIR107]] | biolink:regulates | [[CTNNB1]] |  | "Our findings showed that miRNA-377 and miRNA-107 overexpression could save Aβ 1-42-induced synapse loss by targeting the signaling pathway for GSK-3β, p-GSK-3β, and p-β-catenin." |
| MIR377 (HGNC:31870) | biolink:regulates | [[GSK3B]] |  | "Our findings showed that miRNA-377 and miRNA-107 overexpression could save Aβ 1-42-induced synapse loss by targeting the signaling pathway for GSK-3β, p-GSK-3β, and p-β-catenin." |
| [[MIR107]] | biolink:regulates | [[GSK3B]] |  | "Our findings showed that miRNA-377 and miRNA-107 overexpression could save Aβ 1-42-induced synapse loss by targeting the signaling pathway for GSK-3β, p-GSK-3β, and p-β-catenin." |
