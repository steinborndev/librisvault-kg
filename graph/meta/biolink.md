---
type: meta
title: "BioLink Registry"
created: 2026-09-28
updated: 2026-10-14
content_updated: 2026-10-14
biolink_version: 4.4.5
tags:
  - meta
  - biolink
status: evergreen
related:
  - "[[index]]"
---

# BioLink Registry

The closed lists this wiki's biomedical layer uses: which kinds of node a page may be (its
`category:` field) and which predicates a row of a page's `## Relations` table may carry. Both
lists are taken from the BioLink Model, version 4.4.5. The ingestion service reads this page and
hands both lists to every ingest run; a vault without this page has no biomedical layer at all.

**This page is the contract, not a suggestion.** A page takes exactly one category listed under
"Categories" below. A relation row takes exactly one predicate listed under "Predicates", or no row
is written: a vague relation is worse than none, which is why `biolink:related_to` is not on the
list.

## How an entry is added

Adding a category or a predicate is a human decision, made on this page. An entry is a `###`
heading with the BioLink CURIE, a lead paragraph saying when it applies, and the labelled lines in
the shape of the others. Only canonical, non-deprecated elements of BioLink 4.4.5 belong here.

## Conventions

- **Subject** and **Object** name the categories a row's two ends usually have. They are guidance
  drawn from BioLink's domain and range, narrowed to this page's categories where BioLink declares
  none. A predicate without them takes any category on either end.
- **Symmetric: yes** means the row is written once, on either of the two pages.
- A gene page stands for the gene and its products: there is no separate protein node.
- **Prefixes** lists the identifier prefixes a page of that category may carry in `ids:`, the
  preferred one first.

## Categories

### biolink:Gene

A gene or its products: the gene, its transcripts and the protein it encodes, as one node. Titled
by its HGNC-approved symbol; a gene studied in mouse or rat lands on the page of its human
orthologue.

**Prefixes:** HGNC, NCBIGene, UniProtKB (as a cross-reference for the protein)

### biolink:Disease

A disease or disorder: a disposition to undergo pathological processes, from a syndrome to a
cancer type.

**Prefixes:** MONDO, DOID, OMIM, ORDO, EFO, MESH

### biolink:PhenotypicFeature

An observable trait or clinical sign that is not itself a disease: a symptom, a laboratory
finding, an abnormal measurement.

**Prefixes:** HP, EFO, MEDDRA

### biolink:ChemicalEntity

Any chemical: a drug, a metabolite, an element, a toxin, a nutrient. Small molecules are this
category too.

**Prefixes:** CHEBI, PUBCHEM.COMPOUND, CHEMBL.COMPOUND, DRUGBANK, UNII, MESH

### biolink:BiologicalProcess

A biological process: a chain of molecular events such as apoptosis, autophagy or an immune
response.

**Prefixes:** GO, REACT

### biolink:MolecularActivity

A molecular function carried out by a gene product: kinase activity, receptor binding, transport
of an ion.

**Prefixes:** GO, RHEA, EC

### biolink:CellularComponent

A place in or around a cell: the nucleus, the mitochondrion, the plasma membrane, a complex.

**Prefixes:** GO

### biolink:SequenceVariant

A variant of a gene's or genome's sequence: a SNP, a missense change, an insertion or deletion.
Titled as gene plus change.

**Prefixes:** DBSNP, CLINVAR, CAID

### biolink:OrganismTaxon

A species, such as the organism a study was done in or a plant a compound comes from. A
laboratory line or strain of an animal is a PopulationOfIndividualOrganisms, not a taxon.

**Prefixes:** NCBITaxon

### biolink:PopulationOfIndividualOrganisms

A laboratory animal model or strain: a transgenic, knockout or knock-in line, or an inbred or
outbred strain used in a study (5xFAD mice, APP/PS1 mice, Sprague-Dawley rats). It is the
subject of the phenotypes a study observes in it. Added 2026-10-14 by the user's decision (F-P3-6):
BioLink does not let a taxon have a phenotype, and a model is a population of animals, not a
species. No ontology the vault holds names such lines, so the page carries no `ids:`.

### biolink:CellLine

A cultured cell line used in a study.

**Prefixes:** CLO

## Predicates

### biolink:causes

The subject is a cause of the object: a variant or gene causes a disease, a chemical causes a
condition. Stronger than contributes_to; use it only when the source states causation.

**Subject:** Gene, SequenceVariant, ChemicalEntity
**Object:** Disease, PhenotypicFeature
**Example:** "Biallelic loss-of-function variants in X cause syndrome Y."

### biolink:contributes_to

The subject makes the object more likely or more severe, without being its sole cause.

**Subject:** Gene, SequenceVariant, ChemicalEntity
**Object:** Disease, PhenotypicFeature
**Example:** "Loss of X contributes to early-onset Y."

### biolink:associated_with

A non-causal association between the two, established statistically or by other evidence, where
the source states no direction of effect.

**Symmetric:** yes
**Example:** "Variants in X were associated with Y."

### biolink:correlated_with

A statistical correlation between the two, without a stated direction.

**Symmetric:** yes
**Example:** "Levels of X correlated with the severity of Y."

### biolink:positively_correlated_with

The two move in the same direction: more or presence of one goes with more or presence of the
other.

**Symmetric:** yes
**Example:** "Higher X expression was observed in patients with Y."

### biolink:negatively_correlated_with

The two move in opposite directions: more or presence of one goes with less or absence of the
other.

**Symmetric:** yes
**Example:** "X levels were reduced in patients with Y."

### biolink:associated_with_increased_likelihood_of

The subject makes the object more probable, typically shown statistically: a risk allele, a risk
exposure.

**Subject:** Gene, SequenceVariant, ChemicalEntity, Disease, PhenotypicFeature
**Object:** Disease, PhenotypicFeature
**Example:** "Carriers of the X allele had a higher risk of Y."

### biolink:associated_with_decreased_likelihood_of

The subject makes the object less probable: a protective allele or exposure.

**Subject:** Gene, SequenceVariant, ChemicalEntity, Disease, PhenotypicFeature
**Object:** Disease, PhenotypicFeature
**Example:** "The X variant was associated with a reduced risk of Y."

### biolink:biomarker_for

The subject is measured as an indicator of the presence or state of the object.

**Subject:** Gene, ChemicalEntity
**Object:** Disease, PhenotypicFeature
**Example:** "Serum X is a diagnostic marker for Y."

### biolink:treats

The chemical is able to ameliorate, stabilize or cure the condition, or delay or prevent it, as
the source states for some population.

**Subject:** ChemicalEntity
**Object:** Disease, PhenotypicFeature
**Example:** "X improved outcomes in patients with Y."

### biolink:in_clinical_trials_for

The chemical is being or has been tested in a clinical trial in human patients for the condition,
whatever the result.

**Subject:** ChemicalEntity
**Object:** Disease, PhenotypicFeature
**Example:** "A phase II trial of X in patients with Y."

### biolink:has_adverse_event

The condition occurred during treatment with the chemical, as an untoward effect of it.

**Subject:** ChemicalEntity
**Object:** Disease, PhenotypicFeature
**Example:** "X-induced Y was observed in treated patients."

### biolink:affects

The subject changes a quality of the object: its expression, activity, abundance, localization or
another aspect. The direction and the aspect go into the Qualifiers column.

**Subject:** Gene, SequenceVariant, ChemicalEntity
**Object:** Gene, ChemicalEntity, BiologicalProcess, MolecularActivity
**Qualifiers:** `aspect=<value>; direction=<value>`. Aspect: `expression`, `activity`, `abundance`, `activity_or_abundance`, `synthesis`, `degradation`, `stability`, `localization`, `transport`, `secretion`, `uptake`, `splicing`, `phosphorylation`, `methylation`, `ubiquitination`, or another value of BioLink's GeneOrGeneProductOrChemicalEntityAspectEnum. Direction: `increased`, `decreased`, `upregulated`, `downregulated`.
**Example:** "Treatment with X reduced Y expression."

### biolink:regulates

A form of affects in which the effect comes from a biologically evolved control mechanism, such as
a transcription factor and its target. An external chemical acting on a gene is affects, not
regulates. Qualifiers as for affects.

**Subject:** Gene, ChemicalEntity
**Object:** Gene, BiologicalProcess, MolecularActivity
**Qualifiers:** `aspect=<value>; direction=<value>`, the same values as for affects.
**Example:** "X binds the promoter of Y and represses its transcription."

### biolink:physically_interacts_with

The two make physical contact as part of an interaction, with no causal claim.

**Subject:** Gene, ChemicalEntity
**Object:** Gene, ChemicalEntity
**Symmetric:** yes
**Example:** "X co-immunoprecipitated with Y."

### biolink:directly_physically_interacts_with

The two bind each other directly, as the source shows: a ligand and its receptor, an inhibitor
and its target.

**Subject:** Gene, ChemicalEntity
**Object:** Gene, ChemicalEntity
**Symmetric:** yes
**Example:** "X binds directly to the kinase domain of Y."

### biolink:genetically_interacts_with

Two genes whose phenotypic effects depend on each other: epistasis, synthetic lethality.

**Subject:** Gene
**Object:** Gene
**Symmetric:** yes
**Example:** "Loss of X was synthetically lethal with loss of Y."

### biolink:pharmacologically_interacts_with

Two pharmacologically active chemicals where one alters the availability, efficacy or toxicity of
the other when taken together.

**Subject:** ChemicalEntity
**Object:** ChemicalEntity
**Symmetric:** yes
**Example:** "Co-administration of X increased plasma levels of Y."

### biolink:derives_from

The subject came into existence from the object, inheriting most of its matter: a metabolite
from its precursor, a product from its substrate. The row stands on the product's page.

**Subject:** ChemicalEntity
**Object:** ChemicalEntity
**Example:** "X is converted to its active metabolite Y."

### biolink:actively_involved_in

The subject actively contributes to the process or activity: a gene in a pathway, an enzyme in a
reaction.

**Subject:** Gene, ChemicalEntity
**Object:** BiologicalProcess, MolecularActivity
**Example:** "X is required for Y signaling."

### biolink:located_in

The subject is located in the cellular component without being part of it.

**Subject:** Gene, ChemicalEntity
**Object:** CellularComponent
**Example:** "X accumulates in the mitochondrial matrix."

### biolink:is_sequence_variant_of

The variant is a variant of the gene.

**Subject:** SequenceVariant
**Object:** Gene
**Example:** "The Y variant in X was found in three families."

### biolink:has_phenotype

The subject shows the phenotypic feature: a disease and its signs, a variant or gene and the trait
it produces.

**Subject:** Disease, Gene, SequenceVariant, PopulationOfIndividualOrganisms
**Object:** PhenotypicFeature
**Example:** "Patients with X presented with Y."
