# Heart Disease Prediction using Machine Learning

## Project Overview

This project predicts whether a patient has heart disease using Machine Learning techniques. The model is trained on the UCI Heart Disease Dataset and compares the performance of Logistic Regression and Decision Tree Classifier.

After preprocessing and evaluation, Logistic Regression achieved the best performance and was selected as the final model.

---

## Dataset

- **Dataset:** UCI Heart Disease Dataset
- **Source:** https://archive.ics.uci.edu/dataset/45/heart+disease
- **Target Variable:**
  - 0 → No Heart Disease
  - 1 → Heart Disease

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Missing Value Handling
4. Feature Encoding
5. Exploratory Data Analysis (EDA)
6. Feature Scaling
7. Train-Test Split
8. Logistic Regression Model
9. Decision Tree Model
10. Model Evaluation
11. Model Comparison
12. Model Saving

---

## Exploratory Data Analysis

The following visualizations were performed:

- Heart Disease Distribution
- Age Distribution
- Correlation Heatmap
- Confusion Matrix
- ROC Curve

---

## Machine Learning Models

### Logistic Regression

- Accuracy: **82.61%**
- Precision: **83.02%**
- Recall: **86.27%**

### Decision Tree

- Accuracy: **78.26%**
- Precision: **78.70%**
- Recall: **83.33%**

---

## Model Comparison

| Model | Accuracy | Precision | Recall |
|-------|---------:|----------:|-------:|
| Logistic Regression | **82.61%** | **83.02%** | **86.27%** |
| Decision Tree | 78.26% | 78.70% | 83.33% |

---

## Conclusion

Logistic Regression outperformed Decision Tree across all evaluation metrics. It achieved the highest accuracy, precision, and recall, making it the most suitable model for this heart disease prediction task.

---

## Project Structure

```
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── heart_disease_model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
└── heart_disease_uci.csv
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

Run all cells sequentially.

---

## Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Random Forest Classifier
- XGBoost Classifier
- Streamlit or Flask deployment
- Cloud deployment for real-time prediction

---
