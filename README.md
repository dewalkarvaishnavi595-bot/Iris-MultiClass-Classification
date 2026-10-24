# Machine Learning Projects – Datheon Internship

This repository contains three machine learning projects completed as part of the Datheon internship tasks.

## Task 1: Multi-Class Classification (Iris Dataset)

**Objective:** Classify Iris flowers into different species using machine learning.

**Dataset:** Iris dataset

**Models Used:**
- Logistic Regression
- Decision Tree Classifier

**Techniques:**
- Data exploration and visualization
- Train-test split
- Feature scaling using StandardScaler
- Confusion matrix and classification report
- Accuracy, precision, recall and F1-score
- Multiclass ROC-AUC analysis

**Notebook:** `Iris_MultiClass_Classification.ipynb`

## Task 2: Real Estate Housing Price Prediction

**Objective:** Predict median house values using regression models.

**Dataset:** California Housing dataset

**Models Used:**
- Ordinary Least Squares (Linear Regression)
- Ridge Regression
- Lasso Regression

**Techniques:**
- Missing-value imputation
- Correlation heatmap
- Feature engineering
- Standardization and categorical encoding
- GridSearchCV for Ridge and Lasso
- RMSE, MAE and R² evaluation
- Actual-versus-predicted and residual plots

**Results:** OLS achieved RMSE 69127.04, MAE 49645.49 and R² 0.6353 in the recorded evaluation.

**Notebook:** `Task2_Real_Estate_Housing_Price_Prediction.ipynb`

## Task 3: Predictive Customer Churn Classifier

**Objective:** Predict customer churn and handle class imbalance.

**Dataset:** Telco Customer Churn dataset

**Models Used:**
- Random Forest Classifier
- XGBoost Classifier

**Techniques:**
- Converted `TotalCharges` to numeric
- Handled missing values
- OneHotEncoder for categorical features
- StandardScaler for numerical features
- SMOTE to balance training classes
- ROC-AUC evaluation
- Top 10 feature importance visualization

**Results:**

| Model | ROC-AUC |
|---|---:|
| Random Forest | 0.8162 |
| XGBoost | 0.8410 |

XGBoost achieved the higher ROC-AUC of 0.8410 (84.10%).

**Notebook:** `Task3_Customer_Churn_Classification.ipynb`

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-Learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Jupyter Notebook / Google Colab

## Repository Structure

- `Iris_MultiClass_Classification.ipynb` — Task 1
- `Task2_Real_Estate_Housing_Price_Prediction.ipynb` — Task 2
- `Task3_Customer_Churn_Classification.ipynb` — Task 3
- `README.md` — Project documentation
- `requirements.txt` — Python dependencies

## Conclusion

These projects demonstrate classification, regression, data preprocessing, feature engineering, class-imbalance handling, model evaluation and visualization using Python machine learning libraries.
