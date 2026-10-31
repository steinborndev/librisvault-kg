---
type: source
title: "Hypoxic ADSC exosomes deliver circ-Epc1 and shift microglia in Alzheimer mice"
paper_title: "Hypoxic pretreatment of adipose-derived stem cell exosomes improved cognition by delivery of circ-Epc1 and shifting microglial M1/M2 polarization in an Alzheimer’s disease mice model"
domain: neuroscience
status: developing
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000541
pmid: "35366241"
pmcid: "PMC9037259"
doi: "10.18632/aging.203989"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC9037259/"
sources: ["[[.raw/01M4DY94TWSVKBNZ6FDZNR2C68/normalized.md]]"]
tags: [microglia, neuroinflammation, mouse-model, microrna]
---

# Hypoxic ADSC exosomes deliver circ-Epc1 and shift microglia in Alzheimer mice

A cell-therapy study asking why exosomes from hypoxia-pretreated adipose-derived stem cells (ADSCs) help an [[Alzheimer disease]] mouse model more than exosomes from ordinary ADSCs. The authors propose that hypoxia loads the exosomes with a circular RNA, circ-Epc1, which soaks up the microRNA [[MIR770]] (miR-770-3p) and so lifts the microglial receptor [[TREM2]], tipping microglia from a pro-inflammatory M1 state toward an M2 state. See [[Adipose-derived stem cell exosome therapy]] and [[Microglial cell activation]].

## Design

- Exosomes were prepared from mouse ADSCs (cobblestone morphology, positive for CD29, CD44, CD90 and CD105, negative for vWF, able to form fat and bone lineages) by sequential centrifugation up to 100,000 x g. They were confirmed by CD9 and CD63 western blots, cup-shaped morphology on electron microscopy and a mean diameter of 80-130 nm. ADSCs were cultured in 20% oxygen (Exo) or 1% oxygen (HExo).
- Strand-specific total RNA sequencing of Exo and HExo, with RNase R treatment to enrich circular RNAs, followed by RT-qPCR validation of ten candidates.
- Dual-luciferase reporter assays in [[HEK293]] cells for circ-Epc1 with miRNA mimics, and for the TREM2 3' untranslated region with the miR-770-3p mimic (wild-type versus mutated sites). See [[miRNA binding]].
- [[BV2]] microglial cells transfected with a circ-Epc1 overexpression plasmid, a miR-770-3p mimic and an siRNA against TREM2, alone or combined, then challenged with 1 μg/mL [[Lipopolysaccharide]] for one day. Read-outs: immunofluorescence for Iba-1 (all microglia), [[ITGAM]] (CD11b, called M1) and [[MRC1]] (CD206, called M2), and ELISA for [[IL6]], [[TNF]] and [[IL1B]].
- [[APPswe-PS1dE9 mouse]] animals (called APP/PS1; males, 2 months old, 10 per group) given PBS, Exo, HExo or exosomes from circ-Epc1-overexpressing ADSCs (circ-Epc1-Exo) once a month for two months (exosomes of 1 x 10^9 cells in 100 μL). Read-outs: DiI-labelled exosome tracking, cytokine ELISA on brain tissue, TUNEL staining of hippocampal [[Apoptosis]], microglial staining, hippocampal RT-qPCR, and the [[Morris water maze]].

## Findings

- Exosomes reached the cortex and hippocampus 5 hours after injection. Both Exo and HExo lowered brain IL-6, TNF-α and IL-1β and hippocampal neuronal apoptosis, and shortened escape latency while raising platform crossings in the water maze; HExo was stronger than Exo on each measure.
- Hypoxia changed the circular RNA content of the exosomes: 3,133 circular RNAs were up and 1,554 down in HExo compared with Exo. Of ten up-regulated candidates tested by RT-qPCR, only circ-Epc1 was significantly higher in HExo. It is spliced from an exon of the mouse [[EPC1]] gene (chr18:6448902-6450637).
- Of 13 miRNAs predicted to bind circ-Epc1, only the miR-770-3p mimic lowered reporter signal, and not when its binding site was mutated. miR-770-3p also repressed a reporter carrying the TREM2 3' untranslated region, but not a mutated one.
- In BV2 cells circ-Epc1 overexpression lowered miR-770-3p and raised TREM2 mRNA and protein; the miR-770-3p mimic reversed the TREM2 rise. TREM2 knockdown did not change circ-Epc1 or miR-770-3p, placing TREM2 downstream. The authors conclude that circ-Epc1 regulates TREM2 by sponging miR-770-3p.
- In LPS-challenged BV2 cells circ-Epc1 lowered CD11b-positive and raised CD206-positive cells and lowered IL-6, TNF-α and IL-1β; the miR-770-3p mimic or TREM2 knockdown partly reversed each effect.
- In APP/PS1 mice circ-Epc1-Exo beat HExo on hippocampal apoptosis, escape latency, platform crossings, CD11b-versus-CD206 balance and cytokines, and in hippocampal tissue raised miR-770-3p and lowered TREM2.

## Why This Source Matters

[[TREM2]] is usually discussed as a gene whose loss raises Alzheimer risk. This paper presents a post-transcriptional route to raise it, through a circular RNA delivered by stem cell exosomes, and ties microglial polarization to a testable regulatory axis (circ-Epc1, miR-770-3p, TREM2). It also shows a concrete way hypoxic preconditioning might improve an exosome therapy, which makes the cargo, rather than the cells alone, the object of engineering.

## Assessment

- The in vivo and in vitro directions disagree on the key axis. In BV2 cells circ-Epc1 lowered miR-770-3p and raised TREM2, but in hippocampal tissue of circ-Epc1-Exo mice the text reports higher miR-770-3p and lower TREM2, with no comment, so the in vivo evidence does not support the proposed mechanism as stated.
- Causality in the animal is not tested: miR-770-3p or TREM2 were manipulated only in BV2 cells, not in mice, and circ-Epc1 delivery to microglia, rather than to other cells, was not shown. Whether circ-Epc1 or another cargo of HExo drives the benefit is inferred from sequencing and a ten-candidate screen.
- The microglial model is a single LPS-treated line, not an amyloid challenge, and M1/M2 status rests on one marker each (CD11b, CD206). Fig. 6 legend names F4/80 where the text names Iba-1. Amyloid plaque load or Aβ levels in the treated mice are not reported, so benefit is read from cytokines, apoptosis and behaviour.
- Reporting is loose in places: the injection route is not stated, the Methods mention hyperglycemia pretreatment of exosome donors that is never described again, the Fig. 1 legend names alkaline phosphatase staining where the text names Alizarin Red, and the Discussion says TREM2 overexpression, whereas the experiments used knockdown. The group sizes in the TUNEL panels (n=6) differ from the behaviour panels (n=10). Only male mice were used.

## Open Questions

- Does knocking down miR-770-3p or TREM2 in the hippocampus of APP/PS1 mice abolish the benefit of circ-Epc1-containing exosomes (only BV2 cell experiments were done)?
- Why do hippocampal miR-770-3p and TREM2 move opposite to the BV2 results in circ-Epc1-Exo-treated mice (the text reports the change without discussing the mismatch)?
- Does hypoxic pretreatment of ADSCs raise circ-Epc1 in exosomes from human adipose tissue (only mouse ADSCs were used for exosome production)?
- Do circ-Epc1-containing exosomes lower amyloid-beta plaque load in APP/PS1 mice (plaque and Aβ levels were not reported)?

## Connections

- Disease and models: [[Alzheimer disease]]; [[APPswe-PS1dE9 mouse]]; cell lines [[BV2]] and [[HEK293]]; stimulus [[Lipopolysaccharide]].
- Axis genes: [[EPC1]] (parent gene of circ-Epc1), [[MIR770]], [[TREM2]]; polarization markers [[ITGAM]] and [[MRC1]]; cytokines [[IL6]], [[TNF]], [[IL1B]].
- Concepts: [[Adipose-derived stem cell exosome therapy]], [[Extracellular vesicle]], [[Microglial cell activation]], [[miRNA binding]], [[Neuroinflammation]], [[Apoptosis]]; behavioural method [[Morris water maze]].
- Another study of what controls microglial TREM2 levels: [[TREM2 regulation by YY1 in microglia and Alzheimer disease models]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[EPC1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Taken together, the data show that hypoxic pretreatment of ADSC exosomes improved cognition by delivery of circ-Epc1 and by shifting microglial M1/M2 polarization in an AD mouse model." |
| [[APP]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "APP/PS1 double transgenic AD model mice were then used to study therapeutic effects regarding circ-Epc1 in ADSC exosomes." |
| [[PSEN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "APP/PS1 double transgenic AD model mice were then used to study therapeutic effects regarding circ-Epc1 in ADSC exosomes." |
| amyloid beta (CHEBI:64645; MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The hallmark pathological feature of AD is the deposition of β-amyloid (Aβ), which has strong neurotoxicity in brain tissue, and leads to cognitive impairment." |
| [[EPC1]] | biolink:regulates | [[MIR770]] |  | "Luciferase reporter assays showed that TREM2 and miR-770-3p were downstream targets of circ-Epc1." |
| [[EPC1]] | biolink:regulates | [[TREM2]] |  | "Luciferase reporter assays showed that TREM2 and miR-770-3p were downstream targets of circ-Epc1." |
| [[EPC1]] | biolink:associated_with_decreased_likelihood_of | cognitive impairment (HP:0100543; MESH:D060825) |  | "In vivo experiments showed that circ-Epc1-containing ADSC exosomes increased the therapeutic effect of exosomes by improving cognitive function, decreasing neuronal damage, and shifting hippocampal microglia from the M1 polarization to the M2 polarization stages." |
| [[EPC1]] | biolink:associated_with | neuroinflammation (HP:0033429; MESH:D000090862) |  | "BV2 cells were used to show the regulatory relationships between circ-Epc1, miR-770-3p, and TREM2 and to show how these interactions modulated phenotypic transformations and inflammatory cytokine expressions in microglia." |
| [[MIR770]] | biolink:associated_with | [[TREM2]] |  | "Luciferase reporter assays and RT-qPCR were used to investigate the relationships between circ-Epc1, miR-770-3p, and TREM2." |
| amyloid beta (CHEBI:64645; MESH:D016229) | biolink:causes | neurotoxicity (MONDO:0005527) |  | "The hallmark pathological feature of AD is the deposition of β-amyloid (Aβ), which has strong neurotoxicity in brain tissue, and leads to cognitive impairment." |
| amyloid beta (CHEBI:64645; MESH:D016229) | biolink:causes | cognitive impairment (HP:0100543; MESH:D060825) |  | "The hallmark pathological feature of AD is the deposition of β-amyloid (Aβ), which has strong neurotoxicity in brain tissue, and leads to cognitive impairment." |
| [[EPC1]] | biolink:associated_with | cognitive impairment (HP:0100543; MESH:D060825) |  | "Together, these data suggested that circ-Epc1 may play a role in improving cognitive functions." |
| [[IL6]] | biolink:associated_with | Inflammation (MESH:D007249) |  | "ELISAs detected the presence of inflammatory factors, IL-6, TNF-α, and IL-1β, in brain tissues." |
| [[TNF]] | biolink:associated_with | Inflammation (MESH:D007249) |  | "ELISAs detected the presence of inflammatory factors, IL-6, TNF-α, and IL-1β, in brain tissues." |
| [[IL1B]] | biolink:associated_with | Inflammation (MESH:D007249) |  | "ELISAs detected the presence of inflammatory factors, IL-6, TNF-α, and IL-1β, in brain tissues." |
| [[EPC1]] | biolink:affects | [[MIR770]] | direction=decreased | "Overexpressing circ-Epc1 inhibited miR-770-3p expression, but transfecting miR-770-3p mimics reversed and promoted miR-770-3p expression." |
| [[EPC1]] | biolink:physically_interacts_with | MIR346 (HGNC:31780) |  | "Bioinformatics analyses showed that circ-Epc1 interacted with miRNAs, including miR-344b-5p, miR-346-3p, miR-106a-5p, miR-20a-5p, miR-93-5p, miR-17-5p, miR-467a-5p, miR-290a-3p, mir-293-3p, miR-877-5p, miR-434-5p, miR-770-3p, and miR-296-5p." |
| [[EPC1]] | biolink:physically_interacts_with | MIR106A (HGNC:31494) |  | "Bioinformatics analyses showed that circ-Epc1 interacted with miRNAs, including miR-344b-5p, miR-346-3p, miR-106a-5p, miR-20a-5p, miR-93-5p, miR-17-5p, miR-467a-5p, miR-290a-3p, mir-293-3p, miR-877-5p, miR-434-5p, miR-770-3p, and miR-296-5p." |
| [[EPC1]] | biolink:physically_interacts_with | MIR20A (HGNC:31577) |  | "Bioinformatics analyses showed that circ-Epc1 interacted with miRNAs, including miR-344b-5p, miR-346-3p, miR-106a-5p, miR-20a-5p, miR-93-5p, miR-17-5p, miR-467a-5p, miR-290a-3p, mir-293-3p, miR-877-5p, miR-434-5p, miR-770-3p, and miR-296-5p." |
| [[EPC1]] | biolink:physically_interacts_with | MIR93 (HGNC:31645) |  | "Bioinformatics analyses showed that circ-Epc1 interacted with miRNAs, including miR-344b-5p, miR-346-3p, miR-106a-5p, miR-20a-5p, miR-93-5p, miR-17-5p, miR-467a-5p, miR-290a-3p, mir-293-3p, miR-877-5p, miR-434-5p, miR-770-3p, and miR-296-5p." |
| [[EPC1]] | biolink:physically_interacts_with | MIR17 (HGNC:31547) |  | "Bioinformatics analyses showed that circ-Epc1 interacted with miRNAs, including miR-344b-5p, miR-346-3p, miR-106a-5p, miR-20a-5p, miR-93-5p, miR-17-5p, miR-467a-5p, miR-290a-3p, mir-293-3p, miR-877-5p, miR-434-5p, miR-770-3p, and miR-296-5p." |
| [[EPC1]] | biolink:physically_interacts_with | MIR877 (HGNC:33660) |  | "Bioinformatics analyses showed that circ-Epc1 interacted with miRNAs, including miR-344b-5p, miR-346-3p, miR-106a-5p, miR-20a-5p, miR-93-5p, miR-17-5p, miR-467a-5p, miR-290a-3p, mir-293-3p, miR-877-5p, miR-434-5p, miR-770-3p, and miR-296-5p." |
| [[EPC1]] | biolink:physically_interacts_with | MIR296 (HGNC:31617) |  | "Bioinformatics analyses showed that circ-Epc1 interacted with miRNAs, including miR-344b-5p, miR-346-3p, miR-106a-5p, miR-20a-5p, miR-93-5p, miR-17-5p, miR-467a-5p, miR-290a-3p, mir-293-3p, miR-877-5p, miR-434-5p, miR-770-3p, and miR-296-5p." |
| [[EPC1]] | biolink:affects | [[ITGAM]] | direction=decreased | "The results showed that upregulating circ-Epc1 decreased M1 microglial differentiation by decreasing CD11b expression." |
| [[EPC1]] | biolink:affects | [[MRC1]] | direction=increased | "We also found that upregulating circ-Epc1 promoted M2 microglial differentiation by increasing CD206 expression." |
| [[EPC1]] | biolink:affects | [[IL6]] | direction=decreased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[EPC1]] | biolink:affects | [[TNF]] | direction=decreased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[EPC1]] | biolink:affects | [[IL1B]] | direction=decreased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[MIR770]] | biolink:regulates | [[TREM2]] | direction=decreased | "The luciferase reporter analysis showed that miR-770-3p inhibited luciferase activity in WT cells, but not in cell lines with the MUT sequence (Figure 4E), suggesting that TREM2 was a miR-770-3p target." |
| [[MIR770]] | biolink:affects | [[ITGAM]] | direction=increased | "In contrast, overexpressing miR-770-3p or downregulating TREM2 partially reversed M1 microglial differentiation following circ-Epc1 overexpression." |
| [[MIR770]] | biolink:affects | [[MRC1]] | direction=decreased | "Additionally, overexpressing miR-770-3p or silencing TREM2 partially reversed M2 microglial differentiation in circ-Epc1-overexpressing cells (Figure 5A–5D)." |
| [[MIR770]] | biolink:affects | [[IL6]] | direction=increased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[MIR770]] | biolink:affects | [[TNF]] | direction=increased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[MIR770]] | biolink:affects | [[IL1B]] | direction=increased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[TREM2]] | biolink:affects | [[ITGAM]] | direction=decreased | "In contrast, overexpressing miR-770-3p or downregulating TREM2 partially reversed M1 microglial differentiation following circ-Epc1 overexpression." |
| [[TREM2]] | biolink:affects | [[MRC1]] | direction=increased | "Additionally, overexpressing miR-770-3p or silencing TREM2 partially reversed M2 microglial differentiation in circ-Epc1-overexpressing cells (Figure 5A–5D)." |
| [[TREM2]] | biolink:affects | [[IL6]] | direction=decreased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[TREM2]] | biolink:affects | [[TNF]] | direction=decreased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[TREM2]] | biolink:affects | [[IL1B]] | direction=decreased | "ELISA results showed that miR-770-3p overexpression or silencing TREM2 partially reversed the inhibitory effect of circ-Epc1 on inflammatory factor expressions such as those of IL-6, TNF-α, and IL-1β (Figure 5E–5G)." |
| [[EPC1]] | biolink:physically_interacts_with | [[MIR770]] |  | "Using a luciferase reporter system, we found in the present study that circ-Epc1 interacted with miR-770-3p." |
| [[EPC1]] | biolink:affects | [[TREM2]] | direction=decreased | "RT-qPCR showed that circ-Epc1-Exo treatment also had a greater therapeutic effect than HExo by increasing miR-770-3p and decreasing TREM2 expressions in hippocampal tissues (Figure 6L, 6M)." |
| [[EPC1]] | biolink:negatively_correlated_with | cognitive impairment (HP:0100543; MESH:D060825) |  | "Overall, our data suggested that circ-Epc1 may play a role in improving cognitive function." |
| [[EPC1]] | biolink:negatively_correlated_with | Inflammation (MESH:D007249) |  | "The current study suggested that hypoxia-pretreated ADSC exosome treatment had a greater therapeutic effect than ADSC exosomes at decreasing apoptosis and inflammatory cytokines in the hippocampus." |
| [[MIR770]] | biolink:physically_interacts_with | [[TREM2]] |  | "Further studies found that miR-770-3p interacted with the triggering receptors expressed in TREM2, which was also verified by our luciferase reporter assays." |
| [[MIR770]] | biolink:contributes_to | Inflammation (MESH:D007249) |  | "MiR-770-3p expression can facilitate apoptosis by inducing inflammation." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:physically_interacts_with | [[MIR770]] |  | "Using a luciferase reporter system, we found in the present study that circ-Epc1 interacted with miR-770-3p." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Human genetic investigations have shown that loss-of-function mutations in TREM2 signaling were highly associated with an elevated risk of age-related neurodegenerative traits such as AD." |
| [[TREM2]] | biolink:contributes_to | cognitive impairment (HP:0100543; MESH:D060825) |  | "TREM2 loss confers resilience to synaptic and cognitive impairment in aged mice." |
| [[TREM2]] | biolink:associated_with | Neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Human genetic investigations have shown that loss-of-function mutations in TREM2 signaling were highly associated with an elevated risk of age-related neurodegenerative traits such as AD." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:affects | [[TREM2]] | direction=decreased | "RT-qPCR showed that circ-Epc1-Exo treatment also had a greater therapeutic effect than HExo by increasing miR-770-3p and decreasing TREM2 expressions in hippocampal tissues (Figure 6L, 6M)." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:affects | [[ITGAM]] | direction=decreased | "The results showed that circ-Epc1-Exo treatment had a greater therapeutic effect than HExo by decreasing M1 microglial differentiation and promoting M2 microglial differentiation, through decreasing CD11b and increasing CD206 expressions (Figure 6E–6H)." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:affects | [[MRC1]] | direction=increased | "The results showed that circ-Epc1-Exo treatment had a greater therapeutic effect than HExo by decreasing M1 microglial differentiation and promoting M2 microglial differentiation, through decreasing CD11b and increasing CD206 expressions (Figure 6E–6H)." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:affects | [[IL6]] |  | "ELISA assay results showed that circ-Epc1-Exo treatment had a better therapeutic effect than HExo on inflammatory factor expressions such like TNF-α, IL-1β, and IL-6 (Figure 6I–6K)." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:affects | [[TNF]] |  | "ELISA assay results showed that circ-Epc1-Exo treatment had a better therapeutic effect than HExo on inflammatory factor expressions such like TNF-α, IL-1β, and IL-6 (Figure 6I–6K)." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:affects | [[IL1B]] |  | "ELISA assay results showed that circ-Epc1-Exo treatment had a better therapeutic effect than HExo on inflammatory factor expressions such like TNF-α, IL-1β, and IL-6 (Figure 6I–6K)." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Previous studies have found that circRNAs contributed to AD pathogenesis." |
| Loss-of-function mutation in TREM2 (variant) | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Human genetic investigations have shown that loss-of-function mutations in TREM2 signaling were highly associated with an elevated risk of age-related neurodegenerative traits such as AD." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:treats | cognitive impairment (HP:0100543; MESH:D060825) |  | "Cognitive function tests found that hypoxia-pretreated ADSC exosome treatment had greater effects than treatment with ADSC exosomes at recovering AD-induced cognitive impairments." |
| Loss-of-function mutation in TREM2 (variant) | biolink:associated_with_increased_likelihood_of | Neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Human genetic investigations have shown that loss-of-function mutations in TREM2 signaling were highly associated with an elevated risk of age-related neurodegenerative traits such as AD." |
| Circular RNA (CHEBI:8762; MESH:D000079962) | biolink:negatively_correlated_with | Inflammation (MESH:D007249) |  | "The current study suggested that hypoxia-pretreated ADSC exosome treatment had a greater therapeutic effect than ADSC exosomes at decreasing apoptosis and inflammatory cytokines in the hippocampus." |
| [[EPC1]] | biolink:associated_with_decreased_likelihood_of | neuroinflammation (HP:0033429; MESH:D000090862) |  | "Our in vivo experiments also showed that circ-Epc1-containing ADSC exosomes partially rescued AD-induced cognition impairment by shifting the microglial phenotype from M1 to M2, which resulted in decreased expressions of inflammatory cytokines and less apoptosis of hippocampal neurons." |
| [[TREM2]] | biolink:associated_with | PIK3CA (HGNC:8975) |  | "TREM2 also ameliorates neuroinflammatory responses and cognitive impairment using the PI3K/AKT/FoxO3a pathway in AD mice." |
| [[TREM2]] | biolink:associated_with | AKT1 (HGNC:391) |  | "TREM2 also ameliorates neuroinflammatory responses and cognitive impairment using the PI3K/AKT/FoxO3a pathway in AD mice." |
| [[TREM2]] | biolink:associated_with | FOXO3 (HGNC:3821) |  | "TREM2 also ameliorates neuroinflammatory responses and cognitive impairment using the PI3K/AKT/FoxO3a pathway in AD mice." |
| [[TREM2]] | biolink:regulates | [[TLR4]] | direction=decreased | "Further study discovery that TREM2 can switching microglia from an M1 proinflammatory phenotype to an M2 anti-inflammatory phenotype and inhibit TLR4/NF-κB mediated inflammatory response." |
| [[TREM2]] | biolink:regulates | NF-κB (HGNC:7794) | direction=decreased | "Further study discovery that TREM2 can switching microglia from an M1 proinflammatory phenotype to an M2 anti-inflammatory phenotype and inhibit TLR4/NF-κB mediated inflammatory response." |
| [[TREM2]] | biolink:associated_with_decreased_likelihood_of | Amyloid pathology (MONDO:0019065) |  | "A large majority of the related studies have provided strong evidence that TREM2 dysfunction results in amyloid pathology." |
| [[TREM2]] | biolink:associated_with_decreased_likelihood_of | cognitive impairment (HP:0100543; MESH:D060825) |  | "TREM2 also ameliorates neuroinflammatory responses and cognitive impairment using the PI3K/AKT/FoxO3a pathway in AD mice." |
| [[TREM2]] | biolink:associated_with_decreased_likelihood_of | neuroinflammation (HP:0033429; MESH:D000090862) |  | "TREM2 also ameliorates neuroinflammatory responses and cognitive impairment using the PI3K/AKT/FoxO3a pathway in AD mice." |
| [[TREM2]] | biolink:associated_with | Amyloid plaques (MESH:D058225) |  | "TREM2 has recently been demonstrated to be essential to promote the association between microglia and Aβ plaques." |
| [[TLR4]] | biolink:contributes_to | neuroinflammation (HP:0033429; MESH:D000090862) |  | "Further study discovery that TREM2 can switching microglia from an M1 proinflammatory phenotype to an M2 anti-inflammatory phenotype and inhibit TLR4/NF-κB mediated inflammatory response." |
| NF-κB (HGNC:7794) | biolink:contributes_to | neuroinflammation (HP:0033429; MESH:D000090862) |  | "Further study discovery that TREM2 can switching microglia from an M1 proinflammatory phenotype to an M2 anti-inflammatory phenotype and inhibit TLR4/NF-κB mediated inflammatory response." |
