# **Sales & Profitability Performance Analysis (SQL → Power BI)**

---

> An end-to-end data analytics project
> 
> 
> **SQL**
> 
> **Power BI**
> 
> **DAX**
> 

---

## **Project Overview**

This project demonstrates the full analytics workflow from querying raw retail data in SQL to developing a multi-page interactive Power BI dashboard.

The goal was to uncover **revenue drivers**, **profitability trends**, **discount impacts**, and **customer behavior patterns** to support data-driven retail decisions.

---

## **Dataset Description**

| **Table** | **Description** | **Key Fields** |
| --- | --- | --- |
| **Sales** | Order-level transactional data | OrderID, OrderDate, Sales, Profit, Discount, Quantity, ProductID, CustomerID, RegionID |
| **Products** | Product details | ProductID, Category, Sub-Category, ProductName |
| **Customers** | Customer demographics & segments | CustomerID, CustomerName, Region, Segment |
| **Dates** | Calendar table for time intelligence | Date, Month, Year, Quarter |

---

## **Business Objectives**

1. Measure overall sales, profit, and profitability margin.
2. Identify high-performing and under-performing **regions**, **categories**, and **products**.
3. Evaluate **discount impact** on profit and margin.
4. Analyze **customer segments** and top buyers.
5. Deliver an **executive-ready** Power BI dashboard summarizing key insights.

---

## **Tools & Technologies**

| **Purpose** | **Tool** |
| --- | --- |
| Data Querying | **SQL (MySQL)** |
| Data Modeling & Visualization | **Power BI Desktop (.pbix)** |
| Business Calculations | **DAX** |
| Documentation | **Excel, Markdown, PDF** |

---

## **Workflow Summary**

1. **Data Exploration in SQL** – Verified completeness, cleaned missing values.
2. **KPI Creation in SQL** – Revenue, Profit, Margin, Orders, AOV, Discount.
3. **Data Validation** – Matched SQL KPIs to Power BI measures
4. **Data Modeling in Power BI** – Star schema with dimension tables.
5. **Visualization & Storytelling** – 4-page dashboard with insights.
6. **PDF & Portfolio Packaging** – Exported as Retail_Sales_Performance_Report.pdf.
7. **Insight Documentation** – Highlighted key findings for presentation.

---

## **Power BI Dashboard Overview**

### **Page 1 - Sales & Profitability Overview**

- KPIs: Revenue ($2.3 M), Profit ($286 K), Margin (12.5 %), Orders, Avg Order Value
- Daily & Monthly trend lines
- Quick business summary boxes

### **Page 2 - Regional & Category Performance**

- Sales by Region
- Sales by Category
- Regional × Segment performance
- Dynamic insights (Top Region, Category, Segment)

### **Page 3 — Product Performance**

- Top 5 / Bottom 5 Products by Sales & Profit
- Product category share
- Profit by Region mini-chart
- Dynamic insight cards summarizing best & worst performers

### **Page 4 — Customer & Discount Insights**

- Discount impact on profit (waterfall)
- Customer segment contribution
- Top customers table with margin bars

---

## **Key Metrics**

| **KPI** | **Definition** | **Value (2020–2023)** |
| --- | --- | --- |
| **Total Revenue** | SUM(Sales) | **$2.3M** |
| **Total Profit** | SUM(Profit) | **$286K** |
| **Profit Margin** | SUM(Profit)/SUM(Sales) | **12.5 %** |
| **Total Orders** | COUNT(DISTINCT OrderID) | **≈ 5,000** |
| **Average Order Value (AOV)** | SUM(Sales)/COUNT(DISTINCT OrderID) | **$458.6** |
| **Average Discount** | AVG(Discount) | **15.2 %** |

---

## **Key Insights**

- **West region** leads all with ~31 % of total sales.
- **Technology category** contributes 36 % of revenue and highest profit margin.
- **Discounts > 20 %** sharply reduce profitability.
- **Frequent Buyers** generate ~70 % of overall sales.
- **Top Product:** Canon imageCLASS 2200 ($61.6 K sales, $25.2 K profit).
- **Top Customer:** Emily Phan ($5.5 K profit).
- **Overall Profitability:** Average profit margin = **12.5%**, showing potential for pricing optimization.

---

## **Results & Business Impact**

The analysis revealed clear **profit concentration zones** and **actionable levers**:

- Focus marketing on **West region** and **Technology category**.
- Limit discounts above 20 % to protect margins.
- Strengthen relationships with **high-value repeat customers**.
- Improve pricing on **low-margin product lines**.

---

## **Skills Demonstrated**

- SQL Aggregations & Joins
- Data Cleaning & Validation
- Power BI Data Modeling (Star Schema)
- DAX Calculations & Dynamic Insights
- Visual Storytelling & Dashboard Design
- Business KPI Definition
- End-to-End Analytics Documentation

---

## **Author**

**Aijaz Ahmed**

*Data Analyst | Business Intelligence | SQL | Power BI | Python*
