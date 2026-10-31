---
type: concept
title: "Molecular dynamics simulation"
domain: methods
status: seed
created: 2026-10-09
updated: 2026-10-12
content_updated: 2026-10-12
address: c-000704
aliases: ["MD simulation", "molecular dynamics", "NAMD simulation"]
tags: [in-silico]
---

# Molecular dynamics simulation

Molecular dynamics simulation follows the atoms of a protein-ligand complex in a solvated, neutralised box over time under a force field, to test whether a docked pose stays together. Common read-outs are protein and ligand root mean square deviation (RMSD, lower means a more stable complex), solvent-accessible surface area (how buried the ligand is) and the hydrogen-bond count between ligand and protein. The result depends on the force field, simulation length and a single trajectory, so it supports ranking rather than proving binding.

## Connections

- Used for 100 ns runs (NAMD, CHARMM36m, 303.15 K) on seven drug-regulator pairs after [[Molecular docking]]; ETV6 complexes were the most stable, with [[Lasmiditan]] lowest in RMSD. Study: [[Lasmiditan prioritised for Alzheimer disease by regulator docking and dynamics]]
- Gene tested: [[ETV6]]
- 300 ns GROMACS runs (Amber03) in triplicate on PLCγ2 with proline or arginine at residue 522: overall flexibility was similar, but the arginine formed hydrogen bonds with seventeen residues instead of one neighbour, a coil became a helix and the SH2 domains shifted. Study: [[PLCG2 P522R variant raises PIP2 depletion and endocytosis in microglia]]
- 100 ns GROMACS 2022.3 runs (Amber99sb-ildn, TIP3P water, 300 K, 1 bar, 2 fs steps) of [[6-Gingerol]] with [[ACHE]], [[CASP3]], [[MMP2]] and [[PTGS2]], read as RMSD, RMSF, radius of gyration, hydrogen bonds and Gibbs free energy landscapes; all four complexes stayed associated, one run each. Study: [[6-Gingerol from ginger screened for Alzheimer disease by docking and dynamics]]
