# Customer Shopping Behavior Analysis

This project analyzes customer shopping data to understand purchasing patterns, customer behavior, and product performance. It combines a structured dataset, SQL analysis, and a Jupyter Notebook to explore the business questions behind customer retail activity.

## Project Overview

The analysis focuses on:
- Customer spending and revenue trends
- Gender and subscription-based purchase patterns
- Discount and promo code impact
- Product popularity by category
- Customer segmentation based on purchase history
- Shipping and review rating comparisons

## Dataset

The main dataset is:
- `customer_shopping_behavior.csv`

It contains customer-level transaction data including:
- Customer ID
- Age and gender
- Item purchased and category
- Purchase amount
- Location and shipping type
- Subscription status
- Discount and promo usage
- Review rating
- Previous purchases and frequency of purchases

## Files in this Project

- `customer_behavior.ipynb` – Jupyter Notebook for data exploration and analysis
- `customer_behavior.sql` – SQL queries answering key business questions
- `customer_shopping_behavior.csv` – source dataset
- `customer_behavior_dashboard.pbix` – Power BI dashboard file
- `Customer-Shopping-Behavior-Analysis.pptx` – presentation deck
- `Business Problem Document.pdf` – business problem statement
- `Customer Shopping Behavior Analysis.pdf` – detailed analysis report

## Business Questions Covered

The project answers questions such as:
- Which gender group generates more revenue?
- Which products have the highest average review ratings?
- How do discounts affect spending?
- Do subscribed customers spend more than non-subscribed customers?
- Which products are most frequently purchased by category?
- Are repeat buyers more likely to subscribe?
- Which age groups contribute the most revenue?

## Tools and Technologies

- Python
- Pandas
- Jupyter Notebook
- SQL
- Power BI

## Getting Started

### 1. Install Python dependencies

Make sure Python is installed, then install the required packages:

```bash
pip install pandas jupyter
```

### 2. Open the notebook

Run:

```bash
jupyter notebook customer_behavior.ipynb
```

### 3. Use the SQL queries

Open `customer_behavior.sql` in a SQL client or database environment that supports the dataset schema. The queries are written to answer practical retail analytics questions.

## Recommended Workflow

1. Load the CSV into a dataframe using the notebook
2. Clean and inspect the data
3. Run exploratory data analysis
4. Validate findings with SQL queries
5. Use the dashboard and presentation files for reporting

## Insights Summary

This analysis helps businesses understand consumer behavior, optimize marketing strategies, and improve pricing and product decisions. The results can support actions such as:
- Targeting high-value customer segments
- Improving discount and promo campaigns
- Adjusting inventory based on category trends
- Enhancing customer retention strategies

## License

This project is intended for educational and analytical use.
