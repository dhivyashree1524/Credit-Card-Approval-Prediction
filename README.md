# Credit Card Approval Prediction

## Project Overview
This project predicts credit card approvals based on applicant attributes such as age, income, loan amount, credit score, marital status, and gender. The implementation includes dataset generation, preprocessing, class imbalance handling, model training, evaluation, and feature importance analysis.

## Features
- **Automated dataset creation** if a CSV file is missing
- **Data preprocessing** (handling missing values, encoding categorical variables, and scaling numerical data)
- **SMOTE for class imbalance correction**
- **Training multiple machine learning models** (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost)
- **Performance evaluation** using classification reports, accuracy scores, and confusion matrices
- **Feature importance visualization** for tree-based models

## Installation
Ensure you have the required libraries installed by running:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-approval.git
   cd credit-card-approval
   ```
2. Run the script:
   ```bash
   python main.py
   ```

## Workflow
1. **Dataset Generation** (if missing)
2. **Load and Preprocess Data**
   - Handle missing values
   - Encode categorical data
   - Scale numerical features
3. **Address Class Imbalance** using SMOTE
4. **Train-Test Split**
5. **Train Multiple Models**
6. **Evaluate Model Performance**
7. **Feature Importance Analysis** (for tree-based models)

## Expected Output
- Model accuracy scores
- Confusion matrices
- Classification reports
- Feature importance charts

## Future Improvements
- Optimizing models with hyperparameter tuning
- Adding additional classifiers like Neural Networks
- Deploying the model as a web API


