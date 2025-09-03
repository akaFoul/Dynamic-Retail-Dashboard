## Overview

This project involves the creation of a dynamic retail dashboard using Microsoft Excel, designed to visualize and analyze retail sales data across various dimensions. The dashboard connects to three main data tables-Orders, Returns, and People-and helps businesses gain insights into key sales performance metrics. This project is ideal for businesses looking to enhance their decision-making processes by analyzing data through dynamic visualizations and KPIs.

The dashboard includes key performance indicators (KPls) that track important metrics such as Total Sales, Total Profit, Quantity Sold, Number of Orders, and Profit Margin. These KPis are calculated and displayed on a centralized chart to ensure easy comparison and visualization. The project covers multiple problem statements that help break down the data into actionable insights.

---

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

### **People Table**
| Person            | Region  |
|-------------------|---------|
| Anna Andreadi     | Central |
| Chuck Magee       | South   |
| Kelly Williams    | East    |
| Matt Collister    | West    |
| Deborah Brumfield | Africa  |

---

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

3. **Category-wise Profit** - Breakdown of profit by product category

   <img width="322" height="274" alt="image" src="https://github.com/user-attachments/assets/daa241ae-492b-4c48-8d18-ce696fbc9e97" />
   
4. **Segment-wise Sales Share %** - Breakdown of sales by customer segnent

   <img width="453" height="385" alt="image" src="https://github.com/user-attachments/assets/595f93b2-e498-44f4-81d5-79c30488e7c4" />

5. **Sales by Country** - Sales performance based on different countries

   <img width="623" height="387" alt="image" src="https://github.com/user-attachments/assets/09c98a6f-4303-42f2-a122-063704804163" />

6. **Top 5 Subcategories** - The best-performing subcategories based on sales

   <img width="453" height="391" alt="image" src="https://github.com/user-attachments/assets/ab4bc1c3-f5cc-459b-bc79-a735614c6800" />

7. **Botton 5 Subcategories** - The least-performing subcategories based on sales

    <img width="457" height="390" alt="image" src="https://github.com/user-attachments/assets/1f954403-6d29-4a07-9400-7596b4fa8c84" />

8. **Yearly Sales Trend** - Understanding how sales evolve over the year

    <img width="944" height="174" alt="image" src="https://github.com/user-attachments/assets/d94601e6-c7c4-4755-9788-1f74922a7798" />


---

## Snapshot of Dashboard

<img width="1174" height="649" alt="image" src="https://github.com/user-attachments/assets/2886e8cd-b385-4de5-9539-aed8b3a9ffb2" />

---

## Conclusion

The **Retail Dashboard** serves as an invaluable tool for business analysts and retail managers by providing a comprehensive view of sales performance. The dashboard aggregates data from key business areas and visualizes them dynamically, allowing for quick decision-making. With its ability to calculate essential Kis and generate detailed analyses across different product categories, regions, and time periods, the dashboard ensures that stakeholders can make data-driven decisions to optimize retail operations.
