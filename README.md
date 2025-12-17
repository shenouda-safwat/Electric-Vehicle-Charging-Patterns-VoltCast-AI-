# ⚡ VoltCast AI: Electric Vehicle Energy Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-Regressor-orange?logo=xgboost&logoColor=white)](https://xgboost.readthedocs.io/)
[![License](https://img.shields.io/badge/License-Apache%202.0-green)](LICENSE)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/valakhorasani/electric-vehicle-charging-patterns)

**VoltCast AI** is an advanced Machine Learning project designed to analyze electric vehicle (EV) charging behavior and accurately predict energy consumption. The model leverages **XGBoost Regression** with smart **feature engineering** that reflects the physical nature of EV charging.

---

## 🚀 Overview

With the global shift toward clean energy, understanding EV charging behavior has become critical for energy providers and urban planners. This project aims to:

- Analyze EV charging patterns
- Predict consumed energy (kWh) accurately
- Support power grid load planning and peak optimization

---

## 📊 Dataset

- **Dataset Name:** Electric Vehicle Charging Patterns  
- **Source:** Kaggle  
- **Samples:** 1,320 charging sessions  

### Key Features
- `Vehicle Model`
- `Charging Duration (hours)`
- `Charging Rate (kW)`
- `Time of Day`
- `Temperature`

🔗 Dataset Link:  
https://www.kaggle.com/datasets/valakhorasani/electric-vehicle-charging-patterns

> ⚠️ Note: This dataset is synthetic and intended for learning and experimentation only.

---

## 🛠️ Technologies Used

- **Language:** Python  
- **Libraries:**
  - pandas, numpy
  - xgboost
  - scikit-learn
  - matplotlib, seaborn

---

## 🧠 Model & Feature Engineering

### Problem
Using raw features resulted in poor performance:
- **R² ≈ 0.01**

### Solution
A physics-inspired interaction feature was introduced:




### Final Performance

| Metric | Value |
|------|------|
| **R² Score** | **93.56%** |
| **RMSE** | **5.40 kWh** |

---

## 📈 Visualizations

- Charging peak heatmaps
- Energy vs cost bubble charts
- Residual error analysis plots

---

## 💻 Installation & Usage

```bash
git clone https://github.com/Your_Username/VoltCast-AI.git
cd VoltCast-AI
pip install pandas numpy xgboost scikit-learn matplotlib seaborn

