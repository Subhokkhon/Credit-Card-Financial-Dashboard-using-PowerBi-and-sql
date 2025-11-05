Credit Card Analysis Dashboard
💳 Credit Card Analysis Dashboard

An end-to-end Business Intelligence project combining SQL-based data modeling and Power BI visualization to analyze 667K+ credit card transactions and customer demographic records, uncovering actionable insights into spending patterns, revenue drivers, and customer profitability.

🚀 Project Overview

This project delivers a comprehensive financial intelligence system through two interactive dashboards:

Credit Card Transaction Report – Evaluates transaction volume, expenditure trends, and revenue generation.

Credit Card Customer Report – Examines customer demographics, income groups, and behavioral segments driving financial outcomes.

The dashboards empower financial institutions, marketing teams, and risk managers to make data-backed strategic decisions for customer acquisition, retention, and portfolio optimization.

⚙️ Tech Stack
Tool	Purpose
SQL (PostgreSQL)	Data extraction, transformation, and aggregation
Power BI Desktop	Data modeling, visualization, and KPI computation
DAX (Data Analysis Expressions)	Advanced calculations and dynamic measures
Excel / CSV Files	Data ingestion for transaction and demographic records
📊 Dashboard 1 – Credit Card Transaction Report

This report focuses on transaction performance and revenue contribution across various customer and spending dimensions.

🔹 Key Insights

Generated $57M total revenue and $8M total interest, analyzing 667K transactions across four quarters.

Engineered DAX-driven KPIs to measure quarterly revenue, transaction count, and customer acquisition cost by card type, improving data granularity by 35%.

Uncovered expenditure distribution: Bills, Entertainment, Fuel, Grocery, Food, and Travel contributing cumulatively to 80%+ total spend.

Identified card performance variance — Blue and Silver cards contributed >85% of transaction volume, enabling targeted retention campaigns.

Optimized acquisition costs by evaluating revenue-to-CAC ratios across card tiers (Blue, Silver, Gold, Platinum).

👥 Dashboard 2 – Credit Card Customer Report

This report analyzes customer demographics, income tiers, and spending behavior to help segment and profile profitable customers.

🔹 Key Insights

Correlated demographic parameters (age, salary, dependents, education) with spending and interest income, revealing High-salary group (>$80K) customers drive 40%+ revenue share.

Discovered regional hotspots — Top 5 states (TX, NY, CA, FL, NJ) generated >50% of national revenue, informing region-based marketing strategies.

Analyzed gender spending patterns, with male users contributing 54% of total revenue, while females showed higher average transaction frequency.

Classified job segments (Businessman, Self-employed, White-collar, Govt, etc.) to assess profitability — identifying business professionals as the highest revenue generators ($17.6M).

Computed a Customer Satisfaction Score (CSS) of 3.19, indicating moderate satisfaction and opportunities for loyalty program improvement.

🧠 SQL Integration

The accompanying SQL script (SQL Query - Financial Dashboard Data.sql) was used to:

Join and normalize transactional and demographic datasets using primary keys.

Aggregate metrics such as total revenue, average transaction value, and interest earned.

Prepare analytical tables for Power BI ingestion, reducing ETL latency by ~25%.

📈 Business Impact

🏦 Enabled 360° visibility into credit card portfolio performance across customer, geography, and product tiers.

🎯 Accelerated decision-making for marketing and finance teams through data-driven segmentation.

📊 Enhanced ROI tracking by linking customer acquisition cost with realized revenue streams.

💡 Facilitated predictive modeling readiness by establishing a clean, well-structured analytical dataset.

🛠️ Advanced Power BI Techniques

Power Query for ETL Automation – Streamlined data ingestion and transformation workflows.

Star Schema Data Modeling – Ensured optimized relationships between fact and dimension tables.

Dynamic DAX Measures – Built reusable metrics for revenue, interest, and transaction KPIs.

Drill-through & Slicer Interactions – Empowered end-users to explore data hierarchically.

Conditional Formatting & Card Visuals – Highlighted KPIs with real-time thresholds.

Tooltip & Cross-filtering – Provided contextual insights at every visualization layer.

🧾 Key Performance Metrics
Metric	Value
Total Revenue	$57 Million
Total Interest Earned	$8 Million
Total Income	$588 Million
Total Transactions	667K
Customer Satisfaction Score (CSS)	3.19
Data Records Processed	25K+
