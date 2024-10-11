# Predicting Customer Financial Difficulties using Machine Learning

## Project Overview
This project aims to build and evaluate machine learning models that predict whether customers are likely to fall into arrears or face financial difficulties. Using a synthetic dataset generated with the Faker library, the project implements feature engineering, exploratory data analysis (EDA), and various machine learning models for classification.

## Project Structure
- **data_generation.ipynb**: Notebook for data generation.
- **data_cleaning_.ipynb**: Notebook detailing the steps taken to clean and prepare the generated dataset for analysis.
- **data_preprocessing.ipynb**: Notebook for data exploration, preprocessing, EDA, and feature engineering.
- **model_dev_lr_.ipynb**: Notebook focused on developing Logistic Regression model.
- **model_dev_rf_.ipynb**: Notebook for developing Random Forest model.
- **model_dev_gb+.ipynb**: Notebook for developing Gradient boosting, XGBoost, LGBM, SVC, Decision Tree, Extra Trees, and CatBoost models.
- **README.md**: Project documentation providing an overview of the project and instructions for replication.

## Environment Setup

### Google Colab Setup
1. **Access Google Colab**: Ensure you have a Google account to use Google Colab, a cloud-based Jupyter notebook environment.
2. **Install Required Libraries**: The project requires specific Python libraries, including Faker for synthetic data generation.
pandas
scikit-learn
catboost
xgboost
lightgbm
matplotlib
seaborn
numpy
Faker 
4. **Clone Repository**: Clone the GitHub repository containing the project files into your Google Colab environment.

## Dataset Features
The synthetic dataset includes the following columns, which resemble common customer and contract features in a banking context:

**Contract_Term:** Loan duration in months.
**Contract_Start_Date:** The start date of the contract.
**Contract_End_Date:** The end date of the contract.
**Cost_Amount_GBP:** The asset cost in GBP.
**Regulatory_Compliance:** Indicates whether the contract complies with regulatory standards (Yes/No).
**Customer_Category:** Type of customer (Corporation, Individual, Small Business, Sole Proprietorship, LLC).
**Exposure_Amount_GBP:** The customer’s total financial exposure in GBP.
**Contract_Status:** Current contract status (Closed, Expired, Active).
**Assistance_Flag:** Whether the customer has received assistance (Yes/No).
**Risk_Flag:** Whether the customer is considered at risk of financial difficulty.
**Payment_Status:** Current payment status (Delinquent, Current, Recovered).
**Forbearance_Amount_GBP:** Amount in forbearance in GBP.
**Payment_Interval:** Frequency of payments (Monthly, Quarterly, Annual).
**Late_Payment_Fees_GBP:** Fees incurred for late payments in GBP.
**Total_Arrears_GBP:** Total arrears in GBP.

## Running the Code - Notebooks Overview

### 1. data_generation.ipynb
This notebook generates a synthetic dataset using the Faker library. It simulates customer data with realistic contract terms, payment statuses, and financial information. The key columns include:

Contract_Term, Contract_Start_Date, Contract_End_Date
Cost_Amount_GBP, Exposure_Amount_GBP
Customer_Category, Payment_Status
Total_Arrears_GBP, Late_Payment_Fees_GBP

### 2. data_cleaning_.ipynb
This notebook focuses on cleaning the generated dataset:

Identifies and handles missing values.
Converting data types.
Ensuring consistency.

### 3. data_preprocessing.ipynb
This notebook performs exploratory data analysis (EDA) and feature engineering. It includes:

EDA: Insights on distributions, correlations, and summary statistics for key features.
Feature Engineering:
Debt-to-Exposure Ratio: Ratio of Total_Arrears_GBP to Exposure_Amount_GBP.
Arrears as Percentage of Asset Cost: A percentage column comparing arrears to asset cost.
Arrears Flag: A binary flag indicating whether a customer is in arrears.
Data Splitting: Splits the data into training and testing sets (80-20 ratio).

### 4. model_dev_lr_.ipynb
This notebook trains and evaluates a Logistic Regression model:

Implements LogisticRegression from sklearn.
Evaluates model performance using metrics such as accuracy, precision, recall, and F1-score.

### 5. model_dev_rf_.ipynb
This notebook implements a Random Forest Classifier:

Trains a RandomForestClassifier model.
Features hyperparameter tuning via cross-validation.
Evaluates model performance using the same metrics as logistic regression.

### 6. model_dev_gb+.ipynb
This notebook explores multiple advanced machine learning models, including:

Gradient Boosting Classifier
XGBoost
LGBM
Support Vector Classifier (SVC)
Decision Tree
Extra Trees
CatBoost Classifier

## Conclusion
This project successfully predicts whether a customer is likely to fall into arrears using machine learning. The use of synthetic data allowed us to simulate a realistic banking scenario, and feature engineering, coupled with model selection, played a crucial role in improving model performance.

## Contact Information
For further inquiries or assistance, please contact:
- **Email**: edtengey@st.ug.edu.gh
- **GitHub Repository**: [https://github.com/Tengey/Arrears.git](https://github.com/Tengey/Arrears.git)

## Additional Notes
- **Dependencies**: Ensure all dependencies are installed before running the code.
- **Documentation**: Document any modifications or additional functionality introduced into the project.
- **Instructions**: Provide clear instructions for replicating the data generation process and exploring dataset comparisons.
- **Contributions**: Contributions to the project are welcome. Please fork the repository, create a new branch, and submit a pull request with your changes.
