# Customer Churn Prediction

## Introduction
Customer churn is a critical issue for businesses that operate on a subscription model, such as telecom providers, streaming platforms, and SaaS companies. Predicting and mitigating customer churn can significantly impact revenue, customer retention strategies, and overall operational efficiency.

This project explores the use of machine learning models to predict customer churn based on various factors such as customer tenure, monthly charges, and service subscriptions. Two models are implemented and compared:
- **Logistic Regression**
- **Random Forest Classifier**

By identifying key factors influencing churn, businesses can take proactive steps to improve customer retention and minimize losses.

## Research Objectives
- **Accurate Prediction**: Develop predictive models to identify high-risk customers likely to churn.
- **Feature Importance Analysis**: Determine the most influential factors contributing to customer attrition.
- **Business Impact**: Provide actionable insights for businesses to implement retention strategies and improve customer loyalty.

## Dataset
The project utilizes the **Telecom Customer Churn Dataset** from Kaggle, which includes:
- **Churn Indicator**: Whether the customer has left the service.
- **Service Subscriptions**: Phone, internet, online security, and other add-ons.
- **Account Details**: Tenure, contract type, billing method, and charges.
- **Customer Demographics**: Gender, age, senior status, dependents, and partners.

## Methodology
### Exploratory Data Analysis (EDA)
- **Churn Distribution**: Understanding the proportion of churned vs. retained customers.
- **Key Variables**: Analyzing tenure, monthly charges, and total charges distributions.
- **Feature Importance**: Determining the most relevant factors contributing to churn.

### Machine Learning Models
#### **1. Logistic Regression**
- A linear model that estimates churn probability based on feature weights.
- Provides interpretability and computational efficiency.

#### **2. Random Forest Classifier**
- An ensemble learning method that constructs multiple decision trees.
- Captures complex patterns and ranks feature importance effectively.

### Model Evaluation Metrics
- **Accuracy**: Measures overall correct classification.
- **Precision**: Proportion of correctly predicted positive churn cases.
- **Recall**: Ability to identify actual churn cases.
- **ROC AUC**: Model's ability to differentiate between churned and non-churned customers.

## Results
- **Random Forest achieved an accuracy of ~79.7%** with an ROC AUC of 84%.
- **Logistic Regression performed better in precision and recall** but had limitations in capturing complex relationships.
- **Feature Importance Analysis** revealed that **monthly charges, tenure, and total charges** significantly influence churn probability.

## Business Implications
### Strategies for Reducing Churn:
1. **Targeted Retention Programs**: Identify high-risk customers and offer tailored discounts or loyalty programs.
2. **Service Optimization**: Improve service quality, particularly internet, security, and tech support.
3. **Flexible Payment & Contract Options**: Allow customers to choose plans that align with their needs.
4. **Predictive Communication**: Personalize marketing and customer service interventions based on predictive analytics.

## Implementation
The project is implemented in **Google Colab** using Python and the following libraries:
- **Pandas, NumPy**: Data preprocessing and analysis
- **Matplotlib, Seaborn**: Data visualization
- **Scikit-learn**: Machine learning models and evaluation metrics


## Conclusion
This project demonstrates how machine learning can be used to predict customer churn and provide actionable insights for businesses. By implementing data-driven retention strategies, companies can improve customer satisfaction and reduce attrition rates.



