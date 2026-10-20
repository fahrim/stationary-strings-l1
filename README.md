# Stationary Strings Letter 1 — Sodium-22 Positronium Laboratory Test

> **Türkçe:** [README_TR.md](./README_TR.md)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)

**SS-L1: The Three-Photon Positronium Spectrum — a Correction to arXiv:2605.21289 Eq. (12) and a One-Hour Laboratory Test**

Author: Fahri Meral · Date: October 20, 2026 · Version: v1 (SS-L1)

> **Status:** Unpublished preprint (v1). Not peer-reviewed. *[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23517487-blue.svg)](https://doi.org/10.5281/zenodo.23517487)*

## The claim in one paragraph

The ortho-positronium three-photon spectrum published as Eq. (12) of
arXiv:2605.21289 is the **log-free** 1949 Ore–Powell expression. It is
unnormalised (∫₁⁵¹¹ Ω dE = 2343.47 instead of 1) and diverges as E⁻² at
low energy, i.e. it predicts more low-energy photons than the annihilation
can produce. The correct form carries the original ln(1−x) factors, is
exactly normalised (∫₀⁵¹¹ Ω dE = 1 to 5×10⁻¹³) and vanishes as
Ω(x) ~ (5/3)x. A **one-hour** measurement with a 5 µCi ²²Na source, a
silica aerogel and a small HPGe detector separates the two forms by
**7.8×10⁵ standard deviations** in the band ratio
R = N[10,100] / N[350,490].

## What is and is not claimed

- **Claimed:** the published equation is wrong, and the correction is
  justified by a term-by-term source audit against the 1949 original.
- **Not claimed:** that the measurement has been performed. It has not.
  The table in the paper gives the **predicted** outcome of the proposed
  protocol so that the test can be executed and compared.
- **Independent of the rest of the series:** no model, lock or ansatz of
  Theorems I–X or Stationary Strings XII–XIV enters this letter. That is
  why it is submitted separately.

## Contents

| File | Description |
|---|---|
| `paper/stationary_strings_L1_na22_EN.tex` | Letter, English (Table 1, 6 sections) |
| `paper/stationary_strings_L1_na22_TR.tex` | Turkish version |
| `CITATION.cff` | Citation record |
| `LICENSE` | CC BY 4.0 |

The numerical machinery (`duran_sicimler_sim/na22_experiment.py` in the
[`stationary-strings-v`](https://github.com/fahrim/stationary-strings-v)
repository) computes the three candidate spectra, the band integrals,
the detected counts and the separation statistics.

## Citation

```bibtex
@misc{meral2026na22,
  author = {Fahri Meral},
  title  = {The Three-Photon Positronium Spectrum: a Correction to arXiv:2605.21289 Eq. (12) and a One-Hour Laboratory Test},
  year   = {2026},
  url    = {https://github.com/fahrim/stationary-strings-l1},
  doi    = {10.5281/zenodo.23517487},
}
```

See also `CITATION.cff`.

## License

CC BY 4.0 — see `LICENSE`. Content is not peer-reviewed.
