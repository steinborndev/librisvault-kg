---
type: source
title: "A wild-type neuron subpopulation with familial Alzheimer-like phenotypes"
paper_title: "A unique subpopulation of wild-type neurons recapitulating familial Alzheimer’s disease phenotypes"
domain: neuroscience
status: developing
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001188
pmid: "40783385"
pmcid: "PMC12335501"
doi: "10.1038/s41419-025-07934-0"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC12335501/"
sources: ["[[.raw/01M4P89V98PM80WJBXQMBWSAGR/normalized.md]]"]
tags: [familial-alzheimer, secretase, membrane-trafficking]
---

# A wild-type neuron subpopulation with familial Alzheimer-like phenotypes

A live-cell imaging study in mouse primary cortical neurons from wild-type CD1 embryos. Using FRET biosensors that report [[Gamma-secretase complex]] activity cell by cell ([[FRET biosensors of gamma-secretase activity]]), the authors found that about 20% of ordinary neurons have clearly lower activity than the rest, and that these neurons look like neurons carrying [[Familial Alzheimer disease]] presenilin mutations: they make relatively more long [[Amyloid-beta]], have enlarged endo-lysosomes, and die sooner under glutamate or oxidant challenge. Pharmacological experiments place the inefficient secretase and the endo-lysosomal defect upstream of the vulnerability.

## Methods

- Cortical neurons from E14-16 CD1 mouse embryos, cultured 12-15 days in vitro; biosensors and the calcium reporter YC3.6 delivered by AAV8 under the human synapsin promoter.
- Two sensors built on human [[APP]] C99: C99 YPet-mTurquoise-GL (Y-T) and a near-infrared C99 miRFP720-miRFP670 (720-670) that can be multiplexed with visible dyes. Cleavage lowers FRET, so a high acceptor/donor ratio means low activity.
- Neurons were grouped by FRET ratio relative to the population mean and plus or minus one SD. The top 20% (low activity) and bottom 20% (high activity) were separated by FACS after propidium iodide exclusion of dead cells, lysed and assayed for Aβ38 and Aβ42 by ELISA.
- Endo-lysosome size by LysoPrime Green puncta; cytoplasmic calcium by YC3.6; loss of membrane integrity by time to propidium iodide positivity in time-lapse imaging after [[Glutamate]] (100 μM) or the oxidant [[4,4'-Dithiodipyridine]] (100 μM).
- Causality probes: 16 h with 1 μM [[DAPT]] (secretase inhibitor), 5 h with 100 μM [[Chloroquine]] or 100 nM [[Bafilomycin A1]], and the lysosomotropic [[LLOMe]] at 1-10 mM.
- Statistics: t-tests, Mann-Whitney, one-way and repeated ANOVA, Pearson correlation; at least three independent experiments; imaging analysis blinded.

## Findings

- About 20% of neurons had Y-T FRET ratios above mean plus 1 SD, meaning markedly lower endogenous gamma-secretase activity.
- Sorted low-activity neurons had less Aβ38 and more Aβ42, hence a higher Aβ42/38 ratio, so the carboxypeptidase-like trimming step was also impaired, not only the first cleavage (n = 3 experiments, p below 0.05).
- Endosomes and lysosomes were significantly larger in the neurons above mean plus 1 SD than in those below the mean; cell body size did not differ.
- Baseline calcium was higher in low-activity neurons, and the glutamate-induced calcium rise (peak and sustained) was larger. No rise occurred in calcium-free medium, so influx from outside was the main source. Baseline 720/670 ratio correlated with calcium rise (R2 = 0.272, n = 99 neurons, p below 0.0001).
- Low-activity neurons turned propidium iodide positive sooner after glutamate or DTDP, i.e. they were more vulnerable to [[Excitotoxicity]] and [[Oxidative stress]].
- DAPT enlarged endo-lysosomes, left baseline calcium unchanged, increased glutamate-evoked calcium and raised the number of propidium iodide positive neurons after glutamate or DTDP; APP C-terminal fragments accumulated, confirming inhibition.
- Chloroquine and bafilomycin A1 both shortened time to propidium iodide positivity after DTDP in all three experiments. LLOMe did so in several experiments but not in others.
- The authors infer the order: inefficient gamma-secretase, then endo-lysosomal abnormality, then neuronal vulnerability. They note alkalinised endo-lysosomes from earlier work, propose C99/APP C-terminal fragments (or the YENPTY motif) as a link, and speculate that membrane properties differ in these cells because membrane permeability is raised.

## Assessment

- Wild-type mouse neurons from one embryonic source in culture; the claim that these cells model sporadic disease or "link familial and sporadic cases" is a proposal, not tested in human or aged neurons or in vivo.
- The Aβ comparison uses cell lysates of sorted cells from three experiments, and Aβ42 and Aβ38 only; other peptide lengths and secreted Aβ were not measured.
- Order of events rests on inhibitors (DAPT, chloroquine, bafilomycin A1); DAPT, a non-selective inhibitor, blocks processing of other substrates, and the LLOMe result was inconsistent. The sorted subpopulation was not followed to show it is a stable cell state, and its identity (cell type, marker) is undefined.
- Calcium reporters and biosensors were expressed together by AAV, so expression level could contribute to ratio differences.

## Why This Source Matters

It offers a cell-biological route by which neurons without any mutation can share the phenotypes of [[PSEN1]] and [[PSEN2]] mutant neurons, which bears on whether sporadic [[Late-onset Alzheimer disease]] and [[Early-onset Alzheimer disease]] converge on the same pathway. It also supplies a single-cell imaging platform for neuronal resilience and drug screening.

## Open Questions

- Which neuronal type or molecular marker defines the roughly 20% low gamma-secretase subpopulation (not examined; the neurons were identified only by FRET ratio)?
- Does a subpopulation with low gamma-secretase activity and enlarged endo-lysosomes exist in human neurons or in aged mouse brain in vivo (only embryonic mouse cultures were studied)?
- Why did the lysosomotropic agent LLOMe fail to consistently shorten time to cell death while chloroquine and bafilomycin A1 did (the authors only suggest a different mechanism such as altered autophagy)?
- Do membrane thickness or lipid composition differ in low-activity neurons and explain the shift toward longer Aβ (suggested by the authors, not measured)?

## Connections

- Disease: [[Familial Alzheimer disease]], [[Early-onset Alzheimer disease]], [[Late-onset Alzheimer disease]]
- Genes: [[APP]], [[PSEN1]], [[PSEN2]]; complex: [[Gamma-secretase complex]]
- Peptide and process: [[Amyloid-beta]], [[Amyloid-beta formation]], [[Calcium signalling]]
- Organelles: [[Endosome]], [[Lysosome]]
- Compounds: [[DAPT]], [[Chloroquine]], [[Bafilomycin A1]], [[LLOMe]], [[Glutamate]], [[4,4'-Dithiodipyridine]]
- Method: [[FRET biosensors of gamma-secretase activity]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the genes encoding APP, Presenilin-1 (PSEN1), and PSEN2 result in early-onset Alzheimer’s disease (AD)." |
| [[PSEN1]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the genes encoding APP, Presenilin-1 (PSEN1), and PSEN2 result in early-onset Alzheimer’s disease (AD)." |
| [[PSEN2]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the genes encoding APP, Presenilin-1 (PSEN1), and PSEN2 result in early-onset Alzheimer’s disease (AD)." |
| Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Aβ42 is highly prone to aggregation and forms the core of senile plaques, one of the major pathological hallmarks of AD." |
| PSEN mutations (variant) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the genes encoding APP, Presenilin-1 (PSEN1), and PSEN2 result in early-onset Alzheimer’s disease (AD)." |
| [[APP]] | biolink:causes | [[Familial Alzheimer disease]] |  | "The deterministic mutations causing early-onset familial AD (fAD) have been identified in the genes encoding APP, Presenilin 1 (PSEN1), or PSEN2, which account for 1 to 5% of all cases." |
| [[PSEN1]] | biolink:causes | [[Familial Alzheimer disease]] |  | "The deterministic mutations causing early-onset familial AD (fAD) have been identified in the genes encoding APP, Presenilin 1 (PSEN1), or PSEN2, which account for 1 to 5% of all cases." |
| [[PSEN2]] | biolink:causes | [[Familial Alzheimer disease]] |  | "The deterministic mutations causing early-onset familial AD (fAD) have been identified in the genes encoding APP, Presenilin 1 (PSEN1), or PSEN2, which account for 1 to 5% of all cases." |
| PSEN mutations (variant) | biolink:causes | [[Familial Alzheimer disease]] |  | "fAD-causing PSEN mutations affect, to a certain degree, its endopeptidase-like activity and significantly impair the γ-secretase’s carboxypeptidase-like processivity, resulting in the predominant production of longer Aβ peptides (e.g., Aβ42)." |
| [[APP]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "The N-terminally truncated APP (C99) is first processed by γ-secretase at the epsilon cleavage site (so-called endopeptidase-like activity of γ-secretase), generating the membrane-embedded 48 or 49 amino acid β-amyloid (Aβ) and corresponding intracellular domain fragments." |
| [[APP]] | biolink:affects | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Then, Aβ48 and 49 are cleaved by γ-secretase in a stepwise manner (known as carboxypeptidase-like processivity), generating various Aβ peptides ranging from 37 to 43 amino acids." |
| PSEN mutations (variant) | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "fAD-causing PSEN mutations affect, to a certain degree, its endopeptidase-like activity and significantly impair the γ-secretase’s carboxypeptidase-like processivity, resulting in the predominant production of longer Aβ peptides (e.g., Aβ42)." |
| Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | biolink:associated_with | Senile plaques (HP:0100256; MESH:D058225) |  | "Aβ42 is highly prone to aggregation and forms the core of senile plaques, one of the major pathological hallmarks of AD." |
| PSEN mutations (variant) | biolink:affects | Amyloid-beta 42 (CHEBI:64647; MESH:C075222) | direction=increased | "fAD-causing PSEN mutations affect, to a certain degree, its endopeptidase-like activity and significantly impair the γ-secretase’s carboxypeptidase-like processivity, resulting in the predominant production of longer Aβ peptides (e.g., Aβ42)." |
| [[PSEN1]] | biolink:associated_with | [[Familial Alzheimer disease]] |  | "Earlier studies in fAD PSEN1 knock-in mice also uncovered that neurons with fAD mutations exhibit increased vulnerability phenotypes such as Ca2+ overload and impaired membrane integrity in response to toxic insults (e.g., Glutamate (Glu)-induced excitotoxicity)." |
| [[PSEN1]] | biolink:affects | Ca2+ (CHEBI:29108) | direction=increased | "Earlier studies in fAD PSEN1 knock-in mice also uncovered that neurons with fAD mutations exhibit increased vulnerability phenotypes such as Ca2+ overload and impaired membrane integrity in response to toxic insults (e.g., Glutamate (Glu)-induced excitotoxicity)." |
| [[Familial Alzheimer disease]] | biolink:associated_with | Ca2+ (CHEBI:29108) |  | "Earlier studies in fAD PSEN1 knock-in mice also uncovered that neurons with fAD mutations exhibit increased vulnerability phenotypes such as Ca2+ overload and impaired membrane integrity in response to toxic insults (e.g., Glutamate (Glu)-induced excitotoxicity)." |
| glutamate (CHEBI:16015; MESH:D018698) | biolink:affects | Ca2+ (CHEBI:29108) | direction=increased | "Furthermore, the peak and sustained components of the Glu-induced Ca2+ overload were more significant in the neurons with inefficient γ-secretase than those with active γ-secretase (Fig. 3A, C)." |
| Propidium iodide (CHEBI:51240; MESH:D011419) | biolink:directly_physically_interacts_with | DNA (CHEBI:16991; MESH:D004247) |  | "PI is a cell impermeable dye that releases fluorescence upon binding to DNA if the cell membrane is compromised and thus can specifically label dead and dying neurons (Fig. 4A)." |
| glutamate (CHEBI:16015; MESH:D018698) | biolink:affects | Calcium (CHEBI:29108; MESH:D002118) |  | "Post 5 min recording baseline Ca2+ levels, the neurons pre-incubated with DAPT or vehicle were treated with 100 μM Glu, and the changes in Ca2+ levels were recorded overtime for 15 min." |
| [[APP]] | biolink:has_phenotype | Autosomal dominant inheritance (HP:0000006) |  | "Since the discoveries three decades ago, genetic mutations have been so far identified only in the three genes: APP, PSEN1, and PSEN2, with PSEN mutations accounting for most familial cases (https://www.alzforum.org/mutations)." |
| [[PSEN1]] | biolink:has_phenotype | Autosomal dominant inheritance (HP:0000006) |  | "Since the discoveries three decades ago, genetic mutations have been so far identified only in the three genes: APP, PSEN1, and PSEN2, with PSEN mutations accounting for most familial cases (https://www.alzforum.org/mutations)." |
| [[PSEN2]] | biolink:has_phenotype | Autosomal dominant inheritance (HP:0000006) |  | "Since the discoveries three decades ago, genetic mutations have been so far identified only in the three genes: APP, PSEN1, and PSEN2, with PSEN mutations accounting for most familial cases (https://www.alzforum.org/mutations)." |
| [[DAPT]] (MESH:C048518) | biolink:affects | Calcium (CHEBI:29108; MESH:D002118) | direction=increased | "Glu treatment significantly increased cytoplasmic Ca2+ levels in neurons treated with DAPT compared to those with vehicle control (Fig. 5D)." |
| PSEN mutations (variant) | biolink:has_phenotype | Autosomal dominant inheritance (HP:0000006) |  | "Alzheimer’s disease can be either sporadic or caused by inherited autosomal dominant mutations." |
| [[APP]] | biolink:affects | Calcium (CHEBI:29108; MESH:D002118) |  | "As potential mechanisms, recent studies proposed that C99/APP-CTFs or even the YENPTY motif in the cytoplasmic region of APP CTFs links inefficient γ-secretase with endo-lysosomal abnormalities (e.g., swelling, pH alterations, Ca2+ dysregulation)." |
