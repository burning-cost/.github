# Burning Cost

On the forefront of machine learning and data science research in UK personal lines insurance. Helping teams adopt best practice, best-in-class tooling, and Databricks.

Everything ships as a Python library with Databricks tutorials showing the full workflow on realistic synthetic data.

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
| [insurance-nested-glm](https://github.com/burning-cost/insurance-nested-glm) | Nested GLMs with neural network embeddings for territory clustering |
| [insurance-ebm](https://github.com/burning-cost/insurance-ebm) | Explainable Boosting Machine wrapper with relativities and monotonicity editing |
| [insurance-whittaker](https://github.com/burning-cost/insurance-whittaker) | Whittaker-Henderson 1D/2D smoothing with REML lambda selection |
| [insurance-drn](https://github.com/burning-cost/insurance-drn) | Distributional Refinement Network - full predictive distributions from any baseline |
| [insurance-distributional-glm](https://github.com/burning-cost/insurance-distributional-glm) | GAMLSS for Python - model variance and shape as functions of covariates |
| [insurance-dispersion](https://github.com/burning-cost/insurance-dispersion) | Double GLM for joint mean-dispersion modelling — alternating IRLS, REML, actuarial factor tables |
| [insurance-composite](https://github.com/burning-cost/insurance-composite) | Composite severity regression — spliced body/tail with covariate-dependent threshold, ILF, TVaR |
| [insurance-telematics](https://github.com/burning-cost/insurance-telematics) | HMM/CTHMM telematics risk scoring with TripSimulator and credibility aggregation |
| [insurance-glm-cluster](https://github.com/burning-cost/insurance-glm-cluster) | R2VF factor level clustering — collapses high-cardinality categoricals into pricing bands |
| [insurance-sensitivity](https://github.com/burning-cost/insurance-sensitivity) | Shapley effects for rating factor variance decomposition |

### Experience Rating & Credibility

| Library | Description |
|---------|-------------|
| [experience-rating](https://github.com/burning-cost/experience-rating) | NCD/bonus-malus factors, Markov chains, claiming threshold optimisation |
| [insurance-experience](https://github.com/burning-cost/insurance-experience) | Individual Bayesian posterior experience rating — static/dynamic/surrogate/deep attention credibility |

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
| [insurance-calibration](https://github.com/burning-cost/insurance-calibration) | Balance testing, auto-calibration curves, Murphy score decomposition |
| [insurance-monitoring](https://github.com/burning-cost/insurance-monitoring) | Exposure-weighted drift detection |
| [insurance-deploy](https://github.com/burning-cost/insurance-deploy) | Champion/challenger framework with audit trail |
| [insurance-fairness](https://github.com/burning-cost/insurance-fairness) | Proxy discrimination auditing (FCA EP25/2) |
| [insurance-fairness-ot](https://github.com/burning-cost/insurance-fairness-ot) | Optimal transport discrimination-free pricing (Lindholm, Wasserstein barycenter) |
| [insurance-fairness-diag](https://github.com/burning-cost/insurance-fairness-diag) | D_proxy scalar, Shapley attribution of discrimination, per-policyholder vulnerability scores |
| [insurance-mrm](https://github.com/burning-cost/insurance-mrm) | Model risk management: ModelCard, inventory, risk tier scoring, governance reports |

### Optimisation & Data

| Library | Description |
|---------|-------------|
| [rate-optimiser](https://github.com/burning-cost/rate-optimiser) | Constrained rate optimisation with efficient frontier |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained portfolio rate optimisation |
| [insurance-survival](https://github.com/burning-cost/insurance-survival) | Survival models, cure rate, CLV |
| [insurance-nowcast](https://github.com/burning-cost/insurance-nowcast) | ML-EM nowcasting for claims reporting delays and IBNR by risk segment |
| [insurance-synthetic](https://github.com/burning-cost/insurance-synthetic) | Vine copula synthetic portfolio generation |
| [insurance-datasets](https://github.com/burning-cost/insurance-datasets) | Synthetic UK motor data with known DGP |

---

43 libraries available on [PyPI](https://pypi.org/user/burning-cost/) · Blog and tutorials at [burning-cost.github.io](https://burning-cost.github.io)

Built by pricing practitioners, for pricing practitioners.
