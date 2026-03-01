# 📊 Ecommerce Sales Analytics Project

This is an end-to-end data analytics project analyzing e-commerce sales and customer data with Python, SQL Server, and Power BI. The goal is to extract actionable business insights, build customer segmentation (RFM), and design professional dashboards.

---

## 🛠 Tools Used

| Tool | Purpose |
|------|---------|
| Python | Data cleaning, feature engineering, RFM segmentation |
| SQL Server | Business logic, aggregation, window functions, CTE |
| Power BI | Interactive dashboards & visual storytelling |

---

##  Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist**:

- 113,390 orders
- Customers, products, payments, delivery details
- Public dataset commonly used in analytics projects

Dataset is cleaned and already included under `data/ecommerce_cleaned.csv`.

---

## 📊 Key Business Insights

1. **Total Revenue:** ~15.9M  
2. **Average Order Value:** ~140  
3. **Repeat Customer Rate:** ~2.97%  
4. **Late Delivery %:** ~6.53%  
5. **Top Revenue Year:** 2018  
6. **Top Revenue State:** São Paulo (SP)  
7. **Top Product Category:** Beauty & Health  
8. **Revenue Contribution:**  
   - Others: ~53.16%  
   - Champions: ~21.61%

---

## 📁 Project Structure
Ecommerce-Sales-Analytics/
│
├── data/ # Cleaned dataset
│ └── ecommerce_cleaned.csv
│
├── notebooks/ # Python analysis and RFM
│ └── data_cleaning_and_rfm.ipynb
│
├── sql/ # SQL Server queries
│ └── business_queries.sql
│
├── powerbi/ # Power BI dashboards
│ └── Ecommerce_Sales_Analytics_Dashboard.pbix
│
├── images/ # Dashboard screenshots
│ └── executive_dashboard.png
│ └── segmentation_dashboard.png
│ └── segment_detail.png

# Project overview

---

## 💡 How to Use

### 1️⃣ Python Notebook
Run the notebook in Google Colab to:

- Load and clean raw data
- Perform RFM segmentation
- Create feature metrics for analysis

---

### 2️⃣ SQL Queries
Import the cleaned CSV into SQL Server and run:

- Revenue & orders overview  
- Growth trends  
- Customer rankings  
- Segment performance

---

### 3️⃣ Power BI Dashboard
Connect Power BI to SQL Server and load `ecommerce_data`:

Build professional dashboards including:

✔ Executive Overview  
✔ Customer Segmentation  
✔ Drill-through Analysis  

---

##  Dashboard Preview

Add images below (preview of dashboards):

![Executive Dashboard](images/executive_dashboard.png)  
![Segmentation Dashboard](images/segmentation_dashboard.png)  
![Segment Detail View](images/segment_detail.png)

---

##  Conclusion

This project demonstrates:
✔ End-to-end analysis  
✔ Real business insights  
✔ Professional dashboards  
✔ Good SQL & Python practice

Perfect for entry-level Data Analyst portfolios....



