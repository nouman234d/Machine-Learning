# Heart Disease Classification with XGBoost

This project demonstrates how to apply XGBoost to the Heart Disease dataset for binary classification. The tutorial includes data exploration, preprocessing, model training, performance evaluation, and feature importance visualization.

## Files Included

- final_xgboost_heart_tutorial.ipynb: Jupyter Notebook with full EDA, modeling, and evaluation
- README.md: Project overview and setup instructions
- requirements.txt: List of Python dependencies
- heart.csv: Input dataset used for training and evaluation

## Dataset

The Heart Disease dataset is sourced from the UCI Machine Learning Repository and contains clinical records of patients. The goal is to predict the presence of heart disease based on features like age, blood pressure, cholesterol, and chest pain type.

## Learning Objectives

- Perform EDA with correlation analysis and distribution plots
- Preprocess data using scaling and label encoding
- Train and evaluate an XGBoost classifier
- Visualize feature importances to interpret the model

## Setup Instructions

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Open the notebook:
   ```
   jupyter notebook final_xgboost_heart_tutorial.ipynb
   ```

## References

- Chen, T., & Guestrin, C. (2016). XGBoost: https://doi.org/10.1145/2939672.2939785
- UCI Dataset: https://archive.ics.uci.edu/dataset/45/heart+disease
- XGBoost Docs: https://xgboost.readthedocs.io/en/stable/
- Scikit-learn: https://scikit-learn.org/stable/

## License

MIT License
