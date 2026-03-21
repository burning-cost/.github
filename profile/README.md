# Burning Cost

Open-source Python libraries for UK personal lines insurance pricing. Techniques from data science and quantitative finance that Emblem and Radar can't do.

10 flagship libraries · 34 packages on [PyPI](https://pypi.org/user/burning-cost/) · 15,000+ monthly downloads · [115 articles](https://burning-cost.github.io)

---

## Flagships

### Build Better Models

| Library | What it does |
|---------|-------------|
| [shap-relativities](https://github.com/burning-cost/shap-relativities) | Extract GLM-style factor tables from CatBoost — SHAP-based relativities for Radar/Emblem |
| [insurance-gam](https://github.com/burning-cost/insurance-gam) | EBM and Actuarial NAM — non-linear shape functions with exact Shapley interpretability |
| [insurance-distill](https://github.com/burning-cost/insurance-distill) | GBM-to-GLM distillation — surrogate factor tables for rating engines |
| [insurance-distributional](https://github.com/burning-cost/insurance-distributional) | Distributional GBM — TweedieGBM, GammaGBM, ZIPGBM for per-risk volatility |
| [insurance-cv](https://github.com/burning-cost/insurance-cv) | Temporal cross-validation that respects policy time structure and IBNR lag |

### Deploy and Monitor

| Library | What it does |
|---------|-------------|
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Exposure-weighted PSI/CSI, segmented A/E, sequential A/B testing, PIT calibration |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Distribution-free prediction intervals with finite-sample coverage guarantees |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained rate optimisation — SLSQP, Pareto frontier, FCA ENBP constraints |

### Regulatory Compliance

| Library | What it does |
|---------|-------------|
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | FCA proxy discrimination auditing — Consumer Duty, EP25/2, Equality Act 2010 |
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | DML causal inference — deconfounding, price elasticity, causal forests for HTE |

---

Plus 24 specialist libraries for [spatial rating](https://github.com/burning-cost/insurance-spatial), [severity modelling](https://github.com/burning-cost/insurance-severity), [telematics](https://github.com/burning-cost/insurance-telematics), [credibility](https://github.com/burning-cost/insurance-credibility), [Bayesian pricing](https://github.com/burning-cost/bayesian-pricing), and more. [Full list →](https://burning-cost.github.io/tools/)

## Quick Start

```bash
pip install shap-relativities
```

```python
from shap_relativities import ShapRelativities

sr = ShapRelativities(model, X_train)
factors = sr.factor_table("driver_age", bins=5)
print(factors)  # relativity table ready for Radar/Emblem
```

---

## Resources

- [Getting started](https://burning-cost.github.io/getting-started/) — install, first model, first audit
- [39 Databricks notebooks](https://github.com/burning-cost/burning-cost-examples) — every library benchmarked against standard techniques
- [Full library list](https://burning-cost.github.io/tools/) — all 34 packages with use cases and benchmarks
- [API docs](https://burning-cost.github.io/insurance-fairness/) — pdoc reference for each flagship
- [Blog](https://burning-cost.github.io) — 115 articles on pricing methodology

---

Every library benchmarked on Databricks against standard techniques. Built by pricing practitioners.
