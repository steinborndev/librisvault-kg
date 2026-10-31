---
type: source
title: "Humanized APP knock-in mouse and rat with PSEN1 M139T for Alzheimer disease"
paper_title: "Modeling the β-secretase cleavage site and humanizing amyloid-beta precursor protein in rat and mouse to study Alzheimer’s disease"
domain: neuroscience
status: developing
created: 2026-10-09
updated: 2026-10-09
content_updated: 2026-10-09
address: c-000403
pmid: "33076948"
pmcid: "PMC7574558"
doi: "10.1186/s13024-020-00399-z"
license: "CC BY"
url: "https://pmc.ncbi.nlm.nih.gov/articles/PMC7574558/"
sources: ["[[.raw/01M4DY94RHQY8RCNWQ801YP77N/normalized.md]]"]
tags: [knock-in, rodent-model, secretase, amyloid]
---

# Humanized APP knock-in mouse and rat with PSEN1 M139T for Alzheimer disease

Rodent [[APP]] differs from human APP at three residues inside the amyloid beta sequence (G676R, F681Y, R684H, numbered on the APP770 isoform), and these change how well [[BACE1]] cuts it. The authors modelled the human β-CTF in the BACE1 active site, then used [[CRISPR-Cas9 knock-in humanization]] to replace the three residues in the endogenous mouse and rat App genes. They also knocked the familial Alzheimer mutation [[PSEN1 p.M139T]] into the rat Psen1 gene. The resulting lines are the [[Humanized App mouse]] and the [[Humanized App Psen1 M139T rat]].

## Methods

- Computational model of the humanized β-CTF superposed on the BACE1 crystal structure 5MCQ (peptide inhibitor complex), compared with a rodent β-CTF model.
- Mouse: Cas9 ribonucleoprotein plus a single-stranded repair oligo injected into 72 C57Bl6J embryos; one correctly targeted founder, checked by Sanger sequencing including the five most likely off-target sites, backcrossed and made homozygous. Two silent changes (loss of an EcoRI site, and blocking re-cutting by Cas9) allow genotyping.
- Rat: Cas9 mRNA, guide RNAs and donor oligos injected into Long Evans zygotes for both the App humanization and the Psen1 M139T change; a colony homozygous for humanized App and carrying Psen1 M139T was bred.
- 14-week-old animals (3 female and 3 male per group): western blotting of cerebrum with C-terminal APP and human-specific Aβ antibodies, soluble (diethylamine) and guanidine-extracted Aβ38, 40, 42 by electrochemiluminescent ELISA, Aβ43 by a separate kit, tau isoforms by 3R- and 4R-specific antibodies, X34 and Aβ immunohistology. Control human cortex came from epilepsy surgery. Unpaired t tests and one-way ANOVA.

## Findings

- Modelling: arginine at 676 adds a positive charge that contacts glutamate 326 of BACE1, and tyrosine at 681 adds a hydroxyl that hydrogen bonds asparagine 294; neither BACE1 residue needs to move. The humanized β-CTF is therefore a better BACE1 substrate.
- In brain, the β-CTF to full-length APP ratio was 4.8 times higher in human than mouse and 7.8 times higher than rat (both p < 0.0001).
- Humanization left full-length APP and total CTFs unchanged but raised β-CTF 2.5-fold in mouse and 4.2-fold in rat, and lowered α-CTF (0.6-fold in mouse, 0.7-fold in rat).
- Aβ40 rose from 2091 ± 130 to 4827 ± 257 pg/g in mouse and from 3302 ± 1256 to 9292 ± 516 pg/g in rat. Total soluble Aβ was 7187 ± 1022 pg/g (mouse) and 12,615 ± 1511 pg/g (rat), about half of control human brain (21,141 ± 8712 pg/g); the abstract summarizes this as roughly threefold more human Aβ than the wild-type strains.
- Psen1 M139T in the rat left total Aβ and APP fragments unchanged (11,898 ± 486 against 12,834 ± 676 pg/g) but shifted Aβ toward Aβ42: Aβ42/Aβ40 rose from 0.10 to 0.27, Aβ38/Aβ42 fell from 2.60 to 1.48, and Aβ43 fell 2.5-fold, raising Aβ40/Aβ43 from 42.96 to 92.41. This is read as a less efficient carboxypeptidase-like γ-secretase step and a shift to the Aβ42 product line, with no sign of Notch-related harm (homozygous rats were fertile and healthy).
- No plaques and no insoluble Aβ in guanidine extracts, even in the oldest rats (2 years). The rat 3R to 4R [[MAPT]] ratio was about 1:13, far from 1:1 in human brain, with 3R tau very low in mouse; AT100 phosphorylation appeared with age in knock-in rats, but no tangles formed.

## Assessment

- Group sizes are small (n = 6 per genotype) and the mutant rat data come from one founder line; the authors do not report a second founder for the Psen1 allele.
- The "threefold" figure in the abstract is a rounded summary of different readouts (β-CTF 2.5 to 4.2 fold, Aβ40 2.3 to 2.8 fold); the exact fold change depends on the species and the species-specific ELISA, and the wild-type baseline is measured with a different, rodent-specific detection antibody than the humanized animals.
- The negative plaque result is itself informative but is limited to 2 years in a rat line that has no overexpression; the authors acknowledge that amyloid and tangle development is unlikely at later ages.
- Comparison to a D'Adamio rat with PSEN1 L435F rests on a report that followed animals only to 2 weeks, so the contrast in plaque outcome is weak.

## Open Questions

- Does adding a pathogenic App knock-in (such as the Swedish or Arctic mutations) to the humanized rat produce plaques, as in the [[AppNL-G-F mouse]] (not tested in this work)?
- Why is the PSEN1 L435F mutation embryonically lethal in mice but tolerated by homozygous rats (no explanation given in the literature the authors cite)?
- Do human-microglia or organoid chimeras on a humanized App background develop the glial feedback loops thought to link plaques to neurodegeneration (not examined here)?

## Why This Source Matters

It supplies the missing wild-type control for knock-in Alzheimer models: an endogenous-promoter rodent whose Aβ is human, readable with human Aβ ELISAs, and not distorted by overexpression or random transgene insertion. Its null result, severe Aβ42 shift without plaques or tangles in an aged rat, argues that plaque formation in earlier transgenic models depends on strong APP overexpression and on human-specific cell and ageing context.

## Connections

- Genes: [[APP]], [[BACE1]], [[PSEN1]], [[MAPT]]
- Variants: [[APP p.G676R]], [[APP p.F681Y]], [[APP p.R684H]], [[PSEN1 p.M139T]]
- Models: [[Humanized App mouse]], [[Humanized App Psen1 M139T rat]]; positive-control and related lines [[AppNL-G-F mouse]], [[Tg2576 mouse]]
- Process: [[Amyloid-beta formation]]; disease: [[Early-onset Alzheimer disease]], [[Familial Alzheimer disease]]
- Method: [[CRISPR-Cas9 knock-in humanization]]

## Statements

| Subject | Predicate | Object | Qualifiers | Evidence |
|---|---|---|---|---|
| [[APP]] | biolink:directly_physically_interacts_with | [[BACE1]] |  | "We show that introducing these three amino acid substitutions into the rodent sequence lowers the affinity of the APP substrate for BACE1 cleavage." |
| amyloid-beta (CHEBI:64645; MESH:D016229) | biolink:contributes_to | [[Alzheimer disease]] (MESH:D000544) |  | "Alterations in Aβ generation and aggregation are central to AD." |
| APP p.KM670/671NL (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "APP knock-in models are available that express clinical AD mutations (KM 670/671NL, E693G, I716F) in the endogenous mouse sequence." |
| APP p.E693G (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "APP knock-in models are available that express clinical AD mutations (KM 670/671NL, E693G, I716F) in the endogenous mouse sequence." |
| APP p.I716F (variant) | biolink:associated_with | [[Alzheimer disease]] (MESH:D000544) |  | "APP knock-in models are available that express clinical AD mutations (KM 670/671NL, E693G, I716F) in the endogenous mouse sequence." |
| [[PSEN1 p.M139T]] | biolink:causes | [[Familial Alzheimer disease]] |  | "We also introduced the early-onset familial Alzheimer’s disease (FAD) mutation M139T into the endogenous Rat Psen1 gene." |
| [[APP p.G676R]] | biolink:affects | amyloid-beta (CHEBI:64645; MESH:D016229) |  | "The three amino acid substitutions (G676R, F681Y and R684H) needed to humanize the mouse Aβ sequence have a profound effect on Aβ generation." |
| [[APP p.F681Y]] | biolink:affects | amyloid-beta (CHEBI:64645; MESH:D016229) |  | "The three amino acid substitutions (G676R, F681Y and R684H) needed to humanize the mouse Aβ sequence have a profound effect on Aβ generation." |
| [[APP p.R684H]] | biolink:affects | amyloid-beta (CHEBI:64645; MESH:D016229) |  | "The three amino acid substitutions (G676R, F681Y and R684H) needed to humanize the mouse Aβ sequence have a profound effect on Aβ generation." |
| APP p.KM670/671NL (variant) | biolink:contributes_to | amyloid (MONDO:0019065; MESH:D058225) |  | "These models develop amyloid pathology and interesting phenotypes without potential artefacts introduced by APP overexpression." |
| APP p.E693G (variant) | biolink:contributes_to | amyloid (MONDO:0019065; MESH:D058225) |  | "These models develop amyloid pathology and interesting phenotypes without potential artefacts introduced by APP overexpression." |
| APP p.I716F (variant) | biolink:contributes_to | amyloid (MONDO:0019065; MESH:D058225) |  | "These models develop amyloid pathology and interesting phenotypes without potential artefacts introduced by APP overexpression." |
| [[BACE1]] | biolink:affects | [[APP]] |  | "The ratio of β-CTF over full length APP in human samples is 4.8 (p < 0.0001 and 7.8 (p < 0.0001) times higher compared to mouse and rat, respectively, confirming that human APP is a better substrate for BACE1." |
| arginine (CHEBI:16467; MESH:D001120) | biolink:physically_interacts_with | [[BACE1]] |  | "G676R (replacing the glycine in the rodent sequence with arginine) provides a large positive charge that interacts with glutamate E326 of BACE1." |
| arginine (CHEBI:16467; MESH:D001120) | biolink:physically_interacts_with | glutamate (CHEBI:16015; MESH:D018698) |  | "G676R (replacing the glycine in the rodent sequence with arginine) provides a large positive charge that interacts with glutamate E326 of BACE1." |
| [[APP]] | biolink:affects | Aβ40 (CHEBI:64646) | direction=increased | "In mice, the Aβ40 levels in brain tissue rose from 2091 ± 130 pg/g in WT to 4827 ± 257 pg/g in the KI model (p < 0.0001), while in rats the levels were increased from 3302 ± 1256 pg/g in WT to 9292 ± 516 pg/g in the KI animals (p < 0.0001)." |
| [[PSEN1]] | biolink:affects | Aβ42 (CHEBI:64647) | direction=increased | "Humanization of the Aβ sequence in rat affects APP processing, while the M139T mutation in PSEN1 results in increased Aβ42 production." |
| [[PSEN1 p.M139T]] | biolink:affects | Aβ40 (CHEBI:64646) | direction=increased | "However, the mutation causes a relative shift towards more Aβ42 production, in parallel with a very small amount of Aβ43 and less Aβ40 (Fig. 3c)." |
| [[PSEN1 p.M139T]] | biolink:causes | [[Familial Alzheimer disease]] |  | "The M139T FAD mutation alters Aβ38/Aβ42 and Aβ42/Aβ40 ratios without affecting the endopeptidase cleaving activity responsible for release of the APP intracellular fragment." |
| [[PSEN1 p.M139T]] | NOT biolink:causes | amyloid (MONDO:0019065; MESH:D058225) |  | "Disappointingly, the oldest rat we examined (2 years of ages) did not show amyloid plaque pathology." |
| [[PSEN1 p.M139T]] | biolink:causes | [[Alzheimer disease]] (MESH:D000544) |  | "The PSEN1M139T mutation leads to mean age of disease onset between 39 and 51 years old." |
| [[APP]] | biolink:contributes_to | amyloid plaques (MESH:D058225) |  | "The amyloid plaques in these models seem critically dependent on strong overexpression of APP (and sometimes Presenilin)." |
| [[PSEN1]] | biolink:contributes_to | amyloid plaques (MESH:D058225) |  | "The amyloid plaques in these models seem critically dependent on strong overexpression of APP (and sometimes Presenilin)." |
| [[PSEN1 p.M139T]] | biolink:affects | amyloid-beta 42 (CHEBI:64647; MESH:C075222) | direction=increased | "Our new data confirm these effects, but the strong lowering of Aβ43 and increase in Aβ40/Aβ43 ratio indicate that in vivo the mutation mainly works via a selective shift towards the Aβ42 product pathway and less via destabilization of the enzyme-substrate complex." |
| amyloid-beta 42 (CHEBI:64647; MESH:C075222) | biolink:associated_with | [[Familial Alzheimer disease]] |  | "Preclinical carriers have relatively high levels of Aβ42 in the cerebrospinal fluid." |
| [[PSEN1 p.M139T]] | biolink:affects | amyloid-beta 40 (CHEBI:64646; MESH:C078592) |  | "In vitro this mutant affects the production rates of Aβ38 and Aβ40, while endopeptidase activity is not altered." |
| [[PSEN1 p.M139T]] | NOT biolink:causes | amyloid plaques (MESH:D058225) |  | "The fact that the simple introduction of the PSEN FAD mutations in the rodent homologues does not cause amyloid plaque formation, despite clear alterations in Aβ ratios, suggests that molecular and cellular events upstream and downstream of amyloid plaque formation in humans are lacking in rodents." |
| PSEN1 L435F (variant) | NOT biolink:causes | amyloid plaques (MESH:D058225) |  | "These rats were also reported not to develop amyloid plaques, although it needs to be stated that animals were only followed up to 2 weeks of age." |
