# Online Retail Customer Segmentation

## Project Overview

The objective of this project is to use Recency, Frequency, Monetary (RFM) analysis and Machine Learning techniques to segment customers of an online retail business. RFM analysis is a customer segmentation technique that uses past purchase behavior to divide customers into distinct groups. This method helps businesses tailor their product or service promotions, enhancing customer retention and boosting sales.

## Dataset

The "Online Retail" dataset from the UCI Machine Learning Repository is the basis for this project. The dataset contains online transactions of a UK-based non-store online retail business that primarily sells unique all-occasion gifts. The dataset includes features such as `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, and `Country`.

## Data Preprocessing

The initial phase involves data preprocessing, which includes identifying and handling missing values and outliers. It also includes converting categorical variables into numerical representations using techniques like Label Encoding and One-Hot Encoding.

## Feature Engineering

Customers are classified into distinct categories based on their RFM values:

- **Recency_Binned**: Customers are classified as 'Active', 'Lapsed', or 'Inactive' depending on their Recency scores.
- **Frequency_Binned**: Frequency scores categorize customers into 'Rare', 'Occasional', and 'Regular'.
- **MonetaryValue_Binned**: Based on Monetary Value, customers are segmented into 'Low-spending', 'Medium-spending', and 'High-spending' categories.

## Model Training and Evaluation

Several machine learning models are used for training and testing in this multi-class classification problem, including Support Vector Machines (SVM), Gradient Boosting Classifier, and Random Forest Classifier. 

The evaluation of these models is based on metrics such as accuracy, precision, recall, F1-score, and the confusion matrix. These metrics provide a comprehensive view of the model's performance in predicting customer segmentation.

## Results

Among the models tested, the Random Forest Classifier was the most effective, achieving an average accuracy and recall of approximately 99.42%. The precision and F1-score also demonstrated solid results, confirming the model's ability to accurately identify true positives while avoiding false positives.

## Conclusion

This project offers a solid foundation for understanding customer behavior and dividing customers into categories based on their purchasing patterns, through the application of RFM analysis and machine learning techniques. The high accuracy in model predictions indicates that it is effective in predicting customer segments. This understanding can prove extremely valuable for businesses in formulating effective marketing and sales strategies.
