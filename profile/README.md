# Burning Cost

Python tools for UK personal lines pricing teams. Each library fills a gap that Emblem, Radar, and Excel can't — with Databricks notebooks showing the full workflow on realistic synthetic data.

**Start here:** [burning-cost.github.io](https://burning-cost.github.io)

---

## Where to Start

| Library | What it does |
|---------|-------------|
| [shap-relativities](https://github.com/burning-cost/shap-relativities) | Extract GLM-style rating factors from any GBM |
| [insurance-cv](https://github.com/burning-cost/insurance-cv) | Temporal cross-validation that respects policy time structure |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Drift detection — exposure-weighted PSI/CSI, A/E, Gini drift |
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | FCA proxy discrimination auditing and correction |
| [insurance-datasets](https://github.com/burning-cost/insurance-datasets) | Synthetic UK motor data with known DGP for validation |

## Modelling

| Library | What it does |
|---------|-------------|
| [insurance-gam](https://github.com/burning-cost/insurance-gam) | Interpretable GAMs — EBM tariffs, Actuarial NAM, PIN |
| [insurance-glm-tools](https://github.com/burning-cost/insurance-glm-tools) | GLM factor clustering (R2VF) + neural territory embeddings |
| [insurance-interactions](https://github.com/burning-cost/insurance-interactions) | Automated GLM interaction detection (CANN + NID + SHAP) |
| [insurance-multilevel](https://github.com/burning-cost/insurance-multilevel) | CatBoost + REML random effects for broker/scheme groups |
| [bayesian-pricing](https://github.com/burning-cost/bayesian-pricing) | Hierarchical Bayesian models for thin-data segments |
| [insurance-spatial](https://github.com/burning-cost/insurance-spatial) | BYM2 spatial territory ratemaking |
| [insurance-distributional](https://github.com/burning-cost/insurance-distributional) | Distributional GBMs (Tweedie, Gamma, ZIP, NB) |
| [insurance-distributional-glm](https://github.com/burning-cost/insurance-distributional-glm) | GAMLSS for Python — model variance as a function of covariates |
| [insurance-quantile](https://github.com/burning-cost/insurance-quantile) | Quantile GBM for tail risk — TVaR, ILF, large loss loading |
| [insurance-trend](https://github.com/burning-cost/insurance-trend) | Loss cost trend with structural break detection |
| [insurance-whittaker](https://github.com/burning-cost/insurance-whittaker) | Whittaker-Henderson smoothing with REML lambda selection |
| [insurance-severity](https://github.com/burning-cost/insurance-severity) | Composite severity + distributional refinement networks |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Distribution-free prediction intervals for pricing models |
| [insurance-frequency-severity](https://github.com/burning-cost/insurance-frequency-severity) | Sarmanov copula joint freq-sev modelling |
| [insurance-zit-dglm](https://github.com/burning-cost/insurance-zit-dglm) | Zero-inflated Tweedie double GLM |
| [insurance-dispersion](https://github.com/burning-cost/insurance-dispersion) | Double GLM for joint mean-dispersion modelling |
| [insurance-dynamics](https://github.com/burning-cost/insurance-dynamics) | GAS score-driven models + Bayesian changepoint detection |
| [insurance-credibility](https://github.com/burning-cost/insurance-credibility) | Buhlmann-Straub classical credibility |

## Causal Inference

| Library | What it does |
|---------|-------------|
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | Double ML for confounding-robust rating factors |
| [insurance-causal-policy](https://github.com/burning-cost/insurance-causal-policy) | SDID for rate change evaluation with FCA evidence packs |
| [insurance-uplift](https://github.com/burning-cost/insurance-uplift) | HTE uplift modelling for retention targeting |

## Model Lifecycle

| Library | What it does |
|---------|-------------|
| [insurance-governance](https://github.com/burning-cost/insurance-governance) | PRA SS1/23 validation reports + model risk management |
| [insurance-deploy](https://github.com/burning-cost/insurance-deploy) | Champion/challenger framework with audit trail |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained rate optimisation + efficient frontier |
| [insurance-covariate-shift](https://github.com/burning-cost/insurance-covariate-shift) | Density ratio correction for portfolio drift |

## Specialist

| Library | What it does |
|---------|-------------|
| [insurance-survival](https://github.com/burning-cost/insurance-survival) | Cure models, CLV, lapse tables |
| [insurance-telematics](https://github.com/burning-cost/insurance-telematics) | HMM telematics risk scoring |
| [insurance-thin-data](https://github.com/burning-cost/insurance-thin-data) | Transfer learning + TabPFN for thin segments |
| [insurance-synthetic](https://github.com/burning-cost/insurance-synthetic) | Vine copula synthetic portfolio generation |

---

30+ libraries on [PyPI](https://pypi.org/user/burning-cost/) · 100 tutorials at [burning-cost.github.io](https://burning-cost.github.io)

Built by pricing practitioners, for pricing practitioners.
