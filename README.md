🛒 SmartCart Customer Clustering System

## 📌 Project Overview

SmartCart is a growing global e-commerce platform that collects large-scale customer data. This project focuses on building an **Intelligent Customer Segmentation System** using **Unsupervised Machine Learning** to discover hidden patterns in customer behavior and support personalized marketing strategies.

The system analyzes historical customer transaction and engagement data to group customers into meaningful clusters based on their behavior and spending habits.

---

## ❗ Problem Statement

SmartCart was using **generic marketing strategies** for all customers without understanding different customer behavior patterns.

This resulted in:

* ❌ Missed opportunities to retain high-value customers
* ❌ Late identification of churn-prone users
* ❌ Inefficient marketing spend
* ❌ Lack of personalized customer engagement

The goal was to build a **data-driven customer segmentation model** to improve marketing and retention strategies.

---

## 🎯 Objectives

* Perform customer segmentation using clustering algorithms
* Discover hidden patterns in customer purchasing and engagement behavior
* Enable personalized marketing and targeted campaigns
* Support business decision-making using data insights

---

## 📂 Dataset Description

The dataset contains **2240 customer records** and **22 attributes** covering demographics, purchasing behavior, and engagement activity.

### 👤 Customer Demographics

| Feature        | Description              |
| -------------- | ------------------------ |
| ID             | Unique customer ID       |
| Year_Birth     | Year of birth            |
| Education      | Education level          |
| Marital_Status | Marital status           |
| Income         | Yearly household income  |
| Kidhome        | Number of small children |
| Teenhome       | Number of teenagers      |
| Dt_Customer    | Customer enrollment date |

---

### 💰 Purchase Behavior (Spending Amount)

| Feature          | Description               |
| ---------------- | ------------------------- |
| MntWines         | Spending on wine          |
| MntFruits        | Spending on fruits        |
| MntMeatProducts  | Spending on meat          |
| MntFishProducts  | Spending on fish          |
| MntSweetProducts | Spending on sweets        |
| MntGoldProds     | Spending on gold products |

---

### 🛍 Purchase Behavior (Frequency)

| Feature             | Description               |
| ------------------- | ------------------------- |
| NumDealsPurchases   | Purchases using discounts |
| NumWebPurchases     | Website purchases         |
| NumCatalogPurchases | Catalog purchases         |
| NumStorePurchases   | Store purchases           |
| NumWebVisitsMonth   | Monthly website visits    |

---

### 📢 Customer Feedback & Activity

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| Recency  | Days since last purchase                    |
| Complain | Complaint in last 2 years (1 = Yes, 0 = No) |

---

## 🧠 Machine Learning Approach

This project uses **Unsupervised Learning (Clustering)** to segment customers.

### Steps Performed:

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Data Scaling & Transformation
4. Exploratory Data Analysis (EDA)
5. Model Training using Clustering Algorithms
6. Cluster Evaluation & Visualization
7. Business Insight Generation

---

## 📊 Results & Insights

✔ Identified multiple customer segments based on spending and engagement
✔ Discovered high-value and loyal customer groups
✔ Identified discount-driven and low-engagement customers
✔ Enabled targeted marketing strategy planning
✔ Improved business decision support

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📈 Business Impact

* Improved customer retention planning
* Better marketing resource allocation
* Personalized customer engagement strategy
* Data-driven business decisions

---

## 🚀 Future Improvements

* Deploy model using Flask / FastAPI
* Build interactive dashboard (Streamlit / Power BI style)
* Add real-time customer scoring
* Test advanced clustering techniques

---

## 👨‍💻 Author

**Dhiraj Sharma**
Engineering Student | Data Analytics & ML Enthusiast

