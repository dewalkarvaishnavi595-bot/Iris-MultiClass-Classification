# Machine Learning Projects – Datheon Internship

This repository contains machine learning projects completed as part of the Datheon internship tasks. The projects demonstrate end-to-end machine learning workflows using Python and Scikit-Learn.

---

## Task 1: Multi-Class Benchmark Classification Pipeline

### Objective

Build and evaluate multiclass classification models using the Iris dataset.

### Dataset

The Iris dataset contains 150 samples belonging to three species:

- Setosa
- Versicolor
- Virginica

### Models Used

- Logistic Regression
- Decision Tree Classifier

### Techniques Used

- 80:20 train-test split
- StandardScaler
- Scikit-Learn Pipeline
- Confusion Matrix
- Classification Report
- Accuracy
- Precision
- Recall
- F1-Score
- Multiclass ROC Curve
- AUC analysis
- Decision boundary visualization

### Task 1 Workflow

```text
Load Dataset
     ↓
Data Exploration
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
Logistic Regression / Decision Tree
     ↓
Model Evaluation
     ↓
Confusion Matrix + ROC Curve
```

---

## Task 2: Real Estate Housing Price Prediction

### Objective

Predict median house values using the California Housing dataset and compare OLS, Ridge, and Lasso regression models.

### Dataset

California Housing dataset containing housing-related numerical and categorical features.

### Models Used

- OLS (Linear Regression)
- Ridge Regression (L2)
- Lasso Regression (L1)

### Techniques Used

- Missing-value imputation
- Feature engineering
- Interaction/ratio features
- One-Hot Encoding
- StandardScaler
- 80:20 train-test split
- Multicollinearity analysis
- Correlation heatmap
- GridSearchCV
- RMSE
- MAE
- R²
- Actual vs Predicted visualization
- Residual error analysis

### Engineered Features

- `rooms_per_household`
- `bedrooms_per_room`
- `population_per_household`

### Task 2 Model Results

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| OLS | 69127.04 | 49645.49 | 0.6353 |
| Ridge | 69134.97 | 49652.14 | 0.6353 |
| Lasso | 69128.09 | 49646.43 | 0.6353 |

For this experiment, OLS achieved the lowest RMSE and MAE among the three models.

### Task 2 Workflow

```text
Load Housing Dataset
        ↓
Data Inspection
        ↓
Missing Value Handling
        ↓
Correlation Analysis
        ↓
Feature Engineering
        ↓
Encoding + Scaling
        ↓
Train-Test Split
        ↓
OLS / Ridge / Lasso
        ↓
GridSearchCV
        ↓
Model Comparison
        ↓
Actual vs Predicted + Residual Analysis
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
- GitHub

## Repository Structure

```text
Iris-MultiClass-Classification/
│
├── Iris_MultiClass_Classification.ipynb
├── Task2_Real_Estate_Housing_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Open the required `.ipynb` notebook using Jupyter Notebook or Google Colab.
4. Run the cells sequentially.

## Conclusion

These projects demonstrate complete machine learning workflows covering data preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, and visualization.

The projects were developed as part of the Datheon internship deliverables.
