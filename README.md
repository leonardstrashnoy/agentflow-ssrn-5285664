# AgentFlow — No-Code Agent Framework Based on Logical Primitives

Working copy of the SSRN preprint, on **Leonard Strashnoy's** GitHub, so the GitHub loop (branch → pull request → merge) can be practiced on a repo you control.

| | |
| --- | --- |
| Authors | Dmitry Lande, Leonard Strashnoy |
| SSRN | [5285664](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5285664) |
| DOI | [10.2139/ssrn.5285664](https://doi.org/10.2139/ssrn.5285664) |
| Posted | 22 Jun 2025 |
| Snapshot | [`published/ssrn-5285664.pdf`](published/ssrn-5285664.pdf) |
| Source of truth going forward | [`paper/main.tex`](paper/main.tex) |

This is **not** Dmytro's `semantic-digital-twin-collaborative-cyber-analysis` repo. That one stays his. This one is yours.

## How this repo is meant to work

1. `main` is the current manuscript.
2. You (or Dmytro, once invited as a collaborator **Write**) create a branch, edit `paper/main.tex`, open a pull request.
3. **You** can merge here, because you own the repo.
4. The PDF on SSRN does not change until someone uploads a new version there. Merging on GitHub is not publishing.

LaTeX is the manuscript. Markdown is this README.

## Build the PDF (optional)

```bash
cd paper
pdflatex main.tex
```

The first `main.tex` is a skeleton: title, authors, abstract, section outline. The full camera-ready text is still the SSRN PDF until you port sections across.

## Related

Pulled from [`publications/ssrn-5285664.pdf`](https://github.com/DmytroLande/semantic-digital-twin-collaborative-cyber-analysis/blob/main/publications/ssrn-5285664.pdf) in the SDT experiment repo.
