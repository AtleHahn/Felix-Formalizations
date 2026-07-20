
# Version 5

This directory contains the version of `formalizations.tex` and `naprorchlibrary.tex` obtained
from version 4 after shortening `naprorchlibrary.tex` and slightly adapting `formalizations.tex`

## Terminology

Munkres uses the concept `neighborhood` in a non-standard way.
Many other authors would use the term `open neighborhood` for what
Munkres calls a `neighborhood`.

## Coverage

Compared with version 3, this version adds coverage of sections
§34-§49 of Munkres' book.

There are currently only two instances of `Omitted.` in
`formalizations.tex`, namely in the proofs of theorems
`zorn_subset_family` and
`well_ordering_theorem_local_finiteness`, which formalize versions of
Zorn's lemma and the well-ordering theorem.

In version 6, we plan to move both results, including their proofs, to
the standard library in `naprochelibrary.tex`.

## Note on Section §50

Section §50, the final section on set-theoretic topology, is not yet
included. We plan to include it in version 6 after modifying
`naprochelibrary.tex` further.

At present, `naprochelibrary.tex` contains two notions of natural
numbers:

- von Neumann naturals, and
- positive real naturals.

This duplication led to many very long formal proofs in the current
formalized version of §50, so we decided to omit that section from
version 4 and version 5.
