# 📊 Clinical Visualizations Directory

This directory contains the graphical assets, plots, and charts generated during the Exploratory Data Analysis (EDA) and Model Evaluation phases of the project.

---

## 📈 Featured Visuals

### 1. Model ROC Comparison (`model_roc_comparison.png`)
* **Description:** Visualizes the True Positive Rate (Sensitivity/Recall) against the False Positive Rate (1 - Specificity) for both baseline Logistic Regression and the optimized Random Forest models.
* **Clinical Insight:** Both models show excellent class separation capabilities:
  * **Logistic Regression AUC:** ~0.95
  * **Random Forest AUC:** ~0.94 - 0.96
* **How to Regenerate:** Run all cells in the `week4_clinical_evaluation.ipynb` notebook.
* from this we can easily identify all the patterns.
  

### 2. Exploratory Data Analysis Plots (Generated in Week 2)
* Contains distribution plots of continuous medical biomarkers (age, blood pressure, cholesterol, max heart rate) and categorical symptom risk ratios.
* **How to Regenerate:** Run all cells in the `week2_EDA.ipynb` notebook.

---

## ⚙️ Requirements for Rendering
All plots are generated programmatically in Python using:
* `matplotlib` (v3.0+)
* `seaborn` (v0.11+)
