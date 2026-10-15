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
