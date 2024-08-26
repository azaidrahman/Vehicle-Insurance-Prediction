# Insurance Customer Segmentation Project Summary

## Project Overview
Develop a predictive model for an Insurance company to determine which of their existing Health Insurance policyholders are likely to be interested in a new Vehicle Insurance policy. The model will be built using PyTorch and Scikit.

## Business Context

- The client is an Insurance company that currently provides Health Insurance to its customers.
- They want to predict which of their existing policyholders from the past year might be interested in a new Vehicle Insurance policy.
- This prediction will help the company tailor its communication strategy and optimize its business model and revenue.

## Data Source

Kaggle Dataset: [Health Insurance Cross Sell Prediction](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction)

## Data Description

The dataset contains information about insurance policyholders, including:

### Training Data

| Variable | Definition |
|----------|------------|
| id | Unique ID for the customer |
| Gender | Gender of the customer |
| Age | Age of the customer |
| Driving_License | 0: Customer does not have DL, 1: Customer has DL |
| Region_Code | Unique code for the customer's region |
| Previously_Insured | 1: Customer has Vehicle Insurance, 0: Customer doesn't |
| Vehicle_Age | Age of the Vehicle |
| Vehicle_Damage | 1: Vehicle damaged in the past, 0: No damage |
| Annual_Premium | Amount customer pays as premium per year |
| Policy_Sales_Channel | Anonymized code for customer outreach channel |
| Vintage | Number of days customer associated with the company |
| Response | 1: Customer interested, 0: Customer not interested (target variable) |

## Project Steps
1. Data Preparation: Load and preprocess data using Pandas
2. Model Development: Create a simple machine-learning model using PyTorch
3. Model Training: Train the model on the preprocessed data
4. Inference : Use the trained model and determine binary classification

## Key Skills Demonstrated
- PyTorch for neural network development
- Binary classification modeling
- Data preprocessing with Pandas
- Business interpretation of model results

This project showcases the ability to deploy a machine learning solution using PyTorch and Scikit, demonstrating skills in data preprocessing, model development, and cloud deployment in an insurance context.

## Development Environment

- Jupyter Notebook for all stages of development
- Local development for initial stages
- AWS SageMaker Notebook Instance for later stages and deployment

## Project Goal

The primary goal is to build a model that accurately predicts which existing Health Insurance policyholders are likely to be interested in Vehicle Insurance. This will enable the company to:

1. Target their marketing efforts more effectively
2. Optimize their communication strategy
3. Potentially increase their revenue from Vehicle Insurance policies

## Note on Project Evaluation
All code and thought processes will be documented in Jupyter Notebooks to provide a clear, step-by-step demonstration of the project development. 
