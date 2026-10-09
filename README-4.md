# Bharat Goyal — Telecom Customer Churn Analysis and Prediction

**Internship:** BharatCares × AICTE × IBM SkillsBuild Data Analytics with AI Academic Internship  
**Student:** Bharat Goyal  
**Project:** Telecom Customer Churn Analysis and Prediction

## Project Overview
This project analyzes telecom customer churn using the IBM Telco Customer Churn sample dataset. It demonstrates data loading, cleaning, exploratory data analysis, visualization, preprocessing, Logistic Regression, model evaluation and business recommendations.

## Dataset
Official IBM repository:
https://github.com/IBM/telco-customer-churn-on-icp4d

Raw CSV:
https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

The commonly distributed dataset contains 7,043 customer records and 21 columns. The target is `Churn` (Yes/No).

## Technologies
Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Jupyter Notebook and GitHub.

## Files
- `BharatGoyal_Telecom_Customer_Churn_Analysis.ipynb` — complete code
- `requirements.txt` — Python dependencies
- `BharatGoyal_ProjectReport.docx` — college-format project report
- `README.md` — project overview and setup

## Setup
1. Install Python 3.9+.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Start Jupyter:
   `jupyter notebook`
4. Open `BharatGoyal_Telecom_Customer_Churn_Analysis.ipynb`.
5. The notebook looks for `Telco-Customer-Churn.csv` locally and otherwise attempts to download it from the IBM public source.

## Methodology
- Convert `TotalCharges` to numeric
- Remove `customerID` from predictive features
- Encode `Churn` as 0/1
- Median imputation for numeric variables
- Most-frequent imputation and one-hot encoding for categorical variables
- Standard scaling of numeric variables
- Stratified 80/20 train-test split
- Logistic Regression
- Accuracy, precision, recall, F1-score and ROC-AUC
- Confusion matrix and ROC curve
- Coefficient-based interpretation

## Important Note
`Churn` is an observed historical outcome in the sample data. This project is an educational classification and risk-analysis exercise, not a guarantee of future customer behaviour.

## Submission Checklist
- Code File: `BharatGoyal_Telecom_Customer_Churn_Analysis.ipynb`
- Requirements File: `requirements.txt`
- Project Report: `BharatGoyal_ProjectReport.docx`
- README File: `README.md`
- GitHub repository URL: paste your new repository URL into the internship submission form.
