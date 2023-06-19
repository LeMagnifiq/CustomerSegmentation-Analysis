# Online Retail Customer Segmentation

## Project Overview

This project's objective is to segment customers of an online retail business using Recency, Frequency, Monetary (RFM) analysis, and Machine Learning techniques. The RFM analysis, a customer segmentation approach, utilizes past purchase behavior to categorize customers into groups, aiding businesses in tailoring their communications for product or service promotion. This personalized approach contributes to enhancing customer retention and boosting sales.

## Dataset

This project utilizes the "Online Retail" dataset from the UCI Machine Learning Repository. This dataset comprises online transactions from a UK-based non-store online retail business, primarily selling unique all-occasion gifts. It includes features like `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, and `Country`.

## Data Preprocessing

In the initial phase, data preprocessing encompasses identifying and managing missing values and outliers. It also involves converting categorical variables into numerical representations using techniques like Label Encoding and One-Hot Encoding.

## Feature Engineering

Customers are classified into distinct categories based on their RFM values:

- **Recency_Binned**: Depending on Recency scores, customers receive classifications such as 'Active', 'Lapsed', and 'Inactive'.
- **Frequency_Binned**: Frequency scores dictate customers' categorization into 'Rare', 'Occasional', and 'Regular'.
- **MonetaryValue_Binned**: Monetary Value influences the segmentation of customers into 'Low-spending', 'Medium-spending', and 'High-spending'.

## Model Training and Evaluation

This multi-class classification problem uses several machine learning models for training and testing, including Support Vector Machines (SVM), Gradient Boosting Classifier, and Random Forest Classifier. 

Evaluations of these models rely on metrics such as accuracy, precision, recall, F1-score, and confusion matrix. These metrics offer a holistic view of the model's performance concerning customer segmentation prediction.

## Results

Among the models tested, the Random Forest Classifier emerged as the superior performer, boasting an average accuracy and recall of approximately 99.42%. The precision and F1-score also showed commendable results, affirming the model's balance in correctly identifying true positives while avoiding false positives.

## Conclusion

This project provides a solid foundation for understanding customer behavior and segregating customers based on their purchasing patterns through RFM analysis and machine learning techniques. High accuracy in model predictions indicates the successful prediction of customer segments. Such insights are invaluable to businesses, helping them devise effective marketing and sales strategies.
