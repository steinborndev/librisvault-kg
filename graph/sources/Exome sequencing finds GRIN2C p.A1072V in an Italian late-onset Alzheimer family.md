---
type: source
title: "Exome sequencing finds GRIN2C p.A1072V in an Italian late-onset Alzheimer family"
paper_title: "Exome sequencing reveals a rare damaging variant in GRIN2C in familial late-onset Alzheimer's disease"
domain: neuroscience
status: developing
created: 2026-10-11
updated: 2026-10-11
content_updated: 2026-10-11
address: c-001024
pmid: "39810256"
pmcid: "PMC11730494"
doi: "10.1186/s13195-024-01661-y"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC11730494/"
sources: ["[[.raw/01M4P89V76K40TPW2DWCK9B3T5/normalized.md]]"]
tags: [familial-alzheimer, glutamate-receptor, rare-variant-burden]
---

# Exome sequencing finds GRIN2C p.A1072V in an Italian late-onset Alzheimer family

A family study with functional follow-up. A four-generation Northern Italian pedigree with autosomal dominant [[Late-onset Alzheimer disease]] was worked up by exome sequencing of three affected and two unaffected relatives. The rare missense variant [[GRIN2C p.A1072V]] in [[GRIN2C]] (the GluN2C subunit of the NMDA receptor) segregated with disease, and in rat hippocampal neurons the mutant subunit raised NMDA-induced currents, sat more at the cell surface and colocalized less with [[14-3-3 proteins]].

## Why This Source Matters

Most rare-variant work in [[Alzheimer disease]] concerns [[APP]], [[PSEN1]] and [[PSEN2]] in early-onset families, or risk genes found by large association studies. Here a late-onset family with none of those mutations points at glutamatergic signalling, for which the authors say no clear genetic evidence had existed. It is a single-family result with a gain-of-function-looking phenotype in an overexpression system, so it is a lead for the NMDA receptor axis (also the target of [[Memantine]]), not a replicated risk gene.

## Family and clinical picture

- Proband: 80-year-old woman seen in 2008 at a Turin memory clinic, symptom onset at 78 (short-term memory loss, spatial-temporal disorientation, apathy), preceded by major depression at 72. Mini-Mental State Examination 19 of 30; MRI showed bilateral frontal and parietal atrophy; SPECT showed mild posterior parietal hypoperfusion; lumbar puncture showed reduced Aβ42 and raised phosphorylated tau-181 (see [[Decreased amyloid beta 42 peptide CSF concentration]] and [[Increased CSF phosphorylated tau concentration]]). No myoclonus, cerebellar, spastic or extrapyramidal signs.
- Two siblings were diagnosed in their mid-seventies (one with CSF confirmation) and five more relatives clinically; eight siblings stayed dementia-free until death. All affected met the NIA-AA criteria for probable Alzheimer disease; none had autopsy confirmation.
- [[APOE]] genotypes (reconstructed from [[APOE rs429358]] and [[APOE rs7412]] in exome data for two relatives): ε3ε3 in the proband and two affected relatives, ε2ε4 and ε3ε4 in two others, so APOE ε4 does not explain the pedigree.

## Genetic findings

- Sanger sequencing of APP (plus multiplex PCR for duplication), PSEN1 and PSEN2, and the NeuroX array (about 24,000 variants, 77 neurodegeneration genes), found no known pathogenic variant. Exome sequencing of the three affected and two healthy relatives (BGI exome kit, BGISEQ-500, GATK best practices, hg19) confirmed that.
- Filtering funnel: 1,199 variants in the joint call, 663 "PASS" variants shared by the three affected and wild-type or carrier-only in the two healthy relatives, 22 rare heterozygous variants (gnomAD v2.1.1 allele frequency at most 0.001 and at most 0.02 in the in-house cohort), 16 with CADD phred of 15 or more, and 8 inside identity-by-descent segments, 5 of them on chromosome 17.
- None of the eight genes had an obvious Alzheimer link; GRIN2C had the highest Phenolyzer score (0.086) against the disease terms familial and late-onset Alzheimer disease. The change is NM_000835.6:c.3215C>T, p.Ala1072Val, in exon 13 at chr17:74,842,922, in the cytoplasmic C-terminal domain; Metadome rates the residue intolerant.
- Population frequency: 2.64e-05 in gnomAD v4.0 (15 heterozygous alleles, 13 of them non-Finnish European), with a coverage warning at the position (only 20% of individuals) but a consistent frequency in genomes (2.63e-05). Ages were available for only 3 of the 15 carriers, all under 70, which the authors note is compatible with a late-onset condition.
- Sanger sequencing of 15 relatives: the variant was present in all 6 affected and absent from all 9 unaffected. Single-point parametric linkage in Merlin (autosomal dominant, penetrance 0.90, prevalence 1%) gave a LOD score of 2.070 (p = 0.001).

## Functional findings (rat hippocampal neurons)

- Neurons at 14 days in vitro were cotransfected with EGFP-tagged human GluN2C (wild type or A1072V) plus HA-GluN1 ([[GRIN1]]). Whole-cell voltage clamp at -60 mV with a 6 s puff of 400 µM NMDA gave a larger peak current in A1072V neurons (one-way ANOVA with Tukey test, P = 0.035; numbers of neurons not given in the text).
- The GluN2C/D blocker [[QNZ46]] removed a larger share of the NMDA current in A1072V neurons than in wild-type neurons (unpaired t test, P = 0.002), read as showing that the extra current comes from the mutant GluN2C subunit.
- Surface-to-total GluN2C staining along dendrites was higher for A1072V (t(53) = 2.693, p = 0.0095; 28 and 27 neurons from 4 experiments).
- The residue lies next to the 14-3-3 binding motif and the PKB (AKT) phosphorylation site at Ser1081. A pan-14-3-3 antibody showed less GluN2C and 14-3-3 colocalization for A1072V (t(44) = 4.411, p < 0.0001; 23 neurons per group from 3 experiments). The authors propose that once the mutant receptor reaches the membrane it leaves 14-3-3 quickly, so 14-3-3 acts as a cargo carrier rather than a scaffold.

## Discussion points raised

- Previous exome work found rare damaging variants in ATP8B4 and [[ABCA1]]; a multivariate GWAS of CSF biomarker profiles found a gene-based signal in GRIN2D, and the authors take both as support for rare variants and altered synaptic function.
- Links drawn to [[Excitotoxicity]]: amyloid-beta oligomers and NMDA receptors jointly disturb synapses, and excess dendritic tau raises NMDA receptor activity and calcium. Memantine is reported to lower GluN2C expression and GRIN2C mRNA in prefrontal cortex.
- The authors list as limits that diagnoses are not neuropathologically confirmed and that a single family can only classify the variant as family-specific.

## Methods

Whole-exome sequencing ([[Whole-exome sequencing]]) with segregation and linkage work as described in [[Pedigree linkage and identity-by-descent analysis]]; primary rat neuron cultures (E18-E19, calcium phosphate transfection at DIV10), immunocytochemistry with LSM900 confocal imaging and JACoP colocalization, and whole-cell patch clamp with an Axopatch 200B.

## Assessment

- The LOD score of 2.07 is below the conventional threshold of 3 for linkage, so statistical support rests on the filtering funnel, the IBD sharing and Sanger segregation in 15 people rather than on linkage alone.
- Only three affected exomes were sequenced; the seven other candidate variants in IBD segments (four more on chromosome 17, where GRIN2C lies) are not excluded by the functional work, and Phenolyzer ranking is a weak prior (the authors concede no gene had a clear Alzheimer link).
- The functional data come from overexpression of tagged human GluN2C in rat neurons against endogenous receptors, without a knock-in or patient-derived neurons, with no stated neuron counts for the electrophysiology, and with an unreplicated, indirect readout (pan-14-3-3 colocalization) for the mechanism. Whether higher NMDA current is the cause of disease or incidental is untested; no amyloid or tau measure was made in the model.
- The text has internal slips: the Results list II7 as the proband but also as one of the two relatives with reconstructed APOE genotype, the NMDA concentration is 400 µM in Methods and "400 mM" in a figure legend, QNZ46 is given as 10 mM, and one paragraph on the Ser1081 and 14-3-3 hypothesis is duplicated. The data-availability statement says no datasets were generated, so the exome calls are not deposited.

## Connections

- Gene and variant: [[GRIN2C]], [[GRIN2C p.A1072V]]; partner subunit [[GRIN1]]; interacting proteins [[14-3-3 proteins]]; tool compound [[QNZ46]]; drug [[Memantine]]
- Disease context: [[Late-onset Alzheimer disease]], [[Familial Alzheimer disease]], [[Alzheimer disease]]; excluded genes [[APP]], [[PSEN1]], [[PSEN2]]; genotype [[APOE]]; neighbouring rare-variant gene [[ABCA1]]
- Mechanism context: [[Excitotoxicity]], [[Amyloid-beta]], [[MAPT]]
- Method: [[Whole-exome sequencing]], [[Pedigree linkage and identity-by-descent analysis]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[GRIN2C]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We identified a rare missense variant in GRIN2C associated with late-onset autosomal dominant Alzheimer's disease." |
| [[GRIN2C]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We identified a rare missense variant in GRIN2C associated with late-onset autosomal dominant Alzheimer's disease." |
| [[GRIN2C]] | biolink:associated_with | 14-3-3 proteins (HGNC:12854) |  | "Additionally, immunocytochemistry revealed in neurons expressing the mutant variant a reduced colocalization between the GluN2C subunit and 14-3-3 proteins, which are known to facilitate membrane trafficking of NMDARs." |
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Rare genetic variants in the APP and PSEN1 and PSEN2 genes have been reported as pathogenic causes of early-onset Alzheimer’s disease, but they account for less than 1% of all cases." |
| [[PSEN1]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Rare genetic variants in the APP and PSEN1 and PSEN2 genes have been reported as pathogenic causes of early-onset Alzheimer’s disease, but they account for less than 1% of all cases." |
| [[PSEN2]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Rare genetic variants in the APP and PSEN1 and PSEN2 genes have been reported as pathogenic causes of early-onset Alzheimer’s disease, but they account for less than 1% of all cases." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "These studies have captured approximately 50% of the heritability of late-onset Alzheimer’s disease, and the APOE ε4 allele is the major genetic risk factor for sporadic cases." |
| [[GRIN2C p.A1072V]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We identified a rare missense variant in GRIN2C associated with late-onset autosomal dominant Alzheimer's disease." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "These studies have captured approximately 50% of the heritability of late-onset Alzheimer’s disease, and the APOE ε4 allele is the major genetic risk factor for sporadic cases." |
| [[GRIN2C p.A1072V]] | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "We identified a rare missense variant in GRIN2C associated with late-onset autosomal dominant Alzheimer's disease." |
| [[APP]] | biolink:causes | Early-onset Alzheimer disease (MESH:D000544) |  | "Rare genetic variants in the APP and PSEN1 and PSEN2 genes have been reported as pathogenic causes of early-onset Alzheimer’s disease, but they account for less than 1% of all cases." |
| [[PSEN1]] | biolink:causes | Early-onset Alzheimer disease (MESH:D000544) |  | "Rare genetic variants in the APP and PSEN1 and PSEN2 genes have been reported as pathogenic causes of early-onset Alzheimer’s disease, but they account for less than 1% of all cases." |
| [[PSEN2]] | biolink:causes | Early-onset Alzheimer disease (MESH:D000544) |  | "Rare genetic variants in the APP and PSEN1 and PSEN2 genes have been reported as pathogenic causes of early-onset Alzheimer’s disease, but they account for less than 1% of all cases." |
| 14-3-3 proteins (HGNC:12854) | biolink:affects | N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) | direction=increased | "Additionally, immunocytochemistry revealed in neurons expressing the mutant variant a reduced colocalization between the GluN2C subunit and 14-3-3 proteins, which are known to facilitate membrane trafficking of NMDARs." |
| [[GRIN2C p.A1072V]] | biolink:affects | Glutamate (CHEBI:16015; MESH:D018698) |  | "Primary rat hippocampal neurons overexpressing GluN2CA1072V showed an increase in NMDAR-induced currents, suggesting altered glutamatergic transmission." |
| [[GRIN2C p.A1072V]] | biolink:affects | N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) | direction=increased | "Primary rat hippocampal neurons overexpressing GluN2CA1072V showed an increase in NMDAR-induced currents, suggesting altered glutamatergic transmission." |
| [[GRIN2C]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, we provide data supporting a role for Glun2C-containing NMDARs and 14-3-3 proteins in Alzheimer’s disease pathogenesis." |
| Glutamate (CHEBI:16015; MESH:D018698) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Notably, dysfunction in glutamatergic signaling occurs early in the progression of Alzheimer’s disease, even before the onset of cognitive decline." |
| [[Memantine]] (MESH:D008559) | biolink:treats | [[Alzheimer disease]] (MESH:D000544) |  | "This effect is primarily mediated by the activation of extrasynaptic NMDARs and can be counteracted by memantine, a medication currently used to treat Alzheimer's disease." |
| 14-3-3 proteins (HGNC:12854) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, we provide data supporting a role for Glun2C-containing NMDARs and 14-3-3 proteins in Alzheimer’s disease pathogenesis." |
| GRIN2C p.(A1072V) (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In this study, we examined a large Italian family, and we report for the first time a rare missense variant in GRIN2C associated with late-onset autosomal dominant Alzheimer’s disease." |
| [[MAPT]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Lumbar puncture revealed reduced Aβ42 values and increased phosphorylated tau-181 levels." |
| [[Amyloid-beta]] | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "Lumbar puncture revealed reduced Aβ42 values and increased phosphorylated tau-181 levels." |
| [[PSEN1]] | NOT biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "In 2009, no pathogenic variants were identified in the APP, PSEN1, and PSEN2 genes in the three living patients with Alzheimer's disease, and these negative findings were also confirmed in ES." |
| [[PSEN2]] | NOT biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "In 2009, no pathogenic variants were identified in the APP, PSEN1, and PSEN2 genes in the three living patients with Alzheimer's disease, and these negative findings were also confirmed in ES." |
| [[GRIN2C]] | biolink:contributes_to | neurodegeneration (HP:0002180) |  | "However, excessive NMDAR activity can lead to excitotoxicity and contribute to neurodegeneration." |
| [[Memantine]] (MESH:D008559) | biolink:affects | [[GRIN2C]] | direction=decreased | "This effect is primarily mediated by the activation of extrasynaptic NMDARs and can be counteracted by memantine, a medication currently used to treat Alzheimer's disease." |
| 14-3-3 proteins (HGNC:12854) | biolink:regulates | [[GRIN2C]] | direction=increased | "Interestingly, proteins such as 14-3-3 play a dynamic role in regulating NMDAR trafficking, targeting the receptor to the cell surface to facilitate glutamatergic neurotransmission." |
| Glutamate (CHEBI:16015; MESH:D018698) | biolink:associated_with | Cognitive decline (HP:0001268; MESH:D060825) |  | "Notably, dysfunction in glutamatergic signaling occurs early in the progression of Alzheimer’s disease, even before the onset of cognitive decline." |
| 14-3-3 proteins (HGNC:12854) | biolink:affects | Glutamate (CHEBI:16015; MESH:D018698) | direction=increased | "Interestingly, proteins such as 14-3-3 play a dynamic role in regulating NMDAR trafficking, targeting the receptor to the cell surface to facilitate glutamatergic neurotransmission." |
| [[Memantine]] (MESH:D008559) | biolink:treats | neurodegeneration (HP:0002180) |  | "This effect is primarily mediated by the activation of extrasynaptic NMDARs and can be counteracted by memantine, a medication currently used to treat Alzheimer's disease." |
| selective serotonin reuptake inhibitors (MESH:D017367) | biolink:treats | major depression (MONDO:0002009) |  | "At the age of 72 years, she was diagnosed with major depression and treated with selective serotonin reuptake inhibitors." |
| [[GRIN2C]] | biolink:physically_interacts_with | N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) |  | "GluN2C is one of the subunits that forms the heterotetrameric structure of NMDA receptors." |
| [[GRIN2C]] | biolink:physically_interacts_with | 14-3-3 proteins (HGNC:12854) |  | "GluN2CA1072V amino acid substitution in the GRIN2C gene promotes GluN2C surface expression and negatively affects the interaction of GluN2C with 14-3-3 scaffolding proteins." |
| [[AKT1]] | biolink:physically_interacts_with | [[GRIN2C]] |  | "In the figure, the amino acid substitution (A1072V), the 14-3-3 binding motif, the PKB recognition motif and the PKB phosphorylation site are highlighted." |
| [[GRIN2C]] | biolink:associated_with | [[Familial Alzheimer disease]] |  | "Although none of the corresponding genes had a clearcut relationship with Alzheimer’s disease pathobiology, GRIN2C received the relatively highest score in Phenolyzer analysis (0.086) on the Phenolyzer website accessed 03/2372024, against the disease terms “Alzheimer’s disease familial” and “Alzheimer’s disease late onset” (Supplementary Fig. 1)." |
| [[GRIN2C p.A1072V]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "We found that it segregated in patients with Alzheimer’s disease in the family, but not in family members who did not show any cognitive impairment (Fig. 1A)." |
| APOE ε3ε3 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "For APOE genotyping, the proband was found to carry the APOE ε3ε3 genotype, and two affected relatives (III5 and III12) also carried ε3ε3 genotype." |
| APOE ε2ε4 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Using exome sequencing data and combining rs429358 (T > C) and rs7412 (C > T), APOE genotypes was reconstructed for other two affected relatives (II7, III11) who carried the ε2ε4 genotype and ε3ε4 genotype, respectively." |
| APOE ε3ε4 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Using exome sequencing data and combining rs429358 (T > C) and rs7412 (C > T), APOE genotypes was reconstructed for other two affected relatives (II7, III11) who carried the ε2ε4 genotype and ε3ε4 genotype, respectively." |
| [[GRIN2C p.A1072V]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Linkage between such a rare allele and the dementia phenotype in this family is strongly supported with a LOD score of 2.070 (p = 0.001)." |
| [[GRIN2C p.A1072V]] | biolink:associated_with | [[Cognitive impairment]] (MESH:D060825) |  | "We found that it segregated in patients with Alzheimer’s disease in the family, but not in family members who did not show any cognitive impairment (Fig. 1A)." |
| [[GRIN2C p.A1072V]] | biolink:affects | N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) |  | "Analysis of NMDA-induced responses generated in untreated, GluN2CWT and GluN2CA1072V cells (one-way ANOVA, Tukey's multiple comparisons test, P = 0.035; each dot indicates the NMDA current generated in a single neuron)." |
| [[AKT1]] | biolink:affects | [[GRIN2C]] |  | "When GluN2C-containing NMDARs are phosphorylated at Ser1081 by PKB, they can interact with 14-3-3 proteins." |
| GRIN2C A1072V (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In line with these efforts, our study adds a novel gene to the growing body of evidence supporting the role of rare variants in Alzheimer's disease." |
| GRIN2C A1072V (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "To our knowledge, this study was the first to identify a GRIN2C missense variant in late-onset Alzheimer's disease with functional consequences on NMDAR-induced currents and interaction with 14-3-3 scaffolding proteins." |
| GRIN2C A1072V (variant) | biolink:affects | N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) | direction=increased | "As shown in Fig. 2A, B, we observed an elevated peak current mediated by NMDA in cells overexpressing GluN2CA1072V, suggesting that this change may result in abnormal glutamatergic transmission when NMDAR is activated." |
| GRIN2C A1072V (variant) | biolink:affects | Glutamate (CHEBI:16015; MESH:D018698) |  | "As shown in Fig. 2A, B, we observed an elevated peak current mediated by NMDA in cells overexpressing GluN2CA1072V, suggesting that this change may result in abnormal glutamatergic transmission when NMDAR is activated." |
| ATP8B4 (HGNC:13536) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A recent exome sequencing study identified rare potentially damaging variants in the ATP8B4 and ABCA1 genes that are associated with AD risk." |
| [[ABCA1]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "A recent exome sequencing study identified rare potentially damaging variants in the ATP8B4 and ABCA1 genes that are associated with AD risk." |
| Rare variants (variant) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "To address this limitation, researchers are now employing next-generation strategies, such as exome sequencing and genome sequencing, to identify rare variants that contribute to Alzheimer’s disease." |
| Common variants (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Previous GWASs have identified more than 50 genetic loci associated with late-onset AD, primarily in individuals of European ancestry. However, these studies have mostly identified common variants, and it is believed that only approximately half of the genetic heritability of Alzheimer's disease has been explained thus far." |
| Common variants (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "Previous GWASs have identified more than 50 genetic loci associated with late-onset AD, primarily in individuals of European ancestry. However, these studies have mostly identified common variants, and it is believed that only approximately half of the genetic heritability of Alzheimer's disease has been explained thus far." |
| [[GRIN2C]] | biolink:affects | CREB1 (HGNC:2345) | direction=decreased | "Furthermore, the absence of GluN2C activates intracellular signaling pathways that support neuronal survival, as demonstrated by heightened levels of nuclear cAMP response element-binding protein." |
| [[GRIN2C]] | biolink:associated_with | N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) |  | "GRIN2C encodes the glutamate ionotropic N-Methyl-D-aspartate receptor (NMDA) type subunit 2C (also called GluN2C), and the subunits of NMDA receptors (NMDARs) are known for their distinct roles in regulating synaptic plasticity, as well as influencing processes related to learning and memory." |
| GRIN2D (HGNC:4588) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In this direction, interestingly, a recent study on multivariate GWAS in Alzheimer’s disease that investigated the role of genetic variants on CSF biomarker profiles showed a genome-wide significant gene-based association with variants in GRIN2D and the synaptic functioning components, further supporting a role of altered synaptic function in AD." |
| [[MAPT]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The relationships between the pathological hallmarks of Alzheimer’s disease, such as amyloid-beta (Aβ) deposition and Tau hyperphosphorylation, and glutamatergic transmission have mainly been studied in vitro." |
| [[MAPT]] | biolink:associated_with | neurofibrillary tangles (HP:0002185) |  | "Additionally, Tau, a major component of neurofibrillary tangles, plays a crucial role in regulating synaptic function." |
| [[MAPT]] | biolink:associated_with | Glutamate (CHEBI:16015; MESH:D018698) |  | "The relationships between the pathological hallmarks of Alzheimer’s disease, such as amyloid-beta (Aβ) deposition and Tau hyperphosphorylation, and glutamatergic transmission have mainly been studied in vitro." |
| [[MAPT]] | biolink:affects | N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) |  | "Excess tau in Alzheimer’s disease dendrites controls NMDA receptor activity, leading to an increase in calcium levels in dendrites that can reach damaging levels." |
| [[MAPT]] | biolink:affects | calcium (CHEBI:22984; MESH:D002118) | direction=increased | "Excess tau in Alzheimer’s disease dendrites controls NMDA receptor activity, leading to an increase in calcium levels in dendrites that can reach damaging levels." |
| [[Amyloid-beta]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The relationships between the pathological hallmarks of Alzheimer’s disease, such as amyloid-beta (Aβ) deposition and Tau hyperphosphorylation, and glutamatergic transmission have mainly been studied in vitro." |
| [[Amyloid-beta]] | biolink:affects | Glutamate (CHEBI:16015; MESH:D018698) |  | "The effect of Aβ on synapses is to alter glutamatergic synaptic transmission and decrease the number of surface receptors for glutamate and other synaptic components in hippocampal neurons." |
| Glutamate (CHEBI:16015; MESH:D018698) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "In literature, several studies support the involvement of the neurotransmitter glutamate and its receptors in the pathogenesis of Alzheimer’s disease." |
| N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Several reports have shown that Aβ oligomers and NMDARs contribute to synaptic dysfunction and disruption in AD." |
| calcium (CHEBI:22984; MESH:D002118) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The loss of Ca2+ homeostasis is believed to be connected to the early cognitive deficits observed in AD." |
| [[Amyloid-beta]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Several reports have shown that Aβ oligomers and NMDARs contribute to synaptic dysfunction and disruption in AD." |
| Glutamate (CHEBI:16015; MESH:D018698) | biolink:contributes_to | neurological disorder (MONDO:0000001; MESH:D009422) |  | "Altered glutamatergic neurotransmission could represent a common factor, providing a unifying perspective to explain the neurocognitive impairments and symptomatic features observed in different neurological disorders." |
| Glutamate (CHEBI:16015; MESH:D018698) | biolink:contributes_to | [[Cognitive impairment]] (MESH:D060825) |  | "Altered glutamatergic neurotransmission could represent a common factor, providing a unifying perspective to explain the neurocognitive impairments and symptomatic features observed in different neurological disorders." |
| calcium (CHEBI:22984; MESH:D002118) | biolink:associated_with | [[Cognitive impairment]] (MESH:D060825) |  | "The loss of Ca2+ homeostasis is believed to be connected to the early cognitive deficits observed in AD." |
| N-methyl-D-aspartate (CHEBI:31882; MESH:D016202) | biolink:affects | calcium (CHEBI:22984; MESH:D002118) | direction=increased | "Excess tau in Alzheimer’s disease dendrites controls NMDA receptor activity, leading to an increase in calcium levels in dendrites that can reach damaging levels." |
| 14-3-3 proteins (HGNC:12854) | biolink:biomarker_for | [[Alzheimer disease]] (MESH:D000544) |  | "The presence of 14-3-3 proteins in cerebrospinal fluid serves as a sensitive and specific biomarker for neuronal damage associated with several neurological diseases, including Creutzfeldt‒Jakob disease, Alzheimer's disease, brain cancers, and stroke." |
| 14-3-3 proteins (HGNC:12854) | biolink:biomarker_for | [[Creutzfeldt-Jakob disease]] (MESH:D007562) |  | "The presence of 14-3-3 proteins in cerebrospinal fluid serves as a sensitive and specific biomarker for neuronal damage associated with several neurological diseases, including Creutzfeldt‒Jakob disease, Alzheimer's disease, brain cancers, and stroke." |
| 14-3-3 proteins (HGNC:12854) | biolink:biomarker_for | Brain cancer (MONDO:0001657; MESH:D001932) |  | "The presence of 14-3-3 proteins in cerebrospinal fluid serves as a sensitive and specific biomarker for neuronal damage associated with several neurological diseases, including Creutzfeldt‒Jakob disease, Alzheimer's disease, brain cancers, and stroke." |
| 14-3-3 proteins (HGNC:12854) | biolink:biomarker_for | Stroke (MONDO:0005098; MESH:D020521) |  | "The presence of 14-3-3 proteins in cerebrospinal fluid serves as a sensitive and specific biomarker for neuronal damage associated with several neurological diseases, including Creutzfeldt‒Jakob disease, Alzheimer's disease, brain cancers, and stroke." |
| 14-3-3 proteins (HGNC:12854) | biolink:biomarker_for | Neurological disease (MONDO:0005071) |  | "The presence of 14-3-3 proteins in cerebrospinal fluid serves as a sensitive and specific biomarker for neuronal damage associated with several neurological diseases, including Creutzfeldt‒Jakob disease, Alzheimer's disease, brain cancers, and stroke." |
| GRIN2C p.Ala1072Val (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In conclusion, this study presents findings on a family in which late-onset Alzheimer's disease is associated with the p.(Ala1072Val) variant in the GRIN2C gene." |
| GRIN2C p.Ala1072Val (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "In conclusion, this study presents findings on a family in which late-onset Alzheimer's disease is associated with the p.(Ala1072Val) variant in the GRIN2C gene." |
