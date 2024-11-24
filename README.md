# **red-wine-quality-project**

![redwine](https://github.com/user-attachments/assets/56e4ed15-66d2-4f34-9291-8e78cfa3ccec)

## **Overview**
This project focuses on analyzing red wine samples from Portugal to classify them as "good" or "bad" based on physicochemical properties such as acidity, pH, and alcohol content. Using machine learning, we developed classification models to predict wine quality.

## **Dataset**
- **Source**: [UCI Machine Learning Repository](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)
- **Samples**: 1,599 red wine entries
- **Features**: 11 physicochemical properties (e.g., acidity, residual sugar, alcohol)
- **Target**: Quality score (3–8)
  - **Good Wine**: Quality Score ≥ 6
  - **Bad Wine**: Quality Score ≤ 5

## **Key Steps**
1. Conducted exploratory data analysis (EDA) to understand feature relationships.
2. Standardized features to improve model performance.
3. Built classification models:
   - Logistic Regression (from scratch and libraries)
   - Random Forest
4. Evaluated models using metrics like accuracy and F1 score.

## **Results**
- Training Accuracy: ~74%
- Testing Accuracy: ~31% (indicating overfitting or dataset imbalance).

## **Technologies Used**
- Python
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `matplotlib` and `seaborn` for data visualization
  - `scikit-learn` for machine learning models
