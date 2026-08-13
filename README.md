# 📦 Supply Chain & Delivery Performance Analysis

## 📌 Project Overview

The **Supply Chain & Delivery Performance Analysis** project focuses on analyzing order, delivery, revenue, supplier, shipping, and customer satisfaction data to identify operational bottlenecks and understand how delivery performance affects business outcomes.

The project analyzes **3,000+ orders generating ₹74.17M in revenue** and presents the findings through an interactive Power BI dashboard.

---

## 🎯 Business Problem

A supply chain company receives thousands of orders across different regions, suppliers, products, warehouses, and shipping modes.

However, raw order data does not immediately show **where operational problems are occurring**.

The business needs to understand:

- Delivery delays and overall delivery performance
- Revenue contribution by product category and region
- Supplier and shipping mode performance
- Customer returns
- Customer satisfaction
- Areas where logistics operations can be improved

### Problem Statement

> **Analyze supply chain and delivery data to identify delivery bottlenecks, revenue drivers, supplier performance issues, and relationships between delivery performance and customer outcomes, and present the findings through an interactive Power BI dashboard.**

---

## 🎯 Project Objectives

- Analyze overall delivery performance.
- Identify on-time, delayed, and early deliveries.
- Identify major revenue-generating product categories.
- Compare revenue across different regions.
- Evaluate supplier and shipping mode performance.
- Analyze return patterns based on delivery performance.
- Understand customer satisfaction using customer ratings.
- Provide actionable recommendations to improve supply chain operations.

---

## 🛠️ Tools & Technologies

### Python
- Pandas
- NumPy
- Matplotlib
- Data Cleaning
- Exploratory Data Analysis (EDA)

### Business Intelligence
- Power BI
- DAX
- KPI Cards
- Interactive Filters
- Data Visualization

### Database
- SQL
- MySQL

---

## 📊 Dataset

The dataset contains **3,000+ order records** covering different aspects of the supply chain.

### Major Data Fields

- **Order:** Order ID, Order Date, Customer ID
- **Customer:** Region, City, Customer Rating
- **Product:** Product Category, Product Name
- **Supplier:** Supplier Name
- **Logistics:** Shipping Mode, Warehouse Location
- **Revenue:** Quantity, Unit Price, Total Revenue
- **Delivery:** Expected Delivery Days, Actual Delivery Days, Delay Days, Delivery Status
- **Returns:** Return Status

---

## 🔄 Project Approach

The project followed an end-to-end data analysis process:

**Raw Data → Data Cleaning → EDA → Business Analysis → KPI Creation → Power BI Dashboard → Insights → Recommendations**

### Data Cleaning & Preparation

- Checked missing and duplicate values.
- Validated data types and categorical values.
- Checked delivery-related fields for consistency.
- Prepared the dataset for analysis and visualization.

### Exploratory Data Analysis

Used Python to analyze:

- Delivery performance
- Revenue trends
- Product categories
- Regional performance
- Supplier performance
- Shipping modes
- Returns
- Customer ratings

---

## 📊 Power BI Dashboard

The final analysis was presented through an interactive Power BI dashboard.

The dashboard provides a consolidated view of:

- Total Revenue
- Total Orders
- On-Time Delivery %
- Average Delivery Delay
- Average Customer Rating
- Revenue by Product Category
- Revenue by Region
- Delivery Performance by Shipping Mode
- Supplier Delivery Performance
- Returns by Delivery Status

### Dashboard Preview

![Supply Chain & Delivery Performance Dashboard](dashboard.png)

---

## 📈 Key KPIs

| KPI | Result |
|---|---:|
| Total Orders | **3,000+** |
| Total Revenue | **₹74.17M** |
| On-Time Delivery | **62.60%** |
| Average Delay | **0.88 Days** |
| Average Customer Rating | **3.94 / 5** |

---

## 🔍 Key Insights

### 🚚 Delivery Performance

- **62.60% of orders were delivered on time.**
- A significant portion of orders experienced delays, indicating an opportunity to improve delivery reliability.
- Average delivery delay was **0.88 days**.

### 💰 Revenue Performance

- Electronics, Grocery, and Clothing were among the major revenue-generating product categories.
- Revenue was relatively distributed across the major customer regions.
- North and Central regions were among the stronger revenue contributors.

### 🚛 Supplier Performance

- Supplier delivery performance varied based on average delivery delay.
- Suppliers with higher average delays require further investigation to identify operational bottlenecks.

### 📦 Shipping Performance

- Delivery performance was compared across Air, Road, Sea, and Rail shipping modes.
- Shipping mode performance can be evaluated based on order volume and delivery reliability.

### 🔄 Returns & Customer Satisfaction

- Return patterns were analyzed across different delivery statuses.
- The overall customer rating was **3.94/5**, indicating generally positive customer satisfaction with room for improvement.

---

## 🚧 Challenges Faced & Solutions

### Challenge 1 — Identifying Business Patterns

The dataset contained multiple dimensions such as products, suppliers, regions, shipping modes, delivery performance, and returns.

**Solution:**  
I analyzed the data across different business dimensions using grouping, aggregation, filtering, and visualization to identify meaningful patterns.

### Challenge 2 — Measuring Delivery Performance

Delivery performance depended on expected delivery days, actual delivery days, delay days, and delivery status.

**Solution:**  
I analyzed these fields together to calculate delivery KPIs and classify orders based on their delivery performance.

### Challenge 3 — Presenting Large Amounts of Data

Displaying every metric on one dashboard would make it difficult for business users to understand the important information.

**Solution:**  
I selected the most important KPIs and created focused visualizations for revenue, delivery, suppliers, regions, shipping modes, returns, and customer ratings.

---

## 💡 Business Recommendations

Based on the analysis:

- Monitor suppliers with consistently higher delivery delays.
- Investigate the major causes of delayed orders.
- Optimize shipping modes based on delivery performance and operational requirements.
- Monitor returns alongside delivery performance.
- Maintain reliable inventory and logistics for high-revenue product categories.
- Track customer ratings to identify areas where delivery improvements can enhance customer experience.

---

## 🧠 Key Learning

This project helped me understand how to move from **raw data to business decisions**.

I learned how to:

- Clean and validate real-world datasets.
- Perform exploratory data analysis using Python.
- Create meaningful KPIs.
- Build interactive Power BI dashboards.
- Identify business problems from data.
- Convert analytical findings into actionable recommendations.
- Communicate insights from a business perspective.

---

## 🚀 Future Improvements

The project can be further improved by:

- Adding historical delivery trend analysis.
- Building a supplier performance scorecard.
- Including shipping cost analysis.
- Predicting potential delivery delays.
- Analyzing warehouse-level bottlenecks.
- Building automated dashboard refresh pipelines.# 📦 Supply Chain & Delivery Performance Analysis

## 📌 Project Overview

The **Supply Chain & Delivery Performance Analysis** project focuses on analyzing order, delivery, revenue, supplier, shipping, and customer satisfaction data to identify operational bottlenecks and understand how delivery performance affects business outcomes.

The project analyzes **3,000+ orders generating ₹74.17M in revenue** and presents the findings through an interactive Power BI dashboard.

---

## 🎯 Business Problem

A supply chain company receives thousands of orders across different regions, suppliers, products, warehouses, and shipping modes.

However, raw order data does not immediately show **where operational problems are occurring**.

The business needs to understand:

- Delivery delays and overall delivery performance
- Revenue contribution by product category and region
- Supplier and shipping mode performance
- Customer returns
- Customer satisfaction
- Areas where logistics operations can be improved

### Problem Statement

> **Analyze supply chain and delivery data to identify delivery bottlenecks, revenue drivers, supplier performance issues, and relationships between delivery performance and customer outcomes, and present the findings through an interactive Power BI dashboard.**

---

## 🎯 Project Objectives

- Analyze overall delivery performance.
- Identify on-time, delayed, and early deliveries.
- Identify major revenue-generating product categories.
- Compare revenue across different regions.
- Evaluate supplier and shipping mode performance.
- Analyze return patterns based on delivery performance.
- Understand customer satisfaction using customer ratings.
- Provide actionable recommendations to improve supply chain operations.

---

## 🛠️ Tools & Technologies

### Python
- Pandas
- NumPy
- Matplotlib
- Data Cleaning
- Exploratory Data Analysis (EDA)

### Business Intelligence
- Power BI
- DAX
- KPI Cards
- Interactive Filters
- Data Visualization

### Database
- SQL
- MySQL

---

## 📊 Dataset

The dataset contains **3,000+ order records** covering different aspects of the supply chain.

### Major Data Fields

- **Order:** Order ID, Order Date, Customer ID
- **Customer:** Region, City, Customer Rating
- **Product:** Product Category, Product Name
- **Supplier:** Supplier Name
- **Logistics:** Shipping Mode, Warehouse Location
- **Revenue:** Quantity, Unit Price, Total Revenue
- **Delivery:** Expected Delivery Days, Actual Delivery Days, Delay Days, Delivery Status
- **Returns:** Return Status

---

## 🔄 Project Approach

The project followed an end-to-end data analysis process:

**Raw Data → Data Cleaning → EDA → Business Analysis → KPI Creation → Power BI Dashboard → Insights → Recommendations**

### Data Cleaning & Preparation

- Checked missing and duplicate values.
- Validated data types and categorical values.
- Checked delivery-related fields for consistency.
- Prepared the dataset for analysis and visualization.

### Exploratory Data Analysis

Used Python to analyze:

- Delivery performance
- Revenue trends
- Product categories
- Regional performance
- Supplier performance
- Shipping modes
- Returns
- Customer ratings

---

## 📊 Power BI Dashboard

The final analysis was presented through an interactive Power BI dashboard.

The dashboard provides a consolidated view of:

- Total Revenue
- Total Orders
- On-Time Delivery %
- Average Delivery Delay
- Average Customer Rating
- Revenue by Product Category
- Revenue by Region
- Delivery Performance by Shipping Mode
- Supplier Delivery Performance
- Returns by Delivery Status

### Dashboard Preview

![Supply Chain & Delivery Performance Dashboard](dashboard.png)

---

## 📈 Key KPIs

| KPI | Result |
|---|---:|
| Total Orders | **3,000+** |
| Total Revenue | **₹74.17M** |
| On-Time Delivery | **62.60%** |
| Average Delay | **0.88 Days** |
| Average Customer Rating | **3.94 / 5** |

---

## 🔍 Key Insights

### 🚚 Delivery Performance

- **62.60% of orders were delivered on time.**
- A significant portion of orders experienced delays, indicating an opportunity to improve delivery reliability.
- Average delivery delay was **0.88 days**.

### 💰 Revenue Performance

- Electronics, Grocery, and Clothing were among the major revenue-generating product categories.
- Revenue was relatively distributed across the major customer regions.
- North and Central regions were among the stronger revenue contributors.

### 🚛 Supplier Performance

- Supplier delivery performance varied based on average delivery delay.
- Suppliers with higher average delays require further investigation to identify operational bottlenecks.

### 📦 Shipping Performance

- Delivery performance was compared across Air, Road, Sea, and Rail shipping modes.
- Shipping mode performance can be evaluated based on order volume and delivery reliability.

### 🔄 Returns & Customer Satisfaction

- Return patterns were analyzed across different delivery statuses.
- The overall customer rating was **3.94/5**, indicating generally positive customer satisfaction with room for improvement.

---

## 🚧 Challenges Faced & Solutions

### Challenge 1 — Identifying Business Patterns

The dataset contained multiple dimensions such as products, suppliers, regions, shipping modes, delivery performance, and returns.

**Solution:**  
I analyzed the data across different business dimensions using grouping, aggregation, filtering, and visualization to identify meaningful patterns.

### Challenge 2 — Measuring Delivery Performance

Delivery performance depended on expected delivery days, actual delivery days, delay days, and delivery status.

**Solution:**  
I analyzed these fields together to calculate delivery KPIs and classify orders based on their delivery performance.

### Challenge 3 — Presenting Large Amounts of Data

Displaying every metric on one dashboard would make it difficult for business users to understand the important information.

**Solution:**  
I selected the most important KPIs and created focused visualizations for revenue, delivery, suppliers, regions, shipping modes, returns, and customer ratings.

---

## 💡 Business Recommendations

Based on the analysis:

- Monitor suppliers with consistently higher delivery delays.
- Investigate the major causes of delayed orders.
- Optimize shipping modes based on delivery performance and operational requirements.
- Monitor returns alongside delivery performance.
- Maintain reliable inventory and logistics for high-revenue product categories.
- Track customer ratings to identify areas where delivery improvements can enhance customer experience.

---

## 🧠 Key Learning

This project helped me understand how to move from **raw data to business decisions**.

I learned how to:

- Clean and validate real-world datasets.
- Perform exploratory data analysis using Python.
- Create meaningful KPIs.
- Build interactive Power BI dashboards.
- Identify business problems from data.
- Convert analytical findings into actionable recommendations.
- Communicate insights from a business perspective.

---

## 🚀 Future Improvements

The project can be further improved by:

- Adding historical delivery trend analysis.
- Building a supplier performance scorecard.
- Including shipping cost analysis.
- Predicting potential delivery delays.
- Analyzing warehouse-level bottlenecks.
- Building automated dashboard refresh pipelines.
