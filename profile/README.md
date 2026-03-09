# Burning Cost

Open-source pricing tools for UK personal lines insurance.

We apply techniques from data science and quantitative finance to insurance pricing problems that practitioners actually face — not the toy examples in textbooks. Everything ships as a Python library with Databricks tutorials showing the full workflow on realistic synthetic data.

---

## Libraries

### Model Building

| Library | Description |
|---------|-------------|
| [shap-relativities](https://github.com/burning-cost/shap-relativities) | Extract GLM-style rating factors from GBMs via SHAP |
| [insurance-interactions](https://github.com/burning-cost/insurance-interactions) | Automated GLM interaction detection (CANN + NID + SHAP) |
| [insurance-multilevel](https://github.com/burning-cost/insurance-multilevel) | CatBoost + REML random effects for high-cardinality groups |
| [bayesian-pricing](https://github.com/burning-cost/bayesian-pricing) | Hierarchical Bayesian models for thin-data segments |
| [credibility](https://github.com/burning-cost/credibility) | Bühlmann-Straub credibility weighting |
| [insurance-spatial](https://github.com/burning-cost/insurance-spatial) | BYM2 spatial territory ratemaking |
| [insurance-distributional](https://github.com/burning-cost/insurance-distributional) | Distributional GBMs (Tweedie, Gamma, ZIP, NB) |
| [insurance-quantile](https://github.com/burning-cost/insurance-quantile) | Quantile GBM for tail risk and TVaR |
| [insurance-ilf](https://github.com/burning-cost/insurance-ilf) | MBBEFD exposure curves and ILF tables |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Conformal prediction intervals for Tweedie/Poisson |
| [insurance-trend](https://github.com/burning-cost/insurance-trend) | Loss cost trend analysis with structural break detection |
| [insurance-anam](https://github.com/burning-cost/insurance-anam) | Actuarial Neural Additive Model (interpretable deep learning) |

### Causal Inference & Elasticity

| Library | Description |
|---------|-------------|
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | DML for confounding bias in rating factors |
| [insurance-elasticity](https://github.com/burning-cost/insurance-elasticity) | Causal price elasticity via CausalForestDML |
| [insurance-demand](https://github.com/burning-cost/insurance-demand) | Conversion, retention, DML price elasticity |
| [insurance-causal-policy](https://github.com/burning-cost/insurance-causal-policy) | SDID for causal rate change evaluation |

### Model Lifecycle

| Library | Description |
|---------|-------------|
| [insurance-cv](https://github.com/burning-cost/insurance-cv) | Temporal cross-validation for insurance |
| [insurance-validation](https://github.com/burning-cost/insurance-validation) | PRA SS1/23 model validation reports |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Exposure-weighted drift detection |
| [insurance-deploy](https://github.com/burning-cost/insurance-deploy) | Champion/challenger framework with audit trail |
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | Proxy discrimination auditing (FCA EP25/2) |

### Optimisation & Data

| Library | Description |
|---------|-------------|
| [rate-optimiser](https://github.com/burning-cost/rate-optimiser) | Constrained rate optimisation with efficient frontier |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained portfolio rate optimisation |
| [insurance-survival](https://github.com/burning-cost/insurance-survival) | Survival models, cure rate, CLV |
| [experience-rating](https://github.com/burning-cost/experience-rating) | NCD/bonus-malus factors |
| [insurance-synthetic](https://github.com/burning-cost/insurance-synthetic) | Vine copula synthetic portfolio generation |
| [insurance-datasets](https://github.com/burning-cost/insurance-datasets) | Synthetic UK motor data with known DGP |

---

All libraries available on [PyPI](https://pypi.org/user/burning-cost/) · Blog and tutorials at [burning-cost.github.io](https://burning-cost.github.io)

Built by pricing actuaries, for pricing actuaries.
