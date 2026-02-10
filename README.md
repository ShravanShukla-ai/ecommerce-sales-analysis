# 📊 E-Commerce Sales Data Analysis (EDA)

## 🔍 Project Overview
This project performs an **end-to-end Exploratory Data Analysis (EDA)** on a real-world Brazilian e-commerce dataset to uncover insights related to **sales performance, customer behavior, product categories, and regional demand patterns**.

The goal is to identify key revenue drivers, seasonal trends, and customer retention opportunities that support **data-driven business decision-making**.

---

## 📦 Dataset
- **Source:** Olist Brazilian E-Commerce Dataset (Kaggle)
- **Records:** ~100,000 order-item level transactions
- **Granularity:** Each row represents a unique product purchased within an order
- **Structure:** Multiple relational tables merged into a single analytical dataset

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas** – data cleaning & transformation
- **Matplotlib** – data visualization
- **Jupyter Notebook** – analysis workflow
- **Excel** – initial data inspection

---

## 🧹 Data Preparation
- Selected only analytically relevant columns to create a **clean, optimized dataset**
- Merged multiple tables using appropriate **business keys**
- Validated dataset integrity by checking duplicates at the **order-item level**
- Handled missing values without impacting revenue-based analysis

---

## 📈 Key Analyses & Visualizations
- **Monthly Revenue Trend**
- **Monthly Order Volume**
- **Top 10 Product Categories by Revenue**
- **Top 10 States by Revenue**
- **Repeat vs One-Time Customers**

---

## 🧠 Key Business Insights
- Revenue is **highly concentrated** in a small number of product categories and states
- Sales exhibit **clear seasonality**, indicating opportunities for timed promotions
- Order growth is primarily driven by **increased order volume**, not price inflation
- Customer retention is **low**, highlighting a major opportunity for long-term revenue growth

---

## 💡 Business Recommendations
- Implement **customer loyalty and retention programs**
- Focus marketing and inventory planning on **top-performing categories**
- Leverage seasonal demand peaks for targeted campaigns
- Prioritize high-revenue regions for **logistics and delivery optimization**
- Scale operational capacity to support growing order volumes

---

## 🚀 Future Enhancements
- Customer segmentation using **RFM analysis**
- Predictive modeling for **sales forecasting**
- Cohort analysis for retention tracking

---

## ▶️ How to Run This Project
1. Clone the repository
2. Install required Python libraries
3. Open `ecommerce_eda.ipynb` in Jupyter Notebook
4. Run cells sequentially

---

📌 **Author:** Shravan Shukla  
📎 **Dataset Credit:** Olist / Kaggle
