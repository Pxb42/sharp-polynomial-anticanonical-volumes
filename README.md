# Sharp polynomial upper bounds for anticanonical volumes

**Pinxian Bie, Peien Du and Zhengjie Yu**  
School of Mathematical Sciences, Fudan University

**Manuscript date:** October 7, 2026  
**Status:** Working draft. The results and proofs are still being checked. This manuscript has not been peer-reviewed and may be revised.

[Read the manuscript (PDF)](main.pdf) | [LaTeX source](main.tex) | [BibTeX citation](CITATION.bib)

## Main statement of the draft

The manuscript concerns polynomial upper bounds for anticanonical volumes of varieties of epsilon-Fano type. Its main statement is that, for each positive integer $n$, there is a constant $C_n$ depending only on $n$ such that

$$
\operatorname{vol}(-K_X) \leq C_n\epsilon^{-(2^n-n-1)}
$$

whenever $X$ is a normal projective $\mathbb{Q}$-Gorenstein variety over $\mathbb{C}$ admitting an effective $\mathbb{Q}$-divisor $\Delta$ such that $(X,\Delta)$ is $\epsilon$-lc and $-(K_X+\Delta)$ is ample, with $0<\epsilon\leq 1$.

The draft also addresses the optimality of the exponent, the four-dimensional exponent $11$, and an anticanonical interpolation estimate. Precise statements, assumptions, and proofs are in the manuscript.

## Files

| File | Contents |
| --- | --- |
| `main.pdf` | Compiled manuscript, 30 pages |
| `main.tex` | LaTeX source, including the bibliography |
| `CITATION.bib` | Bibliographic entry for this working draft |
| `SHA256SUMS.txt` | SHA-256 checksums for the manuscript source and PDF |

## Compilation

Use a TeX installation with `latexmk` and the packages listed in `main.tex`:

```sh
latexmk -pdf -no-shell-escape -interaction=nonstopmode -halt-on-error main.tex
```

The bibliography is embedded in the source; a separate `.bib` file is not needed for compilation.

## Citation and feedback

Please cite all three authors and identify the manuscript as a working draft. The entry in `CITATION.bib` records the manuscript date. When citing a specific online version, also include its repository URL and release tag or commit identifier.

Comments and corrections are welcome through repository issues.
