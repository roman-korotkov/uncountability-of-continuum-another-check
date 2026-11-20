# Uncountability of continuum, check

[![DOI](https://zenodo.org/badge/1464943066.svg)](https://doi.org/10.5281/zenodo.24386085)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Preface

This article continues the series Uncountability of Continuum. Its character remains deliberately investigational: rather than offering a finished, self-contained solution, it traces a path of inquiry and invites the reader to follow the same line of thought.

A careful reading of Cantor’s oeuvre reveals a picture of the continuum that differs substantially from the modern mainstream view. His conception is both more accurate and more open than the dogmatic formulations prevalent in contemporary set theory. Cantor approaches the continuum as an object of genuine investigation rather than as a finished engineering specification of an intellectual resource. This perspective sheds light on the carefully qualified statements in his diagonal argument, where he deliberately avoids equating the objects of a shared coordinate space with the real numbers themselves. Such observations strongly support the internal consistency of the alternative reading developed in this series.

At the same time, the article highlights a striking fact: how limited our actual knowledge of the continuum remains. Contemporary mathematics has largely committed itself to a single representation - the continuum as a set of a definite cardinality. Yet the surreal numbers already demonstrate that the continuum is at least a proper class, as Ehrlich has emphasised. A still more careful analysis suggests that if one attempts to compare ratios among entities of this kind (proper classes), the continuum appears as something even more generic. We have been digging extremely deep in one narrow direction of an extremely wide field. In many respects we know almost nothing about the continuum today - and perhaps even less than Cantor himself did.

## Abstract

The article continues the series of studies devoted to a critical analysis of the proofs of the uncountability of the continuum. The work focuses on Cantor’s geometric constructions and the transition from them to his theory of order types. It examines how Cantor divided the domains of reflexivity of infinity: the polynomial domain (where the similarity of the part to the whole is preserved) and the exponential domain (where reflexivity is restricted and predicativity is achieved). It is shown that precisely this division renders the geometric proofs and the diagonal argument correct only under the corresponding assumptions about the morphology of infinity. The connection between the axioms of continuity, Archimedes and regularity and the restriction of impredicativity is analysed. An interpretation is proposed according to which modern set theory substantially simplifies Cantor’s original picture by identifying the continuum with the power set of a countable set. Alternative constructions are considered (surreal numbers, fields of greater cardinality, models in first-order logic) in which continuity and density do not entail automatic uncountability in the strong sense. The article demonstrates that the conflict between predicativity and impredicativity is a structural property of the ordering rather than an intrinsic property of the set of points itself.

## Repository Structure

```text
.
├── article_ru.tex      # Main LaTeX source file in Russian
├── article_ru.bib      # BibTeX bibliography
├── CITATION.cff        # Citation metadata for GitHub and Zenodo
├── LICENSE             # CC BY 4.0 license text
└── README.md           # Project overview and build instructions
```

## Compiling the Paper

To compile the PDF locally using `latexmk` (recommended, handles bibliography passes automatically):

```bash
latexmk -pdf article_ru.tex
```

Alternatively, run `pdflatex` and `bibtex` manually:

```bash
pdflatex article_ru.tex
bibtex article_ru
pdflatex article_ru.tex
pdflatex article_ru.tex
```

## How to Cite

If you reference this work, please cite it via Zenodo or use the following BibTeX entry:

```bibtex
@misc{korotkov2026continuumanother,
  author       = {Korotkov, Roman},
  title        = {Uncountability of continuum, another check},
  year         = {2026},
  publisher    = {Zenodo},
  version      = {v0.9.0},
  doi          = {10.5281/zenodo.24386085},
  url          = {https://doi.org/10.5281/zenodo.24386085}
}
```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
