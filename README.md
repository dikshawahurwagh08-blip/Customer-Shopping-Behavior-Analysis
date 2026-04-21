# 🛍️ Customer Shopping Behavior Analysis

# 📌 Overview :

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, product preferences, and customer segments. The workflow covers end-to-end data analytics, including data cleaning, exploratory analysis, SQL-based business queries, and dashboard visualization.

# 📊 Dataset :
 - Records: 3,900 transactions
 - Features: 18 columns Key Data Includes :
 - Customer demographics (age, gender, location, subscription status)
 - Purchase details (product, category, amount, season)
 - Behavioral insights (discount usage, purchase frequency, ratings)
 - Data Issue:Missing values in review_rating column (handled during cleaning)
   
# 🛠️ Tools & Technologies :
 - Python (Pandas, NumPy) – Data cleaning & EDA
 - PostgreSQL – Querying & business analysis
 - Power BI – Interactive dashboard
 - Gamma – Presentation (PPT) creation
   
# ⚙️ Project Workflow :
 - Data Loading & Exploration (Python)
 - Loaded dataset using Pandas
 - Performed initial inspection (info(), describe())
 - Identified missing values and inconsistencies
   
# Data Cleaning & Preparation :
 - Imputed missing review_rating using median by category
 - Standardized column names (snake_case)
 - Removed redundant columns
   
# Created new features :
 - age_group
 - purchase_frequency_days
   
# Database Integration :
 - Connected Python to PostgreSQL
 - Loaded cleaned dataset into database
 - SQL Analysis (PostgreSQL)

# Key business questions answered:
 - Revenue comparison by gender
 - High-spending discount users
 - Top-rated products
 - Shipping type impact on spending
 - Subscriber vs non-subscriber behavior
 - Customer segmentation (New, Returning, Loyal)
 - Top products by category
 - Revenue by age group
   
# Data Visualization (Power BI) :
 Built an interactive dashboard for insights Key visuals :
  - Revenue distribution
  - Customer segments
  - Product performance
  - Subscription analysis

# 📈 Dashboard : The Power BI dashboard highlights :
  - Customer purchasing trends
  - High-value customer segments
  - Best-performing products
  - Impact of discounts and subscriptions

# Dashboard :

<img width="1349" height="736" alt="image" src="https://github.com/user-attachments/assets/2870058d-962c-46df-b2e2-950bd5a78366" />

    
# 🔍 Key Insights :
 - Subscribers tend to generate higher overall revenue
 - Discount strategies influence purchasing behavior significantly
 - Certain products consistently receive higher ratings
 - Loyal customers contribute a major portion of revenue
 - Age groups show distinct spending patterns
   
💡 Business Recommendations :
  - Promote subscription plans to increase retention
  - Implement loyalty programs for repeat buyers
  - Optimize discount strategies for profitability
  - Focus marketing on high-performing products
  - Target high-revenue customer segments
    
# ✅ Conclusion :

This project demonstrates a complete data analytics pipeline by integrating Python, SQL, and business intelligence tools to generate actionable insights from raw data. It reflects strong capabilities in data cleaning, exploratory data analysis, database querying, and visualization. Beyond technical execution, the project emphasizes the ability to transform complex datasets into meaningful insights that support real-world business decisions. The use of structured SQL queries and interactive dashboards ensures that findings are both accurate and easily interpretable by stakeholders. Additionally, it highlights practical experience in handling real-world, imperfect data, building efficient and scalable workflows, and applying analytical thinking to solve business problems. Overall, the project showcases end-to-end ownership of the analytics process along with effective communication of insights through dashboards and presentations, making it highly relevant for data analyst and business intelligence roles.
