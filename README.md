# librisvault-kg

The knowledge graph [LibrisVault](https://github.com/steinborndev/LibrisVault) built for the
Bio-Agent Knowledge Graph Construction Challenge (NCATS Pharos as the structure, the open-access
literature as evidence, an ontology layer): the graph at **Alzheimer disease**, every edge judged by a
pruning agent, published here in the part its sources' licences allow.

**Licence: [CC BY 4.0](LICENSE)** for everything in this repository. The graph is a derivative of
open-access papers and open databases, each named on every edge and in `ATTRIBUTION.md`. The code
that made it is not in this repository; the base service is public at the link above.

## What is here

| Path | What |
|---|---|
| `kgx/` | the graph as KGX TSV under BioLink 4.4.5, the published part: **15,414 nodes and 45,782 edges** (of 69,998 in the published graph), `kgx validate` exit 0. `grounded_*` is the validated pair; `full_*` adds the 397 entities the agent could not ground, under local `urn:uuid:` identifiers, which `kgx validate` rejects by design. `profile-report.json` counts what the licence filter kept and left out; `harmonisation.sssom.tsv` holds the disease term harmonisation (source term to MONDO) as SSSOM; `README.md` names the columns |
| `graph/` | the graph as Markdown pages, the form the agent writes and reads: 1,108 entity pages, 233 concept pages, 104 source pages (one per paper with an open licence, its Statements table holding every relation the agent stated from it with the paper's sentence), and the BioLink registry page the agent writes against. 28 source pages of abstracts read without an open licence are left out (their statements are in the export by PMID, without the sentence); links to them from other pages stay as they are |
| `corpus/` | the corpus lists as fixed before any paper was read: `corpus.md` (the 50 papers), `corpus-maintenance.md` (papers 51 to 100), `abstracts.md` (the 28 PubMed abstracts read without an open licence, with their PMIDs), `evidence-abstracts.md` (the 821 abstracts the pruning agent read as evidence, by gene) |
| `ATTRIBUTION.md` | every structured source with its licence and its counts; every paper with its licence, PMID, PMCID and DOI and the statements the export holds from it |

## What the licence filter does

An edge is published when its source's licence lets it travel under CC BY 4.0, and only then:

- **Structured sources** (Pharos's associations, the ontology layer): `by` and `public-domain`
  sources are in; share-alike sources (ChEMBL, JensenLab DISEASES) are out, because a share-alike row
  cannot be relicensed CC BY; sources with a restricted licence (CTD, KEGG) or none stated (Pharos's
  own data, DisGeNET, eRAM, TIGA, Monarch, AmyCo, the HPO annotations, and the harmonisation's match
  edges, which rest on them) are out. The table in `ATTRIBUTION.md` counts every one of them.
- **Literature statements**: a statement from a CC BY or CC0 paper is in with its sentence
  (`supporting_text`); 8,244 statements. A statement from a PubMed abstract without
  an open licence is in with its PMID and without its sentence; 263 statements.

What the filter leaves out is not lost: the full graph, sources of every licence, is what the
challenge's demonstration shows, and the write-up names its counts.

## Where it comes from

- Vault commit `de9a799` (the use case's vault, every page and record of the graph in git), exported 2026-10-29.
- Pipeline: LibrisVault's biomedical layer at code commit `228cb19`; the extraction freeze is the tag `kg-freeze`.
- Ontology index: hgnc@2026-09-25, mondo@v2026-09-01, hp@v2026-09-01, go@2026-08-05, chebi@2026-09-09, mesh@2026 (2026-10-04); BioLink 4.4.5; BioLink registry fingerprint `7cbe5c9b0c8f`.
- Pharos read through its GraphQL API for the targets associated with the disease (snapshot 2026-10-06); the literature from Europe PMC's and PubMed's APIs as BioC.

## How to read an edge

Every edge carries BioLink's slots (`subject`, `predicate`, `object`, `primary_knowledge_source`,
`aggregator_knowledge_source`, `publications`, `supporting_text`, `knowledge_level`, `agent_type`)
and, under `x_`, what the pipeline knew about it: the pruning agent's verdict with its confidence and
reason (`x_pruning_verdict`, `x_pruning_confidence`, `x_pruning_reason`), the calibrated confidence that
the edge holds (`has_confidence_score`), whether the paper's sentence supports a literature edge
(`x_support`, `x_support_votes`, `x_support_reason`), the source's licence (`x_license_class`,
`x_license`), and the line or record it was made from (`x_vault_row`, `x_source_row`). `kgx/README.md`
has the full list.

## Citing

Cite the papers an edge rests on (`publications`), the database it came from
(`primary_knowledge_source`), and this repository. `ATTRIBUTION.md` gives each paper's title, identifiers
and licence.
