# Heart Disease Prediction - Decision Trees and Random Forests

## Overview

This project demonstrates the application of tree-based machine learning models — Decision Trees and Random Forests — to classify whether a patient has heart disease based on medical attributes.

The project focuses on:
- Visualizing how decision trees make predictions
- Preventing overfitting through tree depth control
- Using Random Forests to improve accuracy and stability
- Interpreting feature importances
- Evaluating model performance using confusion matrix, accuracy, and cross-validation

---

## Dataset

- **Name**: Heart Disease UCI Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Features**: 13 clinical features such as age, chest pain type, resting blood pressure, cholesterol, etc.
- **Target**: `0 = No disease`, `1 = Disease`

---

## Objectives

- Train and visualize a Decision Tree classifier
- Analyze overfitting and prune tree using `max_depth`
- Train a Random Forest classifier and compare performance
- Interpret feature importances
- Use cross-validation for more robust evaluation

---

## Files Included

- `Day5_TreeModels.ipynb`: Jupyter notebook with all steps and evaluations
- `heart.csv`: Dataset used
- `README.md`: Project documentation

---

## Results Summary

- The unpruned Decision Tree achieved very high accuracy (~98.5%) with excellent precision and recall.
- The confusion matrix confirmed minimal misclassifications.
- Tree visualization helped interpret decision paths.
- Pruning via `max_depth` is recommended to avoid overfitting.
- Random Forest (if added) can further improve generalization.
- Cross-validation provides a reliable estimate of model stability.

---

## Conclusion

This project highlights the strengths of tree-based models for classification problems. Decision Trees offer interpretability, while Random Forests provide robustness and higher generalization performance. Both models are powerful tools, especially in domains like healthcare where decisions must be accurate and explainable.
