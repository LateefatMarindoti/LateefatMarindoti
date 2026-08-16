# Lateefat Marindoti

**Data Analyst | Toronto, ON**

Analytics graduate with four years of marketing, brand and retail experience across banking and beauty retail in Nigeria and Canada. Currently completing a postgraduate certificate in Business Insights and Analytics at Humber Polytechnic.

I work in SQL, Excel, Power BI and Python, and I like the part of the job where a messy export turns into something a team can actually make a decision with.

📧 Marindotiteniola@gmail.com · 📍 Toronto, ON · [LinkedIn](https://www.linkedin.com/in/lateefatmarindoti) · [Dashboard Portfolio](https://www.datascienceportfol.io/lateefatmarindoti).

---

## Tools

| Area | What I use |
|---|---|
| SQL | MySQL, joins, subqueries, CTEs, aggregations, indexing and query optimisation, ETL, DBeaver |
| BI | Power BI (Power Query, DAX, star schema modelling), Excel (PivotTables, XLOOKUP, INDEX/MATCH, FILTER, forecast sheets) |
| Python | pandas, NumPy, Matplotlib, scikit-learn, statsmodels, Jupyter |
| Big data | Databricks, PySpark, Spark SQL |
| Methods | Data cleaning, KPI reporting, customer segmentation, regression, time series forecasting |

**Certification:** Microsoft Certified: Power BI Data Analyst Associate (PL-300), April 2026

---

## Projects

### 1. EV Charging Infrastructure Gap Analysis
*Python, pandas, Jupyter*

Ontario is adding electric vehicles faster than it is adding places to charge them. This project asked where that gap is widest.

I profiled EV registration and charging station data across Ontario, cleaned and joined the sources, engineered the features behind a 60/40 weighted gap score comparing vehicle density against charger availability, and fit a growth forecast reaching R² = 0.76, and wrote the findings up for a non-technical audience.

**What came out of it:** a ranked view of underserved regions and an executive deck presented to the review panel.

📁 [Notebook and deck](./ev-charging-gap-analysis)

---

### 2. Walmart Sales Forecasting and Inventory Management
*Python, statsmodels, PowerPoint*

Retail inventory planning goes wrong in two directions: too much stock ties up cash, too little loses the sale.

I analysed historical Walmart sales, tested several forecasting approaches against a holdout period, and translated the results into inventory recommendations rather than just accuracy scores.

**What came out of it:** demand forecasts by period with a stakeholder presentation on what to stock and when.

📁 [Notebook and presentation](./walmart-sales-forecasting)

---

### 3. RFM Customer Segmentation
*Databricks, PySpark, Spark SQL*

Not every customer is worth the same marketing spend. RFM is the cheapest way to find out which ones are.

I scored roughly 4,300 retail customers on recency, frequency and monetary value using PySpark on a cloud-hosted transaction dataset, then grouped them into 8 segments with a plain-language description of how to treat each one.

**What came out of it:** segment definitions ready to hand to a marketing team.

📁 [Notebook](./rfm-customer-segmentation)

---

### 4. Hotel Financial Performance Report
*Power BI, Power Query, M, DAX*

Financial data arrived as 24 separate monthly files in more than one currency, which is a reporting problem before it is an analysis problem.

I built the whole pipeline in Power Query: folder import, a custom M date table, currency conversion, and a star schema model with proper dimension tables underneath the report.

**What came out of it:** an interactive report where the finance team can compare periods and properties without touching the source files.

📁 [PBIX file and screenshots](./hotel-financial-powerbi)

---

### 5. Retail BI Database and ETL
*MySQL, DBeaver*

The unglamorous half of analytics. A report is only as good as the database under it.

I designed a retail schema, built the ETL process to load it, then went back and improved query performance using indexing and EXPLAIN plans. I also set up user access controls and a backup and recovery process.

**What came out of it:** a documented database with measurably faster queries and access controls that hold up.

📁 [Schema, scripts and documentation](./retail-bi-database)

---

## Currently

Finishing my postgraduate certificate at Humber and looking for data analyst and BI analyst roles in Toronto.
If you want to talk about any of these, email is the fastest way to reach me.
