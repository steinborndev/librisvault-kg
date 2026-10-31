# PMC corpus - 50 open-access papers on Alzheimer disease

Selected 2026-10-06 by `scripts/kg/select-usecase-corpus.mjs` (docs/kg/SPEC.md D17 as amended
2026-10-06, D23), seed **20261006**. It replaces the BioRED-based corpus of 2026-09-27, which is kept in
`corpus-superseded-2026-09-27.md` because earlier runs (X3-P1, X6-P1) used its papers.

**Rule.** Candidates are the research articles of 2019 to 2025 with "Alzheimer" in the title that
Europe PMC lists as open access under CC0, CC BY or CC BY-SA and in PMC, whose title or abstract
names at least two of the targets Pharos associates with Alzheimer disease (MONDO:0004975, 482 targets,
fetched 2026-10-06), as whole, case-sensitive tokens, leaving out symbols of two characters or
fewer and symbols that are ordinary words or abbreviations in this literature. They are ordered by a
seeded shuffle, with articles on subtypes (subtype, subgroup, heterogeneity, early or late onset,
stratification, cluster) taking every other place. The corpus is the first 50 of that order that the
BioC API for PMC delivered and whose license, as the BioC API states it, is one of the three.
Rerunning `draw` and `finalize` with the same seed and the same inputs gives the same list.

**Coverage.** 669 candidates of 10730 articles found (search 2026-10-06). Licenses in the corpus: CC BY 50. Articles on subtypes: 25. Distinct targets named: 42.

**Skipped on the way:** none.

| # | PMCID | PMID | License | Year | Subtype | Targets named | Title |
|---|---|---|---|---|---|---|---|
| 1 | PMC7010721 | 32116649 | CC BY | 2020 | yes | APOE, CD2AP, FERMT2, PTK2B | Genetic Association of FERMT2, HLA-DRB1, CD2AP, and PTK2B Polymorphisms With Alzheimer's Disease Risk in the Southern Chinese Population. |
| 2 | PMC6776503 | 31582723 | CC BY | 2019 |  | APOE, TOMM40 | Genetic risk for Alzheimer's dementia predicts motor deficits through multi-omic systems in older adults. |
| 3 | PMC6742761 | 31515517 | CC BY | 2019 | yes | APP, SORL1 | A novel kit for early diagnosis of Alzheimer's disease using a fluorescent nanoparticle imaging. |
| 4 | PMC9406471 | 36010661 | CC BY | 2022 |  | ADAM10, APP | 2,4-Diacetylphloroglucinol Reduces Beta-Amyloid Production and Secretion by Regulating ADAM10 and Intracellular Trafficking in Cellular and Animal Models of Alzheimer's Disease. |
| 5 | PMC8535278 | 34681041 | CC BY | 2021 | yes | APOC1, APOE, CD33, CLU, SORL1, TOMM40 | Association and Gene-Gene Interactions Study of Late-Onset Alzheimer's Disease in the Russian Population. |
| 6 | PMC8226536 | 34204109 | CC BY | 2021 |  | APOE, TOMM40 | TOMM40 RNA Transcription in Alzheimer's Disease Brain and Its Implication in Mitochondrial Dysfunction. |
| 7 | PMC10253571 | 37298634 | CC BY | 2023 | yes | APP, BIN1 | The Cleavage-Specific Tau 12A12mAb Exerts an Anti-Amyloidogenic Action by Modulating the Endocytic and Bioenergetic Pathways in Alzheimer's Disease Mouse Model. |
| 8 | PMC10193014 | 37044212 | CC BY | 2023 |  | TREM2, YY1 | Regulation of TREM2 expression by transcription factor YY1 and its protective effect against Alzheimer's disease. |
| 9 | PMC7188838 | 32345996 | CC BY | 2020 | yes | ABCA7, APOE, APP, BIN1, CD2AP, CD33, CLU, CR1, EPHA1, MS4A6A, PICALM, PSEN1, PSEN2 | Investigating APOE, APP-Aβ metabolism genes and Alzheimer's disease GWAS hits in brain small vessel ischemic disease. |
| 10 | PMC11753789 | 39612244 | CC BY | 2024 |  | APOE, PSEN1 | Microglial APOE3 Christchurch protects neurons from Tau pathology in a human iPSC-based model of Alzheimer's disease. |
| 11 | PMC8184987 | 34099642 | CC BY | 2021 | yes | APOE, APP, PLCG2 | Common variants in Alzheimer's disease and risk stratification by polygenic risk scores. |
| 12 | PMC8538213 | 34683087 | CC BY | 2021 |  | CELF2, IL6 | Systematic Search for Novel Circulating Biomarkers Associated with Extracellular Vesicles in Alzheimer's Disease: Combining Literature Screening and Database Mining Approaches. |
| 13 | PMC12667055 | 41327266 | CC BY | 2025 | yes | APOE, SORL1 | Domain mapping of disease mutations reveals pathogenic SORL1 variants in Alzheimer's disease. |
| 14 | PMC12426409 | 40949132 | CC BY | 2025 |  | APP, BAX | Systems pharmacology identifies ajugol-mediated NF-κB/caspase-3 inhibition and isoacteoside-driven p62/mTOR-mediated autophagy as key mechanisms of Rehmanniae Radix and its processed form in Alzheimer's treatment. |
| 15 | PMC11575974 | 39560568 | CC BY | 2024 | yes | CACNA2D3, INPP5D | Integrative analysis of single-nucleus RNA sequencing and Mendelian randomization to explore novel risk genes for Alzheimer's disease. |
| 16 | PMC8369699 | 34404470 | CC BY | 2021 |  | APOE, TREM2 | Probability of Alzheimer's disease based on common and rare genetic variants. |
| 17 | PMC8340485 | 34353353 | CC BY | 2021 | yes | IL6, TREM2 | Perivascular spaces are associated with tau pathophysiology and synaptic dysfunction in early Alzheimer's continuum. |
| 18 | PMC8830081 | 35139885 | CC BY | 2022 |  | APOE, INPP5D | Blood and brain transcriptome analysis reveals APOE genotype-mediated and immune-related pathways involved in Alzheimer disease. |
| 19 | PMC10140908 | 37108607 | CC BY | 2023 | yes | APP, PSEN1, PSEN2 | Double Mutations in a Patient with Early-Onset Alzheimer's Disease in Korea: An APP Val551Met and a PSEN2 His169Asn. |
| 20 | PMC7204847 | 32425755 | CC BY | 2020 |  | APP, BACE1 | Opposite Roles of δ- and μ-Opioid Receptors in BACE1 Regulation and Alzheimer's Injury. |
| 21 | PMC9110789 | 35592698 | CC BY | 2022 | yes | APP, TNF | Exercise Modifies the Transcriptional Regulatory Features of Monocytes in Alzheimer's Patients: A Multi-Omics Integration Analysis Based on Single Cell Technology. |
| 22 | PMC12356643 | 40834163 | CC BY | 2025 |  | ACE, APOE | Associations between selected genetic variants and lipid profile variability in response to statins in Alzheimer's disease: a prospective observational study. |
| 23 | PMC9453434 | 36092303 | CC BY | 2022 | yes | APOE, CD33, SORL1 | In Alzheimer-prone brain regions, metabolism and risk-gene expression are strongly correlated. |
| 24 | PMC11401704 | 39281976 | CC BY | 2022 |  | APP, SYP | Inhibition of Glycogen Synthase Kinase and the Neuroprotective Function of Conjugated ZnO-Osthol Nanoparticles in Alzheimer's Disease. |
| 25 | PMC12106835 | 40419479 | CC BY | 2025 | yes | APOE, APP | The APOE isoforms differentially shape the transcriptomic and epigenomic landscapes of human microglia xenografted into a mouse model of Alzheimer's disease. |
| 26 | PMC12786224 | 41515895 | CC BY | 2025 |  | APOE, BCHE | Plasma Protein Panel for Assessing the Risk of Alzheimer's Disease by MRM-MS Analysis: The Study of Two Independent Clinical Cohorts. |
| 27 | PMC6429449 | 30871086 | CC BY | 2019 | yes | APOE, CYP2D6 | Sirtuins in Alzheimer's Disease: SIRT2-Related GenoPhenotypes and Implications for PharmacoEpiGenetics. |
| 28 | PMC7666133 | 33188256 | CC BY | 2020 |  | APP, PSEN1, PSEN2 | Mutational analysis in familial Alzheimer's disease of Han Chinese in Taiwan with a predominant mutation PSEN1 p.Met146Ile. |
| 29 | PMC7574558 | 33076948 | CC BY | 2020 | yes | APP, BACE1, PSEN1 | Modeling the β-secretase cleavage site and humanizing amyloid-beta precursor protein in rat and mouse to study Alzheimer's disease. |
| 30 | PMC12351871 | 40814010 | CC BY | 2025 |  | APP, BACE1 | Targeted delivery of BACE1 siRNA for synergistic treatment of Alzheimer's disease. |
| 31 | PMC6658518 | 31346172 | CC BY | 2019 | yes | APOC1, APOE | Non-coding variability at the APOE locus contributes to the Alzheimer's risk. |
| 32 | PMC9016079 | 35436980 | CC BY | 2022 |  | APOE, BIN1, CASS4, CD33, CLU, CR1, MS4A6A | Allele-specific analysis reveals exon- and cell-type-specific regulatory effects of Alzheimer's disease-associated genetic variants. |
| 33 | PMC10000752 | 36899831 | CC BY | 2023 | yes | APP, TNF | Intrahippocampal Inoculation of Aβ1-42 Peptide in Rat as a Model of Alzheimer's Disease Identified MicroRNA-146a-5p as Blood Marker with Anti-Inflammatory Function in Astrocyte Cells. |
| 34 | PMC10347067 | 37447330 | CC BY | 2023 |  | APOE, DHCR24 | Activation of Liver X Receptors and Peroxisome Proliferator-Activated Receptors by Lipid Extracts of Brown Seaweeds: A Potential Application in Alzheimer's Disease? |
| 35 | PMC6450321 | 30924900 | CC BY | 2019 | yes | NOTCH3, TREM2 | Association of Rare Coding Mutations With Alzheimer Disease and Other Dementias Among Adults of European Ancestry. |
| 36 | PMC9037259 | 35366241 | CC BY | 2022 |  | APP, TREM2 | Hypoxic pretreatment of adipose-derived stem cell exosomes improved cognition by delivery of circ-Epc1 and shifting microglial M1/M2 polarization in an Alzheimer's disease mice model. |
| 37 | PMC9344928 | 35928571 | CC BY | 2022 | yes | APP, IQCK | Novel Alzheimer risk factor IQ motif containing protein K is abundantly expressed in the brain and is markedly increased in patients with Alzheimer's disease. |
| 38 | PMC6389675 | 30837843 | CC BY | 2019 |  | APP, CRH | Mast Cells in Stress, Pain, Blood-Brain Barrier, Neuroinflammation and Alzheimer's Disease. |
| 39 | PMC9547780 | 36066633 | CC BY | 2022 | yes | APOE, BIN1, CR1 | Genome-wide meta-analysis for Alzheimer's disease cerebrospinal fluid biomarkers. |
| 40 | PMC8501163 | 33837271 | CC BY | 2021 |  | APOE, APP | APOE2 mitigates disease-related phenotypes in an isogenic hiPSC-based model of Alzheimer's disease. |
| 41 | PMC8277916 | 34276354 | CC BY | 2021 | yes | ABCA7, ACE, APOE, APP, BIN1, CD33, CLU, PICALM, TREM2 | Computational Drug Repurposing for Alzheimer's Disease Using Risk Genes From GWAS and Single-Cell RNA Sequencing Studies. |
| 42 | PMC10543321 | 37775827 | CC BY | 2023 |  | MDH1, TREM2 | A microglial activity state biomarker panel differentiates FTD-granulin and Alzheimer's disease patients from controls. |
| 43 | PMC7180223 | 32362813 | CC BY | 2020 | yes | ABCA7, BIN1, CD2AP, PICALM, SORL1 | Intracellular Trafficking Mechanisms of Synaptic Dysfunction in Alzheimer's Disease. |
| 44 | PMC6495598 | 31043179 | CC BY | 2019 |  | APP, TNF | Neuroinflammation and amyloid-beta 40 are associated with reduced serotonin transporter (SERT) activity in a transgenic model of familial Alzheimer's disease. |
| 45 | PMC7782705 | 33398016 | CC BY | 2021 | yes | APP, BIN1 | Differential transcript usage unravels gene expression alterations in Alzheimer's disease human brains. |
| 46 | PMC12491701 | 40399225 | CC BY | 2025 |  | APP, BACE1 | Discovery of an APP-selective BACE1 inhibitor for Alzheimer's disease. |
| 47 | PMC6904249 | 31853523 | CC BY | 2019 | yes | APOE, CLU | Clusterin accumulates in synapses in Alzheimer's disease and is increased in apolipoprotein E4 carriers. |
| 48 | PMC12356828 | 40817596 | CC BY | 2025 |  | APOE, APP, ST18 | Integrative snRNA-seq, molecular docking and dynamics simulations identifies Lasmiditan as drug candidate for Alzheimer's disease. |
| 49 | PMC6471359 | 30917570 | CC BY | 2019 | yes | APP, LRRK2, MAPT, PSEN1, TREM2 | Analysis of 50 Neurodegenerative Genes in Clinically Diagnosed Early-Onset Alzheimer's Disease. |
| 50 | PMC12785688 | 41516176 | CC BY | 2025 |  | APOC1, APOE, TOMM40 | Interplay Between 3D Chromatin Architecture and Gene Regulation at the APOE Locus Contributes to Alzheimer's Disease Risk. |
