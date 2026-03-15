# Burning Cost

Open-source Python libraries for UK personal lines insurance pricing. Techniques from data science and quantitative finance that Emblem and Radar can't do.

10 flagship libraries · 36 total on [PyPI](https://pypi.org/user/burning-cost/) · 80+ articles at [burning-cost.github.io](https://burning-cost.github.io)

---

## Regulatory Compliance

| Library | Problem it solves |
|---------|-------------------|
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | Proxy discrimination auditing for FCA EP25/2 and Consumer Duty |
| [insurance-governance](https://github.com/burning-cost/insurance-governance) | PRA SS1/23 model validation reports and model risk management |

## Causal Inference

| Library | Problem it solves |
|---------|-------------------|
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | DML deconfounding - isolate the true effect of a rating factor |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Distribution-free prediction intervals that actually cover |

## Smoothing and Experience Rating

| Library | Problem it solves |
|---------|-------------------|
| [insurance-whittaker](https://github.com/burning-cost/insurance-whittaker) | REML-optimal smoothing for rating tables - replaces manual Excel lambda |
| [insurance-credibility](https://github.com/burning-cost/insurance-credibility) | Buhlmann-Straub credibility for thin segments and scheme effects |

## Advanced Modelling

| Library | Problem it solves |
|---------|-------------------|
| [insurance-gam](https://github.com/burning-cost/insurance-gam) | EBM and Actuarial NAM - non-linear shape functions with exact interpretability |
| [insurance-distributional-glm](https://github.com/burning-cost/insurance-distributional-glm) | GAMLSS in Python - model variance, shape, and tail as functions of covariates |
| [insurance-frequency-severity](https://github.com/burning-cost/insurance-frequency-severity) | Sarmanov copula joint modelling - corrects the independence assumption |

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
from insurance_fairness import ProxyDetector

detector = ProxyDetector(protected="gender")
report = detector.fit(X_train, model)
print(report.proxy_scores_)  # Gini, MI, SHAP for every feature
```

---

## Resources

- [Getting started](https://burning-cost.github.io/getting-started/) - install, first model, first audit
- [35 Databricks notebooks](https://github.com/burning-cost/burning-cost-examples) - benchmarked against standard approaches
- [Full library list](https://burning-cost.github.io/tools/) - all 36 libraries with use cases
- [API docs](https://burning-cost.github.io/insurance-fairness/) - pdoc references for flagship libraries
- [Blog](https://burning-cost.github.io) - 80+ articles on pricing methodology

---

Every library benchmarked on Databricks against standard techniques. Built by pricing practitioners.
