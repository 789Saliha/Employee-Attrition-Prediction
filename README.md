# Employee Attrition Prediction Using Machine Learning

## Project Overview

This project predicts employee attrition using machine learning techniques. The objective is to identify employees who are likely to leave the organization so that HR departments can take proactive measures to improve employee retention.

---

## Dataset

- IBM HR Employee Attrition Dataset
- Total Records: 1470
- Target Variable: Attrition

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Jupyter Notebook

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Train-Test Split
6. SMOTE for Class Balancing
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Feature Importance Analysis

---

## Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Model Performance

| Model | Accuracy | Precision | Recall |
|--------|----------|-----------|--------|
| Logistic Regression | 0.7993 | 0.4000 | 0.5106 |
| Decision Tree | 0.7517 | 0.3088 | 0.4468 |
| Random Forest | 0.7993 | 0.3421 | 0.2766 |
| XGBoost | **0.8265** | **0.4444** | 0.3404 |

---

## Best Model

XGBoost achieved the highest accuracy (82.65%) and precision (44.44%). Logistic Regression achieved the highest recall (51.06%).

---

## Repository Structure

```
Employee-Attrition-Prediction/
│
├── Employee_Attrition_Prediction.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── Employee_Attrition_Project_Report.docx
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone the repository.
2. Install the required packages:

```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```
jupyter notebook
```

4. Run all cells sequentially.

---

## Author

**Saliha**

BS Artificial Intelligence Student
