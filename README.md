# Mall Customer Data Cleaning and Preprocessing

## Overview
This project is part of my ELEVATE LABS Internship – Task 1: Data Cleaning and Preprocessing.  
The goal is to clean, preprocess, and prepare the Mall Customer Segmentation Dataset from Kaggle for further analysis.

---

## Objective
To perform data cleaning and preprocessing using Python (Pandas) by:
- Handling missing values and duplicates  
- Renaming and standardizing column names  
- Ensuring correct data types  
- Adding meaningful new columns for better analysis  

---

## Tools and Technologies Used
- Python  
- Pandas  
- Google Colab  
- GitHub  

---

## Cleaning and Preprocessing Steps
1. Checked and confirmed there were no missing values or duplicate rows.  
2. Renamed columns for consistency:
   - CustomerID → customer_id  
   - Annual Income (k$) → annual_income_k  
   - Spending Score (1-100) → spending_score  
3. Verified and fixed data types (age, income, score as integers).  
4. Standardized text values (for example, gender names).  
5. Added new derived columns:
   - income_level → Low, Medium, High  
   - spending_behavior → Low Spender, Average Spender, High Spender  
6. Exported the cleaned dataset as cleaned_mall_customers.csv  

---

## Dataset Source
Mall Customer Segmentation Dataset  
Link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python  

---

## Internship Learning Outcome
This task helped me:
- Understand data cleaning techniques using Pandas  
- Improve my data preprocessing and feature creation skills  
- Prepare a dataset ready for Exploratory Data Analysis and Machine Learning  

---

## Author
Anusuya S  
Data Analyst Intern at ELEVATE LABS  
Task 1 – Data Cleaning and Preprocessing (Mall Customer Dataset)

