# Customer Churn Analysis and Prediction Project

## Project Overview
This project aims to analyze customer churn behavior for a telecommunications company. It involves cleaning and preparing the dataset, performing exploratory data analysis (EDA), segmenting customers, building a churn prediction model, devising retention strategies, and creating a rich set of visualizations.

**Objective:**
- Identify customers who are likely to churn.
- Understand key factors influencing churn.
- Suggest strategies to retain customers.

## Dataset
The dataset used for this project is the **Telco Customer Churn Dataset**. It contains information about customers' demographics, account details, services subscribed, and whether they have churned.

## Tasks Completed

### Task 1: Data Cleaning and Preprocessing
- Handled missing values, especially in the `TotalCharges` column.
- Converted categorical variables into numerical representations using `LabelEncoder`.
- Dropped irrelevant columns like `customerID`.

### Task 2: Exploratory Data Analysis (EDA)
- Calculated overall churn rate.
- Explored customer distribution based on gender, contract type, payment method.
- Analyzed tenure distribution.
- Visualized relationships between churn and different services.

### Task 3: Customer Segmentation
- Segmented customers based on tenure (New, Intermediate, Loyal).
- Analyzed churn rates across these segments.
- Created a "High Charges" segmentation for monthly charges.

### Task 4: Churn Prediction Model
- Built a Logistic Regression model to predict churn.
- Evaluated the model using accuracy score, confusion matrix, and classification report.

### Task 5: Customer Retention Strategies
- Identified top features influencing churn.
- Calculated customer Lifetime Value (LTV).
- Highlighted high-value customers at risk of churning.
- Proposed data-driven retention strategies.

### Task 6: Visualizations
- Created multiple visualizations to uncover insights:
  - Count plots for gender, contract, internet service, senior citizen.
  - Heatmap for feature correlations.
  - Histograms for tenure and monthly charges.
  - Boxplots and violin plots for churn analysis.
  - Scatter plot for tenure vs monthly charges.
  - Pair plots for multivariate analysis.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Load the dataset `Telco_Customer_Churn_Dataset.csv`.

3. Run the Python script to execute all tasks step-by-step.

4. Visualizations will be automatically generated during EDA and Task 6.

## Results
- Achieved a decent churn prediction model using Logistic Regression.
- Identified significant churn factors like contract type, tenure, internet service.
- Proposed targeted retention strategies.

## Conclusion
This project provides actionable insights into customer churn behavior, identifies high-risk customers, and suggests practical strategies to improve retention. The combination of machine learning and business understanding enables a robust approach to minimizing churn.

