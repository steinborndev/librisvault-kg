---
type: source
title: "PSEN1 transmembrane versus cytoplasmic variants and progression in DIAN"
paper_title: "Location of pathogenic variants in PSEN1 impacts progression of cognitive, clinical, and neurodegenerative measures in autosomal‐dominant Alzheimer's disease"
domain: neuroscience
status: developing
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001232
pmid: "37291760"
pmcid: "PMC10410059"
doi: "10.1111/acel.13871"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC10410059/"
sources: ["[[.raw/01M4P89V9WMCS6BXWYS25PDT8A/normalized.md]]"]
tags: [familial-alzheimer, neuroimaging, biomarker, gamma-secretase]
---

# PSEN1 transmembrane versus cytoplasmic variants and progression in DIAN

Pathogenic [[PSEN1]] variants cause autosomal dominant [[Familial Alzheimer disease]] with high penetrance, yet age at onset, biomarker trajectories and cognitive decline vary widely between carriers. The authors asked whether the location of the variant within PSEN1 explains part of that spread. Using the [[Dominantly Inherited Alzheimer Network]] observational study (DIAN-Obs), they split PSEN1 carriers by whether the changed residue lies in a transmembrane (TM) or a cytoplasmic (CY) region, using UniProt domain annotation (see [[PSEN1 transmembrane and cytoplasmic domain grouping]]), and compared both groups with unaffected sibling non-carriers (NC).

## Key findings

- TM carriers declined faster than CY carriers on cognition, function and brain volume, but the two groups did not differ on amyloid. Both carrier groups had clearly higher amyloid than NC.
- Cognition: Mini-Mental State Examination (MMSE) fell faster with [[Expected years to symptom onset]] (EYO) in TM than CY carriers (cubic EYO by group B = -0.51, SE 0.11, p = 1.2e-06), with the curves diverging from about EYO -3.8 years. Clinical Dementia Rating Sum of Boxes (CDR-SB) rose faster in TM carriers (B = 0.26, SE 0.06, p = 2.4e-06), diverging around EYO -0.9.
- Atrophy: [[Hippocampal atrophy]] was greater in TM carriers (B = -86.2, SE 31.7, p = 0.007) and the groups diverged from EYO -10.9, more than ten years before expected onset. Exploratory FreeSurfer regions that were smaller in TM than CY carriers included superior frontal, rostral anterior cingulate, isthmus cingulate, precuneus, cuneus, superior parietal, lateral occipital, fusiform, amygdala and putamen, mostly diverging near EYO -11. [[Lateral ventricular volume]] diverged at -10.9.
- Mediation: the group effect on MMSE was fully mediated by hippocampal volume (direct effect -0.57, p = 0.004; residual direct effect after adding the mediator -0.12, p = 0.46).
- Amyloid: the cortical Pittsburgh compound B PET composite ([[Amyloid PET]]; linear EYO by group B = 0.02, p = 0.056), the precuneus (p = 0.059) and CSF Aβ42/40 did not differ between TM and CY.
- Tau: CSF phospho-tau 181 by immunoassay differed (B = 1.8, SE 0.6, p = 0.006; [[Increased CSF phosphorylated tau concentration]]). In a mass spectrometry subset (N = 225) only the pT217/T217 ratio differed (B = 0.09, p = 0.018); pT181, pT202 and pT205 ratios did not.
- Adding PiB-PET and CSF phospho-tau 181 to the hippocampal model left the divergence essentially unchanged (EYO -10.1), so the volume gap is not explained by these two measures.
- Longitudinal data (TM N = 75, CY N = 44 with follow-up) agreed in part: annualised MMSE decline (p = 0.013, baseline EYO at or after -3.4) and hippocampal atrophy rate (p = 0.005, baseline EYO at or after -10.7) were faster in TM; CDR-SB slopes did not differ (p = 0.196).
- A pre- versus post-codon 200 split of the same carriers did not separate MMSE, hippocampal volume or CSF phospho-tau 181, so the TM/CY split performed better for these outcomes.

## Methods

- Cohort: PSEN1 carriers in DIAN-Obs with amyloid PET, MRI and clinical assessment; TM N = 135, CY N = 65, NC N = 202. Carriers with a baseline and at least one follow-up visit (N = 119, mean follow-up 3.2 years) entered the longitudinal analyses.
- Imaging: 3T MPRAGE processed with FreeSurfer 5.3 and the Desikan-Killiany atlas, regional volumes adjusted for intracranial volume (hippocampus the a priori region); PiB PET as 40-70 minute SUVR against cerebellar grey matter with partial volume correction.
- CSF: Lumipulse G1200 immunoassays for Aβ40, Aβ42 and phospho-tau 181, plus nano-LC high-resolution mass spectrometry for tau phosphoforms; Benjamini-Hochberg correction applied to the CSF analyses.
- Statistics: linear mixed models with age, sex, APOE ε4 status, education (cognitive outcomes), EYO as a restricted cubic spline, group, EYO by group interaction and a random effect for family. Divergence points were taken where 99% credible intervals of the TM minus CY difference stopped overlapping zero.

## Why This Source Matters

It is a worked example of variant-level stratification inside [[Familial Alzheimer disease]]: a simple two-class split by PSEN1 topology captures progression differences that the older pre/post-codon 200 split and amyloid markers miss. Because hippocampal volume diverges a decade before onset and is the preferred structural endpoint in dominantly inherited trials, the grouping is directly relevant to how trial arms are balanced and analysed. The finding that amyloid does not distinguish the groups, while atrophy does, adds to the evidence that carriers' neurodegeneration is not read out by plaque burden alone.

## Assessment

- Observational, cross-sectional for the main contrasts, with a modest longitudinal subset; no causal claim about the mechanism is tested.
- The CY group was younger, had more APOE ε4 carriers and a lower mean EYO than TM; these were adjusted for, and the differences were absent in the longitudinal subset, but residual confounding remains possible. The authors note that an APOE ε4 effect has not been consistent in dominantly inherited disease.
- Both groups are heterogeneous: earlier work found some TM domains (3 and 5) with high amyloid PET and others (6 and 8) with low, so pooling all nine TM helices may hide amyloid differences.
- The text gives a CDR-SB divergence of -0.9 years while the figure legend gives -1.1, and the legend lists a PiB-PET divergence at EYO -8.4 although the interaction test was not significant; the numbers above follow the text.
- Mechanisms offered are speculative: disturbed intracellular calcium handling in TM variants, non-APP gamma-secretase substrates such as NOTCH, and unmeasured toxic Aβ forms (Aβ43, Aβ37/38, membrane-retained Aβ45-49, oligomers).

## Open Questions

- Do individual PSEN1 variants within the transmembrane group differ enough in progression that variant-level or biochemically informed grouping outperforms the TM/CY split (the study had too few carriers per variant to test)?
- Do toxic Aβ species not measured by PiB PET or CSF Aβ42/40, such as Aβ43 or oligomers, explain the faster atrophy of transmembrane variant carriers?
- Is calcium dysregulation or altered NOTCH processing by gamma-secretase responsible for the amyloid- and tau-independent hippocampal volume loss in transmembrane variant carriers (no mechanistic data in the study)?
- Would stratifying or covarying for PSEN1 domain change the power of dominantly inherited Alzheimer disease trials that use hippocampal volume as an outcome?

## Connections

- Gene and complex: [[PSEN1]], [[Gamma-secretase complex]], substrates [[APP]] and the [[Notch signaling]] pathway; partner presenilin [[PSEN2]]
- Disease: [[Familial Alzheimer disease]], [[Early-onset Alzheimer disease]]
- Phenotypes and biomarkers: [[Hippocampal atrophy]], [[Lateral ventricular volume]], [[Increased CSF phosphorylated tau concentration]], [[Cognitive impairment]], [[Amyloid PET]], [[Amyloid-beta]]
- Covariate: [[APOE]] ε4 status
- Cohort and design: [[Dominantly Inherited Alzheimer Network]], [[Expected years to symptom onset]], [[PSEN1 transmembrane and cytoplasmic domain grouping]]; the CSF protocol followed [[Alzheimer's Disease Neuroimaging Initiative]]
- Mechanistic hypothesis: [[Calcium signalling]]
- Related presenilin domain work: [[Presenilin transmembrane domain 5]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[PSEN1]] | biolink:causes | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "The majority of ADAD disease‐causing mutations occur in presenilin 1 (PSEN1), in which over 300 distinct pathogenic variations have been identified (Psen‐1\|Alzforum, )." |
| [[PSEN1]] | biolink:affects | [[APP]] |  | "As distinct portions of PSEN1 are differentially involved in APP processing by γ‐secretase and the generation of toxic β‐amyloid species, these results have important implications for understanding the pathobiology of ADAD and accounting for a substantial portion of the interindividual heterogeneity in ongoing ADAD clinical trials." |
| [[PSEN1]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "As distinct portions of PSEN1 are differentially involved in APP processing by γ‐secretase and the generation of toxic β‐amyloid species, these results have important implications for understanding the pathobiology of ADAD and accounting for a substantial portion of the interindividual heterogeneity in ongoing ADAD clinical trials." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "AD biomarkers are playing an increasingly integral role in AD therapeutic development, as shown by the profound influence that monitoring reductions in β‐amyloid PET signal have had in recent anti‐amyloid, disease modifying therapeutic trials for AD." |
| PSEN1 pathogenic variant (variant) | biolink:causes | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "Although pathogenic variants in PSEN1 leading to autosomal‐dominant Alzheimer disease (ADAD) are highly penetrant, substantial interindividual variability in the rates of cognitive decline and biomarker change are observed in ADAD." |
| PSEN1 pathogenic variant (variant) | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "We hypothesized that this interindividual variability may be associated with the location of the pathogenic variant within PSEN1." |
| PSEN1 pathogenic variant (variant) | biolink:associated_with | [[Cognitive impairment]] (MESH:D060825) |  | "While both CY and TM groups were found to have similarly elevated beta‐amyloid burden compared to non‐carriers, TM carriers had greater cognitive impairment, smaller hippocampal volume, and elevated phosphorylated tau levels compared to CY carriers." |
| PSEN1 pathogenic variant (variant) | biolink:associated_with | [[Hippocampal atrophy]] |  | "While both CY and TM groups were found to have similarly elevated beta‐amyloid burden compared to non‐carriers, TM carriers had greater cognitive impairment, smaller hippocampal volume, and elevated phosphorylated tau levels compared to CY carriers." |
| [[APP]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "As distinct portions of PSEN1 are differentially involved in APP processing by γ‐secretase and the generation of toxic β‐amyloid species, these results have important implications for understanding the pathobiology of ADAD and accounting for a substantial portion of the interindividual heterogeneity in ongoing ADAD clinical trials." |
| PSEN1 pathogenic variant (variant) | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "While both CY and TM groups were found to have similarly elevated beta‐amyloid burden compared to non‐carriers, TM carriers had greater cognitive impairment, smaller hippocampal volume, and elevated phosphorylated tau levels compared to CY carriers." |
| [[PSEN1]] | biolink:physically_interacts_with | [[APP]] |  | "In addition, the cytoplasmic portions (CY) of PSEN1, broadly speaking, are important for recruiting APP substrate into the γ‐secretase complex, and potentially also for retaining the APP substrate in the γ‐secretase complex to allow for successive γ‐cleavage of APP (processivity)." |
| [[PSEN1]] | biolink:associated_with | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "There is an increasing understanding of the phenotypic diversity of ADAD clinical and pathophysiological presentations associated with mutations in amyloid precursor protein (APP), PSEN1, and PSEN2." |
| [[PSEN2]] | biolink:physically_interacts_with | [[APP]] |  | "PSEN‐1/2 forms the catalytic core of the γ‐secretase complex and consistent with the complexity of γ‐secretase function and its unusual intramembrane proteolytic activity, different domains within PSEN‐1/2 likely play unique roles in the endopeptidase activity of γ‐secretase, docking of APP and other substrates, and in determining the efficiency of processive γ‐cleavage of Aβ peptides." |
| [[PSEN2]] | biolink:associated_with | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "There is an increasing understanding of the phenotypic diversity of ADAD clinical and pathophysiological presentations associated with mutations in amyloid precursor protein (APP), PSEN1, and PSEN2." |
| [[PSEN2]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "PSEN‐1/2 forms the catalytic core of the γ‐secretase complex and consistent with the complexity of γ‐secretase function and its unusual intramembrane proteolytic activity, different domains within PSEN‐1/2 likely play unique roles in the endopeptidase activity of γ‐secretase, docking of APP and other substrates, and in determining the efficiency of processive γ‐cleavage of Aβ peptides." |
| [[APP]] | biolink:associated_with | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "There is an increasing understanding of the phenotypic diversity of ADAD clinical and pathophysiological presentations associated with mutations in amyloid precursor protein (APP), PSEN1, and PSEN2." |
| PSEN1 pathogenic variant (variant) | biolink:associated_with | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "There is an increasing understanding of the phenotypic diversity of ADAD clinical and pathophysiological presentations associated with mutations in amyloid precursor protein (APP), PSEN1, and PSEN2." |
| PSEN1 pathogenic variant (variant) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "While this approach accounted for substantial inter‐individual heterogeneity in β‐amyloid PET, this categorization was not predictive of individual rates of clinical progression." |
| PSEN1 pathogenic variant (variant) | biolink:has_phenotype | [[Cognitive impairment]] (MESH:D060825) |  | "Both TM and CY groups demonstrated significantly lower MMSE scores with increasing EYO compared to the NC group (Table 2)." |
| [[PSEN1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Using FreeSurfer‐defined cortical and sub‐cortical regions of interest, we compared volumetric measures between the PSEN1 cytoplasmic (CY) and transmembrane (TM) groups across the disease continuum." |
| [[PSEN1]] | biolink:associated_with | Dementia (HP:0000726; MESH:D003704) |  | "In addition, the TM group had significantly greater CDR‐SB with increasing EYO as compared to the CY group (cubic EYO*Group: B [SE] = 0.26 [0.06] and p = 2.44e‐06; Table 2)." |
| [[PSEN1]] | biolink:associated_with | Brain atrophy (HP:0012444; MESH:D001284) |  | "Hippocampus and several midline cortical and sub‐cortical regions show greater neurodegeneration in TM carriers as compared to CY carriers." |
| [[PSEN1]] | biolink:associated_with | Neurodegeneration (HP:0002180) |  | "Hippocampus and several midline cortical and sub‐cortical regions show greater neurodegeneration in TM carriers as compared to CY carriers." |
| [[PSEN1]] | biolink:associated_with | [[Hippocampal atrophy]] |  | "We observed that the TM group had significantly lower HV with respect to EYO compared to the NC group (Table 2) and CY group (cubic EYO*Group: B [SE] = −86.22 [31.66] and p = 0.007), suggesting greater HV loss for a given EYO in TM carriers compared to CY carriers, particularly as carriers approached their familial age of symptom onset." |
| [[PSEN1]] | biolink:associated_with | [[Familial Alzheimer disease]] |  | "Using FreeSurfer‐defined cortical and sub‐cortical regions of interest, we compared volumetric measures between the PSEN1 cytoplasmic (CY) and transmembrane (TM) groups across the disease continuum." |
| [[PSEN1]] | biolink:associated_with | [[Cognitive impairment]] (MESH:D060825) |  | "Specifically, the direct effect (β = −0.57, p = 0.004) of PSEN1 grouping on MMSE was not significant when HV was included as a mediator (mediator effect was β = 0.67, p < 2e‐16; residual direct effect was β = −0.12, p = 0.460; Figure S3)." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "Further exploration of group differences in the precuneus, one of the earliest regions in ADAD to accumulate amyloid (Benzinger et al., ), revealed there was also no significant difference between the TM and CY groups in regional amyloid burden across EYO (linear EYO*Group: B [SE] = 0.01 [0.01] and p = 0.059)." |
| Pittsburgh compound B (CHEBI:53725; MESH:C475519) | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "The CY and TM groups did not significantly differ on a cortical composite PiB‐PET measure across EYO (linear EYO*Group: B [SE] = 0.02 [0.01] and p = 0.056; Figure 2e; Table 2)." |
| PSEN1 transmembrane domain variant (variant) | biolink:causes | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "We observed that individuals carrying a pathogenic variant affecting one of the nine transmembrane domains of PSEN1 had more rapid clinical, cognitive, and neurodegenerative progression of disease compared to those with variants affecting cytoplasmic domains." |
| PSEN1 cytoplasmic domain variant (variant) | biolink:causes | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "We observed that individuals carrying a pathogenic variant affecting one of the nine transmembrane domains of PSEN1 had more rapid clinical, cognitive, and neurodegenerative progression of disease compared to those with variants affecting cytoplasmic domains." |
| PSEN1 transmembrane domain variant (variant) | biolink:has_phenotype | Cognitive decline (HP:0001268; MESH:D060825) |  | "TM carriers demonstrate more rapid longitudinal cognitive decline and neurodegeneration as compared to CY carriers." |
| PSEN1 transmembrane domain variant (variant) | biolink:has_phenotype | [[Cognitive impairment]] (MESH:D060825) |  | "However, the findings here indicate that, compared to CY carriers, TM carriers may have more rapid decline in cognitive performance and functional status once the decline phase of ADAD has begun." |
| Neurodegeneration (HP:0002180) | NOT biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "In line with these results, past studies have identified TM pathogenic variants with impairments in intracellular calcium regulation (Psen‐1\|Alzforum, ), raising the possibility that dysregulation of calcium homeostasis may contribute to downstream neurodegeneration independent of Aβ and tau." |
| PSEN1 transmembrane domain variant (variant) | biolink:has_phenotype | Neurodegeneration (HP:0002180) |  | "TM carriers demonstrate more rapid longitudinal cognitive decline and neurodegeneration as compared to CY carriers." |
| Brain atrophy (HP:0012444; MESH:D001284) | NOT biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "This suggests that differences in brain atrophy and cognitive trajectories may not be directly explained by core measures of AD pathology." |
| PSEN1 transmembrane domain variant (variant) | biolink:has_phenotype | Brain atrophy (HP:0012444; MESH:D001284) |  | "Differences in brain atrophy between TM and CY carriers were observed across a wide set of AD‐relevant brain regions, including the hippocampus." |
| [[Hippocampal atrophy]] | NOT biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Observed differences between the CY and TM groups on HV were independent of concurrent levels of Aβ PET or CSF phospho‐tau 181." |
| PSEN1 transmembrane domain variant (variant) | biolink:has_phenotype | [[Hippocampal atrophy]] |  | "Notably, group differences in HV, lateral ventricle size, and midline cortical regions between the CY and TM groups were present 10 years or more prior to the expected age of symptom onset." |
| PSEN1 transmembrane domain variant (variant) | NOT biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "While measures of tau pathology (including phospho‐tau 181 and 217) differed between the CY and TM groups as well, though to a lesser extent, amyloid burden was not significantly different across the CY and TM groups." |
| PSEN1 cytoplasmic domain variant (variant) | NOT biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "While measures of tau pathology (including phospho‐tau 181 and 217) differed between the CY and TM groups as well, though to a lesser extent, amyloid burden was not significantly different across the CY and TM groups." |
| PSEN1 transmembrane domain variant (variant) | biolink:associated_with | Phosphorylated tau 217 (MESH:C000731974) |  | "While measures of tau pathology (including phospho‐tau 181 and 217) differed between the CY and TM groups as well, though to a lesser extent, amyloid burden was not significantly different across the CY and TM groups." |
| PSEN1 cytoplasmic domain variant (variant) | biolink:associated_with | Phosphorylated tau 217 (MESH:C000731974) |  | "While measures of tau pathology (including phospho‐tau 181 and 217) differed between the CY and TM groups as well, though to a lesser extent, amyloid burden was not significantly different across the CY and TM groups." |
| PSEN1 transmembrane domain variant (variant) | biolink:affects | Calcium (CHEBI:22984; MESH:D002118) |  | "In line with these results, past studies have identified TM pathogenic variants with impairments in intracellular calcium regulation (Psen‐1\|Alzforum, ), raising the possibility that dysregulation of calcium homeostasis may contribute to downstream neurodegeneration independent of Aβ and tau." |
| [[PSEN1]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Previous work examining variant‐dependent heterogeneity in CSF and PET measures of Aβ found grouping individuals with pathogenic variants in PSEN1, PSEN2, or APP based on the affected protein domain accounted for variability in Aβ biomarkers (Chhatwal et al., )." |
| [[PSEN1]] | biolink:contributes_to | Neurodegeneration (HP:0002180) |  | "Despite these limitations, the results here support a distinction between ADAD‐causing pathogenic variants that impact CY versus TM regions within PSEN1, whereby TM carriers have more rapid neurodegeneration, clinical and functional decline as compared to CY carriers." |
| [[PSEN1]] | biolink:contributes_to | [[Cognitive impairment]] (MESH:D060825) |  | "Despite these limitations, the results here support a distinction between ADAD‐causing pathogenic variants that impact CY versus TM regions within PSEN1, whereby TM carriers have more rapid neurodegeneration, clinical and functional decline as compared to CY carriers." |
| [[PSEN2]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Previous work examining variant‐dependent heterogeneity in CSF and PET measures of Aβ found grouping individuals with pathogenic variants in PSEN1, PSEN2, or APP based on the affected protein domain accounted for variability in Aβ biomarkers (Chhatwal et al., )." |
| [[APP]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "Previous work examining variant‐dependent heterogeneity in CSF and PET measures of Aβ found grouping individuals with pathogenic variants in PSEN1, PSEN2, or APP based on the affected protein domain accounted for variability in Aβ biomarkers (Chhatwal et al., )." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Indeed, less‐commonly studied monomeric (especially Aβ 43, 38, and 37), membrane retained (Aβ 45–49) and oligomeric forms of Aβ have been associated with AD diagnosis and progression (Devkota et al., ; Liu, Kwak, et al., ; Liu, Lauro, et al., )." |
| [[Amyloid-beta]] (MESH:D016229) | NOT biolink:correlated_with | Neurodegeneration (HP:0002180) |  | "More importantly, a consistent finding here and in this prior report is that levels of Aβ burden do not consistently mirror cognitive and neurodegenerative trajectories in ADAD." |
| [[Amyloid-beta]] (MESH:D016229) | NOT biolink:correlated_with | [[Cognitive impairment]] (MESH:D060825) |  | "More importantly, a consistent finding here and in this prior report is that levels of Aβ burden do not consistently mirror cognitive and neurodegenerative trajectories in ADAD." |
| [[APOE]] | NOT biolink:associated_with | Autosomal-dominant Alzheimer's disease (MONDO:0015140) |  | "It is also notable that a consistent APOE ε4 carrier state effect on disease progression has not been consistently seen in ADAD." |
