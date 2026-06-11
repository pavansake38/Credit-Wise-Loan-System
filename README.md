# CreditWise Loan System

## Overview
CreditWise Loan System is a Machine Learning-based Loan Approval Prediction System that helps predict whether a loan application should be approved based on applicant financial and demographic information.

The project benchmarks multiple machine learning models and uses ensemble learning techniques to achieve high predictive performance while maintaining interpretability.

## Features
- Loan approval prediction
- Automated data preprocessing pipeline
- Missing value imputation
- Feature scaling
- Categorical encoding
- Model benchmarking across multiple algorithms
- Ensemble learning techniques
- Feature importance analysis
- Approval probability estimation

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Highlights
- Built an end-to-end Loan Approval Prediction System in Python.
- Benchmarked 9 machine learning models.
- Achieved:
  - Accuracy: **93.7%**
  - Weighted F1-Score: **0.938**
  - ROC-AUC: **0.980**
- Developed a production-style Scikit-learn Pipeline using ColumnTransformer.
- Implemented preprocessing steps including:
  - Missing value imputation
  - Feature scaling
  - Categorical encoding
- Prevented data leakage through pipeline-based preprocessing.
- Optimized Decision Tree performance using pre-pruning and cost-complexity post-pruning.
- Built an interpretable inference engine with approval probability predictions and feature importance analysis.

## Workflow
1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Data Preprocessing
5. Model Training
6. Model Evaluation
7. Ensemble Learning
8. Loan Approval Prediction
9. Feature Importance Analysis

## Performance Metrics

| Metric | Score |
|----------|----------|
| Accuracy | 93.7% |
| Weighted F1-Score | 0.938 |
| ROC-AUC | 0.980 |

## Results
The system successfully predicts loan approval eligibility with high accuracy and provides interpretable insights into the factors affecting lending decisions.

## Future Improvements
- Deploy as a web application
- Real-time loan approval predictions
- Explainable AI (SHAP/LIME) integration
- Cloud deployment
- API development

## Author
Pavan Sake
