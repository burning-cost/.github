# Burning Cost

Open-source Python libraries for UK personal lines insurance pricing.

## What we build

Emblem and Radar handle GLM workhorse modelling well. We build the tools that sit around them: causal inference for rate change decomposition, conformal prediction intervals for Tweedie and Poisson models, proxy discrimination auditing under FCA EP25/2 and Consumer Duty, exposure-weighted drift detection, and GBM-to-GLM distillation for rating engines.

Each library installs with a single `pip install`, ships with CatBoost and Polars as defaults, and runs on Databricks serverless without configuration. Every package includes a worked notebook on synthetic insurance data.

## Flagship libraries

| Package | Description | Version |
|---------|-------------|---------|
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | FCA proxy discrimination auditing (EP25/2, Consumer Duty) | ![PyPI](https://img.shields.io/pypi/v/insurance-fairness) |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Exposure-weighted drift detection (PSI, CSI, A/E, sequential testing) | ![PyPI](https://img.shields.io/pypi/v/insurance-monitoring) |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Conformal prediction intervals for Tweedie and Poisson models | ![PyPI](https://img.shields.io/pypi/v/insurance-conformal) |
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | Double ML causal inference with CatBoost nuisance models | ![PyPI](https://img.shields.io/pypi/v/insurance-causal) |
| [shap-relativities](https://github.com/burning-cost/shap-relativities) | SHAP-based rating relativities from GBM models | ![PyPI](https://img.shields.io/pypi/v/shap-relativities) |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained portfolio rate optimisation | ![PyPI](https://img.shields.io/pypi/v/insurance-optimise) |
| [insurance-deploy](https://github.com/burning-cost/insurance-deploy) | Champion/challenger deployment framework | ![PyPI](https://img.shields.io/pypi/v/insurance-deploy) |
| [insurance-distill](https://github.com/burning-cost/insurance-distill) | GBM-to-GLM distillation for rating engines | ![PyPI](https://img.shields.io/pypi/v/insurance-distill) |
| [insurance-cv](https://github.com/burning-cost/insurance-cv) | Temporal cross-validation for insurance models | ![PyPI](https://img.shields.io/pypi/v/insurance-cv) |
| [insurance-trend](https://github.com/burning-cost/insurance-trend) | Loss cost trend analysis with structural breaks | ![PyPI](https://img.shields.io/pypi/v/insurance-trend) |

We publish 34 libraries in total, covering severity modelling, credibility, spatial risk, copulas, survival models, GAMs, governance, and more. See the [full list](https://burning-cost.github.io/tools/).

## Resources

- [Website](https://burning-cost.github.io) — documentation and methodology notes
- [Blog](https://burning-cost.github.io/blog/) — worked examples and technique write-ups
- [PyPI](https://pypi.org/user/burning-cost/) — all packages on PyPI
- [Getting started](https://burning-cost.github.io/getting-started/) — install and run your first model in five minutes
