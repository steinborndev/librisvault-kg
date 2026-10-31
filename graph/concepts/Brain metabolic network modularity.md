---
type: concept
title: "Brain metabolic network modularity"
domain: neuroscience
status: seed
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000318
aliases: ["metabolic network modularity", "FDG PET network modularity", "metabolic network fragmentation"]
tags: [neuroimaging]
---

# Brain metabolic network modularity

A brain metabolic network treats brain regions as nodes and the correlation of their [[FDG PET]] uptake across participants as the links. Modularity measures how cleanly such a network splits into modules, groups of regions strongly linked inside and weakly linked between. The Louvain algorithm finds the partition that maximizes modularity; because it is stochastic, a consensus over many runs gives a stable partition, and a variant of the modularity formula lets negative correlations separate modules.

A rise in modularity driven by weaker links between modules is read as network fragmentation, the splitting of an integrated system into poorly communicating parts. It is higher in Alzheimer disease patients than in controls, and in cognitively normal older adults it rose with the group's later progression to [[Mild cognitive impairment]] or [[Alzheimer disease]]. The modules can be mapped to anatomy: one found this way held the hippocampus, amygdala and entorhinal cortex, where neuronal loss begins.

## Connections

- Worked example: modularity 0.0209 in stable cognitively normal elderly rising to 0.0570 in Alzheimer patients, with women more fragmented than men. Study: [[Brain metabolism and Alzheimer risk gene expression in normal elderly]]
- Input data: [[FDG PET]]
- Gene expression was correlated with metabolism inside each module: [[Allen Human Brain Atlas]]
- Related correlation-based module method for gene expression: [[Weighted gene co-expression network analysis]]
