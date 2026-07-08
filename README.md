# MHR-SafeGuard

**An open-source framework for developing trustworthy machine learning systems for mental health risk assessment. MHR-SafeGuard combines leakage-aware data processing, rigorous model evaluation, uncertainty quantification, calibration, explainable AI, counterfactual analysis, robustness and fairness assessment, reproducible experimentation, and safety-aware decision support within a unified and extensible pipeline.**

## Overview

Mental health prediction models often report impressive predictive performance that may not generalize to real-world clinical settings due to methodological issues such as data leakage, inadequate uncertainty estimation, poor calibration, or limited explainability.

MHR-SafeGuard provides an end-to-end workflow for trustworthy mental health risk assessment, integrating leakage-aware learning, nested model selection, uncertainty quantification, explainability, robustness evaluation, fairness assessment, and reproducible experimentation.

## Key Features

- Leakage-aware data processing
- Nested cross-validation
- Hyperparameter optimization
- Bootstrap confidence intervals
- Split-conformal prediction
- Calibration analysis
- Ensemble uncertainty estimation
- SHAP, LIME, and DiCE explanations
- Robustness and fairness evaluation
- Safety-aware decision support
- Automatic report generation
- Publication-ready figures and tables

## Workflow

Dataset
→ Leakage-aware preprocessing
→ Model development
→ Reliability & uncertainty
→ Explainability
→ Safety-aware decision support
→ Reports & reproducible artifacts

## Installation

git clone https://github.com/<username>/MHR-SafeGuard.git

pip install -r requirements.txt

## License

MIT License.
