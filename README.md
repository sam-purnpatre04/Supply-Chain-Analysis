Supply Chain & Delivery Performance Analysis
1. Project Overview

This project focuses on analyzing supply chain and delivery performance to understand how efficiently orders are being delivered and where operational problems are affecting revenue, customer satisfaction, and returns.

The main purpose of this project was not only to analyze the data but to understand the business story behind the data.

I wanted to answer questions such as:

Are orders being delivered on time?
Which regions and product categories generate the most revenue?
Which suppliers have higher delivery delays?
Which warehouses may have delivery bottlenecks?
Which shipping modes perform better?
Are delayed orders more likely to be returned?
Does delivery performance affect customer ratings?
Where can the business improve its supply-chain operations?

The project helped me understand how a Data Analyst can take raw operational data, clean it, analyze it, identify patterns, and convert those patterns into business recommendations.

2. Business Problem

In a supply-chain business, generating revenue is important, but delivering the order on time is equally important.

A company may have strong revenue and a large number of orders, but if customers are receiving their orders late, it can lead to:

Customer dissatisfaction
Product returns
Lower customer ratings
Poor supplier performance
Increased logistics costs
Inefficient warehouse operations
Loss of customer trust

The business therefore needs to understand where delivery problems are happening and how they are connected to customer and business outcomes.

Core Business Question

Are we delivering orders on time, and where are the bottlenecks in our supply chain that may be affecting revenue and customer trust?

3. Project Objective

The main objective of this project was to analyze order-level supply-chain data and evaluate:

Revenue Performance
Total revenue
Revenue by region
Revenue by product category
Revenue by product
Delivery Performance
On-Time, Delayed, and Early orders
Average delivery delay
Delivery performance by supplier
Delivery performance by warehouse
Delivery performance by shipping mode
Customer Experience
Customer ratings
Relationship between delivery performance and ratings
Return behavior
Business Performance
Identify potential supply-chain bottlenecks
Identify areas requiring operational improvement
Provide data-driven recommendations
4. Dataset

The dataset contains order-level supply-chain information where each row represents an order.

The dataset contains approximately 3,000 orders and includes information about customers, products, suppliers, warehouses, shipping, revenue, delivery performance, returns, and customer ratings.

Important Columns

Order Information

Order ID
Order Date
Customer ID

Customer Information

Customer Region
Customer City

Product Information

Product Category
Product Name
Quantity
Unit Price
Total Revenue

Supplier & Logistics Information

Supplier Name
Shipping Mode
Warehouse Location

Delivery Information

Expected Delivery Days
Actual Delivery Days
Delay Days
Delivery Status

Customer Experience

Return Status
Customer Rating

This structure allowed me to analyze the supply chain from multiple business perspectives instead of looking at only revenue or delivery performance.

5. Approach

I followed an end-to-end Data Analyst workflow.

Overall Process

Raw Data → Data Cleaning → Exploratory Data Analysis → SQL Analysis → Python Analysis → Visualization → Power BI Dashboard → Business Insights → Recommendations

I divided the project into different stages so that I could first make the data reliable and then use it for analysis.

6. Data Cleaning

Before starting the analysis, I first inspected the dataset to understand its structure and quality.

I checked:

Number of rows and columns
Data types
Missing values
Duplicate records
Numerical statistics
Date formats
Categorical values

I also made sure that important numerical columns such as revenue, quantity, delivery days, and ratings were stored correctly.

The Order Date column was checked and converted into the appropriate date format so that I could perform time-based analysis.

Duplicate records and missing values were also checked and handled appropriately.

Why Data Cleaning Was Important

If the data contains duplicate orders or incorrect data types, the final analysis can become misleading.

For example, duplicate orders could artificially increase:

Total revenue
Number of orders
Quantity sold
Delivery counts

Therefore, I treated data cleaning as an important first step before performing any business analysis.

7. Exploratory Data Analysis

After cleaning the data, I started exploring the dataset to understand the overall business performance.

I first looked at:

Total Revenue
Total Orders
Total Quantity
Average Customer Rating
Average Delivery Delay

After understanding the overall numbers, I moved towards more detailed business questions.

8. Revenue Analysis

The first major area I analyzed was revenue.

I wanted to understand:

Where is the revenue coming from?

I analyzed revenue across:

Customer regions
Product categories
Products
Suppliers

This helped identify the major revenue contributors.

For example, if one region or product category generates significantly more revenue than others, that area becomes particularly important from a business perspective.

A supply-chain disruption in a high-revenue region or category could have a larger financial impact on the business.

9. Delivery Performance Analysis

After revenue analysis, I moved towards the logistics side of the business.

The main question was:

Are orders actually reaching customers on time?

I analyzed the Delivery Status to understand the distribution of:

On-Time orders
Delayed orders
Early orders

I also calculated the percentage distribution to make the comparison easier.

This helped me understand the overall delivery efficiency of the business.

10. Supplier Performance Analysis

Next, I wanted to understand whether delivery delays were concentrated around specific suppliers.

I compared suppliers based on their average delivery delay.

This allowed me to identify suppliers that showed relatively higher delivery delays.

I did not directly conclude that a supplier was “bad” based only on this analysis.

Instead, I treated high average delay as a potential area for further investigation.

The business could then review supplier performance, delivery agreements, transportation arrangements, or service-level expectations.

11. Warehouse Performance Analysis

I also analyzed delivery delays based on warehouse locations.

The objective was to understand whether some warehouses were experiencing higher delivery delays than others.

If a particular warehouse consistently shows higher delays, it can indicate a possible operational bottleneck.

The business could then investigate:

Inventory availability
Warehouse processing time
Order handling
Dispatch operations
Transportation connectivity
12. Shipping Mode Analysis

Another important part of the project was comparing different shipping modes.

The dataset contains shipping methods such as:

Air
Road
Rail
Sea

I compared these modes based on delivery performance.

This helped me understand which transportation methods had better or weaker delivery consistency.

This analysis can help the business evaluate whether transportation planning or shipping-mode allocation needs improvement.

13. Delivery and Return Analysis

One of the most important analyses in this project was understanding the relationship between delivery performance and returns.

I wanted to answer:

Are delayed orders more likely to be returned?

I compared:

Delivery Status → Return Status

This allowed me to see the number and percentage of returned orders among On-Time, Delayed, and Early deliveries.

This analysis is important because delivery problems may affect the customer's overall experience.

If delayed orders show a higher return rate, it can indicate that improving delivery reliability may help reduce customer dissatisfaction and returns.

I treated this as an association rather than direct causation, because the dataset alone cannot prove that delays directly cause returns.

14. Delivery and Customer Satisfaction Analysis

I also wanted to understand whether delivery performance was related to customer satisfaction.

For this, I compared:

Delivery Status → Customer Rating

I also analyzed customer ratings against the number of delay days.

The purpose was to determine whether customers experiencing greater delivery delays tend to provide lower ratings.

This helped connect the operational side of the supply chain with the customer-experience side.

15. Monthly Revenue Analysis

I also analyzed revenue over time using the Order Date.

This allowed me to understand:

Monthly revenue trends
High-performing periods
Changes in revenue over time

Time-based analysis is useful because it helps the business understand whether revenue is stable or changing across different periods.

16. Tools Used
Python

I used Python as the main environment for data analysis.

Pandas

I used Pandas for:

Data cleaning
Grouping
Aggregation
Sorting
Filtering
Cross-tabulation
Date-based analysis
NumPy

I used NumPy for numerical operations and supporting data-analysis tasks.

Matplotlib

I used Matplotlib to create visualizations and understand patterns in the data.

SQL

I used SQL to perform structured analysis such as:

Aggregations
Grouping
Filtering
Ranking
Delivery and supplier analysis
Revenue analysis
Excel

I used Excel for:

Initial data handling
Data validation
Pivot-table analysis
Summary analysis
Supporting visualizations
Power BI

I used Power BI to create an interactive dashboard that presents the final business insights.

17. Power BI Dashboard

After completing the analysis, I created a Power BI dashboard to communicate the most important findings.

The dashboard contains KPI cards for:

Total Revenue
Total Orders
On-Time Delivery %
Average Delay
Average Customer Rating

It also contains visualizations for:

Revenue by Region
Revenue by Product Category
Delivery Status
Average Delivery Delay by Supplier
Delivery Performance by Shipping Mode
Returns by Delivery Status

The purpose of the dashboard was to allow a business user or decision-maker to understand the overall supply-chain performance quickly without going through the raw dataset.

18. Key Business Insights

The analysis provided several important insights.

Revenue

The company generated approximately ₹74.17 million in revenue across around 3,000 orders.

This helped establish the overall scale of the business.

Delivery

The On-Time Delivery rate was approximately 62.60%.

This means there is a significant opportunity to improve delivery consistency.

The remaining orders include both delayed and early deliveries, so the issue is not only late delivery but also deviation from the expected delivery schedule.

Supplier Performance

Different suppliers showed different levels of delivery delay.

Suppliers with consistently higher average delays can be considered potential areas for operational investigation.

Shipping Performance

Different shipping modes showed differences in delivery performance.

This can help the business evaluate transportation strategies and identify modes that may require further investigation.

Returns

The analysis of Delivery Status against Return Status helped investigate whether delayed orders were associated with higher return rates.

Customer Satisfaction

Comparing delivery performance with customer ratings helped investigate whether delivery issues were reflected in customer satisfaction.

19. Problems I Faced During the Project

I faced several challenges while working on the project.

Problem 1 — Understanding the Dataset

Initially, there were many columns and it was difficult to understand which columns were actually important for business analysis.

How I Solved It

I divided the columns into business categories such as:

Customer → Product → Revenue → Supplier → Logistics → Delivery → Customer Experience

This made the dataset easier to understand.

Problem 2 — Deciding What to Analyze

Another challenge was that there were many possible combinations of columns.

I initially focused too much on simply creating charts.

How I Solved It

I changed my approach and started asking business questions first.

Instead of asking:

“What chart can I make?”

I started asking:

“What business problem can this data help me answer?”

This helped me create more meaningful analysis.

Problem 3 — Understanding Relationships Between Variables

It was not enough to calculate revenue or delivery counts.

I wanted to understand how different parts of the supply chain were connected.

How I Solved It

I compared:

Delivery Status with Return Status
Delivery Status with Customer Rating
Supplier with Delay
Warehouse with Delay
Shipping Mode with Delivery Status

This helped me move from simple descriptive analysis toward more meaningful business analysis.

Problem 4 — Choosing the Right Visualization

I initially had many possible charts and it was difficult to decide what should go into the final dashboard.

How I Solved It

I selected visualizations based on the business question.

For example:

Revenue comparison → Bar/Column Chart
Delivery distribution → Donut Chart
Supplier delay → Bar Chart
Shipping performance → Stacked Column Chart
Returns vs Delivery → Comparison Chart

I avoided putting unnecessary charts into the final dashboard.

20. Business Recommendations

Based on the analysis, I would recommend the following:

1. Improve On-Time Delivery

Since the on-time delivery rate is only around 62.60%, the company should focus on improving delivery reliability.

2. Investigate High-Delay Suppliers

Suppliers with consistently higher average delays should be reviewed for possible operational or service-level issues.

3. Review Warehouse Bottlenecks

Warehouses with higher average delays should be investigated to understand whether inventory handling, processing, or dispatch operations are contributing to delays.

4. Optimize Shipping Modes

Shipping modes with weaker delivery performance should be reviewed to determine whether alternative transportation methods or better route planning can improve delivery consistency.

5. Monitor Delayed Orders

Delayed orders should be closely monitored because delivery problems may be associated with higher return rates and lower customer satisfaction.

6. Protect High-Revenue Areas

High-revenue regions and product categories should receive strong supply-chain support because disruptions in these areas can have a greater financial impact.

21. Overall Impact

The main value of this project was that I moved from raw order-level data to business recommendations.

Instead of only calculating revenue or creating charts, I tried to understand:

What is happening?

Then:

Why might it be happening?

And finally:

What can the business do about it?

The project helped me understand how different areas of supply-chain performance are connected.

For example:

Delivery Performance → Customer Experience → Returns → Business Impact

This helped me develop a more business-oriented approach to data analysis.

22. Key Learnings

This project helped me strengthen my skills in:

Data cleaning
Exploratory Data Analysis
Pandas
NumPy
SQL
Excel
Data visualization
Power BI
Dashboard design
Business storytelling

More importantly, I learned that a Data Analyst should not stop at finding numbers.

The important part is to understand what those numbers mean for the business and communicate the findings clearly.

23. Final Project Story

The complete story of my project can be summarized as:

“I started with raw supply-chain order data and first cleaned and validated it. I then analyzed revenue to understand the major business drivers. After that, I focused on delivery performance to identify delays and potential bottlenecks across suppliers, warehouses, and shipping modes. I then connected delivery performance with returns and customer ratings to understand the possible customer impact. Finally, I used Power BI to present the most important findings through an interactive dashboard and provided recommendations focused on improving delivery reliability, monitoring suppliers and warehouses, optimizing shipping methods, and protecting customer satisfaction.”

24. Interview Presentation Flow

For my final mock interview, I will present the project in this order:

Business Problem

↓

Dataset

↓

Data Cleaning

↓

EDA

↓

Revenue Analysis

↓

Delivery Analysis

↓

Supplier & Warehouse Analysis

↓

Shipping Mode Analysis

↓

Returns & Customer Satisfaction

↓

Power BI Dashboard

↓

Key Insights

↓

Business Recommendations

↓

Challenges & Solutions

↓

Learning

This structure allows me to explain not just what I built, but also why I built it, what I discovered, and how the analysis can help the business.
