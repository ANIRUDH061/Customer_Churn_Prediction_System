## Customer_Churn_Prediction_System
A Machine Learning project that predicts whether a customer will leave an e-commerce platform or continue using it. This system helps businesses identify risky customers early and improve customer retention.


# Project Overview
Customer churn means when a customer stops using a company’s service or platform. For any business, losing customers can reduce profit and growth.
In this project, I used customer behavior data from an e-commerce platform and applied Machine Learning techniques to predict churn.
The model learns from past customer records and predicts whether a customer is likely to churn or stay.

# Problem Statement
The goal of this project is to analyze customer data and build a predictive model that can classify customers into:
Churned Customer
Non-Churned Customer
This helps businesses take action before losing valuable customers.

# Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

# Dataset Description
The dataset contains customer-related information such as:
Customer demographics
Purchase behavior
Usage activity
Subscription details
Other business features
Target Column:
Churned = 1 → Customer Left
Churned = 0 → Customer Stayed

# Project Workflow

1.Import Required Libraries
Necessary Python libraries were imported for:
Data handling
Visualization
Machine learning
Evaluation

2.Load Dataset
The dataset was loaded using Pandas.

3.Data Understanding
Basic dataset analysis was performed:
Check rows and columns
Data types
Missing values
Summary statistics

4.Exploratory Data Analysis (EDA)
Visualizations were created to understand patterns in data.
Examples:
Churn distribution
Customer comparison
Feature relationships
Correlation heatmap

5.Data Preprocessing
Before training the model, data was cleaned and prepared.
Missing Values Handling
Missing values were filled using mean values

6.Train-Test Split
The dataset was divided into:
80% Training Data
20% Testing Data

7.Feature Scaling
Data was standardized using StandardScaler for better model performance.

8.Model Training
The Machine Learning model used in this project

9.Prediction
After training, predictions were made on test data.

10.Model Evaluation
The model performance was checked using:
Accuracy Score
Classification Report
Confusion Matrix

# Conclusion
In this project, I built a Machine Learning model to predict customer churn in an e-commerce platform.
I performed:
Data Analysis
Data Preprocessing
Visualization
Model Training
Prediction
Evaluation
This project shows how data science can solve real business problems and help companies retain customers.
