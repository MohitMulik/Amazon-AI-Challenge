# Amazon ML / AI Challenge

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Machine Learning](https://img.shields.io/badge/Domain-Machine_Learning-FF9900?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![Deep Learning](https://img.shields.io/badge/Framework-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

Machine learning, data processing, and predictive modeling workflows developed for the **Amazon ML Challenge**.

---

## 📌 Challenge Overview

The **Amazon ML Challenge** is a competitive hackathon requiring participants to build high-accuracy predictive machine learning pipelines on large-scale e-commerce datasets. The competition evaluates feature engineering, data preprocessing, model selection, ensemble strategies, and generalization under strict runtime constraints.

---

## 🛠️ Pipeline Architecture

1. **Exploratory Data Analysis (EDA):**
   * Class balance inspection, distribution profiling, and missing value imputation.
   * Textual and numerical feature extraction.
2. **Feature Engineering:**
   * Text embeddings and tokenization.
   * Categorical encoding and numerical scaling.
3. **Model Selection & Experimentation:**
   * Gradient boosting models (XGBoost, LightGBM, CatBoost) for structured tabular features.
   * Deep learning architectures for multimodal text and metadata representations.
4. **Validation & Ensembling:**
   * Stratified K-Fold cross-validation to prevent data leakage and overfitting.
   * Weighted average and blending ensembles for final submission generation.

---

## 📂 Repository Structure

```text
Amazon-AI-Challenge/
├── notebooks/       # Exploratory analysis and baseline model experiments
├── src/
│   ├── preprocessing.py  # Data cleaning and feature engineering pipelines
│   ├── train.py          # Model training and cross-validation loops
│   └── inference.py      # Test set prediction and submission generation
├── requirements.txt # Project dependencies
└── README.md
```

---

## 🚀 Getting Started

### 1. Environment Setup
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

pip install -r requirements.txt
```

### 2. Run Preprocessing & Training
```bash
python src/preprocessing.py
python src/train.py
```

---

## 📄 License
This repository is open-sourced under the MIT License.
