# ✈️ SkyRoutes Airline Profitability Dashboard

![Dashboard Preview](./assets/1(5).png)

## 📌 Overview

The **SkyRoutes Airline Profitability Dashboard** is a Business Intelligence and Data Analytics project focused on analyzing airline route performance using **SQL** and **Microsoft Excel Dashboarding**.

This project uses a dataset of **5,000 airline flight records** to identify profitable routes, evaluate operational efficiency, analyze occupancy trends, and generate meaningful business insights through data visualization.

---

# 🎯 Project Objectives

- Identify the top 10 most frequent airline routes
- Calculate average revenue, operational cost, and profit per route
- Detect underperforming routes with negative profitability
- Analyze seat occupancy percentages
- Study monthly profit trends
- Compare domestic vs international route profitability
- Rank routes based on revenue generated per minute

---

# 🗂️ Dataset Information

| Feature | Description |
|---|---|
| Dataset Name | `AirlineRoutesData.csv` |
| Total Records | 5000 Rows |
| Data Type | Airline Operational & Financial Data |

### Dataset Columns

- FlightID
- RouteCode
- Origin
- Destination
- FlightDate
- FlightDurationMins
- AircraftType
- SeatsAvailable
- SeatsSold
- Revenue
- OperationalCost

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| MySQL Workbench | SQL Analysis |
| SQL | Data Querying |
| Microsoft Excel | Dashboard Development |
| Pivot Tables | Data Aggregation |
| Pivot Charts | Visualization |
| Slicers | Interactive Filtering |

---

# 📊 SQL Analysis

The following business analysis queries were performed:

## 1️⃣ Top 10 Frequent Routes
Identified routes with the highest number of flights.

## 2️⃣ Revenue, Cost & Profit Analysis
Calculated average revenue, operational cost, and profitability for each route.

## 3️⃣ Underperforming Routes
Detected routes generating negative average profit.

## 4️⃣ Occupancy Rate Analysis
Measured seat occupancy percentages across airline routes.

## 5️⃣ Monthly Profit Trend
Analyzed monthly fluctuations in profitability.

## 6️⃣ Domestic vs International Profitability
Compared financial performance between domestic and international routes.

## 7️⃣ Revenue Per Minute Ranking
Ranked routes based on operational efficiency and revenue generation.

---

# 📈 Dashboard Features

The Excel dashboard includes:

- 📌 KPI Cards
- 📊 Bar Charts
- 📈 Monthly Trend Line Charts
- 🍩 Occupancy Analysis
- 💰 Revenue vs Cost Comparison
- 🎛️ Interactive Slicers
- ✈️ Route Performance Insights

### Dashboard Filters

- RouteCode
- AircraftType
- Month
- Origin Airport

---

# 🔍 Key Insights

- High-frequency routes contributed significantly to overall airline revenue.
- International routes showed stronger profitability compared to some domestic routes.
- Higher occupancy rates positively impacted route profitability.
- Seasonal travel patterns influenced monthly revenue trends.
- Certain routes experienced negative profitability due to high operational costs.

---

# 📁 Project Structure

```bash
SkyRoutes-Airline-Profitability-Dashboard/
│
├── AirlineRoutesData.csv
├── SkyRoutesAnalysis.sql
├── RouteProfitDashboard.xlsx
├── BI_Analyst_Case_Study_SkyRoutes.pdf
├── README.md
│
└── assets/
    └── 1(5).png
```

---

# 🚀 How to Run the Project

## 1️⃣ Import Dataset
Import `AirlineRoutesData.csv` into MySQL Workbench.

## 2️⃣ Run SQL Queries
Execute all queries from:

```sql
SkyRoutesAnalysis.sql
```

## 3️⃣ Open Dashboard
Open:

```plaintext
RouteProfitDashboard.xlsx
```

Use slicers and charts to interact with the dashboard.

---

# 📌 Business Value

This project demonstrates how Business Intelligence tools can support:

- Airline route optimization
- Revenue analysis
- Operational efficiency monitoring
- Strategic business decision-making
- Interactive reporting & visualization

---

# 👨‍💻 Author

## Dhrukesh

Business Intelligence & Data Analytics Project

---

# ⭐ Project Highlights

✅ SQL-Based Business Analysis  
✅ Interactive Excel Dashboard  
✅ Airline Profitability Insights  
✅ KPI Reporting & Visualization  
✅ Business Intelligence Case Study  

---

# 📜 License

This project is developed for educational and portfolio purposes.
