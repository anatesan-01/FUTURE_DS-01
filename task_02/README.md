# 📊 Customer Retention & Churn Analysis (SaaS Dashboard)

## 📌 Project Overview

This project analyzes customer retention and churn behavior for a SaaS-style subscription platform using multi-table relational data.

The objective is to understand:

- Why customers churn
- When churn happens in the lifecycle
- Whether pricing plans impact retention
- How product usage and support experience influence churn
- What strategic actions can reduce customer attrition

The analysis is implemented using Power BI with DAX-based measures and an interactive dashboard.

---

## 🎯 Business Problem

Customer churn directly impacts revenue growth in subscription-based businesses.

This project aims to answer key business questions:

- What is the overall churn rate?
- Are higher-tier plans retaining customers better?
- Do customers churn early or late in their lifecycle?
- Is churn caused by low product engagement?
- Is support responsiveness influencing churn?

---

## 📁 Dataset Description

The project uses a synthetic SaaS dataset consisting of multiple relational tables:

- `accounts` – Customer profile and churn flag
- `subscriptions` – Subscription lifecycle and plan information
- `feature_usage` – Product usage behavior
- `support_tickets` – Support interaction details
- `churn_events` – Churn dates and reasons

Relationships were created using:
- `account_id`
- `subscription_id`

The data model mirrors real-world SaaS databases.

---

## 🛠 Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling (One-to-Many Relationships)
- KPI & Interactive Dashboard Design

---

## 📊 Key Metrics Created (DAX Measures)

- Total Customers
- Churned Customers
- Churn Rate (%)
- Active Customers
- Average Tenure (Days)
- Avg Tenure (Churned vs Active)

Customer tenure was calculated dynamically using:

- Signup Date
- Churn Date (if churned)
- Today’s date (if active)

---

## 🔍 Key Insights

### 1️⃣ Overall Churn Rate
Churn rate is approximately **22%**, indicating significant customer attrition risk.

---

### 2️⃣ Churn by Plan Tier
Churn rates are nearly identical across Basic, Pro, and Enterprise plans.

**Insight:**  
Pricing tiers do not provide a meaningful retention advantage.

---

### 3️⃣ Customer Lifecycle (Tenure Analysis)
Churned customers show higher average tenure than active customers.

**Insight:**  
Churn is predominantly late-stage rather than onboarding-related.

---

### 4️⃣ Product Usage vs Churn
Engagement levels between churned and retained users are similar, with retained users slightly higher.

**Insight:**  
Customers continue using the product before churning, suggesting long-term value saturation.

---

### 5️⃣ Support Experience vs Churn
Ticket volume and resolution times are nearly identical between churned and retained users.

**Insight:**  
Churn is not driven by support inefficiencies.

---

## 🧠 Root Cause Interpretation

Churn appears to be systemic and long-term rather than caused by:

- Pricing structure
- Support responsiveness
- Early onboarding failures

The most likely cause is insufficient long-term value differentiation across plan tiers.

---

## 🎯 Business Recommendations

- Re-evaluate differentiation between pricing plans
- Improve long-term feature innovation
- Introduce loyalty or engagement incentives for mature customers
- Focus on sustained value delivery rather than onboarding improvements

---

## 📈 Dashboard Features

The Power BI dashboard includes:

- KPI Summary Row
- Churn Rate by Plan Tier
- Average Tenure by Churn Status
- Engagement vs Churn Analysis
- Support Metrics vs Churn
- Interactive Filters (Plan, Country, Industry)

---

## 💼 Skills Demonstrated

- Customer retention analytics
- Multi-table data modeling
- DAX measure creation
- Churn lifecycle analysis
- Business-driven insight storytelling
- Dashboard design and layout

---

## 📎 Final Summary

This project demonstrates a full SaaS churn analysis workflow — from relational data modeling to business-focused dashboard insights — highlighting late-stage churn driven by long-term value perception rather than operational inefficiencies.

---

## 👤 Author

Natesan A  
Data Science & Analytics Intern  
