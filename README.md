# 🧠 Classification Analysis

This repository contains a comprehensive classification analysis pipeline implemented in Python. It demonstrates best practices in data preprocessing, feature engineering, model training, evaluation, and comparison using various state-of-the-art machine learning algorithms.

## 📌 Project Overview

The primary objective of this notebook is to predict a binary classification target using structured data. The workflow includes:

- Data preparation and exploration
- Feature engineering (with a focus on trend-based features for continuous variables)
- Model training using:
  - Logistic Regression
  - Decision Tree Classifier (CART)
  - Random Forest Classifier
  - Gradient Boosting Classifier (GBM)
- Hyperparameter optimization via `RandomizedSearchCV`
- Model evaluation using metrics such as:
  - ROC AUC Score
  - Confusion Matrix
  - Accuracy, Precision, Recall (if applicable)

## 🔧 Technologies & Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Pydotplus, Graphviz (for decision tree visualization)

## 📊 Key Highlights

- Custom feature engineering based on trends and domain logic
- Model comparison with both interpretability (Logistic Regression, CART) and performance (Ensemble methods)
- Use of `statsmodels` for statistical insights
- Efficient search for best hyperparameters with `RandomizedSearchCV`

## 📈 Output and Visualizations

- ROC Curves
- Confusion Matrices
- Decision Tree diagrams
- Feature importance plots (Random Forest / GBM)

## 📁 File Structure

```
classification_analysis/
├── classification_analysis.ipynb  # Main analysis notebook
├── README.md                      # Project documentation
└── requirements.txt               # Required packages 
```

## 👨‍🔬 Author

Emrullah Karacan  
📫 karacanemrullah69@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/emrullah-karacan-4b596b21b/)
