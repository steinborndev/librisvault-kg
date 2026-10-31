# The export

KGX TSV (BioLink 4.4.5), the publication profile of the published graph at vault commit
`de9a799`: 15,414 nodes and 45,782 edges in the grounded pair.

- `grounded_nodes.tsv`, `grounded_edges.tsv`: the edges between nodes with a CURIE identifier; what
  `kgx validate` checks (`validate-grounded.log`, exit 0).
- `full_nodes.tsv`, `full_edges.tsv`: with the entities the agent could not ground, under local
  `urn:uuid:` identifiers, which `kgx validate` rejects by design.
- `profile-report.json`: what the licence filter kept and left out, per source and for the literature.
- `harmonisation.sssom.tsv`: the disease terms of the structured sources mapped to MONDO, as SSSOM,
  with the match kind as its predicate.

## Columns

Nodes: `id`, `category`, `type` (the ontology class: a gene's SO class), `name`, `synonym`, `xref`,
`description`, `provided_by`, and `x_` columns naming the page or record the node came from.

Edges, beyond BioLink's own slots:

- `x_pruning_verdict`, `x_pruning_confidence`, `x_pruning_reason`: the pruning agent's decision on
  the edge (`keep` or `prune`) and why. A published edge is one with `keep` above 0.5, or one the
  pruning does not judge (GO annotations, ChEMBL's ligands and drugs).
- `has_confidence_score`: the graph's calibrated confidence that the edge holds; a source's own score
  is `x_source_score`.
- `x_support`, `x_support_votes`, `x_support_reason`: whether an independent judge found the paper's
  sentence to support a literature edge (`supports`, `partially supports`, `does not support`), on
  the rows it read.
- `x_license_class`, `x_license`: the source's licence, the filter's input.
- `x_vault_row`, `x_source_row`: the page line or the snapshot record the edge was made from.
- `x_source_kind` (`pharos`, `literature`, `ontology`), `x_evidence_scope`, `x_stated_predicate`
  (the statement's own predicate where the export had to widen it), `x_subject_xref`,
  `x_object_xref`, `x_edge_group`, `x_original_source`, `x_slot`, `x_evidence`, `x_zscore`,
  `x_confidence`, `x_log2fc`: the source's own fields, carried as they were measured.
