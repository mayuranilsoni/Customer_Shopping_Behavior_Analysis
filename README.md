Customer Shopping Behavior Analysis

Project Overview

This is my **deep-dive Data Analytics** project focused on understanding customer shopping behavior. By analyzing **3,900 transactional records**, my goal was to identify key spending patterns, define customer loyalty groups, and measure the revenue impact of subscriptions.

The insights generated from this analysis provide a clear roadmap for **smarter business decisions** related to marketing, product promotion, and discount strategies.

---

Key Questions Answered

I used specific queries to answer vital business questions:

* **Gender & Revenue:** Who generates more total sales: men or women?
* **Loyalty & Spending:** How much more do subscribers spend than non-subscribers?
* **Best Sellers:** What are the Top 5 most-loved (highest-rated) products?
* **Discounts:** Which products are *only* popular when a discount is offered?
* **Age Value:** Which customer age groups bring in the most revenue?
* **Customer Groups:** How did I define and categorize customers (New, Returning, Loyal)?

---

Technology & Methodology

I executed this project using a structured data analysis pipeline:

1. Data Cleaning & Feature Engineering (Python)
* I loaded **3,900 purchases** with 18 data points each.
* I handled **missing values**, specifically filling **37 review scores** using the product category's median rating.
* I created new insights like **customer age groups** and calculated the **days between purchases**.

2. Deep Analysis (PostgreSQL & SQL)
* I loaded the cleaned dataset into a **PostgreSQL** database.
* I ran complex **SQL queries** to perform aggregations and answer all the key business questions listed above.

3. Reporting & Visualization (Power BI)
* I created an **interactive dashboard** in **Power BI** to present my findings (e.g., revenue by age group, loyalty vs. subscription rates) in a clear, visual format.

---

My Actionable Recommendations

Based on my data analysis, here are the strategic recommendations I developed:

| Focus Area | My Recommendation |
| :--- | :--- |
| **Subscription Growth** | Offer **exclusive perks** to encourage sign-ups and increase recurring revenue. |
| **Customer Loyalty** | Create a **rewards program** to convert "Returning" customers into high-value "Loyal" buyers. |
| **Marketing** | Run campaigns that highlight the **top-rated products** and target the **highest-spending age groups**. |
| **Discounts** | **Fine-tune the discount strategy** to ensure promotional boosts do not severely hurt profit margins. |

---

Repository Contents

* `data/`: Contains the original and cleaned CSV files I used.
* `notebooks/`: **Jupyter Notebook** I used for data cleaning, transformation, and feature engineering.
* `sql_queries/`: Text files containing the **PostgreSQL (SQL)** queries I ran for the key findings.
* `power_bi_report/`: Link or screenshot of the final Power BI dashboard I built.
* `README.md`: (This file) Project summary and findings.
