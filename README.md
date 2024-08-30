# Travel Insurance Risk Assessment, Premium Pricing, and Customer Segmentation Model
## logistic-regression-on-travel-insurance-prediction-claims
Build Machine learning model with logistic regression for Enhancing Potential Growth Customer and Minimize Potential Claim Risk on Travel Insurance Company

## Overview

This repository contains an IPython notebook that demonstrates a comprehensive approach to building and evaluating a logistic regression model aimed at solving key problems in the travel insurance industry, including risk assessment, premium pricing, and customer segmentation.

## Project Structure

- **Notebook:** `travel_insurance_model.ipynb`
  - Includes detailed steps from data preprocessing, model training, and evaluation to business applications.
  - Utilizes various techniques like SMOTE, ADASYN, and RandomOverSampler to handle class imbalance in the dataset.
  - Employs Logistic Regression with a focus on optimizing ROC AUC, Precision, and Recall metrics.
  - Presents insights and recommendations for business decision-making based on model outputs.

## Key Components

### 1. **Risk Assessment**
   - **Objective:** Improve the prediction accuracy of claims made by policyholders.
   - **Methods Used:** Logistic Regression with SMOTE, ADASYN, and RandomOverSampler techniques.
   - **Outcome:** Identified key features contributing to risk, providing actionable insights for underwriting decisions.

### 2. **Premium Pricing**
   - **Objective:** Implement dynamic pricing strategies based on assessed risk.
   - **Methods Used:** Odds ratios derived from the logistic regression model to adjust premiums.
   - **Outcome:** A pricing model that aligns premiums with the likelihood of claims, optimizing profitability.

### 3. **Customer Segmentation**
   - **Objective:** Segment customers based on risk profiles for targeted marketing and retention strategies.
   - **Methods Used:** Risk-based and behavioral segmentation.
   - **Outcome:** Tailored marketing campaigns and product offerings, enhancing customer retention and satisfaction.

## Data
- **Dataset:** The notebook uses a travel insurance dataset containing features like age, gender, net sales, commission, and claim status. The dataset is preprocessed to handle missing values, encode categorical variables, and scale numerical features.

## Installation
