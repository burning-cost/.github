# Burning Cost

Open-source Python libraries for UK personal lines insurance pricing.

## What we build

Emblem and Radar handle GLM workhorse modelling well. We build the tools that sit around them: causal inference for rate change decomposition, conformal prediction intervals for Tweedie and Poisson models, proxy discrimination auditing under FCA EP25/2 and Consumer Duty, exposure-weighted drift detection, and GBM-to-GLM distillation for rating engines.

Each library installs with a single `pip install`, ships with CatBoost and Polars as defaults, and runs on Databricks serverless without configuration. Every package includes a worked notebook on synthetic insurance data.

## Flagship libraries

| Package | Description | Version |
|---------|-------------|---------|
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | FCA proxy discrimination auditing (EP25/2, Consumer Duty, Equality Act 2010) | ![PyPI](https://img.shields.io/pypi/v/insurance-fairness) |
| [insurance-governance](https://github.com/burning-cost/insurance-governance) | PRA SS1/23 model validation reports, model risk management | ![PyPI](https://img.shields.io/pypi/v/insurance-governance) |
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | Double ML causal inference with CatBoost nuisance models | ![PyPI](https://img.shields.io/pypi/v/insurance-causal) |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Conformal prediction intervals for Tweedie and Poisson models | ![PyPI](https://img.shields.io/pypi/v/insurance-conformal) |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Exposure-weighted drift detection (PSI, CSI, A/E, sequential testing) | ![PyPI](https://img.shields.io/pypi/v/insurance-monitoring) |
| [insurance-whittaker](https://github.com/burning-cost/insurance-whittaker) | Whittaker-Henderson smoothing — REML lambda, Bayesian CIs | ![PyPI](https://img.shields.io/pypi/v/insurance-whittaker) |
| [insurance-telematics](https://github.com/burning-cost/insurance-telematics) | HMM telematics risk scoring — trip-level sensor data to GLM features | ![PyPI](https://img.shields.io/pypi/v/insurance-telematics) |
| [insurance-credibility](https://github.com/burning-cost/insurance-credibility) | Bühlmann-Straub and Bayesian experience rating | ![PyPI](https://img.shields.io/pypi/v/insurance-credibility) |
| [insurance-frequency-severity](https://github.com/burning-cost/insurance-frequency-severity) | Sarmanov copula joint frequency-severity — analytical premium correction | ![PyPI](https://img.shields.io/pypi/v/insurance-frequency-severity) |
| [insurance-gam](https://github.com/burning-cost/insurance-gam) | EBM tariffs, Actuarial NAM, Pairwise Interaction Networks, exact Shapley | ![PyPI](https://img.shields.io/pypi/v/insurance-gam) |

We publish 34 libraries in total — see the [full list](https://burning-cost.github.io/tools/).

## Resources

- [Website](https://burning-cost.github.io) — 121 articles on pricing methodology
- [Blog](https://burning-cost.github.io/blog/) — worked examples and technique write-ups
- [47 Databricks notebooks](https://github.com/burning-cost/burning-cost-examples) — benchmarked against standard approaches
- [PyPI](https://pypi.org/user/burning-cost/) — all packages on PyPI
- [Getting started](https://burning-cost.github.io/getting-started/) — install and run your first model in five minutes
