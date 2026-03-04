Analyzing Motorcycle Part Sales

📌 Project Overview

I worked for a company that sells motorcycle parts, and they asked for my help in analyzing their sales data. They operate three warehouses in the area, selling both retail and wholesale, and offer a variety of parts while accepting credit cards, cash, and bank transfer as payment methods, each with different fees.
The board of directors wanted to gain a better understanding of wholesale revenue by product line and how it varies month-to-month and across warehouses. I was tasked with calculating net revenue for each product line and grouping the results by month and warehouse, filtering the data so that only "Wholesale" orders are included.
They provided me with access to their database, which contains a table called sales, and I used it to perform the required analysis.

🎯 Project Objective

My goal was to determine how much Wholesale net revenue each product line generated per month per warehouse. I focused on analyzing net revenue to provide clear financial insight into product performance across locations and time periods.

🛠️ Approach

Filtered the dataset to include only Wholesale orders
Calculated net revenue as:
SUM(total) - SUM(payment_fee)
Grouped results by:
product_line
month (June, July, August)
warehouse
Sorted results by product_line, month, and net_revenue (descending)

🗄️ Database Information

Table Used: sales
The dataset includes transactional sales data containing product lines, warehouse locations, order types, totals, and associated payment fees.

📊 Key Outcome

Through this analysis, I identified how wholesale revenue varied by product line, warehouse, and month. This provided clearer visibility into revenue streams and supported better strategic decision-making for the business.
