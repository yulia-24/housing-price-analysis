# Housing Price Analysis

This project uses machine learning and socioeconomic indicators to predict whether U.S. counties experienced above-average housing price growth relative to their state during 2020.

Using demographic, economic, tax, and housing market variables, multiple classification models were evaluated, including Logistic Regression, Random Forest, Support Vector Machines, and Elastic Net regularization.

Results show that nonlinear models substantially outperform traditional linear approaches, with Random Forest achieving the highest predictive accuracy.

---

# Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
EDA + VIF
      ↓
Model Training
      ↓
Hyperparameter Tuning
      ↓
Evaluation
      ↓
Interpretation
```

---

# Models Used

- Logistic Regression
- Elastic Net Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

# Key Findings

- Random Forest achieved the strongest predictive performance
- Nonlinear relationships significantly improved model accuracy
- Education level, taxes, demographics, and homeownership rates were among the strongest predictors
- High-growth counties were often transitional markets rather than already expensive metropolitan areas

---

# Tools & Libraries

- Python
- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib
- seaborn

---

# Repository Structure

```text
housing-price-analysis/
│
├── data/
├── images/
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_model_evaluation.ipynb
└── README.md
```
