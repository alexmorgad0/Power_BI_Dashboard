# Overview

Welcome to my Power BI Dashboard Project.
The goal of this project was to explore and understand sales patterns across products, customers, and regions using interactive Power BI dashboards.

The dataset comes from a retail sales dataset ([Superstore](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)), containing detailed information on orders, customers, products, and regions.

This dashboard helps answer key business questions such as:
1.What are the overall sales trends by year and month?
2.Which product categories and subcategories drive the most sales?
3.Who are the most valuable customers?
4.How does customer churn evolve over time?
5.Which states and cities generate the highest revenue?

# Tools I Used

For my deep dive into the data analyst job market, I harnessed the power of several key tools:

- **Power BI:** for dashboard creation, modeling, and interactivity
- **DAX:** for KPIs and custom measures (e.g., churn rate, buckets, averages)
- **Data Modeling:** Creating helper columns, tables and linking them
- **Power Query:** for initial data cleaning and transformations

# Data Preparation & Modeling

Steps I followed:
1.Imported the sales dataset into Power BI.
2.Cleaned and standardized fields (e.g., dates, sales values).
3.Created calculated columns like Customer Value Buckets (Low <1K, Medium 1K–5K, High >5K).
4.Created measures like Total Sales, Total Orders, Total Customers, Avg Order Value, Churn Rate %
5.Built relationships between helper table and main one

# The Analysis 
## Sales Overview
- **KPIs:** Total Sales ($2M), Total Orders (4,922), Customers (793).
- **Trends:** Sales grew steadily between 2015–2018, with seasonality peaks in November & December.
- **Category Split:** Technology leads with $827K (36.6%), followed by Furniture ($729K, 32.2%) and Office Supplies ($705K, 31.2%).


## Product Insights
- **Top Categories:** Technology dominates, driven by Phones and Machines.
- **Top Sub-Categories:** Phones, Chairs, and Storage lead revenue.
- **Top 10 Products:** Canon Copier is #1 with $61K sales.
- **Treemap:** Shows clear revenue concentration in a few sub-categories within each category.

## Customer Insights
- **Segments:** Consumer = 52% of customers, Corporate = 30%, Home Office = 18%.
- **Churn Rate:** Dropped from 27% (2016) to 13% (2018).
- **Customer Value Buckets:** Medium (1K–5K) accounts for most customers, but High (>5K) drives disproportionate revenue.
- **Top Customers:** Sean Miller leads with $25K sales.

## Region Insights
- **Top States:** California ($457K) and New York ($309K) dominate.
- **Growth Trends:** California and New York shows consistent year-on-year growth while Texas is falling behind.

# Challenges I Faced
- Balancing dashboard aesthetics vs readability (KPIs, slicers, and charts).
- Making navigation intuitive with buttons and consistent color themes.
  
# Conclusion & Insights 
This dashboard provides a full overview of sales dynamics across time, products, customers, and regions.

Key Findings:
- Sales show a strong upward trend with seasonal peaks at year-end.
- Customer churn improvements suggest stronger customer loyalty over time.
- Medium-value customers form the majority, but high-value customers drive the largest share of revenue.
- California and New York are the key regions to focus marketing efforts.
- Some big clients have churned so marketing should also focus to bring them back.
