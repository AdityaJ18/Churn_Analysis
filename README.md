# Customer Churn Analysis & Prediction

## Project Overview

This project focuses on analyzing customer churn patterns and predicting customers who are likely to leave a telecom service provider.

The project combines SQL Server, Python, Machine Learning, and Power BI to analyze customer behavior, identify factors influencing churn, and predict potential churners to support data-driven business decisions.

## Tools & Technologies

- **SQL Server:** Data extraction, querying, and data management.
- **Python:** Data analysis and machine learning.
- **Pandas & NumPy:** Data cleaning and manipulation.
- **Matplotlib & Seaborn:** Exploratory data analysis and visualization.
- **Scikit-learn:** Machine learning and model evaluation.
- **Random Forest:** Customer churn prediction.
- **Power BI:** Interactive dashboard and business insights.

## Project Workflow

### 1. SQL Data Analysis
- Retrieved and explored customer information using SQL Server.
- Used SQL queries and views to organize customer data.
- Prepared separate datasets for churn analysis and newly joined customers.

### 2. Exploratory Data Analysis (EDA)
- Analyzed customer demographics, tenure, services, contracts, and billing information.
- Examined customer churn distribution.
- Identified patterns and factors associated with customer churn.
- Visualized important trends and relationships.

### 3. Data Preprocessing
- Removed unnecessary columns.
- Handled categorical variables using Label Encoding.
- Encoded the target variable:
  - Stayed = 0
  - Churned = 1
- Separated features and target variables.
- Split the dataset into training and testing sets.

### 4. Machine Learning – Random Forest
- Implemented a Random Forest Classification model.
- Trained the model using historical customer data.
- Used the trained model to predict potential churners among newly joined customers.

### 5. Model Evaluation

Evaluated model performance using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

**Model Performance:**

| Metric | Result |
|---|---|
| Accuracy | 85% |
| Precision | 78% |
| Recall | 64%|
| F1-score | 70% |

### 6. Power BI Dashboard

Created an interactive dashboard to visualize customer churn and understand important business metrics.

Dashboard highlights:
- Customer distribution and churn overview.
- Churn analysis by demographics.
- Customer tenure and contract analysis.
- Service usage and payment method analysis.
- Revenue-related insights.


## Machine Learning Results

The trained Random Forest model was applied to the newly joined customer dataset to identify customers predicted as potential churners.

The predicted churn customers were exported for further analysis and potential business follow-up.

## Repository Structure

```text
Churn_Analysis/
│
├── images/
│   ├── Dashboard.png
│   ├── Churn_Distribution.png
│   ├── Confusion_Matrix.png
│   └── Feature_Importance.png
│
├── Churn_Analysis.pbix
├── Churn_Prediction.ipynb
├── Prediction_Data.xlsx
├── SQLQuery1.sql
├── README.md
└── requirements.txt
```

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries:
3. Open the Jupyter Notebook.
4. Update the dataset file path according to your system.
5. Run the notebook cells sequentially.
6. Open the Power BI `.pbix` file to explore the dashboard.

## Key Learnings

- Working with SQL Server for data extraction and querying.
- Performing exploratory data analysis using Python.
- Cleaning and preprocessing real-world datasets.
- Building and evaluating classification models.
- Understanding customer churn patterns.
- Creating interactive dashboards using Power BI.

## Author

**Aditya Jain**

B.Tech – Computer Science Engineering
