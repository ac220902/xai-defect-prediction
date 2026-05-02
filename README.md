# xai-defect-prediction
SHAP-based Explainable AI framework for software defect prediction and risk management in regulated environments — MEng dissertation, University of Leicester
---

## Overview

This project develops a conceptual and applied framework that uses **SHAP (SHapley Additive exPlanations)** to make software defect prediction models interpretable, actionable, and trustworthy — particularly in open-source and regulated software ecosystems where model transparency is critical.

The work sits at the intersection of **Explainable AI (XAI)**, **software quality engineering**, and **responsible AI deployment** — addressing a gap in the literature where defect prediction models are often accurate but opaque, limiting their adoption in risk-sensitive environments.

---

## Motivation

Defect prediction models have existed for decades, but adoption in regulated industries remains low. The core problem: developers and risk managers don't trust what they can't understand.

This project asks: **can we make defect prediction not just accurate, but explainable enough to act on?**

SHAP values provide a mathematically grounded approach to attributing model predictions to individual features — making it possible to tell a developer not just *"this module is likely to have a defect"* but *"here's exactly why the model thinks that, and which factors matter most."*

---

## Research Questions

1. How can SHAP-based XAI methods improve the interpretability of defect prediction models in open-source software projects?
2. What are the limitations of current XAI approaches when applied to software defect prediction in regulated environments?
3. How can a SHAP-based conceptual framework bridge model transparency with real-world risk management?

---

## Methodology

- **Systematic literature review** of XAI methods applied to software defect prediction
- **Framework design**: SHAP-based conceptual architecture for interpretable defect risk management
- **Model evaluation**: assessment of classical ML models (logistic regression, random forest, gradient boosting) on open-source defect datasets
- **Evaluation criteria**: accuracy, robustness, fairness, and interpretability — not just predictive performance
- **Responsible AI lens**: governance considerations for deploying XAI in regulated, safety-critical environments

---

## Tech Stack

- **Python** — core implementation
- **scikit-learn** — model development and evaluation
- **SHAP** — explainability layer
- **pandas / matplotlib / seaborn** — data processing and visualisation
- **Jupyter Notebooks** — experimentation and prototyping

*Full code and notebooks being published progressively. Check back for updates.*

---

## Key Contributions

- A novel SHAP-based framework for explainable defect risk management
- Systematic analysis of XAI method applicability in regulated software environments
- Governance recommendations for responsible AI deployment in open-source and financial software systems

---

## Status

> **Active research** — dissertation submitted May 2026. Code and notebooks being cleaned and published. Full release expected June 2026.

---

## About

**Aditi Chauhan** — MEng AI Engineer, University of Leicester  
Research interests: Explainable AI, Responsible AI, Financial Services AI, Applied ML  
Contact: chauhanaditi2209@gmail.com | [LinkedIn](https://linkedin.com/in/aditichauhan)

---

## License

MIT License — see `LICENSE` for details.
