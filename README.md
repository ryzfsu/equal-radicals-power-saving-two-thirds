# A power saving below two-thirds for equal radicals of consecutive products

Ruiyi Zhang

DOI: [10.5281/zenodo.24021501](https://doi.org/10.5281/zenodo.24021501)

Let `rad(r)` be the product of the distinct primes dividing `r`, and let

    F(X) = #{(m, n) : 1 <= m < n <= X, rad(m(m+1)) = rad(n(n+1))}.

Main theorem: for every `eps > 0`,

    F(X) << X^(109/165 + eps).

This improves the exponent `2/3` of the author's earlier paper
*Equal radicals of consecutive products* (https://doi.org/10.5281/zenodo.23758120);
`109/165 = 2/3 - 1/165`.

The proof uses four-corner gcd coordinates and a first-match partition of the pairs
into thirteen classes. The classes are bounded by divisor and lattice counts, a
uniform square-fibre bound, the determinant method (with Heath-Brown's bihomogeneous
lemma), the Bombieri-Schmidt bound for Thue equations, and, for the long-shift class,
ratio-cell determinants with an exact linear-programming cap. The 72 exact rational
dual certificates of that linear program are printed in Appendix D.

## Contents

- `main.pdf` (61 pages)
- `source/` - LaTeX source: `main.tex` and the section files in `source/sections/`
- `SHA256SUMS`

## Build

    cd source
    pdflatex main.tex
    pdflatex main.tex
    pdflatex main.tex

## Citation

Ruiyi Zhang, *A power saving below two-thirds for equal radicals of consecutive products*, preprint, Zenodo, 2026. https://doi.org/10.5281/zenodo.24021501

```bibtex
@misc{zhang2026powersaving,
  author    = {Zhang, Ruiyi},
  title     = {A power saving below two-thirds for equal radicals of consecutive products},
  year      = {2026},
  publisher = {Zenodo},
  note      = {Preprint},
  doi       = {10.5281/zenodo.24021501},
  url       = {https://doi.org/10.5281/zenodo.24021501}
}
```
