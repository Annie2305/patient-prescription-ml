# Patient-prescription-ml

This repository contains my machine learning solutions for predicting patient prescriptions using Bayesian models and tree-based classifiers. It includes a custom implementation of Naïve Bayes, Decision Trees, Random Forests, and Gradient Boosting.

## 📌 Project Overview
- **Naïve Bayes Classifier:** Implemented from scratch (without pre-built libraries) and validated on a given dataset.
- **Decision Tree Model:** Built using `scikit-learn` with entropy calculations.
- **Ensemble Models:** Implemented Random Forest and Gradient Boosting using `scikit-learn` and `xgboost`.
- **Hyperparameter Tuning:** Optimized models to improve performance.
- **Feature Importance & Selection:** Analyzed most influential features in the dataset.

📂 **src/** _(Source code for models)_
- 📝 `naive_bayes.py` - Custom Naïve Bayes implementation  
- 📝 `decision_tree.py` - Decision Tree classifier  
- 📝 `random_forest.py` - Random Forest classifier  
- 📝 `gradient_boosting.py` - Gradient Boosting classifier  
- 📝 `model_tuning.py` - Hyperparameter tuning  
- 📝 `feature_selection.py` - Feature importance analysis  

📂 **results/** _(Model evaluation reports)_
- 📝 `performance_metrics.txt` 
- 📝 `feature_importance_plot.png`

📂 **data/** _(Dataset location)_
- 📝 `patient_treatment.csv` - Dataset 

## 📜 Acknowledgments

- Course: Introduction to Statistics and Machine Learning (II) – NTHU
- Instructor: Prof.Jeng-Lin Li
- Libraries Used: numpy, pandas, scikit-learn, xgboost
