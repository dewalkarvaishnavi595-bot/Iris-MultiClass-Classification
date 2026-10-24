## Task 3: Predictive Customer Churn Classifier

### Objective
Predict customer churn using ensemble machine learning models and handle class imbalance to improve ROC-AUC performance.

### Dataset
- **Telco Customer Churn Dataset**
- 7,043 customer records
- Target variable: `Churn`

### Models Used
- Random Forest Classifier
- XGBoost Classifier

### Techniques Used
- Converted `TotalCharges` to numeric
- Handled missing values using median imputation
- One-Hot Encoding for categorical features
- Standardized numerical features
- SMOTE for class imbalance
- ROC-AUC evaluation
- Feature importance analysis

### Results

| Model | ROC-AUC |
|---|---:|
| Random Forest | 0.8162 |
| XGBoost | 0.8410 |

**Best Model:** XGBoost  
**ROC-AUC:** 84.10%

### Visualizations
- ROC-AUC curves
- Top 10 feature importance chart

### Workflow
Data Loading → Data Cleaning → Feature Preprocessing → SMOTE → Random Forest & XGBoost → ROC-AUC Evaluation → Feature Importance
