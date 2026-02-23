# Ecom_Sales_Data_Analysis_using_Python
This Python Data Analysis Gives Insights about Revenue and Orders over a period of time along with High Performing products and Return Products insights and detailed Data Driven Recommendations to Stake Holders 

#🛍️ Retail E-Commerce Data Analytics Project
📊 Driving Sustainable Growth Through Data-Driven Insights
📌 1. Project Overview
This project focuses on analyzing transactional data from an E-Commerce Retail Company facing operational and customer satisfaction challenges
The goal of this analysis is to:

Improve financial performance

Optimize inventory management

Reduce cancellations & returns

Enhance fulfillment efficiency

Support data-driven strategic decisions

The analysis was performed entirely using Python for end-to-end retail data analytics workflow.


🎯 2. **Business Problem Statement**

The e-commerce company is experiencing:

Increasing order cancellations

High return rates

Shipping delays

Inventory imbalance (stockouts & overstocking)

Inconsistent revenue growth

The objective is to leverage data analytics to identify operational inefficiencies and recommend improvement strategies.
🛠 3. **Tools & Technologies Used**
🔹 Programming Language

Python 3.x

🔹 Libraries Used

| Purpose                      | Library    |
| ---------------------------- | ---------- |
| Data Cleaning & Manipulation | Pandas     |
| Numerical Computation        | NumPy      |
| Data Visualization           | Matplotlib |
| Statistical Visualization    | Seaborn    |
| Date Handling                | datetime   |

📂 4.** Dataset Description**

The dataset contains transactional-level order data including:

Order ID

Order Date

Order Status (Shipped, Cancelled, Delivered, etc.)

Fulfillment Type (Amazon / Merchant)

Sales Channel

Product Category

SKU

Quantity

Amount

Shipping Location

B2B Flag

Promotion IDs

This allows multi-dimensional retail analysis across revenue, customer behavior, logistics, and product performance

🧹 5. **Data Cleaning & Preprocessing (Pandas)**
Key steps performed:

✅ **Handling Missing Values**

Replaced null values in Amount column with median value

Removed invalid or duplicate records

✅ **Date Standardization**

Converted date column to datetime format

Extracted:

Month

Year

Day of Week

Week Number

✅ **Feature Engineering**
Created new analytical features:

Cancellation Flag

Return Flag

Order Value Category

Weekend vs Weekday Indicator

Delivery Time (where applicable)

📊 6. **Exploratory Data Analysis (EDA)**

Using Matplotlib & Seaborn, the following analyses were performed:

🔹** Financial Performance Analysis**

Revenue trend over time

Monthly growth rate

Average Order Value (AOV)

Top revenue-generating categories

📈 **Insight:**

Revenue showed seasonality spikes.

A small number of categories contribute majority of sales (Pareto principle).
🔹 **Customer Behavior Analysis**

B2B vs B2C revenue contribution

Cancellation trends

Retention indicators

Geographic sales distribution

📈 **Insight:**

B2B customers have higher AOV.

Certain regions show high cancellation rates.

🔹 **Logistics & Fulfillment Analysis**

Comparison between Amazon vs Merchant fulfillment

Cancellation rate by fulfillment type

Shipping performance trends

📈 **Insight:**

Merchant-fulfilled orders have relatively higher cancellation rate.

Delays strongly correlate with cancellation spikes.

🔹 **Product & Inventory Analysis**

High-demand categories

Average quantity ordered

Frequently returned SKUs

Slow-moving vs fast-moving items

📈 **Insight:**

Few SKUs drive high returns.

Inventory imbalance observed in specific categories.

🔹** Customer Satisfaction & Returns**

Return rate by category

Cancellation reasons (inferred)

Impact of promotions on returns

📈 **Insight:**

Certain promotional campaigns correlate with higher returns.

Quality issues suspected in specific categories.

⚠️ 7. **Key Challenges Faced**

Missing and inconsistent data in transaction amount.

Mixed date formats requiring standardization.

High cardinality categorical variables (SKU, location).

Separating true returns from cancellations.

These were addressed using robust Pandas transformation and careful data validation.

📈 8. **Key Business Insights**

20% of products generate ~80% of revenue.

Merchant fulfillment has higher operational inefficiencies.

Specific states contribute disproportionately to cancellations.

B2B segment has strong revenue potential.

Return-heavy categories require quality review.

🚀 9. **Business Recommendations**
🔹 **Inventory Optimization**

Implement ABC classification

Apply dynamic safety stock for high-demand SKUs

Reduce stock for slow-moving categories

🔹 **Fulfillment Improvement**

Improve merchant shipping SLA tracking

Monitor cancellation trigger points

Optimize last-mile delivery partners

🔹 **Customer Strategy**

Develop retention program for B2B customers

Introduce targeted promotions based on buying behavior

Improve quality control in high-return categories

🔹 **Financial Strategy**

Focus marketing on high-margin SKUs

Optimize pricing for high elasticity products

Monitor AOV trends by segment

📊 10. **Visualizations Used**
Revenue Trend Line Charts

Category-wise Bar Charts

Heatmaps for cancellation distribution

Distribution plots for order values

Boxplots for fulfillment comparison

All visualizations were built using:

Matplotlib

Seaborn

🧠 11. **Analytical Skills Demonstrated**
Retail KPI analysis

Customer segmentation

Operational efficiency analysis

Inventory demand insights

Revenue optimization modeling

Data cleaning at scale

Feature engineering for business insights

🎯 12. **Conclusion**

This project demonstrates how Python-based retail analytics can transform raw transactional data into actionable strategic insights.

By combining:

Data cleaning (Pandas)

Statistical analysis

Visualization (Matplotlib & Seaborn)

Business reasoning

We provided data-driven recommendations to support sustainable e-commerce growth
