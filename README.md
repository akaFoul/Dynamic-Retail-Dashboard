## Overview

This project involves the creation of a dynamic retail dashboard using Microsoft Excel, designed to visualize and analyze retail sales data across various dimensions. The dashboard connects to three main data tables-Orders, Returns, and People-and helps businesses gain insights into key sales performance metrics. This project is ideal for businesses looking to enhance their decision-making processes by analyzing data through dynamic visualizations and KPIs.

The dashboard includes key performance indicators (KPls) that track important metrics such as Total Sales, Total Profit, Quantity Sold, Number of Orders, and Profit Margin. These KPis are calculated and displayed on a centralized chart to ensure easy comparison and visualization. The project covers multiple problem statements that help break down the data into actionable insights.

-----

## Sample Data Tables

### **Order Table**
| Category   | Sub-Category | Product Name                                                       | Sales    | Quantity | Discount | Profit   | Shipping Cost | Order Priority | Customer Type |
|------------|--------------|--------------------------------------------------------------------|----------|----------|----------|----------|---------------|----------------|---------------|
| Technology | Accessories  | Plantronics CS510 - Over-the-Head monaural Wireless Headset System | 2309.65  | 7        | 0        | 762.1845 | 933.57        | Critical       | Good          |
| Furniture  | Chairs       | Novimex Executive Leather Armchair, Black                          | 3709.395 | 9        | 0.1      | -288.765 | 923.63        | Critical       | Bad           |
| Technology | Phones       | Nokia Smart Phone, with Caller ID                                  | 5175.171 | 9        | 0.1      | 919.971  | 915.49        | Medium         | Good          |
 
### **Returns Table**
| Returned | Order ID       | Market         |
|----------|----------------|----------------|
| Yes      | MX-2013-168137 | LATAM          |
| Yes      | US-2011-165316 | LATAM          |
| Yes      | ES-2013-1525878| EU             |
| Yes      | CA-2013-118311 | United States  |
| Yes      | ES-2011-1276768| EU             |

### **Returns Table**
| Person            | Region  |
|-------------------|---------|
| Anna Andreadi     | Central |
| Chuck Magee       | South   |
| Kelly Williams    | East    |
| Matt Collister    | West    |
| Deborah Brumfield | Africa  |

----

## KPI Tbale

The KPI table consolidates the most essential performance metrics for the retail analysis. These KPIs altow the dashboard to provide actionable insights by comparing important aspects of sales performance.
| KPT Name       | Symbol | Formula                  |
|----------------|--------|--------------------------|
| Total Sales    | 📈     | SUM(Sales)               |
| Total Profit   | 💰     | SUM(Profit)              |
| Total Quantity | 📦     | SUM(Quantity)            |
| No of Orders   | 🛒     | COUNT(Order ID)          |
| Profitability  | 🔍     | SUM(Profit) / SUM(Sales) |

## Problen Statements Solved

The dynamic retail dashboard answers several business questions, providing in-depth insights into key performance areas:

1. **KPIS** - Total Sales, Total Profit, Quantaty, No. of Orders, Profit Margin

   <img width="660" height="65" alt="image" src="https://github.com/user-attachments/assets/360e7ddd-339b-433f-b8d8-d3f229e68d71" />

2. **Sales and Profit Analysis** - Understanding overall sales and profitability

   <img width="440" height="272" alt="image" src="https://github.com/user-attachments/assets/f5a7bd75-ad1f-417c-9063-62e5a958adfb" />

4. **Category-wise Profit** - Breakdown of profit by product category

   <img width="322" height="274" alt="image" src="https://github.com/user-attachments/assets/daa241ae-492b-4c48-8d18-ce696fbc9e97" />
   
6. **Segment-wise Sales Share %** - Breakdown of sales by customer segnent 

S. **Sales by Country** - Sales performance based on different countries

6. **Top 5 Subcategories** - The best-performing subcategories based on sales

7. **Botton 5 Subcategories** - The least-performing subcategories based on sales

8. **Yearly Sales Trend** - Understanding how sales evolve over the year



