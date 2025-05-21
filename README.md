# 🛍️ Online Retail Data Analysis (RFM, Cohort, Returns)

## 📌 Overview

This project provides an end-to-end analysis of customer purchasing behavior using the **Online Retail dataset** from the UCI Machine Learning Repository. It combines **data wrangling, RFM segmentation, cohort analysis, return behavior exploration**, and an interactive **Power BI dashboard** to visualize insights.

---  

## 🎯 Objectives

- Segment customers using RFM (Recency, Frequency, Monetary) modeling
- Analyze customer retention trends via cohort analysis
- Identify revenue trends by time and country
- Explore product returns and customer behavior
- Deliver insights through a clean Power BI dashboard

---  

## 📂 Files

| File Name                     | Description                                  |
|------------------------------|----------------------------------------------|
| `online_retail_analysis.ipynb` | Full Python notebook (data cleaning, EDA, modeling) |
| `online_retail_cleaned.csv`    | Cleaned transaction data                    |
| `rfm_table.csv`                | RFM segmentation table                      |
| `cohort_retention_counts.csv` | Monthly cohort retention counts             |
| `cohort_revenue.csv`          | Monthly revenue per cohort                  |
| `returns_data.csv`            | Returns-focused dataset                     |
| `Online_Retail_Dashboard.pbix`| Interactive Power BI dashboard file         |

---  

## 🧹 Data Cleaning & Wrangling

- Removed rows with missing `CustomerID`
- Filtered out negative or zero `Quantity` and `UnitPrice`
- Calculated `SalesValue` = `Quantity × UnitPrice`
- Dropped duplicate line items by checking key transactional fields

---  

## 📈 RFM Segmentation

Customers were grouped by:
- **Recency**: Days since last purchase
- **Frequency**: Total invoices
- **Monetary**: Total spend

They were classified into segments like:
- `Champion`, `Loyal`, `At Risk`, `Recent`, `Others`

📊 Visualization: Bar chart of customers by segment + average monetary value by segment.

---  

## 📆 Cohort & Retention Analysis

- Customers were grouped into **monthly cohorts**
- Calculated retention rates and revenue contribution over time
- Visualized via:
  - **Retention heatmap**
  - **Cohort revenue heatmap**
  - **New customers by month**

---  

## 🔁 Return Behavior Analysis

- Identified top returned products and return-prone customers
- Estimated total **financial loss from returns**
- Visualized with:
  - Bar charts (Top returns)
  - Treemap (Top returning customers)
  - Return loss per product

---  

## 📊 Power BI Dashboard Highlights

🔗 **[View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTM0ZmVhNGYtMzM4MS00ZjVkLThhNzQtMjBhZWUyMDgyZjJhIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9)**

Includes:
- Total revenue, monthly sales trends
- Sales by country
- RFM segmentation and performance metrics
- Cohort-based retention and revenue
- Return behavior visuals (loss, products, customers)

---  

## 🛠 Tools Used

- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Power BI**: For all interactive dashboards
- **Excel**: Dataset source (UCI Online Retail)

---  

## 📬 Author

**Etebom Ntuk**  
[LinkedIn Profile](https://www.linkedin.com/in/ntuk-etebom/) • [GitHub Profile](https://github.com/netebom)
