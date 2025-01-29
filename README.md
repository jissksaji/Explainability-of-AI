# 🧠 Explainability in AI for Drug Discovery

This repository explores **Explainability in AI**, focusing on **Decision Trees and Random Forests** for drug discovery applications. Using the **Breast Cancer Wisconsin Dataset**, we implement **machine learning models** and explainability techniques to analyze feature importance.

---

## 🚀 Features

- **Decision Tree & Random Forest Classifiers**
- **Feature Importance using Mean Decrease in Impurity (MDI)**
- **Permutation Feature Importance**
- **Decision Tree Visualization (Graphviz & DTreeViz)**
- **SHAP, LIME & DiCE for Explainability**
- **Comprehensive Pipeline with Preprocessing & Model Training**

---

## 📥Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/jissksaji/Explainability-of-AI.git
cd Explainability-of-AI
```

### **2️⃣ Create and Activate Conda Environment**
```bash
conda env create -f environment.yml
conda activate explainability
```

### **3️⃣ Run the Jupyter Notebook**
```bash
jupyter-notebook explainability.ipynb
```

This will **train the models, evaluate feature importance, and generate visualizations**.

---

## 📑 Overview

This project examines **Decision Trees and Random Forests** using the **Breast Cancer Wisconsin Dataset**, which includes **30 features** derived from **fine needle aspirate (FNA) images**. We focus on **10 key features** for model training and interpretability.

### **Explainability Techniques**
1. **Feature Importance (MDI & Permutation Importance)**
   - Identifies which features contribute most to model decisions.
2. **Visualization**
   - Decision Tree visualization using **Graphviz & DTreeViz**.
3. **SHAP, LIME & DiCE**
   - Explains individual predictions with model-agnostic interpretability tools.

### **Model Performance**
- **Decision Trees** provide transparency but suffer from overfitting.
- **Random Forests** improve accuracy but reduce interpretability.
- **Permutation Importance** confirms that **radius, texture, and area** are key features.

---

## 📊 Results

- **Decision Trees** allow easy interpretation but may be unstable.
- **Random Forests** average multiple trees, improving robustness.
- **SHAP & LIME** provide further insights into individual predictions.

---

## ✨ Special Thanks

Special thanks to **[KalininaLab]** for their guidance and insights on **explainability in AI**.

---

## References

- [Scikit-learn: Decision Trees](https://scikit-learn.org/stable/modules/tree.html)
- [SHAP: Explainable AI](https://shap.readthedocs.io/en/latest/)
- [LIME: Local Explainability](https://github.com/marcotcr/lime)
- [DiCE: Counterfactual Explanations](https://github.com/interpretml/DiCE)

