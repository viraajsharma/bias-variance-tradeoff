# Bias–Variance Tradeoff: Theory and Experiments

This repository contains the code, experiments, and paper draft for a research project on the **Bias–Variance Tradeoff**.  
We explore the tradeoff theoretically and empirically using both **synthetic** and **real-world datasets**, and study techniques like **regularization** (L1, L2, dropout, early stopping) to mitigate overfitting and underfitting.

## 📌 Project Goals
- Theoretical explanation of bias–variance decomposition.
- Controlled experiments on synthetic datasets.
- Application to real-world datasets.
- Evaluate regularization methods to balance bias & variance.
- Professional paper-style report.

## 📂 Repo Structure
- `src/` → Core implementations (models, data, utils).
- `experiments/` → Jupyter notebooks for experiments.
- `results/` → Plots and metrics from experiments.
- `docs/` → Paper draft, notes, references.

## 🚀 Getting Started
```bash
# Clone repo
git clone (https://github.com/viraajsharma/bias-variance-tradeoff.git)
cd bias-variance-tradeoff

# Create environment
python -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate     # (Windows)

# Install requirements
pip install -r requirements.txt
