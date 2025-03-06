# Loan Application Analysis

## Project Overview
This project analyzes loan applications using various machine learning models. The goal is to predict loan approval status based on historical application data. The dataset consists of applicant financial details, loan application records, and previous application history.

## Folder Structure
Loan_Application_Analysis/

   ├── data/

   │   ├── application_data.csv      # Main dataset containing loan application details

   │   ├── previous_application.csv  # Previous loan applications data (not uploaded due to size)

   │   ├── value_dict.csv            # Metadata or mapping values for categorical data

   │
   
   ├── model/
   
   │   ├── [Various ML model files]  # Machine learning models trained for loan prediction
   
   │
   
   ├── Loan_application_analysis.ipynb  # Jupyter Notebook with all relevant code
   
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
   jupyter notebook Loann_application_analysis.ipynb
```

3. Run the cells step by step to explore data preprocessing, model training, and evaluation.

## Dataset Description
- **application_data.csv**: Contains details of loan applications, including applicant income, credit amount, down payment, contract status, and decision timelines.
- **previous_application.csv**: Historical records of previous loan applications (not uploaded due to size).
- **value_dict.csv**: Mapping file for categorical values used in datasets.

## Results & Analysis
The Jupyter Notebook includes the following sections to analyze the loan application data:

### 1. Data Cleaning & Preprocessing
- Handling missing values using imputation techniques.
- Removing duplicate records and outliers.
- Encoding categorical variables appropriately.

### 2. Exploratory Data Analysis (EDA)
- Visualizing distributions of loan amounts, interest rates, and approval status.
- Identifying trends and correlations between applicant features and loan approvals.
- Understanding the impact of previous loan history on new applications.

### 3. Feature Engineering
- Creating new derived features to enhance model performance.
- Scaling and normalizing numerical features for consistency.
- Selecting the most relevant features using statistical tests.

### 4. Model Training & Evaluation
- Training different machine learning models such as Logistic Regression, Random Forest, and XGBoost.
- Using cross-validation techniques to assess model performance.
- Evaluating models using metrics such as accuracy, precision, recall, and F1-score.

### 5. Feature Importance & Insights
- Identifying the most influential features affecting loan approvals.
- Visualizing feature importance scores for interpretability.
- Drawing business insights to improve loan approval decision-making processes.
