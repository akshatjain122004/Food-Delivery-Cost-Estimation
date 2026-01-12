# 📦 Food Delivery Cost Analysis & Estimation

## 📌 Project Overview
This project focuses on analyzing **food delivery order data** to understand **cost drivers, revenue leakage, and profitability factors** in a food delivery platform. Using exploratory data analysis (EDA), the project extracts meaningful business insights from historical order-level data.

The analysis is implemented in a **Jupyter Notebook (`.ipynb`)** using Python data analysis libraries.

---

## 📊 Dataset Description
The dataset contains detailed transactional information related to food delivery orders with the following attributes:

- **Order ID** – Unique identifier for each order  
- **Customer ID** – Unique identifier for customers  
- **Restaurant ID** – Identifier for partner restaurants  
- **Order Date and Time** – Timestamp when the order was placed  
- **Delivery Date and Time** – Timestamp when the order was delivered  
- **Order Value** – Total value of the order  
- **Delivery Fee** – Fee charged for delivery  
- **Payment Method** – Mode of payment used (UPI, Card, Cash, etc.)  
- **Discounts and Offers** – Promotional discounts applied  
- **Commission Fee** – Commission charged from restaurants  
- **Payment Processing Fee** – Transaction processing charges  
- **Refunds / Chargebacks** – Amount refunded or charged back (if any)

---

## 🎯 Objectives of the Analysis
- Understand **revenue and cost structure** of food delivery orders  
- Identify **key contributors to delivery cost and profit variation**  
- Analyze the impact of **discounts, refunds, and commissions**  
- Study **order trends over time**  
- Detect **potential inefficiencies and loss areas**

---

## 🔍 Key Insights Generated
The analysis provides insights such as:
- Relationship between **order value and delivery fee**
- Impact of **discounts and offers on net revenue**
- Contribution of **commission and payment processing fees** to total cost
- Frequency and financial impact of **refunds/chargebacks**
- Order volume and revenue trends based on **time and payment method**

These insights help in understanding how operational and pricing decisions affect overall profitability.

---

## 🛠️ Tech Stack Used
- **Python**
- **Pandas** – Data manipulation and analysis  
- **NumPy** – Numerical computations  
- **Matplotlib / Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis environment  

---

## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Food-Delivery-Cost-Estimation.git
