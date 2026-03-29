# 🛍️ Customer Purchase Behavior Analysis

## 📌 Problem Statement

A retail company aims to better understand customer shopping behavior to improve sales, customer satisfaction, and long-term loyalty. The goal is to analyze customer data to identify trends, understand purchasing patterns, and optimize marketing and product strategies.

---

## 🎯 Project Objective

This project focuses on analyzing customer purchasing behavior using transactional data (~3,900 records) to:

* Identify spending patterns
* Understand customer segments
* Analyze product preferences
* Support data-driven business decisions

---

## 📊 Dataset Information

* **Total Records:** 3,900
* **Total Features:** 18

### 🔑 Key Features:

* **Customer Details:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Category, Purchase Amount, Season, Color
* **Behavioral Data:** Discount Usage, Purchase Frequency, Review Rating, Shipping Type

⚠️ *Note:* Missing values were found in the **Review Rating** column.

---

## 🧹 Data Preprocessing (Python)

Data cleaning and preparation steps included:

* Handling missing values using **median imputation**
* Standardizing column names
* Feature engineering:

  * Age Groups
  * Purchase Frequency (days)
* Removing redundant columns
* Loading cleaned data into **PostgreSQL database**

---

## 🗄️ SQL Analysis & Insights

SQL was used to extract valuable business insights:

* Revenue varied across different customer groups, highlighting key contributors
* Some customers spent significantly even when discounts were applied
* Certain products consistently received higher ratings
* Express shipping users showed slightly higher spending behavior
* Subscription improved customer retention and overall revenue
* Some products were highly dependent on discounts
* Loyal customers contributed the highest number of purchases
* Specific categories showed higher demand and frequency
* Frequent buyers showed strong engagement patterns
* Revenue contribution varied across age groups

---

## 📈 Power BI Dashboard

An interactive dashboard was created to visualize insights:

* Total Customers
* Average Purchase Value
* Category-wise Sales
* Customer Segmentation

📷 *(Add your dashboard screenshot here)*

---

## 💡 Business Recommendations

* Promote subscription plans with exclusive benefits
* Implement strong customer loyalty programs
* Optimize discount strategies for better profitability
* Highlight top-performing products
* Focus marketing on high-value customer segments

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy)
* **SQL (PostgreSQL)**
* **Power BI**
* **Excel**

---

## 🚀 Conclusion

This project demonstrates how customer data can be analyzed to uncover meaningful insights and support strategic decision-making. It highlights the importance of data analytics in improving customer engagement and business performance.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
