# Health_Insurance_Cross_Sell_Prediction
## Introduction
The project focuses on predicting whether customers who have health insurance would also be interested in purchasing vehicle insurance. The dataset consists of 381,109 rows and 12 columns, forming the basis of the analysis.
## Objective
The main objective of the project is to build a predictive model that identifies customers likely to adopt vehicle insurance. This model helps optimize the company's marketing strategy, leading to increased revenue and better resource allocation.
## Libraries and Tools Used
NumPy and Pandas for data manipulation and analysis.

Matplotlib and Seaborn for data visualization.

Plotly Express for interactive visualizations.

Scikit-Learn for machine learning algorithms.

LabelEncoder for encoding categorical features.

MinMaxScaler for feature scaling.

SMOTE for addressing class imbalance.
## Data Overview
The dataset contains information about demographics, vehicle details, and policy information. Key features include Age, Gender, Vehicle Age, Vehicle Damage, Policy Sales Channel, and Response (target variable).
| Feature Name          | Type          | Description                                                                                 |
|-----------------------|---------------|---------------------------------------------------------------------------------------------|
| id                    | (continuous)  | Unique identifier for the Customer.                                                         |
| Age                   | (continuous)  | Age of the Customer.                                                                       |
| Gender                | (dichotomous) | Gender of the Customer.                                                                    |
| Driving_License       | (dichotomous) | 0 for customer not having DL, 1 for customer having DL.                                   |
| Region_Code           | (nominal)     | Unique code for the region of the customer.                                                |
| Previously_Insured    | (dichotomous) | 0 for customer not having vehicle insurance, 1 for customer having vehicle insurance.     |
| Vehicle_Age           | (nominal)     | Age of the vehicle.                                                                        |
| Vehicle_Damage        | (dichotomous) | Customer got their vehicle damaged in the past. 0: No, 1: Yes.                             |
| Annual_Premium        | (continuous)  | The amount the customer needs to pay as premium in the year.                               |
| Policy_Sales_Channel  | (nominal)     | Anonymized Code for the channel of outreaching to the customer (Agents, Mail, Phone, etc.). |
| Vintage               | (continuous)  | Number of days the customer has been associated with the company.                           |
| Response (target variable)  | (dichotomous) | 1: Customer is interested, 0: Customer is not interested.                                 |

## Conclusion
The project started with Exploratory Data Analysis (EDA), extracting insights from the dataset. Addressing imbalanced classes, we selected features and algorithms, testing different models for accuracy.
The project successfully demonstrates the potential of predictive modeling in identifying potential customers for vehicle insurance. 
