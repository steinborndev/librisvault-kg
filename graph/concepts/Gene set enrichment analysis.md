---
type: concept
title: "Gene set enrichment analysis"
domain: methods
status: seed
created: 2026-10-08
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000273
aliases: ["GSEA", "pathway enrichment analysis"]
tags: [transcriptomics, network-analysis]
---

# Gene set enrichment analysis

Gene set enrichment analysis ranks all genes by a differential-expression statistic and tests whether the members of a predefined set (here the MSigDB hallmark collection) cluster at the top or bottom of the list. Each set gets a normalized enrichment score, and the leading-edge genes are those contributing most to it.

## Connections

- Ranked lists were combined blood-and-brain Z-scores (O'Brien method), run separately in APOE ε2/ε3, ε3/ε3 and ε3/ε4 groups, giving 21 significant pathways. Study: [[Blood and brain transcriptome of Alzheimer disease by APOE genotype]]
- Related method: [[Weighted gene co-expression network analysis]]
- Used inside [[Gene2Drug]] to turn drug expression profiles into pathway profiles, and in Enrichr to annotate four Alzheimer risk-gene lists. Study: [[Gene2Drug repurposing candidates for Alzheimer disease risk genes]]
- Run with g:Profiler on genes found in two datasets; usage-changed genes added synapse and vesicle-transport terms that differentially expressed genes alone missed. Study: [[Differential transcript usage in Alzheimer disease brain RNAseq by lobe]]
- Related Gene Ontology network method: [[ClueGO functional network analysis]]
- g:Profiler enrichment of up- and down-regulated signature genes per brain region found 663 terms in superior temporal gyrus versus 22 in dorsolateral prefrontal cortex. Study: [[Predictive gene expression signatures of Alzheimer disease in six brain regions]]
- Run per gene on [[ATP6V1D]], [[ATP6V1G2]], [[CLTB]] and [[NSF]] against hallmark sets; all four fell in oxidative phosphorylation, interferon gamma response, inflammatory response and TNF-alpha signalling via NF-kappaB. Related: [[Immune infiltration analysis]]. Study: [[Four synaptic vesicle cycle genes protective in Alzheimer disease by MR]]
