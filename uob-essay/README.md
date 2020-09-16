# University of Bath Essay Template

Created for MSc Computer Science essay assignments.

## Setup

This makes use of Alex Ball's excellent [Bath Harvard BibTeX style](https://github.com/alex-ball/bathbib). This should be installed as part of a full LaTeX installation as it is available on CTAN, but if it is not:

```bash
tlmgr install bath-bst
```

## References

The template expects a `References.bib` file in the same directory, but this can be renamed.

## Citations

`bathbib` expects `natbib` citations, whose options are [listed here](https://www.overleaf.com/learn/latex/Natbib_citation_styles), but for convenience the common ones are:

> according to **Bird, Smith and Bird (2001)**, this happens when...

```latex
according to \citet{id}, this happens when...
```

> such a claim has been made **(Bird, Smith and Bird (2001))**. In other words...

```latex
such a claim has been made \citep{id}. In other
```
