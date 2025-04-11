# Machine-Learning

# Electrical Grid Stability Classification

A machine learning project that predicts the stability of a 4-node electrical power grid system using various classification algorithms.

## Project Overview
This project analyzes simulated data representing the behavior of a 4-node star system (electricity producer/power grid). The model classifies grid stability based on multiple features including reaction time, power consumption, and price elasticity factors.

## Dataset
- 10,000 samples with 12 features (tau1-4, g1-4, p1-4)
- Target variables: stab (continuous) and stabf (binary classification)
- Data source: UCI Machine Learning Repository (Arzamasov, 2018)

## Methods Implemented
- Logistic Regression (baseline)
- Support Vector Machines (with RBF, Linear, and Polynomial kernels)
- Decision Tree Classification
- Random Forest Classification
- AdaBoost
- Gradient Boosting

## Key Findings
- SVM with RBF kernel achieved the highest F1 score of 0.966 before hyperparameter tuning
- After hyperparameter tuning, Random Forest emerged as the best-performing model
- Applied dimensionality reduction techniques (PCA, t-SNE) for visualization and performance enhancement

## Techniques Applied
- Model evaluation using confusion matrices, accuracy, and F1 scores
- Hyperparameter tuning to optimize model performance
- Cross-validation to ensure model reliability
- Feature selection using SelectPercentile
- Dimensionality reduction with PCA and t-SNE

## Tools and Technologies
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib/Seaborn for visualization

