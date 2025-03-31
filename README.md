# Dyanamic_Retail_Dashboard

## Overview

This project involves the creation of a **dynamic retail dashboard** using **Microsoft Excel**, designed to visualize and analyze retail sales data across various dimensions. The dashboard connects to three main data tables—**Orders, Returns, and People**—helping businesses gain insights into key sales performance metrics. This project is ideal for businesses looking to enhance their decision-making processes by analyzing data through dynamic visualizations and KPIs.

---

## Features

- **Interactive Dashboard:** Provides real-time insights into key performance metrics.
- **Data Integration:** Uses three data tables (**Orders, Returns, and People**) for comprehensive analysis.
- **KPI Tracking:** Monitors crucial business metrics such as **Total Sales, Profit, Quantity Sold, Number of Orders, and Profit Margin**.
- **Actionable Insights:** Solves multiple business problems through in-depth data breakdowns.

---

## Sample Data Tables

### **Orders Table**
| Order ID        | Order Date | Ship Date | Ship Mode     | Customer Name   | Segment     | Country       | Sales   | Profit  | Quantity | Discount |
|---------------|------------|------------|--------------|----------------|------------|--------------|---------|--------|---------|----------|
| CA-2012-124891 | 31-07-2020 | 31-07-2020 | Same Day     | Rick Hansen    | Consumer   | United States | 2309.65 | 762.18 | 7       | 0        |
| IN-2013-77878  | 05-02-2021 | 07-02-2021 | Second Class | Justin Ritter  | Corporate  | Australia     | 3709.40 | -288.77 | 9      | 0.1      |
| IN-2013-71249  | 17-10-2021 | 18-10-2021 | First Class  | Craig Reiter   | Consumer   | Australia     | 5175.17 | 919.97  | 9      | 0.1      |

### **Returns Table**
| Returned | Order ID         | Market     |
|----------|----------------|------------|
| Yes      | MX-2013-168137 | LATAM      |
| Yes      | US-2011-165316 | LATAM      |
| Yes      | ES-2013-1525878 | EU         |
| Yes      | CA-2013-118311  | United States |
| Yes      | ES-2011-1276768 | EU         |

### **People Table**
| Person            | Region  |
|------------------|---------|
| Anna Andreadi    | Central |
| Chuck Magee      | South   |
| Kelly Williams   | East    |
| Matt Collister   | West    |
| Deborah Brumfield | Africa |

---

## KPI Table

The KPI table consolidates the most essential performance metrics for retail analysis, allowing the dashboard to provide actionable insights by comparing key aspects of sales performance.

| KPI Name        | Symbol  | Formula                     |
|---------------|--------|----------------------------|
| Total Sales   | 💰      | `SUM(Sales)`               |
| Total Profit  | 📈      | `SUM(Profit)`              |
| Total Quantity | 📦      | `SUM(Quantity)`            |
| No of Orders  | 🛒      | `COUNT(Order ID)`          |
| Profitability | 🔍      | `SUM(Profit) / SUM(Sales)` |


---


## Problem Statements Solved

The dynamic retail dashboard helps businesses analyze sales and profit data effectively, addressing multiple key problem areas:

1. **Key Performance Indicators (KPIs):** Tracking total sales, total profit, quantity sold, number of orders, and profit margin.  
    ![image](https://github.com/user-attachments/assets/2edd8598-6b12-4a52-9127-721b15f8c00b)


2. **Sales and Profit Analysis:** Understanding overall sales trends and profitability to optimize business strategies.  
    ![image](https://github.com/user-attachments/assets/91778255-e502-4d13-b993-69c7c1a8c1f1)


3. **Category-wise Profit :** Breakdown of profit by product category

![image](https://github.com/user-attachments/assets/aa2f0bb6-1992-423f-8050-db1d83a36358)


4. **Segment-wise Sales Share % :** Breakdown of sales by customer segment

![image](https://github.com/user-attachments/assets/c9f53a3e-b07d-43dd-b1c7-49f68bd8410e)


5. **Sales by Country :** Sales performance based on different countries

![image](https://github.com/user-attachments/assets/848f58a1-9110-44c4-a890-db8ab6a653ec)


6. **Top 5 Subcategories :** The best-performing subcategories based on sales

![image](https://github.com/user-attachments/assets/6f59b81e-50d2-416d-aab5-f97a4bd5d2b8)


7. **Bottom 5 Subcategories :** The least-performing subcategories based on sales

![image](https://github.com/user-attachments/assets/d9cd8f78-358a-43bc-baa7-13e05777cc1f)


8. **Yearly Sales Trend :** Understanding how sales evolve over the year

  ![image](https://github.com/user-attachments/assets/4b67e069-fc42-41d3-bc3d-308125f94f62)

9. **Snapshot of the Dashboard**
![image](https://github.com/user-attachments/assets/8fea0086-e07b-45aa-8255-be65dbad45db)

## Conclusion
The Retail Dashboard serves as an invaluable tool for business analysts and retail managers by providing a comprehensive view of sales performance. The dashboard aggregates data from key business areas and visualizes them dynamically, allowing for quick decision-making. With its ability to calculate essential KPIs and generate detailed analyses across different product categories, regions, and time periods, the dashboard ensures that stakeholders can make data-driven decisions to optimize retail operations.
