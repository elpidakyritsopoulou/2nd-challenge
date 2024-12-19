# Prediction of Employee Attrition Using Machine Learning

## Abstract
Employee attrition presents significant challenges to organizations, such as productivity losses and high recruitment costs. This project leverages machine learning models to predict employee attrition using the IBM HR Analytics dataset. The study explores logistic regression, random forest, support vector machine (SVM), and convolutional neural network (CNN) techniques, achieving up to 90% accuracy with CNNs and 89.4% accuracy with logistic regression. Key factors influencing attrition, such as job satisfaction and monthly income, were identified. Ethical considerations, including fairness and reducing bias, were incorporated throughout the study.

## Objectives
- Predict employee attrition with at least 85% accuracy.
- Evaluate and compare multiple ML and AI techniques.
- Identify key factors influencing attrition.
- Align predictive analytics with ethical and sustainability goals.

## Dataset
The IBM HR Analytics dataset was used, containing 1,470 records with 35 features including:
- Age
- Job Role
- Monthly Income
- Work Environment Satisfaction

The target variable is binary, indicating whether an employee left the company.

## Methodology
### Data Preprocessing
- Missing values handled via median (numeric) and mode (categorical) imputation.
- Categorical variables one-hot encoded.
- Numerical features scaled using StandardScaler.
- Data split into 70% training and 30% testing subsets.

### Models Implemented
1. **Logistic Regression** - Balances interpretability and accuracy (89.4%).
2. **Random Forest** - Captures feature interactions and reduces overfitting.
3. **Support Vector Machine (SVM)** - Effective with kernel functions for non-linear data.
4. **Convolutional Neural Networks (CNNs)** - Achieved the highest accuracy (90%).

### Metrics Used
- Accuracy
- Precision
- Recall
- F1 Score

### Results
- CNN outperformed other models, achieving the highest accuracy.
- Logistic regression provided the best balance between performance and interpretability.
- Key predictors included age, monthly income, and job satisfaction.

## Insights and Recommendations
The findings indicate actionable strategies to improve employee retention, such as focusing on high-risk groups identified by the models. Integrating these insights into HR policies can reduce turnover and improve organizational efficiency.

## Ethical Considerations
- Bias reduction in predictive analytics.
- Alignment with sustainability goals to ensure fairness and equity.

## Repository
All code, including preprocessing scripts, model training, and evaluation, is available at:
[GitHub Repository](https://github.com/elpidakyritsopoulou/2nd-challenge.git)

## References
- Additional references are available in the report.

## Appendices
- Dataset Description
- Exploratory Data Analysis
- Hyperparameter Optimization Details
- Model Performance Metrics
