# Nigerian E-commerce Sales Data Cleaning Challenge

## The Situation

You just started as a data analyst intern at **NaijaShop**, a growing e-commerce company in Lagos.

The sales manager comes to you frustrated and says:

> "We've been tracking sales in Excel for 6 months. Different team members have been entering data — some from Lagos office, some from Abuja, some working remotely. Now the CEO wants a report on our best-selling products and top-performing states, but the data is a mess. Can you clean it up so we can actually analyze it?"

---

## The Dataset

**File:** `raw_sales_data.csv`
**Size:** 500+ rows of customer orders

---

## Issues in the Data

### 1. Customer names – inconsistent formatting

* Some all caps: `TUNDE BAKARE`
* Some all lowercase: `amina ibrahim`
* Extra spaces: `Chinedu Okafor`
* Empty cells

### 2. Phone numbers – different formats

* `08012345678`
* `0803-456-7890`
* `080 4567 8902`
* `"not available"`

### 3. States – inconsistent capitalization

* `lagos`, `LAGOS`, `Lagos` (all same state)

### 4. Products – same product, different names

* `Samsung Phone`, `samsung phone`, `SAMSUNG PHONE`
* `HP Laptop` vs `HP laptop`

### 5. Prices – mixed formatting

* `150000`
* `350,000`

### 6. Dates – multiple formats

* `2024-10-15`
* `15/10/2024`
* `Oct 19 2024`
* `22-10-2024`

### 7. Payment Status – inconsistent

* `Paid`, `paid`, `PAID`

### 8. Missing values

* Missing emails
* Missing quantity
* Phone numbers saying `"not available"`

### 9. Duplicate orders

* Some rows entered twice by mistake

### 10. Emails – inconsistent and invalid

* `CHINEDU@EMAIL.COM` vs `chinedu@email.com`
* `"no email"` (not valid)

---

## Your Manager's Questions (Answer these after cleaning)

1. What is the total revenue for the past 6 months?
2. Which state generates the most sales?
3. What are the top 5 best-selling products?
4. How many unique customers do we have?
5. What is the average order value?
6. Which month had the highest sales?
7. What percentage of orders are paid vs pending vs failed?

---

## Your Deliverables

* A clean CSV file with standardized data
* A brief report answering the 7 questions above
* 3–5 visualizations showing key insights
* A data cleaning documentation explaining what you fixed

---

## Why This Is Perfect Practice

* Realistic – this is exactly what many Nigerian companies deal with
* Common problems – these issues appear in almost every real dataset
* Interview-worthy – great story for job interviews
* Portfolio-ready – you can upload to GitHub and LinkedIn

---

## The Challenge

Can you take this messy data and make it analysis-ready?

Use the skills you learned:

* `.str.strip()` for removing spaces
* `.str.title()` for standardizing capitalization
* `pd.to_numeric()` for cleaning numbers
* `pd.to_datetime()` for date formats
* `.dropna()` or `.fillna()` for missing values
* `.drop_duplicates()` for removing duplicates
* `.replace()` for standardizing categories

