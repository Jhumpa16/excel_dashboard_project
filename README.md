# Dyanamic_Retail_Dashboard
Overview
This project involves the creation of a dynamic retail dashboard using Microsoft Excel, designed to visualize and analyze retail sales data across various dimensions. The dashboard connects to three main data tables—Orders, Returns, and People—and helps businesses gain insights into key sales performance metrics. This project is ideal for businesses looking to enhance their decision-making processes by analyzing data through dynamic visualizations and KPIs.

The dashboard includes key performance indicators (KPIs) that track important metrics such as Total Sales, Total Profit, Quantity Sold, Number of Orders, and Profit Margin. These KPIs are calculated and displayed on a centralized chart to ensure easy comparison and visualization. The project covers multiple problem statements that help break down the data into actionable insights.

Sample Data Tables
Orders Table
Order ID	Order Date	Ship Date	Ship Mode	Customer Name	Segment	Country	Sales	Profit	Quantity	Discount
CA-2012-124891	31-07-2020	31-07-2020	Same Day	Rick Hansen	Consumer	United States	2309.65	762.18	7	0
IN-2013-77878	05-02-2021	07-02-2021	Second Class	Justin Ritter	Corporate	Australia	3709.40	-288.77	9	0.1
IN-2013-71249	17-10-2021	18-10-2021	First Class	Craig Reiter	Consumer	Australia	5175.17	919.97	9	0.1
ES-2013-1579342	28-01-2021	30-01-2021	First Class	Katherine Murray	Home Office	Germany	2892.51	-96.54	5	0.1
SG-2013-4320	05-11-2021	06-11-2021	Same Day	Rick Hansen	Consumer	Senegal	2832.96	311.52	8	0
Return Table
Returned	Order ID	Market
Yes	MX-2013-168137	LATAM
Yes	US-2011-165316	LATAM
Yes	ES-2013-1525878	EU
Yes	CA-2013-118311	United States
Yes	ES-2011-1276768	EU
People Table
Person	Region
Anna Andreadi	Central
Chuck Magee	South
Kelly Williams	East
Matt Collister	West
Deborah Brumfield	Africa
KPI Table
The KPI table consolidates the most essential performance metrics for the retail analysis. These KPIs allow the dashboard to provide actionable insights by comparing important aspects of sales performance.

KPI Name	Symbol	Formula
Total Sales	💰	SUM(Sales)
Total Profit	📈	SUM(Profit)
Total Quantity	📦	SUM(Quantity)
No of Orders	🛒	COUNT(Order ID)
Profitability	🔍	SUM(Profit) / SUM(Sales)
Problem Statements Solved
The dynamic retail dashboard answers several business questions, providing in-depth insights into key performance areas:

KPIs - Total Sales, Total Profit, Quantity, No. of Orders, Profit Margin

![image](https://github.com/user-attachments/assets/4b67e069-fc42-41d3-bc3d-308125f94f62)

Sales and Profit Analysis - Understanding overall sales and profitability

![image](https://github.com/user-attachments/assets/91778255-e502-4d13-b993-69c7c1a8c1f1)


Category-wise Profit - Breakdown of profit by product category

![image](https://github.com/user-attachments/assets/aa2f0bb6-1992-423f-8050-db1d83a36358)


Segment-wise Sales Share % - Breakdown of sales by customer segment

![image](https://github.com/user-attachments/assets/c9f53a3e-b07d-43dd-b1c7-49f68bd8410e)


Sales by Country - Sales performance based on different countries

![image](https://github.com/user-attachments/assets/848f58a1-9110-44c4-a890-db8ab6a653ec)


Top 5 Subcategories - The best-performing subcategories based on sales

![image](https://github.com/user-attachments/assets/6f59b81e-50d2-416d-aab5-f97a4bd5d2b8)


Bottom 5 Subcategories - The least-performing subcategories based on sales

![image](https://github.com/user-attachments/assets/d9cd8f78-358a-43bc-baa7-13e05777cc1f)


Yearly Sales Trend - Understanding how sales evolve over the year

![image](https://github.com/user-attachments/assets/e3300e1e-71ed-49a0-8133-72515a8f1b93)

Snapshot of the Dashboard
![image](https://github.com/user-attachments/assets/8fea0086-e07b-45aa-8255-be65dbad45db)

Conclusion
The Retail Dashboard serves as an invaluable tool for business analysts and retail managers by providing a comprehensive view of sales performance. The dashboard aggregates data from key business areas and visualizes them dynamically, allowing for quick decision-making. With its ability to calculate essential KPIs and generate detailed analyses across different product categories, regions, and time periods, the dashboard ensures that stakeholders can make data-driven decisions to optimize retail operations.
