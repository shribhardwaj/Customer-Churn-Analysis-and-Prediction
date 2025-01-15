# Customer-Churn-Analysis-and-Prediction
Project Overview
This repository contains the code and resources for the Customer Churn Prediction project, which aims to predict customer churn for a business using machine learning. The project uses data preprocessing, exploratory data analysis (EDA), and machine learning techniques, specifically a Random Forest classifier, to predict the likelihood of customers leaving the service. The results can be used to inform retention strategies and improve customer experience.

Problem Statement
The goal of this project is to predict customer churn using historical customer data. The business needs to identify customers who are likely to churn in order to take preventive actions and improve customer retention. The key objectives are:

Data exploration and understanding key churn patterns.
Building a predictive model using machine learning to classify customers as likely to churn or stay.
Visualizing churn data with actionable insights for business decisions.
Dataset
The dataset contains customer information and features that might influence customer churn, such as:

Demographic information (age, gender, etc.)
Account information (subscription type, tenure, etc.)
Usage patterns (frequency, spend, etc.)
Historical churn data
The data is clean and ready for analysis, containing several important columns, including:

CustomerID
Churned (target variable)
Demographic and service-related features
Data Cleaning
Data Preprocessing: Performed data cleaning by removing duplicates and handling missing values.
Feature Engineering: Created new features such as account tenure from the Start Date column and performed transformations where needed.
Normalization: Normalized numerical features to ensure consistency across all input features.
Key Steps
1. ETL Process (SQL Server):
Used SQL Server to extract, clean, and transform raw data.
Conducted exploratory data analysis (EDA) to understand the underlying patterns in customer churn.
2. Exploratory Data Analysis (EDA):
Visualized churn rates, customer demographics, and trends using Power BI.
Identified key variables that influence customer churn, including Monthly Spend, Tenure, and Subscription Type.
3. Machine Learning Model:
Built a Random Forest classifier to predict customer churn.
The model achieved an accuracy of 84% with precision, recall, and feature importance analysis.
4. Data Visualization (Power BI):
Created an interactive dashboard to visualize:
Churn rates by customer demographics and account details.
Predicted churn likelihood for each customer.
Important factors affecting churn, such as tenure and monthly spend.
Used Power BI for the dashboard to allow for easy filtering and exploration of churn trends.
Technologies Used
SQL Server: Data extraction, transformation, and loading (ETL).
Python (Jupyter Notebook): Machine learning model development (Random Forest), data analysis, and model evaluation.
Power BI: Data visualization and dashboarding to present insights and predictions.
Excel: Exported churn predictions for further analysis and business use.
Results
Model Accuracy: The Random Forest classifier achieved 84% accuracy in predicting customer churn.
Key Insights:
High churn is correlated with customers having a low tenure and high monthly spend.
Predictive model helps identify customers at high risk of churning.
Dashboard visualizes churn rates and customer profiles for targeted retention efforts.
Project Files
Folder containing SQL scripts for data extraction and ETL processes.
Folder containing Python scripts for data preprocessing, model training, and prediction.
Jupyter notebook for building and evaluating the churn prediction model.
Power BI file with the interactive dashboard and visualizations.
Conclusion
This project showcases the application of machine learning and data visualization to predict customer churn. By leveraging data from multiple sources and building an accurate churn prediction model, businesses can identify high-risk customers and take proactive measures to reduce churn, ultimately improving retention strategies.
