# Typed Crossings

**What casts, refinement proofs and chain-of-thought checks carry across a boundary.**

A claim established in one structure is routinely reused in another: an identity on the natural numbers after a cast to the integers, a property of a specification after refinement to an implementation, the validity of a written chain of reasoning as a statement about the computation that produced it. Whether the claim survives is a property of the map that carries it. This position paper argues that such a crossing should be declared and typed: by its kind, which fixes what a failure of the crossing consists in, and by what it preserves, under which conditions. It examines three cases (casts in Lean 4, refinement proofs in system verification, chain of thought and proof kernels in machine learning) and comes with a partial mechanisation in Lean 4.

## Contents

| File | |
|---|---|
| [`typed-crossings-v1.0.pdf`](typed-crossings-v1.0.pdf) | The paper, v1.0, byte-identical to the Zenodo deposit (md5 `614cefae475f7f89dc023bd2328a526e`) |
| [`main.tex`](main.tex), [`sections/`](sections/) | LaTeX source |
| [`refs.bib`](refs.bib), [`main.bbl`](main.bbl) | Bibliography |
| [`code/`](code/) | The Lean files the listings are taken from: copies from [lem-lean](https://github.com/Barnes70/lem-lean) at tag [`v0.4.0`](https://github.com/Barnes70/lem-lean/tree/v0.4.0) |

## Build

The paper compiles with pdfLaTeX:

```sh
pdflatex main
bibtex main
pdflatex main
pdflatex main
```

## Related

- **Lean package:** [Barnes70/lem-lean](https://github.com/Barnes70/lem-lean) — the definitions and machine-checked results the paper refers to.
- **Source of the vocabulary:** [Barnes70/layered-event-modelling](https://github.com/Barnes70/layered-event-modelling) — Layered Event Modelling, Version 1.0, [10.5281/zenodo.23438101](https://doi.org/10.5281/zenodo.23438101).
- **Essays the paper draws on:** [Invisible Coercions and Untyped Refinement](https://www.barnes.ch/BP-Invisible-Coercions.html), [Where Does a Model Reason?](https://www.barnes.ch/BP-Where-Does-A-Model-Reason.html) — [barnes.ch](https://www.barnes.ch).

## Versions

| Version | Date | DOI |
|---|---|---|
| 1.0 | 2026-11-14 | [10.5281/zenodo.24219769](https://doi.org/10.5281/zenodo.24219769) |

All versions: concept DOI [10.5281/zenodo.24219768](https://doi.org/10.5281/zenodo.24219768).

## How to cite

> Kreinz, B. (2026). *Typed Crossings: What Casts, Refinement Proofs and Chain-of-Thought Checks Carry Across a Boundary* (Version 1.0) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.24219769

```bibtex
@misc{kreinz2026typedcrossings,
  author    = {Kreinz, Bernhard},
  title     = {Typed Crossings: What Casts, Refinement Proofs and
               Chain-of-Thought Checks Carry Across a Boundary},
  year      = {2026},
  version   = {1.0},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.24219769},
  url       = {https://doi.org/10.5281/zenodo.24219769}
}
```

## License

Text and figures: [CC BY 4.0](LICENSE) © 2026 Bernhard Kreinz ([ORCID 0009-0005-2148-9903](https://orcid.org/0009-0005-2148-9903)). The Lean files in [`code/`](code/) are licensed under the [Apache License 2.0](code/LICENSE).
