# Payment-Fraud

![images](https://github.com/user-attachments/assets/9bd32bec-ba12-46eb-ac45-c4ea74ca3a22)


# Problem statement

In the digital era, online transactions are growing rapidly, making payment systems more convenient—but also more vulnerable to fraudulent activities. Fraudsters exploit weaknesses in transaction systems, leading to significant financial losses for businesses and customers alike. Detecting such fraud in real time is a major challenge due to the sheer volume of transactions and the subtle patterns that distinguish legitimate behavior from fraudulent ones.

This project aims to tackle the problem of payment fraud by leveraging data science and machine learning techniques. By analyzing key features such as account age, payment method, transaction time, and payment method history, the goal is to build a predictive model that can accurately identify potentially fraudulent transactions. The outcome can help businesses enhance their fraud detection systems, minimize losses, and build customer trust.

# Business Problem

Payment fraud poses a serious threat to online businesses, leading to financial losses, damage to brand reputation, and reduced customer trust. Traditional rule-based fraud detection systems often fail to keep up with evolving fraud patterns, resulting in either missed fraud or too many false alarms that impact genuine customers.

The business needs a smarter, data-driven solution to accurately detect fraudulent transactions in real time without disrupting legitimate payments. This project addresses that need by applying machine learning to identify high-risk transactions, helping the business reduce fraud losses, improve operational efficiency, and enhance the overall customer experience.

# Understanding the Problem Statement

Online payment fraud is increasing, and identifying it in real-time is a challenge because fraudulent transactions often look similar to genuine ones. Manual checks and basic rules are not enough to catch all fraud without affecting real customers.

In this project, we use transaction data with features like account age, transaction time, and payment method to build a machine learning model that can predict whether a transaction is fraudulent, helping businesses reduce risk and protect users.

# Data Source

The dataset used for this project is a sample transaction dataset containing key features such as:

  * accountAgeDays: Age of the customer’s account
  * numItems: Number of items in the transaction
  * localTime: Local transaction time (hour-based)
  * paymentMethod: Encoded payment method used
  * paymentMethodAgeDays: Age of the payment method
  * label: Indicates whether the transaction is fraudulent (1) or legitimate (0)

This data is synthetically generated or anonymized for analysis and modeling purposes, suitable for training and testing fraud detection models.

Dataset : [payment_fraud.csv](https://github.com/user-attachments/files/19665924/payment_fraud.csv)

# Processing of Analysis

1. Data Cleaning

 * Checked for missing values and data types.
 * Verified data consistency (e.g., no negative values in time or age).

2. Exploratory Data Analysis (EDA)

 * Visualized distributions of key features (e.g., account age, local time).
 * Analyzed class imbalance between fraud (label=1) and non-fraud (label=0).
 * Explored correlations and patterns between features and fraud cases.

3. Feature Engineering

 * Scaled numerical features for model compatibility.
 * Converted categorical variables like paymentMethod into numerical format if needed.

4. Model Preparation

 * Split the dataset into training and testing sets.
 * Applied machine learning models (e.g., Random Forest) for classification.
 * Evaluated performance using metrics like accuracy, precision, recall, and F1-score.

# Conclusion

This project shows how machine learning can effectively detect fraudulent transactions by analyzing key features like account age and payment method. The model helps reduce fraud risk and improve security in online payments.
