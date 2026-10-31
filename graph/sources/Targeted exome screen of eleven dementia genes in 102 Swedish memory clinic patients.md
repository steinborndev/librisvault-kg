---
type: source
title: "Targeted exome screen of eleven dementia genes in 102 Swedish memory clinic patients"
paper_title: "Mutation analysis of disease causing genes in patients with early onset or familial forms of Alzheimer’s disease and frontotemporal dementia"
domain: neuroscience
status: developing
created: 2026-10-12
updated: 2026-10-12
content_updated: 2026-10-12
address: c-001406
pmid: "35120450"
pmcid: "PMC8817590"
doi: "10.1186/s12864-022-08343-9"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC8817590/"
sources: ["[[.raw/01M4P89VCKFAC8E67N481DT79A/normalized.md]]"]
tags: [familial-alzheimer, rare-variant-burden, dementia]
---

# Targeted exome screen of eleven dementia genes in 102 Swedish memory clinic patients

A BMC Genomics study from Uppsala that sequenced every coding exon of eleven dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP, FUS) in 102 memory-clinic patients with onset before 65 years and/or a first-degree relative with dementia. It found three clearly pathogenic mutations, a handful of variants of uncertain significance, a very high APOE ε4 frequency and an unexpectedly common TREM2 risk allele.

## Cohort and methods

- 102 patients seen 2006 to 2019: 77 [[Alzheimer disease]] (90.9% with known heredity, mean onset 60.8 years, range 34 to 76), 7 behavioral variant and 4 other [[Frontotemporal dementia]], 5 semantic variant primary progressive aphasia, 2 other dementias and 7 [[Mild cognitive impairment]] (mostly with Alzheimer heredity). Diagnoses used established criteria and, mostly, cerebrospinal fluid Alzheimer biomarkers.
- Exons plus at least 25 flanking nucleotides were enriched with an Agilent SureSelect custom design (Illumina MiSeq) or Life Technologies AmpliSeq (IonTorrent); average target coverage was over 97%. Reads were aligned to hg19 and annotated with Ensembl Variant Effect Predictor, dbSNP, gnomAD and the Alzforum mutation database. See [[Targeted gene panel sequencing]].
- The authors note the design cannot see structural variants, repeats such as the C9ORF72 hexanucleotide expansion, or genes outside the panel (they name CR1, SORL1, BACE1, ABCA7 as susceptibility genes not examined).

## Findings

- Pathogenic: [[PSEN1 p.P264L]] in two siblings with onset at 50 and 42 years (a family with onset at 40 to 50 years); [[PSEN1 p.M146V]] in a man with onset at 34 years and no reported heredity, later with seizures; and the [[APP p.690_695del]] deletion (Uppsala mutation) in two siblings and a cousin, with onset at 40 to 50 years in earlier generations, absent in more than 500 other Swedish samples.
- Uncertain significance: [[FUS p.S57del]] in an Alzheimer patient (previously reported in sporadic amyotrophic lateral sclerosis), two further FUS deletions ([[FUS p.229_231del]] with [[PSEN2 p.A252T]] in one patient with behavioral variant FTD, [[FUS p.166_167del]] in one with semantic variant primary progressive aphasia), the new [[PSEN2 p.I144L]], [[GRN p.A324V]], [[MAPT p.V224G]], [[MAPT p.A239T]] and [[APOE p.R269G]] (earlier linked to familial hypercholesterolemia). No likely pathogenic variant was found in TARDBP, CHMP2B or VCP.
- APOE ε4 allele frequency was 54% in all 102 patients (57% in the 77 Alzheimer cases; 32 homozygous, 45 ε3/ε4), against 10 to 15% in the general Caucasian population and 25 to 35% usually reported in Alzheimer disease.
- [[TREM2 p.R62H]] was carried by eight Alzheimer and two MCI patients, an allele frequency of 4.9% against about 1% in European and American databases; both Uppsala-mutation siblings carried it.

## Assessment

- Pathogenicity calls for the uncertain variants rest on in silico scores (SIFT, PolyPhen-2), rarity and earlier reports, without segregation or functional data; the authors themselves say further analysis is needed. Most carriers are single cases.
- The 4.9% TREM2 R62H frequency comes from a selected, small clinic cohort (the 102 patients, 10 carriers) compared with population databases, not with matched controls, and the paper cites conflicting association results for this allele.
- Cohort selection for early onset or heredity makes the 54% APOE ε4 figure a statement about this referral group; no control group was sequenced.
- The text gives no per-variant details beyond what is in the clinical table, and the Uppsala-mutation functional evidence is cited from earlier work rather than shown here.

## Open Questions

- Does TREM2 p.R62H occur at a higher frequency in Swedish early-onset or familial Alzheimer patients than in matched Swedish controls (here compared only with population database frequencies)?
- Do FUS p.S57del, FUS p.229_231del and FUS p.166_167del segregate with dementia in the carriers' families (family DNA was not available for most relatives)?
- Does the co-occurrence of TREM2 p.R62H with the Uppsala APP deletion modify age at onset or severity in carriers?
- Which of the screened families carry pathogenic changes in genes outside the eleven-gene panel, such as SORL1 or ABCA7, or structural variants and C9ORF72 repeat expansions?

## Why This Source Matters

It is a worked example of a small clinic-based gene screen across Alzheimer disease and frontotemporal dementia: about 3% of patients had a clearly pathogenic APP or PSEN1 mutation, and further carriers had variants that cannot be classified. It documents the Uppsala deletion in a clinical series and reports a high TREM2 R62H allele frequency that merits replication.

## Connections

- Genes: [[PSEN1]], [[PSEN2]], [[APP]], [[MAPT]], [[GRN]], [[APOE]], [[TREM2]], [[FUS]]
- Variants: [[PSEN1 p.P264L]], [[PSEN1 p.M146V]], [[APP p.690_695del]], [[PSEN2 p.I144L]], [[PSEN2 p.A252T]], [[FUS p.S57del]], [[FUS p.229_231del]], [[FUS p.166_167del]], [[GRN p.A324V]], [[MAPT p.V224G]], [[MAPT p.A239T]], [[APOE p.R269G]], [[TREM2 p.R62H]]
- Diseases: [[Early-onset Alzheimer disease]], [[Familial Alzheimer disease]], [[Frontotemporal dementia]], [[Mild cognitive impairment]]
- Method: [[Targeted gene panel sequencing]]
- Comparable clinic or population gene screens: [[Fifty-gene neurodegeneration panel in eight Thai early-onset Alzheimer patients]], [[Familial Alzheimer disease mutations in Han Chinese in Taiwan]], [[Double APP and PSEN2 mutations in a Korean patient with early-onset Alzheimer disease]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[MAPT]] | biolink:causes | [[Frontotemporal dementia]] (MESH:D057180) |  | "Mutations in the tau gene (MAPT) lead to frontotemporal dementia (FTD), whereas mutations in the genes for the amyloid-β precursor protein (APP) and the presenilins (PSEN1, PSEN2) cause early-onset, dominantly inherited forms of Alzheimer’s disease (AD)." |
| [[MAPT]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[MAPT]] | biolink:associated_with | neurofibrillary tangles (HP:0002185) |  | "Alzheimer’s disease is neuropathologically characterized by the formation and extracellular deposition of insoluble plaques, consisting of the 38–43 amino acid long peptide amyloid-β (Aβ) and intracellular neurofibrillary tangles of the tau protein, as well as a substantial neuronal loss." |
| [[BACE1]] | biolink:affects | [[APP]] |  | "Whereas the Swedish mutation results in an increased cleavage by β-secretase and thereby elevated levels of all forms of Aβ, the Arctic mutation leads to a conformational change of Aβ and increased formation of toxic Aβ protofibrils." |
| [[APP]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the tau gene (MAPT) lead to frontotemporal dementia (FTD), whereas mutations in the genes for the amyloid-β precursor protein (APP) and the presenilins (PSEN1, PSEN2) cause early-onset, dominantly inherited forms of Alzheimer’s disease (AD)." |
| [[APP]] | biolink:causes | early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "Mutations in the tau gene (MAPT) lead to frontotemporal dementia (FTD), whereas mutations in the genes for the amyloid-β precursor protein (APP) and the presenilins (PSEN1, PSEN2) cause early-onset, dominantly inherited forms of Alzheimer’s disease (AD)." |
| [[APP]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[PSEN1]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the tau gene (MAPT) lead to frontotemporal dementia (FTD), whereas mutations in the genes for the amyloid-β precursor protein (APP) and the presenilins (PSEN1, PSEN2) cause early-onset, dominantly inherited forms of Alzheimer’s disease (AD)." |
| [[PSEN1]] | biolink:causes | early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "Mutations in the tau gene (MAPT) lead to frontotemporal dementia (FTD), whereas mutations in the genes for the amyloid-β precursor protein (APP) and the presenilins (PSEN1, PSEN2) cause early-onset, dominantly inherited forms of Alzheimer’s disease (AD)." |
| [[PSEN1]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[PSEN1]] | biolink:affects | amyloid-β 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Moreover, mutations in PSEN1 and PSEN2 have been shown to increase the generation of the longer and more aggregation prone form of Aβ (Aβ42)." |
| [[PSEN2]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Mutations in the tau gene (MAPT) lead to frontotemporal dementia (FTD), whereas mutations in the genes for the amyloid-β precursor protein (APP) and the presenilins (PSEN1, PSEN2) cause early-onset, dominantly inherited forms of Alzheimer’s disease (AD)." |
| [[PSEN2]] | biolink:causes | early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "Mutations in the tau gene (MAPT) lead to frontotemporal dementia (FTD), whereas mutations in the genes for the amyloid-β precursor protein (APP) and the presenilins (PSEN1, PSEN2) cause early-onset, dominantly inherited forms of Alzheimer’s disease (AD)." |
| [[PSEN2]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[PSEN2]] | biolink:affects | amyloid-β 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Moreover, mutations in PSEN1 and PSEN2 have been shown to increase the generation of the longer and more aggregation prone form of Aβ (Aβ42)." |
| [[APOE]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[GRN]] | biolink:causes | [[Frontotemporal dementia]] (MESH:D057180) |  | "Most notably, the understanding of frontotemporal dementia has been further advanced by the identification of disease causing mutations in the genes for TAR DNA-binding protein-43 (TARDBP), progranulin (GRN) and C9orf72-SMCR8 complex subunit (C9ORF72)." |
| [[GRN]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[TARDBP]] | biolink:causes | [[Frontotemporal dementia]] (MESH:D057180) |  | "Most notably, the understanding of frontotemporal dementia has been further advanced by the identification of disease causing mutations in the genes for TAR DNA-binding protein-43 (TARDBP), progranulin (GRN) and C9orf72-SMCR8 complex subunit (C9ORF72)." |
| [[TARDBP]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| CHMP2B (HGNC:24537) | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[TREM2]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Moreover, discoveries of rare variants in the triggering receptor expressed on myeloid cells 2 (TREM2) gene have highlighted the involvement of immunological and inflammatory pathways in AD pathogenesis." |
| [[TREM2]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| VCP (HGNC:12666) | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| [[FUS]] | biolink:associated_with | dementia (MONDO:0001627; MESH:D003704) |  | "Using targeted exome sequencing we have screened all coding exons in eleven known dementia genes (PSEN1, PSEN2, APP, MAPT, APOE, GRN, TARDBP, CHMP2B, TREM2, VCP and FUS) in 102 patients with AD, FTD, other dementia diagnoses or mild cognitive impairment." |
| C9ORF72 (HGNC:28337) | biolink:causes | [[Frontotemporal dementia]] (MESH:D057180) |  | "Most notably, the understanding of frontotemporal dementia has been further advanced by the identification of disease causing mutations in the genes for TAR DNA-binding protein-43 (TARDBP), progranulin (GRN) and C9orf72-SMCR8 complex subunit (C9ORF72)." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "According to the amyloid cascade hypothesis, AD is initiated by increased levels or a changed conformation of Aβ which can promote the formation of toxic oligomers and protofibrils before the formation of insoluble plaques." |
| [[PSEN1 p.P264L]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "We found three AD patients with two previously identified pathogenic mutations in PSEN1 (Pro264Leu and Met146Val)." |
| [[PSEN1 p.M146V]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "We found three AD patients with two previously identified pathogenic mutations in PSEN1 (Pro264Leu and Met146Val)." |
| [[APP p.690_695del]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "In this screen, we also identified the recently reported APP mutation in two siblings with AD." |
| APP Swedish mutation (variant) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Functional analyses of these mutations have significantly increased our understanding of the disease pathogenesis." |
| APP Arctic mutation (variant) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Functional analyses of these mutations have significantly increased our understanding of the disease pathogenesis." |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "Finally, APOE ε4 was prevalent in this patient group with an allele frequency of 54%." |
| [[Amyloid-beta]] (MESH:D016229) | biolink:associated_with | amyloid plaques (HP:0100256; MESH:D058225) |  | "Alzheimer’s disease is neuropathologically characterized by the formation and extracellular deposition of insoluble plaques, consisting of the 38–43 amino acid long peptide amyloid-β (Aβ) and intracellular neurofibrillary tangles of the tau protein, as well as a substantial neuronal loss." |
| APP Swedish mutation (variant) | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "Whereas the Swedish mutation results in an increased cleavage by β-secretase and thereby elevated levels of all forms of Aβ, the Arctic mutation leads to a conformational change of Aβ and increased formation of toxic Aβ protofibrils." |
| APP Arctic mutation (variant) | biolink:affects | [[Amyloid-beta]] (MESH:D016229) |  | "Whereas the Swedish mutation results in an increased cleavage by β-secretase and thereby elevated levels of all forms of Aβ, the Arctic mutation leads to a conformational change of Aβ and increased formation of toxic Aβ protofibrils." |
| APP Swedish mutation (variant) | biolink:affects | amyloid-β 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Whereas the Swedish mutation results in an increased cleavage by β-secretase and thereby elevated levels of all forms of Aβ" |
| [[APOE]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "When only including the 77 AD cases in the analysis, a slightly higher APOE ε4 allele frequency was observed (57%) (Table 2)." |
| [[APOE]] | biolink:causes | autosomal dominant hypercholesterolemia (MESH:D006937) |  | "This APOE mutation had previously been reported as a likely cause of autosomal dominant hypercholesterolemia." |
| [[APP p.690_695del]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "Furthermore, we extensively studied clinical and pathological features of this deletion and the data strongly suggest that the Uppsala mutation is the cause of AD in this family." |
| FUS S57del (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In one individual with AD and a known family history of dementia we found a Ser57 deletion (rs777545405) in FUS (Fig. 1)." |
| [[PSEN2 p.I144L]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In addition, PSEN2 I144L (rs764718172), which has not been reported in any previous studies, was found in an AD patient with a family history of disease (Fig. 1)." |
| [[APOE p.R269G]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "In one patient with early onset AD we identified the R269G (rs267606661) mutation." |
| [[APP p.690_695del]] | biolink:causes | early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "This in frame deletion, named the Uppsala mutation, was found in two siblings and a cousin suffering from an aggressive early onset form of AD." |
| [[APOE p.R269G]] | biolink:associated_with | early-onset Alzheimer disease (MONDO:0015140; MESH:D000544) |  | "In one patient with early onset AD we identified the R269G (rs267606661) mutation." |
| FUS S57del (variant) | biolink:associated_with | amyotrophic lateral sclerosis (MONDO:0004976; MESH:D000690) |  | "This deletion had been previously reported as likely pathogenic in a patient with sporadic amyotrophic lateral sclerosis (ALS)." |
| [[FUS p.229_231del]] | biolink:associated_with | behavioral variant frontotemporal dementia (MONDO:0017160) |  | "In PSEN2, the A252T mutation (rs138836272) was identified in a patient with the behavioral variant of FTD (bvFTD), also carrying the Δ229-231 deletion in FUS (Fig. 1 and Table 1)." |
| [[PSEN2 p.A252T]] | biolink:associated_with | behavioral variant frontotemporal dementia (MONDO:0017160) |  | "In PSEN2, the A252T mutation (rs138836272) was identified in a patient with the behavioral variant of FTD (bvFTD), also carrying the Δ229-231 deletion in FUS (Fig. 1 and Table 1)." |
| [[APOE p.R269G]] | biolink:causes | autosomal dominant hypercholesterolemia (MESH:D006937) |  | "This APOE mutation had previously been reported as a likely cause of autosomal dominant hypercholesterolemia." |
| [[PSEN1 p.P264L]] | biolink:has_phenotype | [[Cognitive impairment]] (MESH:D060825) |  | "The siblings suffered from global cognitive impairment and early personality changes and both displayed a clear hypometabolism in posterior temporo-parietal cortex on FDG-PET." |
| [[PSEN1 p.P264L]] | biolink:has_phenotype | personality changes (HP:0000751) |  | "The siblings suffered from global cognitive impairment and early personality changes and both displayed a clear hypometabolism in posterior temporo-parietal cortex on FDG-PET." |
| [[PSEN1 p.M146V]] | biolink:has_phenotype | [[Memory impairment]] |  | "The other PSEN1 mutation, M146V (rs63750306), was identified in an AD patient who had presented with slight short term memory dysfunction and spatial disorientation already at about 30 years of age." |
| FUS S57del (variant) | biolink:has_phenotype | [[Memory impairment]] |  | "Our patient had experienced memory problems before the age of 60 years, but no typical ALS symptoms had been reported." |
| [[PSEN1 p.M146V]] | biolink:has_phenotype | spatial disorientation (HP:0001289; MESH:D003221) |  | "The other PSEN1 mutation, M146V (rs63750306), was identified in an AD patient who had presented with slight short term memory dysfunction and spatial disorientation already at about 30 years of age." |
| [[PSEN1 p.M146V]] | biolink:has_phenotype | [[Seizure]] (MESH:D012640) |  | "At later disease stages the patient suffered from myoclonic epileptic seizures and gait difficulties." |
| [[PSEN1 p.M146V]] | biolink:has_phenotype | gait difficulties (HP:0001288) |  | "At later disease stages the patient suffered from myoclonic epileptic seizures and gait difficulties." |
| [[APP p.690_695del]] | biolink:has_phenotype | autosomal dominant inheritance (HP:0000006) |  | "A typical pattern of autosomal dominant inheritance and age at disease onset of 40–50 years had been reported in earlier generations of the family." |
| [[PSEN1 p.P264L]] | biolink:has_phenotype | family history (HP:0032316) |  | "In the same family, the father and another sibling also suffered from the disease, although DNA samples were not available from them (Fig. 1)." |
| [[PSEN1 p.M146V]] | NOT biolink:has_phenotype | family history (HP:0032316) |  | "Interestingly, no heredity had been reported in this family." |
| FUS S57del (variant) | biolink:has_phenotype | family history (HP:0032316) |  | "In one individual with AD and a known family history of dementia we found a Ser57 deletion (rs777545405) in FUS (Fig. 1)." |
| [[PSEN2 p.I144L]] | biolink:has_phenotype | family history (HP:0032316) |  | "In addition, PSEN2 I144L (rs764718172), which has not been reported in any previous studies, was found in an AD patient with a family history of disease (Fig. 1)." |
| [[PSEN2 p.A252T]] | biolink:associated_with | [[FUS p.229_231del]] |  | "In PSEN2, the A252T mutation (rs138836272) was identified in a patient with the behavioral variant of FTD (bvFTD), also carrying the Δ229-231 deletion in FUS (Fig. 1 and Table 1)." |
| [[TREM2]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "We also included TREM2 in our analyses, since several studies have recently reported that rare variants in this gene could confer an increased AD risk similar to APOE ε4." |
| [[TREM2 p.R62H]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, in another study of 85 133 subjects, a strongly significant association between AD and TREM2 R62H was found, although the allele frequency was low (1.4% in AD cases and 0.9% in controls)." |
| rs143332484 (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "However, in another study of 85 133 subjects, a strongly significant association between AD and TREM2 R62H was found, although the allele frequency was low (1.4% in AD cases and 0.9% in controls)." |
| [[APP p.690_695del]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "The recently reported deletion in APP, resulting in a six amino acid shorter version of the Aβ peptide, is to our knowledge the first dominantly inherited form of AD caused by a large deletion in Aβ [ ]." |
| APP single amino acid deletion in Aβ (variant) | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "This APP mutation was described to have a recessive mode of inheritance and seems to cause disease due to an increased oligomerization and higher resistance to proteolytic degradation of Aβ." |
| [[MAPT p.V224G]] | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "The MAPT V224G was reported in several studies and found in both AD patients and controls." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "The APOE ε4 allele is the strongest risk factor for late onset AD." |
| [[APOE]] | biolink:associated_with | Dementia (HP:0000726; MESH:D003704) |  | "Thus the high APOE ε4 frequency of over 50% in the patients included in our study, confirms that APOE is of importance also in familial dementia." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "The APOE ε4 allele is the strongest risk factor for late onset AD." |
| [[TREM2 p.R62H]] | biolink:associated_with | [[Cognitive impairment]] (MESH:D060825) |  | "We found that eight AD and two patients with mild cognitive impairment (MCI) were carriers of the TREM2 R62H allele (rs143332484), which gives an allele frequency of 4.9%." |
| rs143332484 (variant) | biolink:associated_with | [[Cognitive impairment]] (MESH:D060825) |  | "We found that eight AD and two patients with mild cognitive impairment (MCI) were carriers of the TREM2 R62H allele (rs143332484), which gives an allele frequency of 4.9%." |
| [[TREM2 p.R62H]] | biolink:associated_with | [[APP p.690_695del]] |  | "Interestingly, also the two AD patients with the Uppsala mutation were found to carry the TREM2 R62H allele." |
| rs143332484 (variant) | biolink:associated_with | [[APP p.690_695del]] |  | "Interestingly, also the two AD patients with the Uppsala mutation were found to carry the TREM2 R62H allele." |
| [[MAPT p.A239T]] | biolink:associated_with | [[Frontotemporal dementia]] (MESH:D057180) |  | "The MAPT A239T variant was described in an FTD patient carrying pathogenic deletion in GRN gene." |
| GRN deletion (variant) | biolink:associated_with | [[Frontotemporal dementia]] (MESH:D057180) |  | "The MAPT A239T variant was described in an FTD patient carrying pathogenic deletion in GRN gene." |
| [[PSEN1 p.P264L]] | biolink:has_phenotype | autosomal dominant inheritance (HP:0000006) |  | "Both of these mutations have been previously described as pathogenic, causing autosomal dominantly inherited disease forms." |
| [[PSEN1 p.P264L]] | biolink:causes | Dementia (HP:0000726; MESH:D003704) |  | "Despite the fact that all individuals with this mutation get dementia at an early age, there is an interindividual variation of symptoms." |
| [[PSEN1 p.P264L]] | biolink:has_phenotype | Spastic paraparesis (HP:0002313; MESH:D020336) |  | "In the study by Martikainen et al., one of the three patients carrying this mutation displayed spastic paraparesis, whereas the other two patients presented with parkinsonism." |
| [[PSEN1 p.P264L]] | biolink:has_phenotype | [[Parkinsonism]] (MESH:D020734) |  | "In the study by Martikainen et al., one of the three patients carrying this mutation displayed spastic paraparesis, whereas the other two patients presented with parkinsonism." |
| [[PSEN1 p.P264L]] | biolink:has_phenotype | Cotton wool plaques (HP:0500028) |  | "With respect to neuropathology, all three cases exhibited abundant cotton wool plaques in the brain at autopsy." |
| [[PSEN1 p.M146V]] | biolink:has_phenotype | autosomal dominant inheritance (HP:0000006) |  | "Both of these mutations have been previously described as pathogenic, causing autosomal dominantly inherited disease forms." |
| [[PSEN1 p.M146V]] | biolink:causes | Early onset Alzheimer disease (MESH:D000544) |  | "The PSEN1 M146V mutation usually causes early onset AD with an onset age at about 40 years." |
| [[PSEN1 p.M146V]] | biolink:has_phenotype | amyloid plaques (HP:0100256; MESH:D058225) |  | "Brain examination revealed considerably higher numbers of neuritic plaques and neurofibrillary tangles in all examined brain regions, as compared to sporadic AD patients." |
| [[PSEN1 p.M146V]] | biolink:has_phenotype | neurofibrillary tangles (HP:0002185) |  | "Brain examination revealed considerably higher numbers of neuritic plaques and neurofibrillary tangles in all examined brain regions, as compared to sporadic AD patients." |
| [[APP p.690_695del]] | biolink:has_phenotype | autosomal dominant inheritance (HP:0000006) |  | "The recently reported deletion in APP, resulting in a six amino acid shorter version of the Aβ peptide, is to our knowledge the first dominantly inherited form of AD caused by a large deletion in Aβ [ ]." |
| [[APOE]] | biolink:associated_with | Dementia (HP:0000726; MESH:D003704) |  | "Thus the high APOE ε4 frequency of over 50% in the patients included in our study, confirms that APOE is of importance also in familial dementia." |
| [[APP p.690_695del]] | biolink:contributes_to | amyloid plaques (HP:0100256; MESH:D058225) |  | "Furthermore, the Uppsala Aβ mutant adopts unique polymorphs that accelerate the formation of fibrils and their deposition into amyloid plaques." |
| [[APP]] | biolink:associated_with | [[Amyloid-beta]] (MESH:D016229) |  | "As recently described, the Uppsala APP mutation causes increased Aβ generation by altering α-secretase and β-secretase cleavages of APP." |
| [[BACE1]] | biolink:physically_interacts_with | [[APP]] |  | "As recently described, the Uppsala APP mutation causes increased Aβ generation by altering α-secretase and β-secretase cleavages of APP." |
| [[APP p.690_695del]] | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "As recently described, the Uppsala APP mutation causes increased Aβ generation by altering α-secretase and β-secretase cleavages of APP." |
| APP single amino acid deletion in Aβ (variant) | biolink:affects | [[Amyloid-beta]] (MESH:D016229) | direction=increased | "This APP mutation was described to have a recessive mode of inheritance and seems to cause disease due to an increased oligomerization and higher resistance to proteolytic degradation of Aβ." |
| [[MAPT p.A239T]] | biolink:associated_with | GRN deletion (variant) |  | "The MAPT A239T variant was described in an FTD patient carrying pathogenic deletion in GRN gene." |
| [[APOE]] | biolink:associated_with_increased_likelihood_of | [[Late-onset Alzheimer disease]] (MESH:D000544) |  | "The APOE ε4 allele is the strongest risk factor for late onset AD." |
| [[CR1]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Variations in several of these genes, such as CR1, SORL1, BACE1, ABCA7, could also predispose for familial early onset form of the disease." |
| [[SORL1]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Variations in several of these genes, such as CR1, SORL1, BACE1, ABCA7, could also predispose for familial early onset form of the disease." |
| [[BACE1]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Variations in several of these genes, such as CR1, SORL1, BACE1, ABCA7, could also predispose for familial early onset form of the disease." |
| [[ABCA7]] | biolink:associated_with_increased_likelihood_of | [[Alzheimer disease]] (MESH:D000544) |  | "Variations in several of these genes, such as CR1, SORL1, BACE1, ABCA7, could also predispose for familial early onset form of the disease." |
| [[MAPT]] | biolink:contributes_to | [[Frontotemporal dementia]] (MESH:D057180) |  | "Nevertheless, PSEN1, PSEN2 and APP mutations are the main causes of autosomal-dominant early-onset AD, whereas mutations in MAPT and GRN account for a significant part of genetic FTD." |
| [[GRN]] | biolink:contributes_to | [[Frontotemporal dementia]] (MESH:D057180) |  | "Nevertheless, PSEN1, PSEN2 and APP mutations are the main causes of autosomal-dominant early-onset AD, whereas mutations in MAPT and GRN account for a significant part of genetic FTD." |
| Hexanucleotide repeat expansion (variant) | biolink:causes | [[Frontotemporal dementia]] (MESH:D057180) |  | "Another limitation is that it cannot be used to analyze the structural variants, like deletions and insertions, and repetitive sequences like the hexanucleotide repeat expansions in C9ORF72 causing FTD." |
