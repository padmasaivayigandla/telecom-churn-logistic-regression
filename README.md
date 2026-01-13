Telecom Churn Prediction using Logistic Regression
==================================================
Project Overview: 
Customer churn is a critical challenge in the telecom industry. This project focuses on predicting whether a telecom customer is likely to **churn (leave the service)** or **retain**, using historical customer data and **Logistic Regression**.

The goal is to help the business identify high-risk customers early and take proactive retention measures.

Problem Statement:
Using customer demographic, account, and usage data with 21 predictor variables, build a machine learning model to predict customer churn.

- **Target Variable:** `Churn` (Yes / No)
- **Business Objective:** Reduce customer churn by identifying high-risk customers

Dataset Description
===================
The dataset is divided into multiple CSV files:

- `churn-data.csv` – Target variable and churn labels
- `customer-data.csv` – Customer demographic details
- `internet-data.csv` – Internet service usage and plans
- `Telecom-Churn-Data-Dictionary.csv` – Description of all variables

Total records represent telecom customers over a defined time period.
> Note: The dataset is part of an academic case study and is not publicly shareable.

Tools & Technologies Used
=========================
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

Approach & Methodology
======================
1. **Data Understanding & Merging**
   - Combined multiple datasets into a single analytical dataset
   - Reviewed data dictionary for feature understanding

2. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Converted categorical variables using dummy encoding
   - Standardized numerical features

3. **Exploratory Data Analysis (EDA)**
   - Analyzed churn distribution
   - Identified key churn drivers
   - Visualized relationships between features and churn

4. **Model Building**
   - Built a Logistic Regression model
   - Checked multicollinearity using VIF
   - Selected statistically significant features

5. **Model Evaluation**
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Curve

6. **Business Interpretation**
   - Interpreted coefficients to understand churn drivers
   - Translated results into actionable business insights

Key Insights:
- Customers with **month-to-month contracts** are more likely to churn
- **Higher monthly charges** increase churn probability
- **Longer tenure** significantly reduces churn risk
- Add-on services improve customer retention

Model Performance:
- Logistic Regression provided strong interpretability
- Balanced precision and recall for churn prediction
- ROC-AUC used to validate classification effectiveness

How to Run the Project:
1. Clone the repository
2. Install required Python libraries
3. Open the Jupyter Notebook
4. Run all cells sequentially

Conclusion:
This project demonstrates how **logistic regression** can be effectively used to solve real-world business problems like customer churn. The model provides both **predictive power** and **business interpretability**, enabling data-driven retention strategies.

Author

Padmasaivayigandla

Data Analyst | Machine Learning Enthusiast 
