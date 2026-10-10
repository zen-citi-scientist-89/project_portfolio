# Olist Store Data Analytics Portfolio

A data analytics and business intelligence portfolio project focused on understanding customer behavior, order performance, seller activity, and marketplace trends using the Olist Store public dataset.

This repository demonstrates a structured approach to exploratory data analysis, data profiling, and business-oriented insight generation in the context of Brazilian e-commerce. It is designed to showcase practical analytics skills relevant to junior to mid-level data analyst or data scientist roles.

## Overview

The Olist dataset is a realistic e-commerce dataset released for public analysis. It contains transaction-level information across multiple dimensions, including orders, customers, sellers, products, payments, reviews, and product locations.

This project explores the marketplace from a business perspective, using data to answer questions related to:

- order completion and delivery performance
- payment behavior and purchasing patterns
- customer repeat purchase behavior
- category-level revenue and product performance
- seller reliability and review quality
- regional and geospatial differences in demand

## Why this project

This repository reflects a real-world analytics workflow that is commonly expected in business and data teams:

- understanding and validating raw data sources
- profiling schema and data quality issues
- designing analytical questions from business context
- using SQL and Python for exploratory analysis
- translating findings into actionable insights
- documenting work clearly for a portfolio or stakeholder review

## Dataset

The analysis is built on the Olist Store dataset, a public Brazilian e-commerce dataset containing historical marketplace data. The core tables include:

- customers
- orders
- order items
- products
- sellers
- payments
- order reviews
- geolocation

This dataset is ideal for hands-on analytics work because it combines operational, product, financial, and customer signals in one coherent business context.

## Repository structure

```text
project_portfolio/
├── data/
│   └── profiles/
├── notebooks/
│   ├── data_profliling.ipynb
│   └── explore_schema_data_w_duck_db.ipynb
├── .gitignore
├── README.md
└── LICENSE (if added in future)
```

## Notebooks

### 1. Data profiling

[notebooks/data_profliling.ipynb](notebooks/data_profliling.ipynb)

This notebook focuses on understanding the dataset structure, detecting missing values, identifying anomalies, and summarizing variable distributions. It is a foundational step for building trust in the data before deeper analysis.

### 2. Schema exploration with DuckDB

[notebooks/explore_schema_data_w_duck_db.ipynb](notebooks/explore_schema_data_w_duck_db.ipynb)

This notebook explores the underlying schema and relationships between tables. By querying the data with DuckDB, it helps uncover joins, data types, table structure, and opportunities for deeper analysis.

## Example business questions addressed

This project is designed to answer practical marketplace questions such as:

- Which product categories generate the highest revenue?
- How do order values differ across customer segments and cities?
- What payment methods are most commonly used?
- Are customer repeat purchases associated with satisfaction or delivery speed?
- Which sellers have the strongest product and delivery performance?
- Do late deliveries correlate with lower review scores?
- What region-specific patterns emerge in customer demand and order behavior?

## Tools and technologies

- Python
- Jupyter Notebook
- Pandas
- DuckDB
- SQL
- GitHub for version control and portfolio presentation

## Portfolio value

This project demonstrates the ability to:

- profile and assess a raw business dataset
- explore database structure and relationships
- produce insights from messy real-world e-commerce data
- communicate analysis in a clear, portfolio-ready format
- connect analytical work back to business questions and decision-making

## Suggested professional summary

> I built a data analytics project around the Olist Store dataset to explore how a Brazilian marketplace operates across customer, seller, payment, fulfillment, and product dimensions. The work demonstrates my ability to profile data, investigate business-relevant questions, and translate analytical findings into clear, actionable insights.

## Getting started

1. Clone this repository.
2. Ensure the Olist dataset is available in the `data/` folder or update paths as needed.
3. Open the notebooks in sequence to review the schema and profiling results.
4. Extend the analysis with custom SQL queries, visualizations, and business-focused storytelling.

## Project goals

- build a clean and reusable analytics workflow for the Olist dataset
- showcase data profiling and exploratory analysis skills
- apply e-commerce business reasoning to public data
- create a polished, presentable portfolio project for hiring or networking

## Notes

This project is intended for portfolio development and educational analysis. It is not focused on deployment or production systems, but rather on proving analytical thinking, technical fluency, and the ability to work with realistic business data.

## License

This project is intended for personal, educational, and portfolio use. Any commercial or larger-scale reuse should comply with the original Olist dataset licensing and usage terms.
