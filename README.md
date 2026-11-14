# Customer Churn Prediction Using Machine Learning

## 1. Project Overview

This beginner-friendly machine learning project analyzes customer information and predicts whether a customer is likely to leave a service (customer churn).

## 2. Machine Learning Algorithms

- Logistic Regression
- Random Forest Classifier

## 3. Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## 4. Project Structure

```text
Customer-Churn-Prediction/
├── dataset/
│   ├── README.md
│   └── Telco-Customer-Churn.csv
├── images/
│   ├── README.md
│   ├── churn_distribution.png
│   ├── numeric_feature_distributions.png
│   ├── model_comparison.png
│   └── confusion_matrix.png
├── models/
│   ├── README.md
│   └── customer_churn_pipeline.joblib
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## 5. Dataset Information

This project uses the IBM Telco Customer Churn dataset.

- Dataset file: `Telco-Customer-Churn.csv`
- Target column: `Churn`
- Target values: `Yes` and `No`
- The `customerID` column is removed because it is an identifier.

Check the dataset's license and redistribution terms before uploading the CSV publicly. If redistribution is not permitted, keep the CSV locally and provide instructions for obtaining it.

## 6. Project Workflow

1. Import Python libraries.
2. Load the dataset.
3. Clean and preprocess the data.
4. Perform Exploratory Data Analysis (EDA).
5. Split the data into training and testing sets.
6. Train Logistic Regression and Random Forest models.
7. Evaluate and compare model performance.
8. Generate a confusion matrix.
9. Save the trained model.
10. Predict churn for a sample customer.

## 7. Model Performance

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 74.0% | 76.4% |
| Precision | 50.6% | 54.9% |
| Recall | 77.7% | 60.2% |
| F1 Score | 61.3% | 57.4% |
| ROC AUC | 84.0% | 81.6% |

Logistic Regression achieved the higher F1 Score and ROC AUC in this experiment.

## 8. How to Run the Project

1. Install Python 3.
2. Open a terminal in the project folder.
3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the notebook inside the `notebooks` folder.
6. Run all cells from top to bottom.

Make sure the dataset file path in the notebook matches your folder structure.

## 9. Saved Outputs

- Visualizations: `images/`
- Trained model: `models/customer_churn_pipeline.joblib`

## 10. Conclusion

This project demonstrates how machine learning can help identify customers who may leave a service. It compares two classification algorithms and evaluates their performance using multiple metrics.