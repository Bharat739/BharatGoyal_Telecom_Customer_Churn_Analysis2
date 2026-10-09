# Telecom_Customer_Churn_Analysis

**Student:** Bharat Goyal  
**Program:** IBM SkillsBuild Data Analytics with AI Academic Internship  
**Organization:** BharatCares in association with AICTE

## Project Overview

This project analyzes telecom customer data to understand customer churn and builds a machine-learning model to predict whether a customer is likely to leave the service.

The workflow covers:

- Data loading and understanding
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Churn-rate analysis by customer characteristics
- Data visualization
- Machine-learning classification
- Model evaluation using Accuracy, Precision, Recall, F1-score and ROC-AUC
- Feature-importance / coefficient analysis
- Business recommendations for customer retention

## Dataset

The project is designed around the **IBM Telco Customer Churn** dataset. The dataset contains customer-level telecom information such as tenure, contract type, internet service, monthly charges, total charges and churn status.

Dataset/reference source:

https://github.com/IBM/watsonx-ai-samples/blob/master/cpd4.5/data/customer_churn/WA_FnUseC_TelcoCustomerChurn.csv

The original public dataset contains 7,043 customer records and 21 columns.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```text
BharatGoyal_Telecom_Customer_Churn_Analysis.ipynb
requirements.txt
BharatGoyal_ProjectReport.docx
README.md
```

## Setup

1. Install Python 3.9 or newer.
2. Open a terminal/Command Prompt.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the project notebook and run all cells from top to bottom.

## Data Loading

The notebook first checks for a local file named:

```text
WA_FnUseC_TelcoCustomerChurn.csv
```

If it is not present, the notebook attempts to download the public IBM sample dataset automatically. If internet access is unavailable, it creates a clearly labelled synthetic demonstration dataset so that the complete workflow can still be executed and studied.

For an official submission, downloading the public dataset beforehand and keeping the CSV in the same folder is recommended.

## Expected Outcome

The notebook produces:

- Dataset summary
- Missing-value analysis
- Churn distribution
- Churn-rate visualizations
- Numerical/categorical analysis
- Logistic Regression model
- Confusion matrix
- Classification report
- ROC curve and ROC-AUC
- Model coefficient analysis
- Actionable business recommendations

## Important Note

This is an educational data-analytics and machine-learning project. Model predictions should be treated as analytical signals, not as guaranteed predictions of individual customer behavior.
