# Credit Card Analytics Dashboard  
**Power BI + PostgreSQL | Data Analytics | Customer Segmentation**

---
## 📈 Dashboard Screenshots

**Transaction Report**  
![Screenshot 2025-05-23 003343](https://github.com/user-attachments/assets/ebab17a7-fb15-46b3-affb-e3b909eea001)

**Customer Insights**  
![Screenshot 2025-05-23 205505](https://github.com/user-attachments/assets/cf776610-2b7c-4dad-b75b-e03469a26b6b)

---
## 📘 Project Description

The **Credit Card Analytics Dashboard** is a comprehensive business intelligence solution built using **Power BI**, **PostgreSQL**, **SQL**, and **DAX**. It analyzes over **656,000 credit card transactions** and customer profiles to uncover strategic insights into revenue trends, customer satisfaction, transaction behavior, and product performance.

This solution is designed for financial institutions to support data-driven decisions by visualizing key metrics such as revenue, interest, transaction types, activation rates, and customer segmentation — all through interactive, executive-ready dashboards.

---

## 🎯 Purpose & Vision

As someone passionate about solving business problems using data, I wanted to create a comprehensive solution that mirrors real-world analytics use cases in the financial domain. Credit card companies deal with massive customer data, but often struggle to turn it into actionable insights.

This project was built to:

* Practice and showcase end-to-end BI workflow using realistic datasets
* Deliver business-ready KPIs and dashboards using industry-standard tools
* Demonstrate how data storytelling can support decision-making in finance and customer analytics

---

## 🔧 Development Workflow

The project involved building a complete BI solution from scratch — from data ingestion to insight generation. Here's the step-by-step process I followed:

1. **Data Collection**
   Imported CSVs representing transaction-level (`credit_card.csv`) and customer demographic data (`customer.csv`).

2. **Database Setup**
   Loaded the data into **PostgreSQL**, created relational tables, and cleaned/joined them using **SQL**.

3. **Data Preparation**
   Connected PostgreSQL to Power BI using **ODBC**. Used **Power Query** to clean column types, handle nulls, and shape data for modeling.

4. **Data Modeling**
   Created a **star schema** with fact and dimension tables. Defined relationships and hierarchies to support filtering and slicing.

5. **DAX & KPI Measures**
   Built 25+ **DAX measures** for business metrics like:

   * Revenue & Interest
   * Customer Satisfaction Score (CSS)
   * Activation Rate & Delinquency Rate
   * Quarterly Growth & Segmentation by category

6. **Dashboard Design**
   Developed two Power BI report pages:

   * **Transaction Report** – revenue, usage mode, card type, quarter-wise trends
   * **Customer Report** – demographic segmentation, satisfaction trends, revenue contribution

7. **Insight Generation**
   Used slicers, drill-downs, and conditional formatting to uncover patterns and deliver business insights backed by data.

---

## ✅ Key Features

* Analyze 656K+ transactions and \$55M+ in revenue
* Dynamic segmentation by job, income, education, and location
* Track KPIs: Revenue, Interest Earned, CSS, Activation, and Delinquency
* Compare performance across quarters and transaction modes
* Identify high-value customers and underutilized card types
* Fully interactive Power BI dashboard with slicers and drill-downs

---

## 🧠 Skills Demonstrated

* **SQL & Data Modeling**: Cleaned and structured transactional data in PostgreSQL
* **Power Query**: Performed ETL and data transformation workflows
* **Power BI & DAX**: Built KPIs, measures, and dynamic visualizations
* **Data Storytelling**: Delivered actionable insights from raw datasets
* **Business Strategy**: Recommended product and campaign improvements

---

## 📊 Project Insights

* **Q3** reported the highest revenue (\$14.2M) and transaction volume (166.6K)
* **Blue** and **Silver** cards make up **93% of usage**; Platinum is underutilized
* **Swipe** transactions dominate at \$35M; Online is only \$3M
* **Top customer group**: Businessmen (\$17.3M), Graduates (\$22M)
* **Top states**: TX, NY, CA — together account for **68%** of revenue
* **CSS avg**: 3.19 | **Activation rate**: 57.5% | **Delinquency rate**: 6.06%

---

## 💼 Business Recommendations

* Promote Platinum card with bundled rewards to boost adoption
* Expand online transaction usage via incentives and awareness
* Personalize offers for high-value segments (Businessmen, Graduates)
* Use successful state strategies (TX, NY, CA) to grow underperforming markets
* Enhance customer satisfaction using post-transaction surveys

---

## 🧰 Tech Stack

| Category       | Tools                      |
| -------------- | -------------------------- |
| Data Storage   | PostgreSQL                 |
| ETL & Cleaning | Power Query, SQL           |
| Visualization  | Power BI, DAX              |
| Modeling       | Star schema, relationships |
| Deployment     | Power BI Desktop           |

---


## 🚀 Future Enhancements

To further elevate this project and bring more value to end-users and decision-makers, the following features are planned:

1. **🔮 Predictive Analytics**
   - Integrate Python or R models to forecast:
     - Customer churn
     - High-risk (delinquent) profiles
     - Lifetime value (LTV)

2. **📡 Real-Time Data Integration**
   - Stream live credit card transactions via APIs or Kafka
   - Implement incremental refresh for near real-time dashboards

3. **📥 Automated Reporting**
   - Schedule email delivery of executive KPI summaries using Power BI Service
   - Customize reports based on region or department filters

4. **🌎 Geo Mapping**
   - Visualize customer distribution and revenue using Power BI map visuals and custom shape files

---

## 📁 Repository Structure

```
Credit_Card_Insights/
├── data/
│   ├── credit_card.csv
│   ├── customer.csv
│   ├── cc_add.csv
│   └── cust_add.csv
├── sql/
│   └── Financial_Dashboard_Data.sql
├── dashboard/
│   └── Credit_Card_Report.pbix
├── reports/
│   ├── Credit_Card_Transaction_Report.pdf
│   └── Credit_Card_Customer_Report.pdf
└── README.md
```

---
## 👤 About the Author

**Swathi M.**
📧 [swathixm@gmail.com](mailto:swathixm@gmail.com)
🎓 Master’s in Information Systems
📍 Arlington, TX
🔗 [LinkedIn](https://www.linkedin.com/in/swathi-manjunatha)

> “Turning transactional data into actionable insights for smarter decisions.”

---
