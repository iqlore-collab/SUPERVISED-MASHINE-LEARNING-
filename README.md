# SUPERVISED-MASHINE-LEARNING-
Housing Classification Project — Decision Trees, Grid Search and Ensemble Models

This repository contains a sequence of machine learning notebooks built on a housing classification dataset.

The goal is to predict whether a house is expensive:

- `Expensive = 0` → not expensive
- `Expensive = 1` → expensive

The project evolves from a simple interpretable decision tree to a more practical machine learning workflow with hyperparameter tuning and ensemble methods.

---

# Notebook Overview

## 1. `02_decision_tree_housing_EN_github_practical_model.ipynb`

### Purpose
This notebook introduces practical decision tree modeling.

### Main topics
- baseline model
- missing value imputation
- class imbalance
- confusion matrix
- overfitting
- feature importance
- recall / precision / f1
- balanced accuracy
- practical model selection

### Why this notebook matters
This notebook focuses on understanding:
- how decision trees work,
- how model depth affects overfitting,
- why accuracy alone is not enough,
- how class imbalance changes evaluation.

It is intentionally educational and interpretable.

---

## 2. `03_grid_search_cross_validation_housing_PL_github.ipynb`

### Purpose
This notebook introduces a more professional machine learning workflow.

### Main topics
- pipelines
- cross-validation
- GridSearchCV
- automatic hyperparameter tuning
- optimization by `f1`
- optimization by `recall`
- business-oriented model selection

### Why this notebook matters
This notebook moves from:
- manual experimentation
to:
- automated model selection.

It demonstrates:
- how to validate models correctly,
- how to tune hyperparameters,
- how scoring metrics influence the final model.

This notebook is closer to a real machine learning workflow used in practice.

---

## 3. `04_advanced_classification_housing_EN_github.ipynb`

### Purpose
This notebook extends the project into a more advanced applied ML workflow.

### Main topics
- Random Forest
- Gradient Boosting
- ensemble methods
- ROC curves
- Precision-Recall curves
- threshold tuning
- comparison of multiple models
- advanced evaluation

### Why this notebook matters
This notebook demonstrates how modern ML workflows go beyond single decision trees.

It introduces:
- stronger ensemble models,
- probability-based decision thresholds,
- precision vs recall tradeoffs,
- practical business-oriented optimization.

This is the most advanced notebook in the repository.

---

# Dataset

The notebooks use a housing classification dataset derived from the Ames Housing dataset.

Only selected numerical features are used:
- LotArea
- LotFrontage
- TotalBsmtSF
- BedroomAbvGr
- Fireplaces
- PoolArea
- GarageCars
- WoodDeckSF
- ScreenPorch

---

# Key Machine Learning Concepts Covered

The repository demonstrates:
- baseline models
- train/test split
- missing value imputation
- class imbalance
- confusion matrices
- precision / recall / f1
- balanced accuracy
- overfitting
- decision trees
- cross-validation
- GridSearchCV
- ensemble learning
- Random Forest
- Gradient Boosting
- ROC-AUC
- Precision-Recall curves
- threshold tuning

---

# Recommended Reading Order

1. `02_decision_tree_housing_EN_github_practical_model.ipynb`
2. `03_grid_search_cross_validation_housing_EN_github.ipynb`
3. `04_advanced_classification_housing_EN_github.ipynb`

The notebooks are designed as a progression:
- from interpretable models,
- to practical ML workflows,
- to more advanced applied machine learning.

---

# Tools and Libraries

The project uses:
- Python
- pandas
- scikit-learn
- matplotlib

The notebooks are compatible with:
- Google Colab
- Jupyter Notebook

