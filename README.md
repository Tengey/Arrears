# Predictive Model for Identifying Customers in Financial Difficulties


## Project Overview

This project focuses on developing a predictive model to identify customers likely to experience financial difficulties in a merchant bank setting. 
The model utilizes synthetic data generation techniques to simulate various customer financial behaviours and contract statuses. 


## Project Structure

**historical_data_generation.ipynb:** Google Colab for generating synthetic data, introducing bias, and preparing the dataset.
**data files:** Files containing the generated datasets.
**models:** Files where trained models and related files will be stored.
**README.md:** Project documentation.


## Environment Setup

### Google Colab Setup

**Access Google Colab:**
Ensure you have a Google account to use Google Colab, a cloud-based Jupyter notebook environment.

**Install Required Libraries:**
The project requires the Faker library for synthetic data generation. Install it using the following command in a code cell:
!pip install faker

**Clone Repository:**
Clone the repository containing the project files from GitHub to your Google Colab environment.


## Running the Code

### Data Generation

**Data Generation Process:**
The project generates synthetic historical data to simulate customer contracts and financial behaviours.
Open `historical_data_generation.ipynb` in Google Colab.
Run the provided Python script to generate datasets with and without bias.

**Understanding Bias Introduction:**
**Functionality:** Bias is introduced into the 'Customer_Category' column to simulate scenarios where certain customer types are more prevalent.
**Code Execution:** Use the provided functions (generate_customer_category, introduce_bias) to modify the dataset accordingly.

### Comparing Datasets

**Dataset Files:**

**historical_arrears_data_1.csv** --> Unbiased dataset.
**historical_arrears_data_2.csv** --> Dataset with bias introduced in the 'Customer_Category' column.


## Data Files

The historical data used in this project can be downloaded from the following links respectively as per the above:

### [Download Historical Data 1](https://drive.google.com/file/d/1T9X0B-S6FbrczHEsJIlw-iarcjqt8FF2/view?usp=drive_link)

### [Download Historical Data 2](https://drive.google.com/file/d/1ZzkvOdmZ4cRWBBHr0xVQPFdFPSxNVu_J/view?usp=drive_link)


## Synthetic Data Generation

Synthetic data is generated using Python's random module and the Faker library to replicate realistic customer financial contract scenarios.
Explore the impact of bias on predictive modelling by comparing datasets with different bias levels.
The synthetic data generation process involves creating a dataset that simulates real-world financial transactions and customer behaviours. Key features include:

**Customer_ID**: Unique identifier for each customer.
**Contract_Term**: Duration of the financial contract in months.
**Contract_Start_Date**: Start date of the contract.
**Contract_End_Date**: End date of the contract.
**Cost_Amount_GBP**: Cost of the asset in GBP.
**Regulatory_Compliance**: Whether the contract is compliant with regulations.
**Customer_Category**: Type of customer (e.g., Corporation, Individual).
**Exposure_Amount_GBP**: Amount of exposure in GBP.
**Contract_Status**: Status of the contract (e.g., Active, Closed).
**Assistance_Flag**: Indicator if the customer received financial assistance.
**Risk_Flag**: Indicator if the customer is considered high risk.
**Payment_Status**: Current payment status (e.g., Delinquent, Current).
**Forbearance_Amount_GBP**: Amount in GBP for forbearance.
**Payment_Interval**: Frequency of payments (e.g., Monthly).
**Late_Payment_Fees_GBP**: Amount of late payment fees in GBP.
**Total_Arrears_GBP**: Total amount of arrears in GBP.


## Contact Information
For further inquiries or assistance, please contact:
Email: edtengey@st.ug.edu.gh
GitHub Repository: [https://github.com/Tengey/Arrears.git]


## Additional Notes
Ensure all dependencies are installed before running the code.
Document any modifications or additional functionality introduced to the project.
Provide clear instructions for replicating the data generation process and exploring dataset comparisons.
Contributions to the project are welcome. Please fork the repository, create a new branch, and submit a pull request with your changes.
