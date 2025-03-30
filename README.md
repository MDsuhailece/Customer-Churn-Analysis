# Project Overview
This project analyzes customer churn behavior using a dataset containing customer demographics, service usage, contract details, and payment preferences. The goal is to identify key factors contributing to churn and provide actionable recommendations to improve customer retention

# Key Features
✔ Data Cleaning & Preprocessing: Handles missing values, converts data types, and refines categorical variables.

✔ Exploratory Data Analysis (EDA): Analyzes customer demographics, service subscriptions, and contract preferences.

✔ Churn Prediction Analysis: Identifies high-risk customer segments based on tenure, payment methods, and services.

✔ Data Visualization: Generates bar charts, histograms, and correlation heatmaps to highlight trends.

✔ Actionable Insights & Recommendations: Provides data-driven strategies to reduce churn and improve retention.

# Repository Contents
📂 data/ – Contains the customer churn dataset.
📂 notebooks/ – Jupyter Notebook with analysis and visualizations.
📂 scripts/ – Python scripts for data processing and visualization.
📄 README.md – Overview of the project, findings, and setup instructions.

# Data Sources
The dataset used in this analysis contains customer details, including:

Demographics: Gender, Senior Citizen, Dependents

Service Usage: Phone Service, Internet Service, Streaming Services

Contract & Payments: Monthly/Yearly Contract, Payment Methods

Churn Status: Whether the customer left or stayed

# Installation
To run this project locally, you'll need the following Python libraries:

pandas: For data manipulation and analysis.
matplotlib: For creating visualizations.
seaborn: For advanced statistical plots.
numpy: For numeric computations. This project utilizes several Python libraries that are typically pre-installed in Jupyter Notebook environments. To get started, ensure the following libraries are available:
import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

import numpy as np

If you are running this project in an environment where these libraries are not pre-installed, you can install them using:

pip install pandas numpy matplotlib seaborn 

# Results
✅ Overall churn rate: ~26.54% of customers leave the service.

✅ High churn in month-to-month contracts: 45% churn vs. 5% for 2-year contracts.

✅ Senior citizens churn more: 40% churn vs. 20% for younger customers.

✅ Customers without security services churn more: 35% churn vs. 15% for protected users.

✅ Electronic check payment users have the highest churn: 40% churn vs. 18% for auto-pay users.

# Visualizations
📊 Churn distribution by tenure, service type, and payment methods

📈 Contract type vs. churn percentage

📉 Feature importance analysis using correlation and machine learning models

# Key Insights
Customers with short tenures (1-6 months) have a 45% churn rate—early retention strategies are crucial.

Month-to-month customers churn significantly more (45%)—long-term contracts improve retention.

Lack of Online Security & Tech Support increases churn risk by 20%.

Fiber optic internet customers leave more often (30% churn)—price sensitivity may be a factor.

Electronic check users churn at 40%—offering better payment options can help.

# Recommendations
🔹 Enhance Early Engagement: Provide discounts, onboarding support, and personalized communication within the first 3 months.
🔹 Promote Long-Term Contracts: Incentivize customers to switch from month-to-month plans to annual contracts.
🔹 Encourage Service Bundling: Offer discounted packages for security and support services to reduce churn.
🔹 Improve Payment Flexibility: Convert electronic check users to auto-pay by offering small incentives.
🔹 Target At-Risk Customers: Use predictive analytics to proactively retain high-risk customers.
