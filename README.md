# Coffee_Shop

---

![Image](https://github.com/user-attachments/assets/7dd1f978-630d-486c-8983-5a5d01410be0)

---

## Project Context
The company provides a sample dataset of their coffee sales for a specific period. The task is to analyze the data and uncover patterns, inconsistencies, and insights to support business decisions.

---

## Objective
The goal of the process:
- Identify anomalies and patterns in the data.
- Generate valuable insights.
- Provide data-driven recommendations to improve performance and strategy.

---

## Available Data Tables & Variables
This project includes several relational tables:
- Customer: Contains demographic and store preference data (customer_id, home_store, email, gender, birthdate, etc.)
- Generation: Links each customer to a generational group (generation)
- Pastry Inventory: Tracks inventory and sales targets per product (product_id, start_of_day, quantity_sold, waste, etc.)
- Product: Includes product information like (product_category, retail_price, promo_yn, new_product_yn, etc.)
- Sales Outlet: Describes the physical stores (store_city, store_address, manager, store_type, etc.)
- Sales Receipts: Contains transactional data (transaction_id, sales_outlet_id, customer_id, product_id, quantity, unit_price, etc.)

---

## Process
The process in this project including:
- Cleaning and preparing the data.
- Joining and transforming datasets.
- Performing exploratory data analysis (EDA).
- Visualizing key trends and metrics.
- Recommending actions to improve store and product performance.

---

## Business Problem
The company is facing a significant waste issue, with:
- 37.3 million units of products wasted in a month
- 58.19% of daily stock not being sold
- An estimated $115 million in financial loss, assuming a 6.8% margin (according to the Specialty Coffee Association)

The business challenge is: <br/>
*How can the company reduce product waste and improve operational efficiency while increasing sales performance?*

---

## Insights & Recommendations
### Insight
- All transactions were made by loyalty cardholders.
- No promotions were run at the start of the month; they peaked mid-month.
- Best-selling products are consistent across generations and outlets.
- A large stock-sales gap is observed daily.
- Waste levels are consistent per product and outlet over time.
### Recommendations
- Run targeted promotions just before closing hours to clear potential waste.
- Promote high-performing products (e.g., Ouro Brasileo) in underperforming outlets like Astoria.
- Using predictive analytics based on historical trends, the daily stock must be reduced to around 632,000/day (relative per product). 
- Develop acquisition strategies to attract new customers beyond loyalty cardholders.

---

## Tools Used
- Python (Pandas, Numpy, Scipy, Matplotlib, Seaborn)
- SQL
- Tableau
- Ms Power Point

---
