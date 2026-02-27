📊 E-commerce Growth & User Value Analysis (Olist)

📌 Project Background
This project analyzes a Brazilian e-commerce dataset (Olist) to:
Build a structured order-level fact table
Construct core business KPI system
Analyze user retention using Cohort methodology
Segment users via RFM model
Provide growth-oriented business insights

🏗 Data Modeling
Integrated multi-table order, payment, and customer datasets
Constructed an order-level fact table (99,441 orders)
Standardized GMV, time dimensions, and user identifiers
Saved processed dataset as intermediate layer (parquet)

📈 KPI & Growth Analysis
Built monthly metrics including:
GMV
Order count
AOV (Average Order Value)
Repeat purchase rate
Key Finding:
Over 75% of users placed only 1 order
Growth relies heavily on new user acquisition

🔄 Cohort Retention Analysis
Constructed retention matrix using:
Cohort month (first purchase month)
Cohort index (months since first purchase)
Key Insights:
Average month-1 retention ≈ 0.5%
Retention curve shows long-tail return behavior (6–12 months)
Retention structure relatively stable across cohorts

👥 RFM User Segmentation
Calculated:
Recency
Frequency
Monetary
Revenue Concentration:
Top 20% users contribute 53.5% of total GMV
User Structure:
High-value users: 6.9%
Low-value users: 16%
Majority are single-purchase users

🎯 Business Recommendations
Develop retention strategies for first-time buyers (coupon targeting, re-engagement campaigns)
Enhance high-value user loyalty via membership or personalization
Focus on lifecycle marketing to convert one-time users to repeat customers

🛠 Tech Stack
Python
Pandas
Matplotlib
Parquet
GitHub for version control

🚀 How to Run
Place raw data into data/raw/
Run notebooks sequentially:
01_data_check_and_schema
02_kpi_and_growth_analysis
03_cohort_retention_analysis
04_rfm_user_segmentation

🧠 Analytical Focus
This project emphasizes:
Structured data modeling
Business metric system design
Lifecycle analysis
User value concentration analysis
Data-driven strategy formulation