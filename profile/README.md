# Burning Cost

Open-source Python libraries for UK personal lines insurance pricing. Techniques from data science and quantitative finance that Emblem and Radar can't do.

36 libraries on [PyPI](https://pypi.org/user/burning-cost/) · 74 articles at [burning-cost.github.io](https://burning-cost.github.io)

---

## Quick Start

```bash
pip install shap-relativities
```

```python
from shap_relativities import SHAPRelativities
from catboost import CatBoostRegressor

model = CatBoostRegressor().fit(X_train, y_train)
rel = SHAPRelativities(model, base_values={"age_band": "30-35"})
print(rel.fit(X).relativities_)
```

---

## Core Libraries

| Library | What it does | Install |
|---------|-------------|---------|
| [shap-relativities](https://github.com/burning-cost/shap-relativities) | SHAP-based rating relativities from GBM models | `pip install shap-relativities` |
| [insurance-cv](https://github.com/burning-cost/insurance-cv) | Temporal cross-validation respecting policy time structure | `pip install insurance-cv` |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Exposure-weighted PSI/CSI, A/E ratios, Gini drift | `pip install insurance-monitoring` |
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | Proxy discrimination auditing, FCA EP25/2 | `pip install insurance-fairness` |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained rate optimisation, FCA ENBP enforcement | `pip install insurance-optimise` |
| [insurance-governance](https://github.com/burning-cost/insurance-governance) | PRA SS1/23 model validation and risk management | `pip install insurance-governance` |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Distribution-free prediction intervals for Tweedie/Poisson | `pip install insurance-conformal` |
| [insurance-causal-policy](https://github.com/burning-cost/insurance-causal-policy) | SDID for causal rate change evaluation | `pip install insurance-causal-policy` |
| [insurance-elasticity](https://github.com/burning-cost/insurance-elasticity) | Causal price elasticity with double machine learning | `pip install insurance-elasticity` |
| [insurance-spatial](https://github.com/burning-cost/insurance-spatial) | BYM2 territory ratemaking with PyMC 5 | `pip install insurance-spatial` |

---

## Resources

- [Getting started guide](https://burning-cost.github.io/getting-started/) — install, first model, first audit
- [Examples repo](https://github.com/burning-cost/burning-cost-examples) — worked notebooks on realistic synthetic data
- [Full library list](https://burning-cost.github.io/tools/) — all 36 libraries with use cases
- [Blog](https://burning-cost.github.io) — 74 articles on pricing methodology

---

Built by pricing practitioners, for pricing practitioners.
