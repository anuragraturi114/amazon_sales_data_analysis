## Amazon Sales Data Analysis & Visualization

### Project Overview

This project focuses on extracting, transforming, and analyzing Amazon sales data to uncover meaningful trends and business insights. With increasing competition and the need for optimized distribution and decision-making, sales management analytics has become crucial in modern enterprises. This project aims to:
- Understand sales trends across time.
- Calculate key performance metrics.
- Identify relationships between variables impacting sales and profit.
- Provide actionable business intelligence through visual dashboards.

### Dataset
- Contains transactional-level data of Amazon sales including:
- order Date, Product Category, Region
-	Sales, Profit, Quantity Sold
-	Discount, Shipping Cost, Customer Segment

## Tech Stack
-	Python (Pandas, NumPy, Matplotlib, Seaborn)
-	Tableau for dashboards
-	Excel for preliminary exploration
-	Jupyter Notebook for scripting & EDA

### ETL Process

 ####  Extract:
- Imported the CSV using pandas.
- checked for missing values, data types, and inconsistencies.

  #### Transform:
-	Converted date formats and derived:
-	Year, Month, Year-Month
-	Handled missing/null values
-	Created custom fields for:
-	Profit Margin, Sales Category
-	Discount Buckets, etc.

  #### Load:
-	Final cleaned dataset used for:
-	Python-based EDA
-	Tableau dashboards

### Sales Trend Analysis
- Monthly & Yearly Trends show seasonal spikes around Q4.
- Sales grew steadily YoY with minor dips during off-seasons.
- Best months: November & December due to holiday season surge.

### Profitability Insights
- Categories like Electronics and Home Office yielded high margins.
- High shipping costs and discounts above 20% often led to reduced profitability.

### Key Relationships Identified
- Sales ↑ when Discount is 10–15%, but too much discount → ↓ Profit
- Shipping Cost has a significant negative impact on Net Profit
- Customer Segments: Corporate buyers provided more consistent profit than consumers.



