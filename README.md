Customer Shopping Behaviour Analysis

Overview: An end-to-end data analytics project analyzing 3,900 customer purchases to understand spending patterns, product preferences, customer segments, discounts, and subscription behavior. 

Tools:

* Python (Pandas, NumPy)
* Jupyter Notebook
* MySQL & SQL
* Power BI

Workflow:

Data Loading → EDA → Data Cleaning → Feature Engineering → MySQL → SQL Analysis → Power BI Dashboard

Data Cleaning:

* Handled missing Review Ratings
* Standardized column names
* Removed redundant columns
* Created `age_group` and `purchase_frequency_days` features 

SQL Analysis:

Analyzed:

* Revenue by gender and age group
* Top-rated and best-selling products
* Discount usage
* Subscription behavior
* Customer segmentation
* Shipping preferences 

Dashboard:

Interactive Power BI dashboard presenting key customer and business insights. 

Key Recommendations:

* Increase subscription adoption
* Strengthen customer loyalty programs
* Optimize discount strategies
* Promote top-performing products
* Target high-revenue customer groups 

Project Structure:

├── data/
├── notebooks/
├── sql/
├── dashboard/
├── images/
└── README.md

How to Run

1. Run the Jupyter Notebook for cleaning and EDA.
2. Load the cleaned data into MySQL.
3. Execute the SQL queries.
4. Open the `.pbix` file in Power BI and refresh the data.
