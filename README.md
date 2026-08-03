# Customer Spending & Loyalty Analysis

## Overview
This project examines customer shopping behavior using a dataset of 3,900 purchase records. It explores category performance, spending patterns, customer segments, ratings, shipping preferences, subscription status, discounts, and purchase frequency.

The project combines Python-based exploratory analysis with SQL queries to turn raw customer records into structured business insights.

## Objectives
- Understand the overall customer and purchase profile.
- Compare spend across product categories, locations, seasons, age groups, and customer segments.
- Identify products with strong demand or rating signals.
- Evaluate descriptive differences across subscription, discount, and shipping groups.
- Document the data limitations and recommendations for future analysis.

## Dataset
The dataset contains 3,900 records and 18 fields, including:

- Customer attributes: customer ID, age, gender, and location
- Purchase attributes: item, category, purchase amount, size, color, and season
- Experience and loyalty attributes: review rating, subscription status, discount use, promo-code use, prior purchases, and purchase frequency
- Fulfilment and checkout attributes: shipping type and payment method

## Project files
| File | Description |
|---|---|
| `Customer_Shopping_Behavior_Analysis.ipynb` | Python notebook for loading, cleaning, exploring, and analysing the customer-shopping data. |
| `customer_behavior_sql_queries.sql` | SQL analysis questions covering customers, products, discounts, shipping, subscriptions, and segments. |
| `customer_shopping_behavior.csv` | Dataset used throughout the project. |
| `Business Problem Document.pdf` | Business context, project scope, stakeholders, questions, and success criteria. |
| `Customer Shopping Behavior Analysis.pdf` | Detailed report covering preparation, analysis, charts, findings, limitations, and recommendations. |
| `Customer-Shopping-Behavior-Analysis.pptx` | Presentation summarising the analysis process and key findings. |
| `assets/` | Visuals used in the report and presentation. |

## Key observations from the analysis
- Total recorded spend is **$233,081**, with an average purchase amount of **$59.76**.
- **Clothing** contributes the largest recorded spend, followed by **Accessories**.
- Customers aged **55+** account for the highest total recorded spend because they are also the largest age group in the dataset.
- Average purchase amount is similar across shipping methods; delivery type alone does not show a strong spend difference in this sample.
- The file does not include transaction dates, product cost, inventory levels, promotion cost, or customer history over time. Findings should therefore be treated as descriptive.

## How to use the project
1. Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook or Google Colab.
2. Run the notebook cells to inspect the data and reproduce the analysis.
3. Import the dataset into a SQL database and run `customer_behavior_sql_queries.sql` to reproduce the SQL analysis.
4. Review the report and presentation for the project narrative and findings.

