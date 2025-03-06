# E-Commerce Data Analysis Using RDD, Dataframes and PySpark SQL

## Project Overview
This project analyzes e-commerce transactions and customer behavior using machine learning techniques. The goal is to gain insights into customer purchasing patterns, payment behaviors, and transaction statuses. Additionally, this project aims to test and compare the performance of RDDs, DataFrames, and PySpark SQL in processing large-scale e-commerce data.

## Folder Structure
Loan_Application_Analysis/

   ├── data/

   │   ├── application_data.csv      # Main dataset containing loan application details

   │   ├── previous_application.csv  # Previous loan applications data (not uploaded due to size)

   │   ├── value_dict.csv            # Metadata or mapping values for categorical data
      
   ├── Ecommerce_analysis.ipynb  # Jupyter Notebook with all relevant code
   
   ├── README.md  # Project documentation
   
   ├── requirements.txt  # Dependencies required to run the project

## Installation
Ensure you have Python installed (preferably Python 3.8 or above). Install the required dependencies using the following command:
```sh
pip install -r requirements.txt 
```

## Usage
1. Unzip data.zip file
2. Open the Jupyter Notebook:
```sh
   jupyter notebook Ecommerce_analysis.ipynb
```

3. Execute the cells step by step to analyze customer transactions, purchase trends, model predictions, and compare RDDs, DataFrames, and PySpark SQL.

## Dataset Description
- **application_data.csv**: Contains details of e-commerce transactions, including order amounts, payment methods, transaction approvals, and rejection reasons.
- **previous_application.csv**:  Historical transaction records.
- **value_dict.csv**: Mapping file for categorical values used in datasets.

## Results & Analysis

The Jupyter Notebook includes the following sections:

### 1. Data Cleaning & Preprocessing

- Handling missing values and incorrect data entries.
- Encoding categorical features appropriately.

### 2. Exploratory Data Analysis (EDA)

- Visualizing transaction volume and customer purchase patterns.
- Analyzing correlations between order values, payment types, and approval rates.

### 3. RDDs vs DataFrames vs PySpark SQL Comparison

- Implementing queries using RDDs, DataFrames, and PySpark SQL.
- Measuring and comparing execution times.
- Analyzing performance differences and discussing trade-offs.

### 4. Business Insights & Recommendations

- **Total Approved Loan Amount per Year and Month**: Analyzed historical loan data to determine loan approval trends.
- **Income Analysis by Education Type**: Computed the average income per education category to understand financial behavior.
- **Credit Request Analysis**: Filtered applicants with low credit scores from the past year.
- **Age-Based Property and Car Ownership**: Examined how age influences property and vehicle ownership.
- **Gender-Based Loan Approvals Over Time**: Created visualizations to explore gender-based approval trends.
- **Scatter Plot Analysis**: Studied the relationship between applicant age and total approved credit, using log scales where necessary.
