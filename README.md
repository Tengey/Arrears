Project Overview
This project focuses on developing a predictive model to identify customers likely to experience financial difficulties in a merchant bank setting. The model utilizes synthetic data generation techniques to simulate various customer financial behaviours and contract statuses.

Environment Setup

Google Colab Setup

Access Google Colab:
Ensure you have a Google account to use Google Colab, a cloud-based Jupyter notebook environment.

Install Required Libraries:
The project requires the Faker library for synthetic data generation. Install it using the following command in a code cell:
!pip install faker

Clone Repository:
Clone the repository containing the project files from GitHub to your Google Colab environment.

Running the Code

Data Generation

Data Generation Process:
The project generates synthetic historical data to simulate customer contracts and financial behaviours.
Run the provided Python script to generate datasets with and without bias.

Understanding Bias Introduction:
Functionality: Bias is introduced into the 'Customer_Category' column to simulate scenarios where certain customer types are more prevalent.
Code Execution: Use the provided functions (generate_customer_category, introduce_bias) to modify the dataset accordingly.

Comparing Datasets:

Dataset Files:
historical_arrears_data_1.csv: Unbiased dataset.
historical_arrears_data_2.csv: Dataset with bias introduced in the 'Customer_Category' column.

Synthetic Data Generation

Synthetic data is generated using Python's random module and the Faker library to replicate realistic customer financial contract scenarios.
Explore the impact of bias on predictive modelling by comparing datasets with different bias levels.

Contact Information
For further inquiries or assistance, please contact:
Email: edtengey@st.ug.edu.gh
GitHub Repository: [https://github.com/Tengey/Arrears.git]

Additional Notes
Ensure all dependencies are installed before running the code.
Document any modifications or additional functionality introduced to the project.
Provide clear instructions for replicating the data generation process and exploring dataset comparisons.
