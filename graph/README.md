# The graph as Markdown

The form the agent writes and reads: one page per entity, concept and source, in a git-versioned
vault. Each page has YAML frontmatter (`type`, `title`, `category` in BioLink's terms, `ids` as
CURIEs, `aliases`, `domain`, `tags`) and a body with `[[wikilinks]]` to other pages.

- `entities/` (1,108): genes, proteins, diseases, phenotypes, chemicals, processes, cell lines,
  models and taxa, each with its identifiers and what the sources say about it.
- `concepts/` (233): methods, mechanisms and other ideas the papers share.
- `sources/` (104): one page per paper with an open licence, with the agent's reading of it and,
  under `## Statements`, every relation the agent stated from it: subject, BioLink predicate, object
  with its identifier, qualifiers, and the paper's own sentence as evidence. These rows are the
  literature edges of the export (`x_vault_row` names the page and line).
- `meta/biolink.md`: the BioLink registry, the closed list of categories and predicates the agent
  writes against.

28 source pages are not here: papers read from their PubMed abstract alone, without an open
licence. Their Statements tables quote the abstract, which is what the export leaves out too; their
statements are in `kgx/` by PMID (`publications`) without `supporting_text`, and `corpus/abstracts.md`
lists them. Links to them from other pages are left as they are.
