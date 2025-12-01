# Nigerian E-commerce Sales Analysis

**Your boss says:**
*"Analyze our last 6 months of sales data and present findings to the CEO tomorrow morning. I need answers to these questions."*

---

## THE 7 QUESTIONS YOU MUST ANSWER

1. **What is our total revenue (from paid orders only)?**
2. **How many unique customers do we have?**
3. **What are the top 5 best-selling products?**
4. **Which 5 states generate the most revenue?**
5. **What is the average order value?**
6. **What percentage of orders are Paid vs Pending vs Failed?**
7. **What is the monthly sales trend (Oct, Nov, Dec)?**

---

## YOUR TASKS (DO THESE IN ORDER)

### TASK 1 — Load your cleaned data

* Load the CSV you cleaned earlier.
* Display first 10 rows.
* Check the shape (how many rows and columns).

### TASK 2 — Create a `Total_Amount` column

* `Total_Amount = Price × Quantity`
* Store result in a new column called `Total_Amount`.

### TASK 3 — Create a `Revenue` column

* If `PaymentStatus == 'Paid'` → `Revenue = Total_Amount`
* Otherwise → `Revenue = 0`

### TASK 4 — Answer Question 1 — Total Revenue

* Sum all values in the `Revenue` column.
* Print the result.

### TASK 5 — Answer Question 2 — Unique Customers

* Count unique values in the `CustomerName` column.
* Print the result.

### TASK 6 — Answer Question 3 — Top 5 Products

* Group by `Product`.
* Count how many times each product appears (or sum quantities if available).
* Sort from highest to lowest.
* Take top 5.
* Print the result.

### TASK 7 — Answer Question 4 — Top 5 States by Revenue

* Group by `State`.
* Sum the `Revenue` for each state.
* Sort from highest to lowest.
* Take top 5.
* Print the result.

### TASK 8 — Answer Question 5 — Average Order Value

* Calculate mean of `Total_Amount` column.
* Print the result.

### TASK 9 — Answer Question 6 — Payment Status Breakdown

* Count how many orders for each `PaymentStatus`.
* Calculate percentage for each.
* Print the result.

### TASK 10 — Answer Question 7 — Monthly Trend

* Extract month from `OrderDate`.
* Group by month.
* Count orders per month.
* Sort by month.
* Print the result.

### TASK 11 — Create 3 visualizations

* **Bar chart:** Top 5 products.
* **Bar chart:** Top 5 states by revenue.
* **Line chart:** Monthly sales trend.

### TASK 12 — Save your results

* Save a summary report as `analysis_results.txt`.
* Save charts as image files (e.g., `top5_products.png`, `top5_states_revenue.png`, `monthly_trend.png`).

---

## DELIVERABLES

1. **Python script** with all analysis (fully reproducible).
2. **3 chart images** (bar: products, bar: states, line: monthly trend).
3. **Text file** with answers to all 7 questions (`analysis_results.txt`).

---

