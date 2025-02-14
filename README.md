# Automatic Ticket Classification

## Project Overview
This project involves building a machine learning model to automatically classify customer complaints based on the products and services mentioned in the support tickets. The classification helps in efficient issue resolution and enhances customer satisfaction for a financial company.

## Problem Statement
For financial institutions, customer complaints serve as a key indicator of shortcomings in their products and services. Efficient resolution of these complaints helps reduce customer dissatisfaction and improves retention.

Currently, companies assign support employees to manually evaluate and allocate each ticket, which becomes tedious and inefficient as the customer base grows. To address this, we aim to automate the classification of customer complaints using **Natural Language Processing (NLP)** techniques.

## Business Goal
The goal is to develop an **automated complaint classification model** that:
- Categorizes complaints into relevant product/service categories.
- Enables quick ticket resolution.
- Reduces manual effort and improves efficiency.

We will use **Non-Negative Matrix Factorization (NMF)** for topic modeling to identify patterns and recurring words in customer complaints. These patterns will help classify tickets into predefined categories.

## Categories for Classification
1. **Credit Card / Prepaid Card**
2. **Bank Account Services**
3. **Theft/Dispute Reporting**
4. **Mortgages/Loans**
5. **Others**

Once the topic modeling is complete, we will use supervised learning models such as **Logistic Regression, Decision Tree, Random Forest, and Naïve Bayes** to classify new customer complaints accurately.

## Dataset
The dataset consists of **78,313 customer complaints** with **22 features**, stored in JSON format. This data will be converted into a DataFrame for processing.

## Tasks Overview
To successfully implement the project, the following steps are undertaken:

1. **Data Loading** – Convert JSON data to a structured DataFrame.
2. **Text Preprocessing** – Clean and normalize text data (removal of stop words, stemming, etc.).
3. **Exploratory Data Analysis (EDA)** – Understand data distribution and trends.
4. **Feature Extraction** – Extract important features using NLP techniques.
5. **Topic Modeling** – Use NMF to detect recurring themes in complaints.
6. **Model Building (Supervised Learning)** – Train models like Logistic Regression, Naïve Bayes, Decision Tree, and Random Forest.
7. **Model Training & Evaluation** – Select the best model using appropriate evaluation metrics.
8. **Model Inference** – Use the trained model to classify new complaints.

## Expected Outcome
- A trained model capable of **automatically classifying complaints** into relevant categories.
- Identification of key patterns and words associated with different complaint types.
- A streamlined customer complaint resolution system.

## License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute this project with proper attribution.

---
### Contributors
- [Abhradeep Chandra Paul]
For any queries or contributions, feel free to contact us!

