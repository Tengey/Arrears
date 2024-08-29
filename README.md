# Predictive Model Identifying Customers Likely to Fall into Financial Difficulties

## Project Overview
This project aims to develop a predictive model that identifies customers who are likely to experience financial difficulties within a merchant bank setting. The model leverages synthetic data generation techniques to simulate various customer financial behaviours and contract statuses. The primary goal is to create a robust and accurate predictive system that can aid in early identification of at-risk customers.

## Project Structure
- **library_installation.ipynb**:Notebook for installing necessary library.
- **historical_data_generation.ipynb**: Google Colab notebook for generating synthetic data, introducing bias, and preparing the dataset.
- **data_cleaning.ipynb**: Notebook detailing the steps taken to clean and prepare the generated datasets for analysis.
- **data_exploration_preprocessing.ipynb**: Notebook for data exploration, preprocessing, and comparative analysis to prepare data for modelling.
- **model_dev_lr.ipynb**: Notebook focused on developing a Logistic Regression model.
- **model_dev_nn.ipynb**: Notebook for developing a Neural Network model.
- **model_dev_rf.ipynb**: Notebook for developing a Random Forest model.
- **model_dev_gb.ipynb**: Notebook for developing a Gradient Boosting model.
- **README.md**: Project documentation providing an overview of the project and instructions for replication.

## Environment Setup

### Google Colab Setup
1. **Access Google Colab**: Ensure you have a Google account to use Google Colab, a cloud-based Jupyter notebook environment.
2. **Install Required Libraries**: The project requires specific Python libraries, including Faker for synthetic data generation. 
3. **Clone Repository**: Clone the GitHub repository containing the project files into your Google Colab environment.

## Running the Code

### Data Generation
- **Data Generation Process**: The project generates synthetic historical data to simulate customer contracts and financial behaviours. Open `historical_data_generation.ipynb` in Google Colab and execute the provided Python scripts to generate datasets with and without bias.
- **Dataset Files**:
  - `historical_arrears_data_1.pkl`: Unbiased dataset.
  - `historical_arrears_data_2.pkl`: Biased dataset.

### Data Cleaning
- **Data Cleaning Process**: The generated datasets are cleaned by handling missing values, converting data types, and ensuring consistency. Detailed steps for data cleaning are provided in `data_cleaning.ipynb`.

### Data Exploration and Preprocessing
- **Data Exploration**: Comparative analysis is conducted to explore and preprocess the data, making it ready for model training and testing. Detailed steps are documented in `data_exploration_preprocessing.ipynb`.

### Data Preprocessing
- **Feature Engineering**: Target and feature variables are defined and encoded.
- **Train-Test Split**: The dataset is split into training and testing sets in an 80:20 ratio.

## Model Development
- **Logistic Regression Model**: Developed in `model_dev_lr.ipynb`, focusing on binary classification for predicting customer financial difficulties.
- **Neural Network Model**: Explored in `model_dev_nn.ipynb`, leveraging deep learning techniques for enhanced predictive accuracy.
- **Random Forest Regressor Model**: Developed in `model_dev_rf.ipynb`, utilizing ensemble learning for robust predictions.
- **Gradient Boosting Regressor Model**: Explored in `model_dev_gb.ipynb`, focusing on boosting techniques to improve model performance.

## Contact Information
For further inquiries or assistance, please contact:
- **Email**: edtengey@st.ug.edu.gh
- **GitHub Repository**: [https://github.com/Tengey/Arrears.git](https://github.com/Tengey/Arrears.git)

## Additional Notes
- **Dependencies**: Ensure all dependencies are installed before running the code.
- **Documentation**: Document any modifications or additional functionality introduced into the project.
- **Instructions**: Provide clear instructions for replicating the data generation process and exploring dataset comparisons.
- **Contributions**: Contributions to the project are welcome. Please fork the repository, create a new branch, and submit a pull request with your changes.
