---
type: concept
title: "FRET biosensors of gamma-secretase activity"
domain: methods
status: seed
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001197
aliases: ["C99 Y-T biosensor", "C99 720-670 biosensor", "gamma-secretase FRET sensor"]
tags: [secretase]
---

# FRET biosensors of gamma-secretase activity

Genetically encoded sensors that report endogenous [[Gamma-secretase complex]] (endopeptidase-like) activity in single live neurons over time. Each carries human [[APP]] C99 flanked by a donor and an acceptor fluorophore; cleavage separates them and lowers the acceptor/donor FRET ratio, so a high ratio means low activity. The C99 YPet-mTurquoise-GL version works in the visible range and can be read by flow cytometry; the near-infrared miRFP720-miRFP670 version leaves the visible spectrum free for other dyes and reporters (multiplexing). They are delivered by AAV under the synapsin promoter.

## Uses and limits

- Sorting neurons by activity with FACS (top and bottom 20% of the FRET ratio) so that Aβ can be measured by ELISA in each group.
- Multiplexing with a lysosome dye (LysoPrime Green) and the calcium reporter YC3.6 to relate activity to endo-lysosome size and calcium load in the same cell, and with propidium iodide time-lapse imaging to relate it to cell death.
- The sensor reports only the first cleavage; the carboxypeptidase-like step was inferred from Aβ42/38 in sorted cells.

## Connections

- Source using both sensors in mouse cortical neurons: [[A wild-type neuron subpopulation with familial Alzheimer-like phenotypes]]
- Biology: [[Amyloid-beta formation]], [[Lysosome]], [[Calcium signalling]]
