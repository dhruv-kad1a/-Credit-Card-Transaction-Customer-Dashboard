# 📊 Credit Card Transaction & Customer Dashboard

## 🔹 Project Objective
To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

## 🛠 Tech Stack
* Database: PostgreSQL (ccdb)
* Data Visualization: Power BI
* Languages/Queries: SQL, DAX

## 📂 Data & Database Setup
* Imported 4 CSV files (Credit Card & Customer as primary, 2 additional datasets).
* Created ccdb database in PostgreSQL with two main tables:
    * ``cc_detail`` (credit card transaction details)
    * ``cust_detail`` (customer demographic details)
* Loaded CSV data into PostgreSQL using COPY command.

## 📈 DAX Measures Implemented
* Age Group Segmentation (20–30, 30–40, 40–50, 50–60, 60+)
* Income Group Classification (Low, Med, High)
* Week Calculation (``WEEKNUM``)
* Revenue Metrics:
   * Revenue = Annual Fees + Transaction Amount + Interest Earned
   * Current Week Revenue vs. Previous Week Revenue (WoW comparison)
 
