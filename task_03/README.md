# 📊 Bank Marketing Analysis – Task_03

## 📌 Project Overview

This project analyzes the Bank Marketing Dataset related to direct marketing campaigns of a Portuguese banking institution.

The objective is to predict whether a client will subscribe to a term deposit.

Target Variable:
y → Has the client subscribed a term deposit? (yes/no)

---

## 📂 Dataset Information

Title: Bank Marketing  
Time Period: May 2008 – November 2010  
Type: Binary Classification  

Files Used:
- bank-full.csv (45,211 rows, 16 features + target)
- bank-additional-full.csv (41,188 rows, 20 features + target)

The dataset is publicly available for research purposes.

Citation (Original Dataset):
S. Moro, R. Laureano and P. Cortez (2011).
Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology.
Proceedings of ESM’2011.

Citation (Extended Dataset):
S. Moro, P. Cortez and P. Rita (2014).
A Data-Driven Approach to Predict the Success of Bank Telemarketing.
Decision Support Systems.

---

## 🧾 Attribute Description

Client Information:
- age
- job
- marital
- education
- default
- balance
- housing
- loan

Last Contact Information:
- contact
- month
- day_of_week
- duration

Campaign Information:
- campaign
- pdays
- previous
- poutcome

Social & Economic Indicators (Extended Dataset):
- emp.var.rate
- cons.price.idx
- cons.conf.idx
- euribor3m
- nr.employed

Target:
- y (yes / no)

---

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Analyze customer demographics
- Identify factors influencing term deposit subscription
- Build classification models
- Evaluate model performance
- Create Power BI dashboard

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Power BI

---

## 📊 Steps Performed

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis
5. Feature Engineering
6. Model Building
7. Model Evaluation
8. Dashboard Creation

---

## 📁 Project Structure

Task_03/
│
├── data/
│   ├── bank-full.csv
│   ├── bank-additional-full.csv
│
├── notebooks/
│   └── bank_marketing_analysis.ipynb
│
├── dashboard/
│   └── bank_marketing_dashboard.pbix
│
├── README.md

---

## 📌 Important Notes

- The duration feature should not be used for real-world prediction because it is only known after the call ends.
- Some categorical features contain "unknown" values that must be handled properly.

---

## 👨‍💻 Author

Future Intern – Data Science Task_03

