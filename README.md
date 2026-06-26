Markdown
# Customer Churn Prediction and Customer Segmentation System

## Overview

This project is a Machine Learning system that performs two important business analytics tasks:

1. **Customer Churn Prediction**
2. **Customer Segmentation**

The project predicts whether a customer is likely to leave the company and also groups customers into meaningful segments using clustering.

---

## Project Objectives

- Analyze customer behavior using Exploratory Data Analysis.
- Predict customer churn using Machine Learning classification models.
- Segment customers based on usage, charges, tenure, support tickets, and satisfaction.
- Help businesses identify high-risk customers and create targeted retention strategies.

---

## Dataset

The dataset used in this project is a synthetic customer churn dataset created for learning and project demonstration purposes.

### Dataset File

```txt
customer_churn_data.csv
Dataset Columns
Column Name	Description
CustomerID	Unique customer ID
Gender	Customer gender
Age	Customer age
Tenure	Number of months the customer has stayed
MonthlyCharges	Monthly billing amount
TotalCharges	Total amount charged to the customer
ContractType	Type of customer contract
InternetService	Internet service type
PaymentMethod	Payment method used by customer
SupportTickets	Number of support tickets raised
DataUsageGB	Monthly data usage in GB
SatisfactionScore	Customer satisfaction score from 1 to 5
Churn	Target variable, 1 means churn and 0 means not churn
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Jupyter Notebook / Google Colab
Machine Learning Tasks
1. Customer Churn Prediction

Customer churn prediction is performed using classification models.

Models Used
Logistic Regression
Random Forest Classifier
Evaluation Metrics
Accuracy Score
ROC-AUC Score
Classification Report
Confusion Matrix
ROC Curve
2. Customer Segmentation

Customer segmentation is performed using the K-Means clustering algorithm.

Algorithm Used
K-Means Clustering
Features Used for Segmentation
Age
Tenure
MonthlyCharges
TotalCharges
SupportTickets
DataUsageGB
SatisfactionScore
Segment Types

The customers are grouped into segments such as:

At Risk Customers
High Value Customers
Regular Customers
Project Files
Txt
customer-churn-segmentation-ml/
│
├── Customer_Churn_Prediction_and_Segmentation.ipynb
├── README.md
├── customer_churn_data.csv
├── churn_prediction_model.pkl
└── segmented_customers.csv
File Description
File Name	Description
Customer_Churn_Prediction_and_Segmentation.ipynb	Main Jupyter Notebook containing complete ML code
README.md	Project documentation
customer_churn_data.csv	Dataset used for training and analysis
churn_prediction_model.pkl	Saved churn prediction model
segmented_customers.csv	Dataset with customer segment labels
Project Workflow
Import required libraries
Load customer churn dataset
Perform basic data analysis
Visualize churn distribution
Preprocess numerical and categorical features
Train churn prediction models
Evaluate model performance
Select the best model
Save the trained model
Apply K-Means clustering for customer segmentation
Visualize customer segments using PCA
Save segmented customer data
Installation

Install the required Python libraries:

Bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib notebook

If you are using Google Colab, run:

Python
!pip install pandas numpy matplotlib seaborn scikit-learn joblib
How to Run the Project
Option 1: Using Jupyter Notebook

Clone or download this repository.

Open terminal in the project folder.

Run:

Bash
jupyter notebook
Open:
Txt
Customer_Churn_Prediction_and_Segmentation.ipynb
Run all cells.
Option 2: Using Google Colab
Open Google Colab:
Txt
https://colab.research.google.com
Upload the notebook file:
Txt
Customer_Churn_Prediction_and_Segmentation.ipynb
Upload the dataset:
Txt
customer_churn_data.csv
Run all cells.
Model Output

After running the notebook, the project generates:

Txt
churn_prediction_model.pkl
segmented_customers.csv
Results

The churn prediction model helps identify customers who may leave the service.

The segmentation model groups customers into meaningful categories:

Customers with high churn risk
Customers with high value
Regular customers

These insights can help a company improve customer retention and marketing strategies.

Business Use Case

This project can help companies:

Identify customers likely to churn
Improve customer retention strategies
Create personalized marketing campaigns
Understand customer behavior
Focus on high-value customers
Reduce customer loss
Future Improvements
Use real-world customer data
Add more customer behavior features
Try advanced models like XGBoost or LightGBM
Deploy the model using Flask or Streamlit
Build an interactive dashboard
Add automated customer churn alerts
Author

Created as a Machine Learning project for Customer Churn Prediction and Customer Segmentation.

License

This project is for educational and learning purposes.
