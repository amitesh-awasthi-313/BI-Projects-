# 📊 OTT Platform Analytics Dashboard - Power BI

Welcome to the **OTT Platform Analytics Dashboard**, a project developed using **Power BI** to visualize user behavior, content performance, and platform engagement for an OTT streaming service.

This dashboard delivers executive-level insights by transforming raw platform data into **interactive visualizations** and **data-driven decisions**.

---

## 🧩 Project Overview
This dashboard visualizes the performance of shows, categories, and user engagement patterns using data from an OTT platform’s backend.

### Key Features:
- 📈 Total watch time, views, and unique users
- 🧑‍💻 Category-wise breakdown (Content, Views, Users, Ads Impressions)
- 📊 Monthly trends for watch time and views
- 🥇 Top-performing shows by view count
- 🎯 Filters for category selection

---

## 🔍 Key Metrics Tracked
| Metric                    | Description                                  |
|--------------------------|----------------------------------------------|
| `Count of show id`       | Total unique shows available                 |
| `Sum of users`           | Cumulative users who engaged with content    |
| `Sum of watched_time`    | Total viewing time across all content        |
| `Average watched time`   | Avg. viewing time per user/content           |
| `Count of views`         | Total video plays                            |
| `Top 5 Contents`         | Most viewed shows                            |
| `Watch Time Trends`      | Monthly trend of views vs. watch time        |

---

## 🧠 Tools & Technologies
| Tool           | Purpose                                         |
|----------------|--------------------------------------------------|
| **Power BI**   | Visualization and report creation                |
| **AWS Athena** | Data warehouse queried via ODBC connection       |
| **ODBC Driver**| Used to connect Power BI to Athena               |
| **SQL / Presto** | Query language for Athena                        |
| **AWS S3**     | Underlying storage layer for Athena tables       |

---

## 📊 Visual Breakdown
- **Donut Charts**: Content Ratio, Views Ratio, User Ratio, and Ads Impressions per category.
- **Line & Area Chart**: Time-based trend showing spikes and drops in viewership.
- **Bar Chart**: Highlights Top 5 content by views.

---

## 📦 Data Source
Data is queried live from **AWS Athena** using the **ODBC connector**, which connects Power BI directly to Athena’s Presto-based SQL engine. Data resides in **S3** in a structured format such as Parquet or CSV.

---

## 📌 Use Case
This dashboard can be used by:
- 📺 OTT Product Teams for **content planning**
- 📢 Marketing Teams to **analyze campaign ROI**
- 📊 BI Analysts to **monitor engagement**
- 💼 Executives to make **data-driven decisions**

---

## 👨‍💻 Author
**Amitesh Awasthi**  
Data Analyst @ Appsquadz Software Pvt. Ltd.  
Expert in BI dashboards, SQL, AWS Glue, and ETL automation.

- [LinkedIn](https://www.linkedin.com/in/amitesh-awasthi)
- [GitHub](https://github.com/amiteshawasthi)

---

## ⭐ If you like this project
Don’t forget to **Star** 🌟 this repo or connect with me to collaborate on more analytics pipelines!

