---
type: source
title: "Network pharmacology of seven heat-clearing herbs for Alzheimer disease"
paper_title: "Network Pharmacology Study of Heat-Clearing and Detoxifying Traditional Chinese Medicine for Alzheimer's Disease"
domain: pharmacology
status: developing
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001481
pmid: "32382304"
pmcid: "PMC7196989"
doi: "10.1155/2020/7831675"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC7196989/"
sources: ["[[.raw/01M4P89VDWR73W6FKFGSKNWE95/normalized.md]]"]
tags: [herbal-medicine, natural-product, in-silico, network-analysis]
---

# Network pharmacology of seven heat-clearing herbs for Alzheimer disease

A 2020 purely computational study asking whether seven herbs of [[Heat-clearing and detoxifying traditional Chinese medicine]] share an anti-[[Alzheimer disease]] mechanism. Herb ingredients and their predicted targets come from the TCMSP database, Alzheimer genes from GeneCards, and the overlap is analysed as herb-ingredient-target-disease networks, a protein interaction network and enrichment. The authors conclude that the shared mechanism is anti-inflammatory and propose [[Chlorogenic acid]] and [[Quercetin]] as the common active ingredients.

## Design

- Herb selection: 61 TCMSP herbs containing chlorogenic acid, 499 TCMSP herbs related to Alzheimer disease and 96 heat-clearing and detoxifying herbs from the Chinese Pharmacopoeia 2015 overlapped in 12 herbs; a literature check kept the 7 with reported anti-Alzheimer effects: Andrographis paniculata, Coptis chinensis, Phellodendron amurense bark (Cortex Phellodendri amurensis), Lonicera japonica, Houttuynia cordata, Centella asiatica and Gardenia jasminoides.
- Ingredients: TCMSP filter of oral bioavailability at least 30% and drug-likeness at least 0.18, leaving 64 ingredients (13, 10, 17, 8, 5, 2 and 9 per herb in the order above) with 1032 target entries (111, 222, 219, 113, 119, 80 and 168).
- Disease genes: 711 genes with a GeneCards relevance score above 10.
- Analysis: overlap by R, networks in Cytoscape 3.7.1, a [[STRING protein interaction network analysis]] of targets shared by at least 5 herbs, Gene Ontology enrichment in OmicShare and Reactome pathway enrichment (FDR-corrected).

## Findings

- Per-herb networks ranged from 30 nodes (Andrographis paniculata) to 77 (Coptis chinensis). [[Quercetin]] was the top ingredient in six of the seven (degree 58 in Coptis, 32-33 elsewhere; Andrographis paniculata instead led with wogonin, degree 11); [[Kaempferol]] (degree 15) ranked second in Houttuynia and Gardenia.
- [[PTGS1]] was a high-degree target in all seven networks (degree 11 in Andrographis paniculata, 15 in Phellodendron); [[AR]] was high-degree in four, and [[PTGS2]] led the Coptis network (degree 10). The authors tie PTGS1 to arachidonic acid driven inflammation.
- 34 targets were shared by at least 5 herbs and the disease. Examples: [[EGFR]], [[ESR1]], [[ESR2]] and [[VEGFA]] (5 herbs); [[ACHE]], [[BCL2]] and [[CASP8]] (6 herbs); AR, [[CASP3]] and CASP9 (all 7).
- In the protein interaction network of these 34, [[IL6]] (degree 29), CASP3 (26), VEGFA (24), [[MYC]] (23), EGFR (23), ESR1 (22) and [[ERBB2]] (21) were the pivotal nodes.
- Gene Ontology terms were generic (cellular process, response to stimulus, binding, catalytic activity). 33 of the 34 targets mapped to 319 Reactome pathways, concentrated in immune system, signal transduction and gene expression. The five leading pathways (P at most 0.001 after FDR) were the IL-4 and IL-13 signaling pathway ([[IL4]], [[IL13]]), ESR-mediated signaling, TFAP2 (AP-2) regulation of growth factor transcription, extranuclear estrogen signaling and nuclear receptor signaling; see [[Estrogen signaling pathway]].
- The discussion reads these as anti-[[Neuroinflammation]]: IL-4 and IL-13 activating microglia to degrade amyloid-beta, and estrogen receptors suppressing inflammation and hippocampal amyloid-beta deposition. All of this is argued from cited literature, not tested.

## Assessment

- No experiment of any kind: targets are database predictions, so "key target" means high network degree and nothing about binding or effect direction. Degree of an ingredient also scales with how many targets TCMSP lists for it, which favours promiscuous flavonoids such as quercetin.
- Chlorogenic acid was a selection criterion, yet the results never show its targets or degree; its proposed role rests on literature in the discussion. The conclusion that it and quercetin are indispensable is stated by the authors as a hypothesis.
- Reporting is uneven: the abstract names PTGS1 among the key targets although PTGS1 is not among the examples given for the 34 shared targets; the discussion says 34 targets were enriched while the results say 33 mapped. Supplementary tables carry the full lists; the data are stated to be available only on request.
- The authors name database differences, screening cut-offs and tool choice as limits and call for experimental verification.

## Open Questions

- Does quercetin, at concentrations reachable in brain, change IL6, CASP3 or VEGFA expression in an Alzheimer model (the study is purely predictive; no assay was run)?
- Do the seven herbs lower neuroinflammation markers in an amyloid mouse model to a comparable degree (only monomer or extract studies of individual herbs were cited)?

## Why This Source Matters

It is a compact example of the herb-ingredient-target-disease workflow applied across several herbs at once rather than to one herb, and it shows how the shared-target step turns a list of herbs into a single inflammation hypothesis. It also marks the limits of the approach: the headline targets are those any large flavonoid-rich herb set would return.

## Connections

- Method: [[Network pharmacology with multi-omics for herbal medicines]], [[STRING protein interaction network analysis]]
- Herb group: [[Heat-clearing and detoxifying traditional Chinese medicine]]; the formula Huanglian-Jie-Du-Tang is covered under [[Traditional Chinese medicine decoctions]]
- Disease: [[Alzheimer disease]]; process: [[Neuroinflammation]]
- Compounds: [[Quercetin]], [[Kaempferol]], [[Chlorogenic acid]], [[Berberine]], [[Palmatine]]
- Genes: [[PTGS1]], [[IL6]], [[CASP3]], [[VEGFA]], [[AR]], [[MYC]], [[ESR1]], [[EGFR]], [[ERBB2]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[PTGS1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The results showed that PTGS1, IL-6, CASP3, and VEGFA were the predicted key gene targets." |
| [[IL6]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The results showed that PTGS1, IL-6, CASP3, and VEGFA were the predicted key gene targets." |
| [[CASP3]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The results showed that PTGS1, IL-6, CASP3, and VEGFA were the predicted key gene targets." |
| [[VEGFA]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The results showed that PTGS1, IL-6, CASP3, and VEGFA were the predicted key gene targets." |
| [[IL4]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The IL-4 and IL-13 signaling pathway, the ESR-mediated signaling pathway, and the extranuclear estrogen signaling pathway were the significant pathways associated with the 7 herbs." |
| [[IL13]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The IL-4 and IL-13 signaling pathway, the ESR-mediated signaling pathway, and the extranuclear estrogen signaling pathway were the significant pathways associated with the 7 herbs." |
| [[ESR1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The IL-4 and IL-13 signaling pathway, the ESR-mediated signaling pathway, and the extranuclear estrogen signaling pathway were the significant pathways associated with the 7 herbs." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "More importantly, CGA can significantly alleviate inflammation and oxidative stress, two important promoters of AD." |
| [[Quercetin]] (MESH:D011794) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "This study revealed that the analogous anti-AD mechanism of the 7 herbs of HDTCM may be associated with anti-inflammation, which is a common effect of the chlorogenic acid and quercetin components." |
| geniposide (CHEBI:5299; MESH:C007835) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, a large number of modern pharmacological studies on natural ingredients isolated from HDTCM sources (such as geniposide, andrographolide, and berberine) and their effects on AD have been performed." |
| andrographolide (CHEBI:65408; MESH:C030419) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, a large number of modern pharmacological studies on natural ingredients isolated from HDTCM sources (such as geniposide, andrographolide, and berberine) and their effects on AD have been performed." |
| [[Berberine]] (MESH:D001599) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, a large number of modern pharmacological studies on natural ingredients isolated from HDTCM sources (such as geniposide, andrographolide, and berberine) and their effects on AD have been performed." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "For example, Huanglian-Jie-Du-Tang, a decoction that is composed of HDTCM relevant herbs such as Coptis chinensis, Cortex Phellodendri, and Scutellaria baicalensis, is used for clearing heat, purging pathogenic fire, and reducing amyloid-β accumulation during the treatment of AD." |
| [[PTGS2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "First, the targets of the main active ingredients of the 7 herbs were mapped to the targets of AD." |
| [[AR]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "First, the targets of the main active ingredients of the 7 herbs were mapped to the targets of AD." |
| NR3C2 (HGNC:7979) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "First, the targets of the main active ingredients of the 7 herbs were mapped to the targets of AD." |
| GSTM1 (HGNC:4632) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "First, the targets of the main active ingredients of the 7 herbs were mapped to the targets of AD." |
| IGF2 (HGNC:5466) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "First, the targets of the main active ingredients of the 7 herbs were mapped to the targets of AD." |
| [[PPARG]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "First, the targets of the main active ingredients of the 7 herbs were mapped to the targets of AD." |
| [[EGFR]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| [[ESR2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| [[ACHE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| [[BCL2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| [[CASP8]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| CAV1 (HGNC:1527) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| CASP9 (HGNC:1511) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| F7 (HGNC:3544) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "As shown in Figure 3(h), purple represents the shared targets of 5 herbs-AD common targets (such as EGFR, ESR1, ESR2, and VEGFA), blue represents the shared targets of 6 herbs-AD common targets (such as ACHE, BCL2, CASP8, and CAV1), and green represents the shared targets of 7 herbs-AD common targets (such as AR, CASP3, CASP9, and F7)." |
| [[IL6]] | biolink:positively_correlated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In one study, scientists reported that the level of IL-6, an inflammatory factor closely related to inflammation, in AD patients was significantly elevated." |
| [[MYC]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The analysis results showed that IL-6 (degree = 29), CASP3 (degree = 26), VEGFA (degree = 24), MYC (degree = 23), EGFR (degree = 23), ESR1 (degree = 22), and ERBB2 (degree = 21) were the pivotal targets in this network." |
| [[ERBB2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The analysis results showed that IL-6 (degree = 29), CASP3 (degree = 26), VEGFA (degree = 24), MYC (degree = 23), EGFR (degree = 23), ESR1 (degree = 22), and ERBB2 (degree = 21) were the pivotal targets in this network." |
| arachidonic acid (CHEBI:15843; MESH:D016718) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, researchers have confirmed that the arachidonic acid metabolism pathway mediates the development of AD and Aβ plaques generation, and the upregulation of arachidonic acid has also been observed in an AD model." |
| [[VEGFA]] | biolink:contributes_to | inflammation (MESH:D007249) |  | "In addition, one study found that VEGFA, an instigator of inflammation, was involved in the therapeutic regulatory network of AD and had a neuroprotective function." |
| [[CASP3]] | biolink:contributes_to | inflammation (MESH:D007249) |  | "Investigators have also found that downgrading the expression of CASP3 could reduce the inflammation induced by LPS in astrocytes associated with neurotic plaques in AD." |
| [[IL6]] | biolink:associated_with | inflammation (MESH:D007249) |  | "In one study, scientists reported that the level of IL-6, an inflammatory factor closely related to inflammation, in AD patients was significantly elevated." |
| [[PTGS1]] | biolink:associated_with | arachidonic acid (CHEBI:15843; MESH:D016718) |  | "The results of one analysis showed that PTGS1 is associated with arachidonic acid-induced inflammation." |
| [[PTGS1]] | biolink:associated_with | inflammation (MESH:D007249) |  | "The results of one analysis showed that PTGS1 is associated with arachidonic acid-induced inflammation." |
| arachidonic acid (CHEBI:15843; MESH:D016718) | biolink:causes | inflammation (MESH:D007249) |  | "The results of one analysis showed that PTGS1 is associated with arachidonic acid-induced inflammation." |
| arachidonic acid (CHEBI:15843; MESH:D016718) | biolink:associated_with | amyloid plaques (MESH:D058225) |  | "Moreover, researchers have confirmed that the arachidonic acid metabolism pathway mediates the development of AD and Aβ plaques generation, and the upregulation of arachidonic acid has also been observed in an AD model." |
| [[Lipopolysaccharide]] (MESH:D008070) | biolink:causes | inflammation (MESH:D007249) |  | "Investigators have also found that downgrading the expression of CASP3 could reduce the inflammation induced by LPS in astrocytes associated with neurotic plaques in AD." |
| [[IL4]] | biolink:associated_with | [[IL13]] |  | "Remarkably, IL-4 and IL-13 can activate microglia, the pivotal sources of inflammatory factors and oxidative stress in the brain, to induce Aβ degradation and improve cognitive impairment." |
| [[IL4]] | biolink:associated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "It was previously found that the IL-4 and IL-13 signaling pathways play a neuromodulating role by regulating the oxidative stress in AD and other neurodegenerative diseases." |
| [[IL4]] | biolink:associated_with_decreased_likelihood_of | [[Cognitive impairment]] (MESH:D060825) |  | "Remarkably, IL-4 and IL-13 can activate microglia, the pivotal sources of inflammatory factors and oxidative stress in the brain, to induce Aβ degradation and improve cognitive impairment." |
| [[IL13]] | biolink:associated_with | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "It was previously found that the IL-4 and IL-13 signaling pathways play a neuromodulating role by regulating the oxidative stress in AD and other neurodegenerative diseases." |
| [[IL13]] | biolink:associated_with_decreased_likelihood_of | [[Cognitive impairment]] (MESH:D060825) |  | "Remarkably, IL-4 and IL-13 can activate microglia, the pivotal sources of inflammatory factors and oxidative stress in the brain, to induce Aβ degradation and improve cognitive impairment." |
| [[ESR1]] | biolink:associated_with_decreased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Simultaneously, researchers found that the estrogen receptor can provide a protective anti-inflammatory effect by inhibiting inflammation in neurodegenerative disorders such as AD and reducing Aβ deposition in the hippocampus to improve memory capacity." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, based on its anti-inflammatory effects, CGA is likely to be one of the main active ingredients against AD in the 7 herbs." |
| [[Quercetin]] (MESH:D011794) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "Finally, we propose a hypothesis suggesting that CGA and quercetin, two main shared active ingredients, may play an indispensable role in the anti-AD efficacy of these 7 herbs, which requires verification and deserves further study." |
| [[ESR1]] | biolink:associated_with_decreased_likelihood_of | neurodegenerative disease (MONDO:0005559; MESH:D019636) |  | "Simultaneously, researchers found that the estrogen receptor can provide a protective anti-inflammatory effect by inhibiting inflammation in neurodegenerative disorders such as AD and reducing Aβ deposition in the hippocampus to improve memory capacity." |
| [[ESR1]] | biolink:associated_with_decreased_likelihood_of | neuroinflammation (HP:0033429; MESH:D007249) |  | "Simultaneously, researchers found that the estrogen receptor can provide a protective anti-inflammatory effect by inhibiting inflammation in neurodegenerative disorders such as AD and reducing Aβ deposition in the hippocampus to improve memory capacity." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:treats | neuroinflammation (HP:0033429; MESH:D007249) |  | "Moreover, based on its anti-inflammatory effects, CGA is likely to be one of the main active ingredients against AD in the 7 herbs." |
| [[ESR1]] | biolink:associated_with_decreased_likelihood_of | [[Memory impairment]] (MESH:D000647) |  | "Simultaneously, researchers found that the estrogen receptor can provide a protective anti-inflammatory effect by inhibiting inflammation in neurodegenerative disorders such as AD and reducing Aβ deposition in the hippocampus to improve memory capacity." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:associated_with | [[Quercetin]] (MESH:D011794) |  | "Finally, we propose a hypothesis suggesting that CGA and quercetin, two main shared active ingredients, may play an indispensable role in the anti-AD efficacy of these 7 herbs, which requires verification and deserves further study." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:affects | malondialdehyde (CHEBI:566274; MESH:D008315) | direction=decreased | "For example, CGA can exert antiamnesic activity by inhibiting the expression of acetylcholinesterase and malondialdehyde." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:pharmacologically_interacts_with | selenium (CHEBI:27568; MESH:D012643) |  | "In another interesting study, researchers found that CGA combined with selenium nanoparticles inhibited Aβ aggregation." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:affects | [[ACHE]] | direction=decreased | "For example, CGA can exert antiamnesic activity by inhibiting the expression of acetylcholinesterase and malondialdehyde." |
| [[Chlorogenic acid]] (MESH:D002726) | biolink:treats | [[Memory impairment]] (MESH:D000647) |  | "For example, CGA can exert antiamnesic activity by inhibiting the expression of acetylcholinesterase and malondialdehyde." |
