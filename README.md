# AdventureWorks_Dashboard

## Business Objective:
To monitor and optimize sales performance and return behavior across products, customers, and categories, in order to support strategic decisions on inventory, pricing, customer segmentation, and product development.

## Dashboard Summary
This dashboard was built to address key performance challenges faced by the business — namely, controlling return rates, optimizing product profitability, and understanding customer value. By tying sales and returns data together, the dashboard equips decision-makers with insights to improve pricing strategies, manage underperforming SKUs, and drive targeted customer outreach, ultimately contributing to revenue growth and cost containment.

## Tech Stack & Key Features Used
### Tech Stack

**Power BI Desktop**
1. Power Query – Data extraction, transformation, and cleansing
2. DAX (Data Analysis Expressions) – Complex calculations and KPI logic
3. Data Modeling – Star schema design and relationship management
4. Data Visualization – Interactive charts, slicers, and cards for storytelling

### Advanced Features Implemented
1. Calculated Columns & Measures – Custom KPIs like revenue per customer, return % by product, monthly targets, etc.
2. Numeric & Field Parameters – Dynamic switching between metrics (e.g., revenue vs orders) and dimension slicing (e.g., product categories)
3. Bookmarks & Custom Navigation Buttons – Seamless multi-page navigation and storytelling experience
4. Custom Tooltips – Contextual, hover-based drilldowns without page transitions

### AI-Powered Insights
1. Anomaly Detection – Automatic identification of revenue/order spikes or dips across time
2. Smart Narratives – Auto-generated textual summaries of visual insights
3. Key Influencers – AI-driven analysis of what factors impact return rates or order volumes
4. Q&A Visuals – Natural language question box for real-time data exploration
5. Decomposition Tree – Drilldown into root causes of sales and return behaviors


## Page-Level Business Purpose & Questions

### Page 1: Executive Summary

**Business Purpose:** Provide leadership with a top-level view of business health and identify red flags early (e.g., high return rates, monthly revenue dips).

![Executive Summary](https://github.com/dbshreyas/AdventureWorks_Dashboard_Power_BI/blob/main/Dashboard%20Snapshots/1%20Executive%20Summary.png)

**Key Questions Answered:**

1. What’s the current revenue, customer count, and order volume?
2. What are the key trends in revenue over time?
3. Which categories are performing well (or poorly)?
4. What are the top 10 selling products and their return percentages?
5. What’s the most returned product type — and is there a return issue?


### Page 2: Product Analysis

**Business Purpose:** Enable product managers to evaluate product-level profitability and simulate pricing strategies.

![Product Analysis](https://github.com/dbshreyas/AdventureWorks_Dashboard_Power_BI/blob/main/Dashboard%20Snapshots/2%20Product%20Details.png)

**Key Questions Answered:**

1. Is this product hitting revenue, order, and profit targets?
2. How have orders and profit trended historically?
3. What is the impact of a price change (via simulation)?
4. Is this product worth keeping, scaling, or optimizing?

### Page 3: Customer Analysis

**Business Purpose:** Help marketing and sales teams identify high-value customers and potential customer segments for targeted campaigns.

![Customer Analysis](https://github.com/dbshreyas/AdventureWorks_Dashboard_Power_BI/blob/main/Dashboard%20Snapshots/3%20Customer%20Details.png)

**Key Questions Answered:**

1. Who are our top customers by revenue?
2. What is the revenue per customer and how is it changing?
3. Which income levels and occupations bring in the most orders?
4. Is the customer base growing over time?


## Overall Business Objective Deepdive
**High Return Rates on Key Products**

1. The business may be seeing profitability leakage from excessive returns (e.g., helmets and shorts).

2. This dashboard highlights those products and can guide interventions (e.g., QC checks, product redesign, customer education).

**Plateauing Revenue / Orders**

1. Revenue and order growth may be flattening, as shown in the monthly revenue dip.

2. This may prompt the company to explore category-level or product-level actions.

**Product Portfolio Optimization**

1. Certain SKUs may have high orders but low margins or high returns. Decisions need to be made on discontinuation, reengineering, or bundling.

**Customer Segmentation for Targeting**

1. Understanding which customer segments are driving value allows better campaign design, retention efforts, or upselling strategies.

**Price Sensitivity Analysis**

1. The product simulation tool enables controlled pricing strategy testing without deploying changes across the platform.
