# S.T.A.R.-Labs — Interactive Binder Demonstrations

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LcosmosS/S.T.A.R.-Labs-Binder/main?urlpath=lab/tree/notebooks/00_welcome.ipynb)

Lightweight JupyterLab companion to [S.T.A.R.-Labs](https://github.com/LcosmosS/S.T.A.R.-Labs).

**Scientific status:** These notebooks are illustrative and exploratory. They are **not** registered controlled experiments, independent reproductions, or evidence for ACSC, ECC, GLMPCT, RTCH, cosmological correspondence, or the Birch–Swinnerton-Dyer conjecture. Refer to the main repository for authoritative protocols, registries, data provenance, and eligibility.

## Launch and use

Click **Launch Binder** above. The initial build may take several minutes. In JupyterLab, run **Run → Run All Cells**. Binder sessions are ephemeral; download any work you want to retain.

## Notebooks

- [00 — Welcome and environment smoke test](notebooks/00_welcome.ipynb)
- [01 — Synthetic arithmetic projection](notebooks/01_arithmetic_projection.ipynb)

## Lightweight environment

The root `requirements.txt` pins only NumPy and Matplotlib; Jupyter is supplied by the Binder base environment. Python 3.11 is requested in `runtime.txt`. No Git LFS objects, submodules, survey datasets, credentials, or controlled-experiment machinery are included.

## Research integrity

All examples are synthetic or pedagogical and have no inferential endpoint. No notebook execution should be reported as a registered scientific result. For controlled experiments, use the [canonical S.T.A.R.-Labs repository](https://github.com/LcosmosS/S.T.A.R.-Labs).

## Temporary research-themed demonstrations

The following five notebooks are **standalone pedagogical adaptations** of concepts appearing in the main repository. They are **not copies of the original scientific computations**. All inputs are synthetic, all outputs are non-evidentiary, and no registered experiment is executed. Source links and methodological limitations are stated inside each notebook.

1. [Logarithmic arithmetic projection](notebooks/02_projection_from_source.ipynb) — synthetic coordinate transform
2. [Scalar field and derivatives](notebooks/03_entropy_field_from_source.ipynb) — Gaussian toy field, not thermodynamic entropy
3. [Illustrative geodesics](notebooks/04_geodesics_from_source.ipynb) — great circles on a unit sphere, not spacetime
4. [Metric perturbations](notebooks/05_metric_perturbations_from_source.ipynb) — positive-definite matrix toy model, not gravitational field equations
5. [Topology-inspired stability](notebooks/06_tda_stability_from_source.ipynb) — distance-matrix sensitivity, **not** persistent homology

These demonstrations are intended to be replaced by independently reviewed scientific notebooks once their source data, software environment, reproducibility tests, and relevant protocol requirements are ready. Replacing a demonstration does not change any evidence or execution eligibility flag in the canonical research repository.
