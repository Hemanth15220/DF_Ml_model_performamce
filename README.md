# DF_Ml_model_performamce
# 📊 Research Project: Exploring the Impact of Data Transformation Techniques on Machine Learning Model Performance

This repository contains the code, datasets, and findings from a research project that investigates how different data transformation techniques affect the performance of various machine learning models. The study evaluates transformations like normalization, standardization, log transformation, and encoding in the context of classification tasks using popular datasets.

---

## 🧠 Research Objective

To systematically examine the influence of preprocessing transformations on machine learning performance, and to identify which techniques are most suitable for different types of models and data distributions.

---

## 📝 Abstract

Data transformation is a critical preprocessing step in machine learning that significantly influences model performance. This study explores the impact of various transformation techniques—including normalization, standardization, encoding, and log transformation—on classification performance across multiple real-world datasets. We assess accuracy, training time, and algorithm behavior for models like logistic regression, decision trees, SVM, k-NN, and random forests.

---

## 📚 Methodology

1. **Datasets Used:**
   - Iris
   - Wine
   - Breast Cancer
   - Digits

2. **Data Transformation Techniques:**
   - Normalization (Min-Max Scaling)
   - Standardization (Z-score)
   - Log Transformation
   - One-Hot Encoding

3. **Models Evaluated:**
   - Logistic Regression
   - Support Vector Machines (SVM)
   - Decision Trees
   - k-Nearest Neighbors (k-NN)
   - Random Forest

4. **Evaluation Metrics:**
   - Accuracy
   - F1-Score
   - Training Time
   - Model Sensitivity to Scaling

---

## 🔍 Key Findings

- **Normalization** improves k-NN and SVM performance significantly.
- **Standardization** is effective for gradient-based models like logistic regression and SVM.
- **Tree-based models** (Decision Trees, Random Forests) are largely unaffected by transformations.
- **Log transformation** is particularly helpful for skewed feature distributions.



