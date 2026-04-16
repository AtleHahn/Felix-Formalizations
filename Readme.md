# Felix Formalizations

This repository contains the most recent versions of our preliminary
autoformalization experiments with the proof assistant
[Felix (Naproche/ZF)](https://github.com/adelon/felix).

The project focuses on material from James R. Munkres'
[*Topology* (2nd ed.)](https://www.amazon.com/Topology-2nd-James-Munkres/dp/0131816292),
with source LaTeX artifacts in `latex-files/` and generated HTML
documentation in `docs/`.

## Documentation

Browse the generated documentation at
[atlehahn.github.io/Felix-Formalizations/docs/index.html](https://atlehahn.github.io/Felix-Formalizations/docs/index.html),
which includes:

- Topological spaces
- Basis and order topologies
- Product, subspace, metric, and quotient topologies
- Connectedness, compactness, countability, and separation axioms
- The Urysohn lemma

## LaTeX Sources

The `latex-files/` directory collects intermediate and distilled LaTeX versions
of the formalizations. See [`latex-files/Readme.md`](latex-files/Readme.md) for
the folder-specific overview.

The current HTML documentation is based on:

- `latex-files/naprochelibrary.tex`
- `latex-files/Distillation_Round_8/formalizations_shortened_8_times_after_elaboration_and_adaption_to_new_felix_version.tex`

Additional source material is preserved in:

- `Distillation_Round_8`
- `Distillation_Round_9`

These files complement the HTML output in `docs/` by preserving the underlying
source material and iteration history.

## Scope

These files represent ongoing, preliminary work on autoformalizing textbook
mathematics in Felix.
