# connes-embedding-docs

Generated HTML API documentation for the Lean 4 formalization *"A machine-checked
operator-algebraic route to the negative Connes Embedding Problem"*.

**Read it here:** https://jpeig.github.io/connes-embedding-docs/

This repository contains **build output only** — no sources, no proofs. Every page is
produced by [doc-gen4](https://github.com/leanprover/doc-gen4) from the Lean sources and
shows declaration statements and documentation; tactic proofs are not part of doc-gen4
output. Cross-references into Mathlib resolve against the
[published Mathlib documentation](https://leanprover-community.github.io/mathlib4_docs/).

The formalization itself lives in a separate private repository. Its headline result is
`cep_false_operator_algebraic_single_scaffold`, whose kernel-checked axiom footprint is

```
[propext, Classical.choice, Quot.sound, ZFib.CEP.kirchberg_game_separation_ucp_structured]
```

— Lean's three standard axioms plus exactly one named citation (the MIP*=RE synchronous-game
separation), with no `sorryAx`. Access to the sources, the reproduction commands and the
frozen axiom audit is available on request: jorrit@yom.net.

Do not edit these files by hand; they are regenerated and force-replaced by the build.
