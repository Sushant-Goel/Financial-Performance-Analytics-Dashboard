# Financial-Performance-Analytics-Dashboard
Revenue • Expense • Receivables • Collections • Liquidity

**1. Project Overview**
This project is an end-to-end financial analytics case study built to simulate how a finance team (FP&A / Credit Control / Business Finance) monitors operational performance and liquidity.
Using a transaction-level dataset containing invoice dates, due dates, customers, payment status, and invoice amounts, I developed a financial analysis model that evaluates both profitability and cash realization efficiency. The project replicates a typical mid-size FMCG / B2B company environment where sales are largely credit-based and collection management directly impacts working capital.

**2. Business Objective**
The model answers practical finance questions:
* Is revenue actually converting into cash?
* Are receivables being collected on time?
* Is working capital getting blocked in debtors?
* Are expenses growing faster than revenue?
* Which periods show collection stress?

 **3. Dataset Description**
The dataset consists of transactional records including:
* Invoice Number
* Invoice Date
* Due Date
* Customer Name
* Invoice Amount
* Payment Status (Paid / Partial Paid / Unpaid)
* Budgeted Expense & Actual Expense

4. Tools & Technologies Used
* **Microsoft Excel** – Data modeling & financial calculations
* **Power Query** – Data cleaning, transformation, and shaping
* **Power BI** – Interactive dashboards & reporting
* **DAX (Data Analysis Expressions)** – KPI and time-intelligence measures

**5. Financial KPIs Developed**
Revenue & Profitability
* Monthly Revenue
* Month-on-Month (MoM) Growth
* Year-to-Date (YTD) Revenue
* Expense ratio
* Budget vs Actual Expense

**Receivables & Credit Control
* Collection Efficiency
* Overdue Amount
* Receivables Ageing (0–30, 31–60, 61–90, 90+ days)

Working Capital & Liquidity
* Days Sales Outstanding (DSO)
* Outstanding Receivables

**6. Technical Implementation**
#Excel (Financial Model)
Used for building the base financial model and validating calculations.

Key Excel functions applied:
* **SUMIFS**
* **XLOOKUP**
* **IF**
* **IFS**
* **COUNTIFS**
* **Pivot Tables**
* **Conditional Formatting**

Excel was used to:
* Derive overdue invoices using Due Date logic
* Categorize ageing buckets
* Reconcile paid vs unpaid receivables
* Prepare monthly performance tables

#Power Query (Data Transformation)
* Removed inconsistencies
* Standardized date formats
* Created calendar table
* Calculated days overdue
* Structured fact and dimension tables

#Power BI (Visualization Layer)

An interactive finance dashboard was developed including:
* Revenue trend analysis
* Expense performance
* Receivables ageing
* Customer outstanding tracking
* Working capital indicators

The dashboard allows slicers by:
* Month
* Department
* Region

#DAX Measures Implemented

Key DAX functions used:
* CALCULATE
* DIVIDE
* FILTER
* SUM
* TOTALYTD
* DATEADD
* IF

These were used to compute:
* Revenue Growth (MoM)
* Expense Ratio
* Collection Efficiency
* Overdue Amount
* DSO

**7. Business Insights Generated**

The analysis highlighted realistic finance observations such as:
* A portion of receivables consistently moving beyond 60+ days
* Periods where revenue increased but collections did not follow
* Working capital pressure driven by overdue customers
* Months where expense growth outpaced revenue growth
* Identification of customers contributing most to outstanding balance

**8. What This Project Demonstrates**

This project reflects practical finance capabilities:
* Credit & receivables analysis
* KPI framework design
* Working capital monitoring
* Data-driven decision support

**9. Screenshots/Demos**
show what the dashboard looks like
Example : https://github.com/Sushant-Goel/Financial-Performance-Analytics-Dashboard/blob/main/Snapshot%20of%20Dashboard.png
