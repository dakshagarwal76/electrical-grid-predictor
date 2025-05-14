# 🔌 Electrical Grid Stability Predictor

A machine learning project using regression and classification models to analyze and predict the stability of an electrical grid system.

## 📄 Project Description

This repository contains a comprehensive machine learning analysis of the **Electrical Grid Stability Simulated Data** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/471/electrical%2Bgrid%2Bstabi).

The project explores both **regression** and **classification** approaches to model grid stability:

- ✅ 5 Regression Models
- ✅ 5 Classification Models
- ✅ Hyperparameter Tuning on top 3 models in each category
- ✅ Model Evaluation using metrics and visualizations
- ✅ Comparative Analysis of all models

### 🔍 Objectives:
- Predict the **stability score** (`stab` - a continuous variable)
- Classify the system as **stable** or **unstable** (`stabf` - categorical)

---

## 📊 Dataset Overview

- **Source**: [UCI Electrical Grid Stability Simulated Data](https://archive.ics.uci.edu/dataset/471/electrical%2Bgrid%2Bstabi)
- **Features**: 12 predictors including:
  - `tau1`–`tau4`: Reaction time constants
  - `p1`–`p4`: Nominal power values
  - `g1`–`g4`: Price elasticity coefficients
- **Targets**:
  - `stab`: Real-valued indicator of grid stability
  - `stabf`: Categorical label (`stable` or `unstable`)

---

## 📈 Project Highlights

- Performance metrics: R², MSE, MAE for regression; Accuracy, F1-score, and confusion matrix for classification
- Model visualizations and comparison plots
- Clean workflow and well-commented code in Colab

---


## 🚀 Future Ideas

- Implement feature selection techniques
- Add a web interface with Streamlit
- Explore deep learning models (MLPs)

---
