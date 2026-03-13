# Burning Cost

Python libraries for UK personal lines pricing teams. Each library ships with a Databricks notebook showing the full workflow on realistic synthetic data.

---

## Core Modelling

| Library | Description |
|---------|-------------|
| [shap-relativities](https://github.com/burning-cost/shap-relativities) | SHAP-based rating relativities from GBMs |
| [insurance-gam](https://github.com/burning-cost/insurance-gam) | Interpretable GAMs — EBM tariffs, Actuarial NAM, PIN |
| [insurance-glm-tools](https://github.com/burning-cost/insurance-glm-tools) | GLM category clustering (R2VF) + neural embeddings for territory |
| [insurance-interactions](https://github.com/burning-cost/insurance-interactions) | Automated GLM interaction detection (CANN + NID + SHAP) |
| [insurance-multilevel](https://github.com/burning-cost/insurance-multilevel) | CatBoost + REML random effects for high-cardinality groups |
| [bayesian-pricing](https://github.com/burning-cost/bayesian-pricing) | Hierarchical Bayesian models for thin-data segments |
| [insurance-spatial](https://github.com/burning-cost/insurance-spatial) | BYM2 spatial territory ratemaking |
| [insurance-distributional](https://github.com/burning-cost/insurance-distributional) | Distributional GBMs (Tweedie, Gamma, ZIP, NB) |
| [insurance-distributional-glm](https://github.com/burning-cost/insurance-distributional-glm) | GAMLSS for Python — model variance and shape as functions of covariates |
| [insurance-dispersion](https://github.com/burning-cost/insurance-dispersion) | Double GLM for joint mean-dispersion modelling |
| [insurance-quantile](https://github.com/burning-cost/insurance-quantile) | Quantile GBM + EQRN for tail risk |
| [insurance-ilf](https://github.com/burning-cost/insurance-ilf) | MBBEFD exposure curves and ILF tables |
| [insurance-conformal](https://github.com/burning-cost/insurance-conformal) | Conformal prediction — intervals, risk control, claims, multivariate |
| [insurance-conformal-ts](https://github.com/burning-cost/insurance-conformal-ts) | Conformal prediction for non-exchangeable claims time series |
| [insurance-trend](https://github.com/burning-cost/insurance-trend) | Loss cost trend with structural break detection |
| [insurance-whittaker](https://github.com/burning-cost/insurance-whittaker) | Whittaker-Henderson smoothing with REML lambda selection |
| [insurance-severity](https://github.com/burning-cost/insurance-severity) | Composite severity + distributional refinement networks |
| [insurance-nflow](https://github.com/burning-cost/insurance-nflow) | Normalizing flows for severity modelling |
| [insurance-evt](https://github.com/burning-cost/insurance-evt) | Extreme value theory for catastrophic claims |
| [insurance-frequency-severity](https://github.com/burning-cost/insurance-frequency-severity) | Sarmanov copula joint freq-sev + neural dependent two-part models |
| [insurance-zit-dglm](https://github.com/burning-cost/insurance-zit-dglm) | Zero-inflated Tweedie double GLM |
| [insurance-poisson-mixture-nn](https://github.com/burning-cost/insurance-poisson-mixture-nn) | Neural Poisson mixture for structural zero-claimers |
| [insurance-dynamics](https://github.com/burning-cost/insurance-dynamics) | GAS score-driven models + Bayesian changepoint detection |
| [insurance-garch](https://github.com/burning-cost/insurance-garch) | GARCH volatility for claims inflation |
| [insurance-scmoe](https://github.com/burning-cost/insurance-scmoe) | Spatially Clustered Mixture of Experts |
| [insurance-nowcast](https://github.com/burning-cost/insurance-nowcast) | ML-EM nowcasting for claims reporting delays |

## Credibility & Experience Rating

| Library | Description |
|---------|-------------|
| [insurance-credibility](https://github.com/burning-cost/insurance-credibility) | Bühlmann-Straub classical credibility + experience rating |
| [insurance-experience](https://github.com/burning-cost/insurance-experience) | Individual Bayesian posterior experience rating |
| [insurance-credibility-transformer](https://github.com/burning-cost/insurance-credibility-transformer) | Transformer with CLS credibility token |

## Causal Inference & Elasticity

| Library | Description |
|---------|-------------|
| [insurance-causal](https://github.com/burning-cost/insurance-causal) | DML + automatic debiased ML + causal elasticity |
| [insurance-causal-policy](https://github.com/burning-cost/insurance-causal-policy) | SDID for rate change evaluation |
| [insurance-tmle](https://github.com/burning-cost/insurance-tmle) | Targeted Maximum Likelihood Estimation |
| [insurance-bcf](https://github.com/burning-cost/insurance-bcf) | Bayesian Causal Forests |
| [insurance-counterfactual-sets](https://github.com/burning-cost/insurance-counterfactual-sets) | Conformal ITE for individual counterfactuals |
| [insurance-mediation](https://github.com/burning-cost/insurance-mediation) | Causal mediation for proxy discrimination |

## Fairness & Regulation

| Library | Description |
|---------|-------------|
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | Proxy discrimination auditing + OT correction + diagnostics |
| [insurance-fair-longterm](https://github.com/burning-cost/insurance-fair-longterm) | Multi-state fairness for long-term pricing |
| [insurance-recourse](https://github.com/burning-cost/insurance-recourse) | Algorithmic recourse for Consumer Duty |
| [insurance-rdd](https://github.com/burning-cost/insurance-rdd) | Regression discontinuity for rating thresholds |
| [insurance-bunching](https://github.com/burning-cost/insurance-bunching) | Bunching estimators for threshold gaming |

## Optimisation & Strategy

| Library | Description |
|---------|-------------|
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained rate optimisation + demand modelling |
| [insurance-dro](https://github.com/burning-cost/insurance-dro) | Distributionally robust rate optimisation |
| [insurance-online](https://github.com/burning-cost/insurance-online) | Bandit algorithms for GIPP-compliant pricing |
| [insurance-uplift](https://github.com/burning-cost/insurance-uplift) | HTE uplift modelling for retention |

## Model Lifecycle

| Library | Description |
|---------|-------------|
| [insurance-cv](https://github.com/burning-cost/insurance-cv) | Temporal cross-validation |
| [insurance-governance](https://github.com/burning-cost/insurance-governance) | PRA SS1/23 validation + model risk management |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Drift detection + calibration testing |
| [insurance-deploy](https://github.com/burning-cost/insurance-deploy) | Champion/challenger framework |
| [insurance-conformal-fraud](https://github.com/burning-cost/insurance-conformal-fraud) | Conformal anomaly detection for claims fraud |
| [insurance-sensitivity](https://github.com/burning-cost/insurance-sensitivity) | Global sensitivity analysis (Shapley effects) |
| [insurance-reconcile](https://github.com/burning-cost/insurance-reconcile) | Hierarchical forecast reconciliation |
| [insurance-covariate-shift](https://github.com/burning-cost/insurance-covariate-shift) | Density ratio correction for book shifts |
| [insurance-lda-risk](https://github.com/burning-cost/insurance-lda-risk) | LDA operational risk |

## Survival

| Library | Description |
|---------|-------------|
| [insurance-survival](https://github.com/burning-cost/insurance-survival) | Survival models + cure models + competing risks + recurrent events |
| [insurance-jlm](https://github.com/burning-cost/insurance-jlm) | Joint longitudinal-survival for telematics repricing |

## Thin Data

| Library | Description |
|---------|-------------|
| [insurance-thin-data](https://github.com/burning-cost/insurance-thin-data) | Transfer learning + TabPFN foundation models |
| [insurance-copula](https://github.com/burning-cost/insurance-copula) | Vine copulas for multi-peril pricing |

## Data

| Library | Description |
|---------|-------------|
| [insurance-synthetic](https://github.com/burning-cost/insurance-synthetic) | Vine copula synthetic portfolio generation |
| [insurance-datasets](https://github.com/burning-cost/insurance-datasets) | Synthetic UK motor data with known DGP |
| [insurance-telematics](https://github.com/burning-cost/insurance-telematics) | HMM telematics risk scoring |

---

59 libraries on [PyPI](https://pypi.org/user/burning-cost/) · 100 tutorials at [burning-cost.github.io](https://burning-cost.github.io)

Built by pricing practitioners, for pricing practitioners.
