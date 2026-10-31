---
type: concept
title: "Blood-brain barrier permeability prediction"
domain: pharmacology
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000706
aliases: ["logBB prediction", "CNS drug-likeness filter", "central nervous system penetration prediction"]
tags: [in-silico]
---

# Blood-brain barrier permeability prediction

Brain entry of a drug is estimated from computed descriptors: lipophilicity (logP, and logD at pH 7.4), topological polar surface area (TPSA), molecular weight, and an efflux flag for P-glycoprotein. One widely used empirical equation, derived from Clark's model, gives the blood-brain partition coefficient as logBB = 0.152 x logP - 0.0148 x TPSA + 0.139, read as very high at 0.7 or above and low or very low below -0.3. Compounds with logP 3 to 4 and TPSA 60 to 75 Å2 are treated as the favourable window; very lipophilic compounds with low polar surface area tend to be efflux substrates and are pumped back out. These are screening estimates and not measurements of brain concentration. For the barrier itself see [[Blood-brain barrier dysfunction]].

## Connections

- Applied to the docking hits to drop polar drugs (bictegravir, methotrexate, vardenafil, sofosbuvir) and efflux substrates ([[Tolnaftate]], [[Fluspirilene]]) and to favour [[Lasmiditan]], compared with [[Donepezil]] and risperidone as known CNS-penetrant drugs. Study: [[Lasmiditan prioritised for Alzheimer disease by regulator docking and dynamics]]
- Preceded by: [[Molecular docking]]
- SVM and LiCABEDS classifiers predicted [[Antrocin]] to be blood-brain barrier permeable. Study: [[Multiomic analysis of Alzheimer brain finds five upregulated genes and antrocin]]
- The chalcone [[LM-031]] met Lipinski criteria and the polar-surface-area rule (under 90 Å2) in silico, then showed high passive permeability in a PAMPA-BBB assay (4.80 × 10-6 cm/s against 21.75 for testosterone and 0.11 for theophylline). Study: [[LM-031 targets HSPB1, NRF2 and CREB in Tau cell and 3xTg-AD mouse models]]
- The support vector machine and LiCABEDS server (1,593 training compounds, threshold 0.02) scored [[Antrocin]] 0.038; the BOILED-Egg model and SwissADME rules (molecular weight 234.33 Da, no P-glycoprotein efflux) supported the call. Study: [[Multiomic analysis of Alzheimer brain finds five upregulated genes and antrocin]]
