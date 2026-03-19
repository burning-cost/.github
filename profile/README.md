# Burning Cost

Open-source Python libraries for UK personal lines insurance pricing. Techniques from data science and quantitative finance that Emblem and Radar can't do.

10 flagship libraries · 37 total on [PyPI](https://pypi.org/user/burning-cost/) · 107 articles at [burning-cost.github.io](https://burning-cost.github.io)

---

## Regulatory Compliance

| Library | Problem it solves |
|---------|-------------------|
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | Proxy discrimination auditing for FCA Consumer Duty and Equality Act 2010 |
| [insurance-governance](https://github.com/burning-cost/insurance-governance) | PRA SS1/23 model validation reports and model risk management |

## Causal Inference

| Library | Problem it solves |
|---------|-------------------|
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | DML deconfounding - isolate the true effect of a rating factor |
| [insurance-causal-policy](https://github.com/burning-cost/insurance-causal-policy) | Synthetic diff-in-diffs for causal rate change evaluation |
| [insurance-elasticity](https://github.com/burning-cost/insurance-elasticity) | DR-Learner and CausalForest for causal price elasticity estimation |
| [insurance-demand](https://github.com/burning-cost/insurance-demand) | Conversion, retention, and DML price elasticity in one pipeline |

## Smoothing and Experience Rating

| Library | Problem it solves |
|---------|-------------------|
| [insurance-whittaker](https://github.com/burning-cost/insurance-whittaker) | REML-optimal smoothing for rating tables - replaces manual Excel lambda |
| [insurance-credibility](https://github.com/burning-cost/insurance-credibility) | Buhlmann-Straub credibility for thin segments and scheme effects |
| [experience-rating](https://github.com/burning-cost/experience-rating) | Fleet experience modification factors and NCD/bonus-malus |

## Advanced Modelling

| Library | Problem it solves |
|---------|-------------------|
| [insurance-gam](https://github.com/burning-cost/insurance-gam) | EBM and Actuarial NAM - non-linear shape functions with exact interpretability |
| [insurance-distributional-glm](https://github.com/burning-cost/insurance-distributional-glm) | GAMLSS in Python - model variance, shape, and tail as functions of covariates |
| [insurance-frequency-severity](https://github.com/burning-cost/insurance-frequency-severity) | Sarmanov copula joint modelling - corrects the independence assumption |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Distribution-free prediction intervals with finite-sample coverage guarantees |
| [insurance-conformal-ts](https://github.com/burning-cost/insurance-conformal-ts) | Conformal prediction intervals for non-exchangeable claims time series |
| [insurance-distill](https://github.com/burning-cost/insurance-distill) | GBM-to-GLM distillation for Radar/Emblem - transferability without interpretability loss |

## Telematics

| Library | Problem it solves |
|---------|-------------------|
| [insurance-telematics](https://github.com/burning-cost/insurance-telematics) | HMM latent-state features from trip-level sensor data |

---

## Quick Start

```bash
pip install insurance-fairness
```

```python
from insurance_fairness import FairnessAudit

audit = FairnessAudit(
    protected_col="gender",
    outcome_col="claim_cost",
    exposure_col="exposure",
)
report = audit.run(df, model)
print(report.summary())  # RAG status, proxy R², calibration by group
```

---

## Resources

- [Getting started](https://burning-cost.github.io/getting-started/) - install, first model, first audit
- [35 Databricks notebooks](https://github.com/burning-cost/burning-cost-examples) - benchmarked against standard approaches
- [Full library list](https://burning-cost.github.io/tools/) - all 37 libraries with use cases
- [API docs](https://burning-cost.github.io/insurance-fairness/) - pdoc references for flagship libraries
- [Blog](https://burning-cost.github.io) - 107 articles on pricing methodology

---

Every library benchmarked on Databricks against standard techniques. Built by pricing practitioners.
