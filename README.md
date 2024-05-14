# Propensify : Identifying Customer Response to Marketing Campaigns #
Welcome to the Propensify project repository! This comprehensive notebook provides a detailed walkthrough of our groundbreaking approach to identifying customer responses to marketing campaigns. From development to deployment, this notebook covers every step of the process, offering insightful analyses and hands-on demonstrations.

# Overview #
In this project, we aim to develop a model that accurately predicts customer responses to marketing campaigns. By leveraging machine learning techniques and thorough data analysis, we can optimize marketing strategies and enhance campaign effectiveness.

# Notebook Contents #
Define IAM Role: Setting up the necessary IAM role for accessing AWS services.

Dependencies and Imports: Importing required libraries and packages for data analysis and model training.

Load Dataset: Loading the dataset from Amazon S3 and merging the train and test datasets into a Pandas DataFrame.

Data Preprocessing: Dropping unnecessary columns, handling missing values, balancing the dataset, and performing feature engineering.

Correlation Analysis: Analyzing the correlation between different features in the dataset.

Splitting Data: Splitting the dataset into features and target variables for model training.

Training Model: Training an XGBoost model using Amazon SageMaker.

Deploying Model: Deploying the trained model using Amazon SageMaker for real-time inference.

Making Predictions: Making predictions using the deployed model and evaluating its performance.

Cleanup: Deleting the deployed endpoint and concluding the notebook.
Usage

To replicate our results or apply the model to your own dataset, follow these steps:

Clone the repository to your local machine.
Set up an AWS account and configure IAM roles with appropriate permissions.
Ensure you have the necessary dependencies installed (see Dependencies and Imports section).
Replace the dataset paths with your own data or upload your dataset to Amazon S3.
Run the notebook cells sequentially.

## Author ##
Riddhi Sharma - Data Scientist
