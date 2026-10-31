---
type: source
title: "Double APP and PSEN2 mutations in a Korean patient with early-onset Alzheimer disease"
paper_title: "Double Mutations in a Patient with Early-Onset Alzheimer’s Disease in Korea: An APP Val551Met and a PSEN2 His169Asn"
domain: neuroscience
status: developing
created: 2026-10-08
updated: 2026-10-08
content_updated: 2026-10-08
address: c-000275
pmid: "37108607"
pmcid: "PMC10140908"
doi: "10.3390/ijms24087446"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC10140908/"
sources: ["[[.raw/01M4DY94MSS37VNXBKE9GKVQFJ/normalized.md]]"]
tags: [familial-alzheimer, case-report, whole-exome-sequencing]
---

# Double APP and PSEN2 mutations in a Korean patient with early-onset Alzheimer disease

A single-patient case report. A 63-year-old Korean woman with progressive memory decline and mild right hippocampal atrophy carried two heterozygous rare missense variants, [[APP p.V551M]] (rs761339914) and [[PSEN2 p.H169N]] (rs533813519), found by whole-exome sequencing and confirmed by Sanger sequencing. The authors present it as the first reported case with rare variants in both [[APP]] and [[PSEN2]], and suggest the two may act together.

## Case

- Memory decline began about 2 years before her first visit; Mini-Mental State Examination 27/30 and global deterioration scale 2 at first, with visuospatial dysfunction on neuropsychological testing. Brain MRI showed mild right hippocampal atrophy. The first diagnosis was mild cognitive impairment due to [[Alzheimer disease]].
- Two years later she scored 24/30 (global deterioration scale 3), could not find a familiar route, and was started on donepezil 10 mg/day.
- Her mother was diagnosed with Alzheimer disease in her early 70s and died in her 80s. Three siblings had no neurodegenerative symptoms and declined genetic testing, so the origin of both variants (inherited or de novo) is unknown.

## Methods

- DNA from whole blood; whole-exome sequencing on an Illumina platform, with variants confirmed by exon-specific PCR and Sanger sequencing. Diagnosis followed National Institute on Aging-Alzheimer's Association criteria; the study had institutional review board approval and consent.
- Allele frequencies were taken from the TOPMED, ExAC, 8.3 KJPN and Korean population databases. PolyPhen-2 and SIFT classed the substitutions, and Missense3D with Discovery Studio 3.5 Visualizer modelled the mutant structures and neighbouring-residue contacts.

## Findings

- APP rs761339914 is very rare in general databases (0.000008 in TOPMED, 0.000025 in ExAC); the authors call the change novel. PolyPhen-2 read it as likely damaging and SIFT as tolerated.
- PSEN2 rs533813519 is 0.000165 in ExAC and 0.000057 in TOPMED, but higher in Korean data (0.00078 in 8.3 KJPN, 0.0041 in the Korean database). It has been reported before in five patients (one in Korea, four in China), all with onset before 65 years and progressive memory loss; this patient is the sixth in East Asia.
- The predicted APP structure showed no overall change, but Met551 made a hydrophobic contact with Leu480 on the other helix chain instead of the wild-type contact with Ala553. This sits in the E2 domain, which mediates APP self-dimerisation, so the authors propose altered dimerisation and altered amyloid beta production.
- Other E2 domain changes (Arg486Trp, Lys496Gln, Tyr538His, Val562Ile) are described as low-risk and unable to cause disease alone; cells carrying Tyr538His and Val562Ile, near Val551Met, showed lower amyloid beta 40.
- PSEN2 His169Asn lies in transmembrane domain III, a conserved region holding other Alzheimer-linked changes (Met174Ile, Met174Val, Ser175Cys, Ser175Phe, Phe183Ser), and is predicted to twist the helix. Because it has been seen only in East Asians, the authors suggest a founder mutation.
- They argue that a minor-effect APP variant combined with PSEN2 His169Asn could bring on disease, in the spirit of a rare-variant risk score, and that an East Asian screening panel for [[Early-onset Alzheimer disease]] should include PSEN2 His169Asn.

## Assessment

- One patient, no segregation data, no functional assay: the synergy between the two variants is a hypothesis from structure prediction only. Family members were not tested and the family history could not be fully defined.
- PolyPhen-2 and SIFT disagree on APP p.V551M, and the structural model shows no gross change; the pathogenicity of the APP variant is unsupported by the data shown.
- Reading PSEN2 His169Asn as a founder mutation rests on its absence from non-Asian databases and six case reports.

## Open Questions

- Does APP p.V551M change amyloid beta 40 and 42 secretion or APP dimerisation in cells (only structure prediction was done)?
- Is PSEN2 p.H169N, in cells or knock-in models, enough to alter the ratio of amyloid beta 42 to 40 without the APP change?
- Do the APP and PSEN2 variants co-segregate with disease in the patient's relatives (the siblings declined genetic testing and the mother's status is unknown)?
- Do East Asian carriers of PSEN2 p.H169N share a haplotype, which would support a founder origin?

## Why This Source Matters

It adds a worked example of a digenic rare-variant case to the vault's familial Alzheimer material: where the [[SORL1]] sequencing study excluded carriers of pathogenic APP and presenilin variants, this report shows that kind of carrier clinically, in an East Asian patient whose onset is later than typical presenilin disease. It also gives population frequencies for PSEN2 p.H169N that show why Korean and Chinese cohorts need ancestry-specific screening panels.

## Connections

- Genes: [[APP]], [[PSEN2]]; pathway: [[Amyloid-beta formation]]
- Variants: [[APP p.V551M]], [[PSEN2 p.H169N]]
- Disease: [[Early-onset Alzheimer disease]], [[Alzheimer disease]]
- Related variant interpretation by structural domain: [[Domain mapping of disease mutations]], [[Domain mapping of SORL1 missense variants in Alzheimer disease]]
- Combining rare variants into a risk estimate: [[Polygenic risk score]], [[Probability of Alzheimer disease from polygenic score, APOE and rare variants]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[BACE1]] | biolink:affects | [[APP]] |  | "Aβ peptides are generated by the sequential cleavage of APP by β-secretase and γ-secretase." |
| [[APP]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the genes encoding amyloid precursor protein (APP), presenilin 1 (PS1), and presenilin 2 (PS2) proteins affect amyloid beta (Aβ) generation, leading to altered APP cleavage and the pathophysiology underlying Alzheimer’s disease (AD) progression." |
| [[APP]] | biolink:contributes_to | Early-onset Alzheimer disease (MESH:D000544) |  | "The etiology of early-onset Alzheimer’s disease (EOAD) is associated with alterations in the production of amyloid beta (Aβ) species caused by mutations in the APP, PSEN1, and PSEN2 genes." |
| [[PSEN2]] | biolink:associated_with | [[PSEN1]] |  | "PSEN2, which has 87 reported rare mutations, is highly homologous to PSEN1." |
| [[PSEN1]] | biolink:physically_interacts_with | NCSTN (HGNC:17091) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| [[PSEN1]] | biolink:physically_interacts_with | PSENEN (HGNC:30100) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| [[PSEN1]] | biolink:physically_interacts_with | APH1A (HGNC:29509) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| [[PSEN1]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the genes encoding amyloid precursor protein (APP), presenilin 1 (PS1), and presenilin 2 (PS2) proteins affect amyloid beta (Aβ) generation, leading to altered APP cleavage and the pathophysiology underlying Alzheimer’s disease (AD) progression." |
| [[PSEN1]] | biolink:contributes_to | Early-onset Alzheimer disease (MESH:D000544) |  | "The etiology of early-onset Alzheimer’s disease (EOAD) is associated with alterations in the production of amyloid beta (Aβ) species caused by mutations in the APP, PSEN1, and PSEN2 genes." |
| [[PSEN1]] | biolink:affects | Amyloid beta (CHEBI:64645; MESH:D016229) |  | "Mutations in the genes encoding amyloid precursor protein (APP), presenilin 1 (PS1), and presenilin 2 (PS2) proteins affect amyloid beta (Aβ) generation, leading to altered APP cleavage and the pathophysiology underlying Alzheimer’s disease (AD) progression." |
| [[PSEN1]] | biolink:affects | Amyloid beta 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Based on the Alzforum database (, assessed on 14 February 2023), mutations in PSEN1 have been reported in 357 cases, which typically resulted in increased Aβ42 secretion compared with Aβ40 secretion." |
| [[PSEN2]] | biolink:physically_interacts_with | NCSTN (HGNC:17091) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| [[PSEN2]] | biolink:physically_interacts_with | PSENEN (HGNC:30100) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| [[PSEN2]] | biolink:physically_interacts_with | APH1A (HGNC:29509) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| [[PSEN2]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the genes encoding amyloid precursor protein (APP), presenilin 1 (PS1), and presenilin 2 (PS2) proteins affect amyloid beta (Aβ) generation, leading to altered APP cleavage and the pathophysiology underlying Alzheimer’s disease (AD) progression." |
| [[PSEN2]] | biolink:contributes_to | Early-onset Alzheimer disease (MESH:D000544) |  | "The etiology of early-onset Alzheimer’s disease (EOAD) is associated with alterations in the production of amyloid beta (Aβ) species caused by mutations in the APP, PSEN1, and PSEN2 genes." |
| [[PSEN2]] | biolink:affects | Amyloid beta (CHEBI:64645; MESH:D016229) |  | "Mutations in the genes encoding amyloid precursor protein (APP), presenilin 1 (PS1), and presenilin 2 (PS2) proteins affect amyloid beta (Aβ) generation, leading to altered APP cleavage and the pathophysiology underlying Alzheimer’s disease (AD) progression." |
| [[MAPT]] | biolink:contributes_to | Neurofibrillary tangles (HP:0002185) |  | "Patients with early-onset Alzheimer’s disease (EOAD) have numerous mutations in the aforementioned genes related to the deposition of extracellular Aβ plaques and intraneuronal neurofibrillary tangles by tau proteins in the brain." |
| NCSTN (HGNC:17091) | biolink:physically_interacts_with | PSENEN (HGNC:30100) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| NCSTN (HGNC:17091) | biolink:physically_interacts_with | APH1A (HGNC:29509) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| PSENEN (HGNC:30100) | biolink:physically_interacts_with | APH1A (HGNC:29509) |  | "PS1 and PS2 are crucial γ-secretase components, which belong to a multiprotein complex composed of intramembrane proteases as well as nicastrin, presenilin enhancer 2, and anterior pharynx defective 1." |
| [[BACE1]] | biolink:affects | Amyloid beta (CHEBI:64645; MESH:D016229) | direction=increased | "Aβ peptides are generated by the sequential cleavage of APP by β-secretase and γ-secretase." |
| [[APP p.V551M]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Two AD-related mutations, in APP (rs761339914; c.G1651A; p.V551M) and PSEN2 (rs533813519; c.C505A; p.H169N), were identified." |
| [[PSEN2 p.H169N]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Two AD-related mutations, in APP (rs761339914; c.G1651A; p.V551M) and PSEN2 (rs533813519; c.C505A; p.H169N), were identified." |
| Amyloid beta (CHEBI:64645; MESH:D016229) | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "The etiology of early-onset Alzheimer’s disease (EOAD) is associated with alterations in the production of amyloid beta (Aβ) species caused by mutations in the APP, PSEN1, and PSEN2 genes." |
| [[APP p.V551M]] | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "This article describes the clinical phenotype of a 64-year-old Korean woman with EOAD who had double mutations in APP and PSEN2, which included a novel APP Val551Met mutation and a PSEN2 His169Asn previously reported in Asian patients." |
| [[PSEN2 p.H169N]] | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "The second mutation was PSEN2 His169Asn mutation, which was previously reported in five EOAD patients from Korea and China, with a relatively high frequency in the East Asian population." |
| [[APP p.V551M]] | biolink:affects | Amyloid beta (CHEBI:64645; MESH:D016229) |  | "The APP Val551Met mutation in the E2 domain may influence APP homodimerization through changes in intramolecular interactions between adjacent amino acids, altering Aβ production." |
| APP Swedish double mutation (variant) | biolink:affects | Amyloid beta (CHEBI:64645; MESH:D016229) | direction=increased | "In a previous report, a Swedish double mutation located adjacent to the β-secretase cleavage site of APP has been found to increase the production and secretion of Aβ." |
| [[APP p.V551M]] | biolink:associated_with | [[PSEN2 p.H169N]] |  | "Notably, the co-existence of APP Val551Met and PSEN2 His169Asn may induce a synergistic effect by both mutations." |
| [[APP p.V551M]] | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "In this study, a Korean patient with EOAD presented with a novel APP Val551Met mutation and a sixth PSEN2 His169Asn mutation in East Asia." |
| [[PSEN2 p.H169N]] | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "In this study, a Korean patient with EOAD presented with a novel APP Val551Met mutation and a sixth PSEN2 His169Asn mutation in East Asia." |
| APP Arg486Trp (variant) | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "Among the mutations in the APP E2 domain, the Arg486Trp mutation was described in one patient with familial EOAD from a British cohort." |
| APP Lys496Gln (variant) | biolink:associated_with | Early-onset Alzheimer disease (MESH:D000544) |  | "In other de novo cases, Lys496Gln has been reported in EOAD while Tyr538His and Val562Ile have been reported in late-onset AD." |
| APP Tyr538His (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "In other de novo cases, Lys496Gln has been reported in EOAD while Tyr538His and Val562Ile have been reported in late-onset AD." |
| APP Val562Ile (variant) | biolink:associated_with | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "In other de novo cases, Lys496Gln has been reported in EOAD while Tyr538His and Val562Ile have been reported in late-onset AD." |
| APP Tyr538His (variant) | biolink:affects | Amyloid beta 40 (CHEBI:64646; MESH:C078592) | direction=decreased | "Notably, cells with Tyr538His and Val562Ile mutations near Val551Met have shown decreased Aβ40 production." |
| APP Val562Ile (variant) | biolink:affects | Amyloid beta 40 (CHEBI:64646; MESH:C078592) | direction=decreased | "Notably, cells with Tyr538His and Val562Ile mutations near Val551Met have shown decreased Aβ40 production." |
| methionine (CHEBI:16643; MESH:D008715) | biolink:physically_interacts_with | leucine (CHEBI:25017; MESH:D007930) |  | "Contrastingly, in the intra-interaction among amino acids, Met551 exhibited a hydrophobic interaction with Leu480 of the other α-helix chain rather than Ala553." |
| methionine (CHEBI:16643; MESH:D008715) | NOT biolink:physically_interacts_with | alanine (CHEBI:16449; MESH:D000409) |  | "Contrastingly, in the intra-interaction among amino acids, Met551 exhibited a hydrophobic interaction with Leu480 of the other α-helix chain rather than Ala553." |
| [[APP]] | biolink:affects | Amyloid beta (CHEBI:64645; MESH:D016229) | direction=increased | "For example, Aβ production is increased 6–8 times upon the formation of a stable APP dimer through the expression of a cysteine mutation in the ectodomain juxtamembrane region." |
| [[APP p.V551M]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Although one APP Val551Met may have minor effects, its combination with PSEN2 His169Asn could facilitate the onset of AD." |
| [[PSEN2 p.H169N]] | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Although all cases strongly demonstrate the high-penetrance gene mutations of the AD pathology, the contribution of the mutation to the AD pathophysiology could be relatively modest given the reported age of onset in these patients compared with that in patients with PSEN1 mutations." |
| [[PSEN2 p.H169N]] | biolink:has_phenotype | Memory impairment (HP:0002354) |  | "The clinical manifestation of the previous cases was presented to an early onset age of less than 65 years, with a progressive memory impairment similar to our patient." |
| [[PSEN2 p.H169N]] | biolink:contributes_to | Early-onset Alzheimer disease (MESH:D000544) |  | "The clinical manifestation of the previous cases was presented to an early onset age of less than 65 years, with a progressive memory impairment similar to our patient." |
| [[PSEN2 p.H169N]] | biolink:associated_with | histidine (CHEBI:15971; MESH:D006639) |  | "PSEN2 His169Asn was predicted to be structurally pathogenic by causing a significant twist in the helix, resulting from the substitution of histidine for asparagine." |
| [[PSEN2 p.H169N]] | biolink:associated_with | asparagine (CHEBI:17196; MESH:D001216) |  | "PSEN2 His169Asn was predicted to be structurally pathogenic by causing a significant twist in the helix, resulting from the substitution of histidine for asparagine." |
| PSEN2 M174I (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PSEN2 His169Asn is located in TMIII, which is a highly conserved domain in proteins that includes other AD-related variants, including Met174Ile, Met174Val, Ser175Cys, Ser175Phe, and Phe183Ser." |
| PSEN2 M174V (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PSEN2 His169Asn is located in TMIII, which is a highly conserved domain in proteins that includes other AD-related variants, including Met174Ile, Met174Val, Ser175Cys, Ser175Phe, and Phe183Ser." |
| PSEN2 S175C (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PSEN2 His169Asn is located in TMIII, which is a highly conserved domain in proteins that includes other AD-related variants, including Met174Ile, Met174Val, Ser175Cys, Ser175Phe, and Phe183Ser." |
| PSEN2 S175F (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PSEN2 His169Asn is located in TMIII, which is a highly conserved domain in proteins that includes other AD-related variants, including Met174Ile, Met174Val, Ser175Cys, Ser175Phe, and Phe183Ser." |
| PSEN2 F183S (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "PSEN2 His169Asn is located in TMIII, which is a highly conserved domain in proteins that includes other AD-related variants, including Met174Ile, Met174Val, Ser175Cys, Ser175Phe, and Phe183Ser." |
