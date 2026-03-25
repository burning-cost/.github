# Burning Cost

Open-source Python libraries for UK personal lines insurance pricing.

## What we build

Emblem and Radar handle GLM workhorse modelling well. We build the tools that sit around them: causal inference for rate change decomposition, conformal prediction intervals for Tweedie and Poisson models, proxy discrimination auditing under FCA EP25/2 and Consumer Duty, exposure-weighted drift detection, and GBM-to-GLM distillation for rating engines.

Each library installs with a single `pip install`, ships with CatBoost and Polars as defaults, and runs on Databricks serverless without configuration. Every package includes a worked notebook on synthetic insurance data.

## Flagship libraries

| Package | What it does | Downloads/month |
|---------|-------------|-----------------|
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | Double ML causal inference with CatBoost nuisance models | 1,551 |
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | FCA proxy discrimination auditing (EP25/2, Consumer Duty, Equality Act 2010) | 1,434 |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Exposure-weighted drift detection (PSI, CSI, A/E, sequential testing) | 1,135 |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Conformal prediction intervals for Tweedie and Poisson models | ![PyPI](https://img.shields.io/pypi/v/insurance-conformal) |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained portfolio rate optimisation with FCA ENBP compliance | 875 |
| [insurance-gam](https://github.com/burning-cost/insurance-gam) | EBM tariffs, Actuarial NAM, PIN, exact Shapley values | 803 |
| [insurance-credibility](https://github.com/burning-cost/insurance-credibility) | Buhlmann-Straub and Bayesian experience rating | 741 |
| [insurance-frequency-severity](https://github.com/burning-cost/insurance-frequency-severity) | Sarmanov copula joint frequency-severity modelling | 677 |
| [insurance-whittaker](https://github.com/burning-cost/insurance-whittaker) | Whittaker-Henderson smoothing with REML lambda and Bayesian CIs | ![PyPI](https://img.shields.io/pypi/v/insurance-whittaker) |
| [insurance-telematics](https://github.com/burning-cost/insurance-telematics) | HMM telematics risk scoring from trip-level sensor data | ![PyPI](https://img.shields.io/pypi/v/insurance-telematics) |

22,600+ downloads/month across 34 published packages. Every library includes Databricks notebooks, benchmarks against standard techniques, and honest limitations sections.

## Resources

- [Website](https://burning-cost.github.io) — 130+ articles on pricing methodology
- [Blog](https://burning-cost.github.io/blog/) — worked examples and technique write-ups
- [Databricks notebooks](https://github.com/burning-cost/burning-cost-examples) — benchmarked against standard approaches
- [PyPI](https://pypi.org/user/burning-cost/) — all packages on PyPI
- [Libraries](https://burning-cost.github.io/libraries/) — documentation, API reference, and expected performance for all flagships
