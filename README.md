# 📊 Regional Sales Analysis

## 📝 Project Description
This project analyzes regional sales performance. It combines data transformation, exploratory analysis, and interactive dashboards to derive business insights. Built using Power BI, Python (Pandas, NumPy, Matplotlib), and Excel, this highlights my capability to extract value from complex datasets and make data-driven business recommendations.

## 🔍 Project Overview
The analysis explores sales trends across products, customers, and regions. We merge multiple datasets to derive insights into unit economics, regional demand, customer concentration, and revenue performance relative to budget targets. A Power BI dashboard was built to help decision-makers monitor and navigate this data effectively.

## 📂 Dataset Structure (Source: Kaggle)
Sales Orders: Order-level data with product and customer references.
Customers: Customer names and their index IDs.
Regions: Location details including population, income, and coordinates.
State Regions: Auxiliary mapping (less relevant to final analysis).
Products: Mapping of product descriptions.
2017 Budgets: Sales budget per product for 2017.

## 📊 Power BI Dashboard Preview

#### 🔸 State Performance
![State Performance](https://github.com/trinitarn/Regional_Sales_Analysis/blob/main/Screenshot%20State.png)
##### Top 5 states by total revenue:

California leads significantly with over $220 million in revenue.

Followed by Illinois, Florida, Texas, and New York — each generating over $100M.

These states are key markets and indicate regions where sales efforts are already yielding strong results.

##### Monthly Revenue Trend:
Peak revenue occurred in February, exceeding $125 millions
A noticeable decline starts from April onwards, suggesting a seasonal trend or operational gap.

#### 🔸 Product Performance
![Product Performance](https://github.com/trinitarn/Regional_Sales_Analysis/blob/main/Screenshot%20Product.png)

##### Top Revenue-Generating Products:
The bar chart shows that the top 5 products generate over $100M each, while the long tail of products sees significantly lower sales.
These top products are potential flagships — focus inventory and promotions accordingly.

##### Channel Breakdown:
Wholesale is the largest channel (~54%), followed by Distributor (31%) and Export (15%).
Export, while smallest, may offer higher margins per transaction and should be analyzed for strategic growth.

##### Elastic vs Inelastic Product Analysis:
Inelastic products (higher price & high demand): Strong performers like Product 11 and Product 13. These show strong unit economics — customers are willing to pay more and buy more.
Elastic/substitutable products: Lower price and lower volume — e.g., Product 1, Product 10 — possibly underperforming due to commoditization.

#### 🔸 Customer Analysis
![Customer Analysis](https://github.com/trinitarn/Regional_Sales_Analysis/blob/main/Screenshot%20Customer.png)
##### Customer Spend Distribution:
The scatterplot of Customer Index vs Revenue reveals a Pareto trend: a small portion of customers (likely <20%) drive a majority of revenue.
Many customers have low spend, indicating opportunities to either reactivate or refine targeting.

##### Profit Contribution by Customer:
Aibox Company is the top customer with over $4.9M in profit and $12.6M in revenue.
Other major contributors: Aimbo Corp, Actavis Company, and Accord Group.

##### RMF Table (Recency - Monetary - Frequency):
This table evaluates:
Sum of Profit
Sum of Total Revenue
Days Gap (Recency)
For example:
Aimbo Corp shows low recency (3.45 days) and high value, indicating strong loyalty.
Accudial Company has higher recency (4.13) with solid returns, possibly needing more engagement.

### Recommendation:
1. Continue to invest in high-performing inelastic products.
Reposition or market substitutable products more aggressively.
2. Marketing Focus by Customer Type:
Using scatterplots and customer-product matrices, we identified:
Which customers consistently purchase inelastic products (high loyalty, less price sensitivity).
Which customers lean towards substitutable goods — ideal targets for promotions or pricing strategies.
3. Recommendations: Investigate Q2-Q3 dip and align campaigns with high-performance months.
4. Use RMF to segment: reward loyal customers, re-engage at-risk ones, and promote upselling to profitable but infrequent buyers.

## 🔧 Tools & Skills Demonstrated
Data Cleaning & Wrangling: Used Python (Pandas) to merge the innitial [dataset](https://github.com/trinitarn/Regional_Sales_Analysis/blob/main/Regional%20Sales%20Dataset.xlsx), clean keys, map references. You can see the code [here](https://github.com/trinitarn/Regional_Sales_Analysis/blob/main/Regional%20Sales%20Analysis.ipynb). 
Business Intelligence: Designed KPI cards, dynamic filters, and drill-down visuals in Power BI.
Visualization: Developed clear, actionable insights with advanced DAX and Power BI features. You can see the final dashboard [here](https://github.com/trinitarn/Regional_Sales_Analysis/blob/main/The%20Dashboard.pbix).
Communication: Translated raw numbers into executive-ready insights and strategies.
Excel: Performed cross-validation, initial data profiling, and pivot summaries.
