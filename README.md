# 📊 ElectroHub Sales Performance & Business Intelligence Dashboard

An interactive Power BI project analysing retail sales performance, product trends, promotional activities, and customer behaviour to generate actionable business insights.

## 📌 Project Overview

ElectroHub is a retail business offering products across multiple categories, including Electronics, Clothing, Footwear, Home Appliances, Accessories, Kitchenware, Bags, and Personal Care.

This project uses Microsoft Power BI to transform retail sales data into an interactive business intelligence dashboard. It enables users to monitor key performance indicators, identify revenue drivers, evaluate product performance, compare promotional activities, and understand customer contributions.

The report consists of four analytical pages:

1. Executive Sales Overview
2. Product Performance Analysis
3. Promotion Effectiveness
4. Customer Analytics

## 🎯 Business Problem

Retail businesses generate large volumes of sales data, but raw transaction records do not automatically provide the insights needed for effective decision-making.

ElectroHub needed a consolidated reporting solution to answer questions such as:

- How is the business performing over time?
- Which product lines and individual products generate the most revenue?
- Which products have comparatively low sales?
- How do sales and discounts vary across promotions and advertising types?
- Which customers contribute the most revenue?
- Which cities represent the largest sales markets?

The goal was to develop an interactive dashboard that answers these questions and supports data-driven business decisions.

## 🎯 Project Objectives

- Monitor gross sales, net sales, discounts, units sold, and customer metrics.
- Analyse sales trends over time.
- Identify top-performing and low-performing products.
- Compare sales across product lines.
- Evaluate sales and discount patterns associated with promotions.
- Identify high-value customers and measure revenue contribution.
- Compare sales performance across cities.
- Translate analytical findings into practical business recommendations.

## 🛠️ Tools & Technologies

| Tool | Application |
|---|---|
| Microsoft Power BI | Interactive dashboard development and data visualization |
| Power Query | Data preparation and transformation |
| DAX | KPI calculations and analytical measures |
| Data Modelling | Relationships between sales, customer, product, and promotion tables |
| Data Visualization | Presenting trends, comparisons, rankings, and business insights |

## 🗂️ Dataset Description

The dataset contains more than 3,000 sales records and is organized into four logical tables.

| Table | Key Fields |
|---|---|
| Fact Sales | Date, CustomerID, PromotionID, Product ID, Units Sold, Price Per Unit, Total Sales, Discount Percentage, Discount Value, Net Sales |
| Customer | Customer ID, Customer Name, City, State, Pincode, EmailID, Phone Number |
| Product | ProductID, Product Name, Product Line, Price (INR) |
| Promotion | PromotionID, Promotion Name, Ad Type, Coupon Code, Price Reduction Type |

The dataset covers eight product lines and includes customer, product, transaction, date, and promotion information.

### Dataset Source & Attribution

**Dataset creator/course attribution:** Krish Naik.

The dataset is credited to Krish Naik as the source indicated for this project.
This repository documents an independent portfolio analysis. Credit for the original dataset belongs to its source; the dashboard design, analytical measures, visualizations, and business interpretation presented here reflect the work carried out for this project.

## ⚙️ Data Preparation & Modelling

The data was prepared and organized for analysis in Power BI.

Key activities included:

- Reviewing the dataset structure and field types.
- Establishing relationships between the sales fact table and the Customer, Product, and Promotion dimension tables.
- Preparing measures for sales, discounts, units sold, and customer analysis.
- Handling transactions without a named promotion separately from named promotional campaigns.
- Developing DAX measures for KPIs and revenue contribution.
- Configuring interactive slicers and report-level filtering.

The resulting data model supports analysis across products, customers, promotions, locations, and time periods.

## 📊 Dashboard Pages

### 1. Executive Sales Overview

<img width="664" height="376" alt="Image" src="https://github.com/user-attachments/assets/9e040674-d52f-44f9-9af5-1d3f2d01b837" />

This page provides a high-level view of ElectroHub's performance.

**Key visualizations**
- KPI cards for customers, gross sales, discounts, net sales, and units sold.
- Monthly sales trend.
- Net sales by product line.
- Top five products by sales.
- Top five cities by sales.

**Key insights**
- Electronics generated approximately ₹90M in net sales.
- Apple iPhone 14 led product sales at approximately ₹21M.
- Bhopal recorded the highest sales among the five displayed cities, at ₹15.4M.

### 2. Product Performance Analysis

<img width="670" height="374" alt="Image" src="https://github.com/user-attachments/assets/1740e48a-27ac-4b27-bdf7-2f41fdeae049" />

This page compares product performance by revenue and volume.

**Key visualizations**
- Top 10 products by sales.
- Bottom 10 products by sales.
- Units sold by product line.
- Top 10 products by units sold.
- KPI cards for product count, units sold, average net sales per product, and top-product contribution.

**Key insights**
- Clothing recorded 1,243 units sold, followed by Electronics with 1,202 units.
- Apple iPhone 14 led both sales value and unit volume, generating approximately ₹21M from 281 units.
- Zara Casual Shirt and Colgate Toothpaste appeared at the top and bottom of the displayed bottom-10 ranking, at approximately ₹0.56M and ₹0.02M, respectively.

### 3. Promotion Effectiveness

<img width="669" height="376" alt="Image" src="https://github.com/user-attachments/assets/11602f45-9afd-433d-ad47-706a90f4a568" />

This page examines sales and discount patterns associated with promotional activities.

**Key visualizations**
- Net sales by promotion.
- Monthly promotional sales trend.
- Discount value by promotion.
- Sales by advertising type.
- Discount value versus net sales.

**Key insights**
- Transactions classified as “No Promotion” generated approximately ₹103M in net sales.
- Summer Sale generated approximately ₹17M in net sales and recorded ₹4.3M in discounts.
- Weekend Flash Sale generated approximately ₹2M in net sales.

*Note: Sales associated with a promotion do not establish that the promotion caused additional sales. Measuring incremental effectiveness would require an appropriate baseline and campaign cost information.*

### 4. Customer Analytics

<img width="665" height="375" alt="Image" src="https://github.com/user-attachments/assets/7d22bce3-2bf4-480a-8f94-2a998b8898d5" />

This page explores customer revenue contribution and geographic sales distribution.

**Key visualizations**
- Top 10 customers by net sales.
- Customer net sales and revenue contribution.
- Customer distribution by revenue segment.
- Net sales by city.
- Customer-level KPI cards.

**Key insights**
- The top 10 customers contributed approximately 26.96% of total net sales.
- Mohit Aggarwal was the leading customer at approximately ₹4.4M in net sales.
- Lucknow recorded the highest sales among the displayed cities, at approximately ₹6.2M, followed closely by Indore at ₹6.1M.

## 💡 Business Recommendations

Based on the dashboard findings, the following actions merit further investigation:

1. **Protect leading product lines:** Review inventory, product margins, and demand patterns in Electronics to sustain performance.
2. **Investigate low-sales products:** Examine margins, availability, and demand before making stocking or discontinuation decisions.
3. **Evaluate promotional efficiency:** Compare campaign costs, discounts, and sales against an appropriate baseline before increasing promotional spending.
4. **Strengthen customer retention:** Develop retention strategies for high-value customers while identifying opportunities to grow revenue from other segments.
5. **Explore geographic opportunities:** Investigate demand and operating costs in leading cities such as Lucknow and Indore before allocating additional resources.

## ⚠️ Limitations & Future Improvements

Potential enhancements include:

- Adding product costs and profit margins to support profitability analysis.
- Incorporating campaign expenditure and a baseline for promotional ROI.
- Adding a unique Order ID for order counts and average order value analysis.
- Integrating inventory and stock availability data.
- Analysing repeat purchases, customer retention, and customer lifetime value.

## 📁 Repository Structure

```text
ElectroHub-Sales-Analytics/
│
├── README.md
├── ElectroHub-Sales-Performance.pbix
└── images/
    ├── executive-sales-overview.png
    ├── product-performance.png
    ├── promotion-effectiveness.png
    └── customer-analytics.png
```

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Install Microsoft Power BI Desktop.
3. Open `ElectroHub-Sales-Performance.pbix`.
4. If prompted, reconnect the data source to the appropriate dataset file.
5. Explore the report pages using the available slicers and filters.

## 👤 Credits & Acknowledgements

- **Dataset attribution:** Krish Naik — add the verified original dataset URL above.
- **Project author:** Moses Amusa 
- **Tools:** Microsoft Power BI, Power Query, and DAX.

This project was developed for educational and portfolio purposes. Dataset attribution does not imply endorsement by the original creator.

---

*This project demonstrates practical skills in data modelling, DAX, interactive dashboard design, business analysis, and data storytelling.*
