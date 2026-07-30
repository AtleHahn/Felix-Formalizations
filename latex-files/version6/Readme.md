
# Version 6

This directory contains the version of `formalizations.tex` and `naprochelibrary.tex` obtained
from version 5 after modifying `naprochelibrary.tex` and `formalizations.tex` in the following way:

In version 5 the file `naprochelibrary.tex` contained two different notions of natural
numbers:

- von Neumann naturals, and
- positive real naturals.

Von Neumann naturals have now been removed from `naprochelibrary.tex` and the file `formalizations.tex`
was modified accordingly.

## Terminology

Munkres uses the concept `neighborhood` in a non-standard way.
Many other authors would use the term `open neighborhood` for what
Munkres calls a `neighborhood`.

## Coverage

There are currently only two instances of `Omitted.` in
`formalizations.tex`, namely in the proofs of theorems
`zorn_subset_family` and
`well_ordering_theorem_local_finiteness`, which formalize versions of
Zorn's lemma and the well-ordering theorem.

We plan to move both results, including their proofs, to
the standard library in `naprochelibrary.tex`.

 
