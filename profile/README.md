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
| [insurance-evt](https://github.com/burning-cost/insurance-evt) | Extreme Value Theory for catastrophic claim severity — GPD/GEV, profile likelihood CIs, censored MLE, reinsurance layer pricing, Solvency II 1-in-200 |
| [insurance-tabpfn](https://github.com/burning-cost/insurance-tabpfn) | Foundation model pricing for thin segments — TabPFN v2/TabICLv2 backend, GLM benchmark, PDP relativities, CommitteeReport |

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
| [insurance-counterfactual-sets](https://github.com/burning-cost/insurance-counterfactual-sets) | Weighted conformal ITE for individual counterfactuals — Lei & Candès 2021, sensitivity analysis, FCA ENBP harm reports |
| [insurance-mediation](https://github.com/burning-cost/insurance-mediation) | Causal mediation for FCA proxy discrimination — CDE/NDE/NIE, Poisson/Gamma/Tweedie GLMs, Imai sensitivity, FCA HTML report |

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
| [insurance-conformal-fraud](https://github.com/burning-cost/insurance-conformal-fraud) | Conformal anomaly detection for claims fraud — BH FDR control, integrative conformal p-values, IFB Fisher combination, Mondrian stratification |
| [insurance-reconcile](https://github.com/burning-cost/insurance-reconcile) | Hierarchical forecast reconciliation — PremiumWeightedMinTrace, LossRatioReconciler, FreqSevReconciler, InsuranceHierarchy DSL |

### Optimisation & Data

| Library | Description |
|---------|-------------|
| [rate-optimiser](https://github.com/burning-cost/rate-optimiser) | Constrained rate optimisation with efficient frontier |
| [insurance-optimise](https://github.com/burning-cost/insurance-optimise) | Constrained portfolio rate optimisation |
| [insurance-survival](https://github.com/burning-cost/insurance-survival) | Survival models, cure rate, CLV |
| [insurance-cure](https://github.com/burning-cost/insurance-cure) | Mixture cure models — WeibullMCM/LogNormalMCM/CoxMCM, EM algorithm, Maller-Zhou test, non-claimer scoring |
| [insurance-uplift](https://github.com/burning-cost/insurance-uplift) | HTE uplift modelling for retention — CausalForestDML, Qini/AUUC, four customer taxonomy, PolicyTree, ENBP constraint, Consumer Duty fairness audit (127 tests) |
| [insurance-nowcast](https://github.com/burning-cost/insurance-nowcast) | ML-EM nowcasting for claims reporting delays and IBNR by risk segment |
| [insurance-synthetic](https://github.com/burning-cost/insurance-synthetic) | Vine copula synthetic portfolio generation |
| [insurance-datasets](https://github.com/burning-cost/insurance-datasets) | Synthetic UK motor data with known DGP |

---

54 libraries available on [PyPI](https://pypi.org/user/burning-cost/) · Blog and tutorials at [burning-cost.github.io](https://burning-cost.github.io)

Built by pricing practitioners, for pricing practitioners.
