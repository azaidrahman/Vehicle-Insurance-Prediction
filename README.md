# Insurance Customer Segmentation Project Summary

## Project Overview
Customer segmentation model for an insurance company using PyTorch and deploy it on AWS SageMaker. The model will help predict customer interest in vehicle insurance based on various demographic and insurance-related features.

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

### Test Data
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

### Final Data

| Variable | Definition |
|----------|------------|
| id | Unique ID for the customer |
| Vintage | Number of days customer associated with the company |

## Project Steps
1. Data Preparation: Load and preprocess data using Pandas
2. Model Development: Create a simple autoencoder using PyTorch
3. AWS SageMaker Deployment: Deploy the model on AWS SageMaker
4. Visualization: Create basic visualizations of customer segments

## Key Skills Demonstrated
- PyTorch for neural network development
- AWS SageMaker for model deployment
- Data preprocessing with Pandas
- Basic data visualization
- Understanding of dimensionality reduction and customer segmentation

This project showcases the ability to deploy a machine learning solution using PyTorch and AWS, demonstrating skills in data preprocessing, model development, and cloud deployment in an insurance context.
