# 🍽️ Restaurant Business Intelligence & Performance Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Dataset-green?logo=microsoftexcel)
![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

The **Restaurant Business Intelligence & Performance Analytics Dashboard** is an end-to-end data analytics project developed using Microsoft Power BI.

The project focuses on analyzing restaurant business operations, customer behavior, order performance, restaurant-level metrics, and delivery operations through interactive dashboards.

The objective is to transform raw restaurant and transaction data into meaningful business information that can help stakeholders understand performance, identify trends, and make data-driven decisions.

The report contains six analytical pages covering different aspects of restaurant business performance.

## 🎯 Business Problem

Restaurant businesses generate large amounts of data related to customers, restaurants, orders, revenue, and delivery operations.

However, raw data alone does not provide clear insights into business performance.

Some important business questions include:

- Which restaurants perform better?
- How do customer ordering patterns vary?
- Which restaurants and cuisines attract more orders?
- How can order and revenue performance be monitored?
- How efficiently are delivery operations performing?
- How can restaurant-level performance be explored in detail?

This project addresses these analytical requirements through an interactive Power BI reporting solution.

## 🎯 Project Objectives

- Analyze overall restaurant business performance.
- Understand customer behavior and ordering patterns.
- Explore restaurant performance and cuisine distribution.
- Monitor delivery and operational performance.
- Develop advanced analytical views.
- Build interactive reports for business decision-making.
- Practice data modeling, visualization, and business intelligence techniques.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data preparation and transformation |
| DAX | Measures and analytical calculations |
| Microsoft Excel | Dataset storage and source data |
| Data Modeling | Connecting business entities and transaction data |

## 📂 Dataset Description

The project uses an Excel workbook containing four sheets.

| Dataset | Records | Columns |
|---|---:|---:|
| Restaurants | 56,250 | 14 |
| Customers | 20,000 | 5 |
| Orders | 200,000 | 8 |
| DateTable | 1,000 | 6 |
| **Total** | **277,250** | **33** |

### 1. Restaurants

Contains restaurant-level information.

Key columns:
- RestaurantID
- Name
- Address
- Online Order Availability
- Table Booking Availability
- Rating
- Votes
- Location
- Restaurant Type
- Dishes Liked
- Cuisines
- Approximate Cost for Two
- Restaurant Listing Type
- Listing City

### 2. Customers

Contains customer information.

Key columns:
- CustomerID
- CustomerName
- City
- SignupDate
- CustomerType

### 3. Orders

Contains transaction and order information.

Key columns:
- OrderID
- RestaurantID
- CustomerID
- OrderDate
- OrderValue
- DeliveryTimeMins
- OrderStatus
- Quantity

### 4. DateTable

Contains calendar information for time-based analysis.

Key columns:
- Date
- Year
- MonthNo
- MonthName
- Quarter
- Day

## 📊 Dashboard Structure

The Power BI report contains six pages.

### 1. Exclusive – Business Overview

Provides an overall view of restaurant business performance.

Purpose:
- Monitor business performance.
- Explore high-level trends.
- Understand key business indicators.

### 2. Customer Analysis

Focuses on customer-related analytics.

Purpose:
- Explore customer behavior.
- Analyze customer segments.
- Understand ordering patterns.

### 3. Restaurant Analysis

Focuses on restaurant-level performance.

Purpose:
- Explore restaurant ratings.
- Analyze restaurant categories and cuisines.
- Compare restaurant performance.

### 4. Delivery & Operations

Focuses on order fulfillment and delivery operations.

Purpose:
- Examine delivery performance.
- Analyze order statuses.
- Understand operational patterns.

### 5. Advanced Insights

Provides additional analytical views.

Purpose:
- Explore advanced business metrics.
- Compare different performance dimensions.
- Support deeper business analysis.

### 6. Restaurant Details

Provides a detailed restaurant-level view.

Purpose:
- Explore individual restaurant information.
- Investigate restaurant-specific performance.
- Navigate from broader analysis to detailed information.

## 📈 Key Business Analysis Areas

The project is structured around five major analytical areas:

1. **Revenue Analysis:** Understanding order value and business performance.
2. **Customer Analytics:** Exploring customer segments and ordering behavior.
3. **Restaurant Analytics:** Comparing restaurant performance and cuisine categories.
4. **Operational Analytics:** Understanding order fulfillment and delivery efficiency.
5. **Advanced Analytics:** Exploring relationships and patterns across business dimensions.

## 🧩 Data Model

The dataset contains four major entities:

- Restaurants
- Customers
- Orders
- DateTable

The intended analytical relationships are:

- Restaurants → Orders using RestaurantID.
- Customers → Orders using CustomerID.
- DateTable → Orders using OrderDate.

These relationships should be configured as appropriate one-to-many relationships after validating key uniqueness and matching values.

## 📁 Repository Structure

```text
restaurant-business-intelligence-dashboard/
│
├── Dashboard/
│   └── Business_Project_1.pbix
│
├── Dataset/
│   └── dataset.xlsx
│
├── Screenshots/
│   ├── overview.png
│   ├── customer_analysis.png
│   ├── restaurant_analysis.png
│   ├── delivery_operations.png
│   ├── advanced_insights.png
│   └── restaurant_details.png
│
├── README.md
└── .gitignore
```

## 🚀 How to Use This Project

1. Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/restaurant-business-intelligence-dashboard.git
```

2. Open the downloaded project folder.

3. Navigate to the Dashboard folder.

4. Open the `.pbix` file using Microsoft Power BI Desktop.

5. If required, configure the data source and semantic model connection.

6. Refresh the report after ensuring that the required data sources and permissions are available.

7. Explore the six dashboard pages and their interactive visualizations.

## 💡 Learning Outcomes

Through this project, I explored:

- Business Intelligence and data visualization.
- Working with multi-table datasets.
- Power BI report development.
- Data modeling concepts.
- DAX-based analytical calculations.
- Customer and restaurant analytics.
- Operational performance analysis.
- Interactive dashboard design.
- Translating business questions into analytical reports.

## 🔮 Future Improvements

Potential improvements for future versions include:

- More detailed customer segmentation.
- Restaurant ranking and benchmarking.
- Customer lifetime value analysis.
- Revenue forecasting.
- Delivery performance optimization.
- Advanced predictive analytics.
- More comprehensive business insights.
- Automated data refresh and reporting.

## 👨‍💻 Author

**Antaran Adhwaryu**

B.Tech Computer Science Engineering | AI & ML

Interested in:
- Data Analytics
- Business Intelligence
- Artificial Intelligence & Machine Learning
- Data Science
- Full-Stack Development

🔗 **GitHub:** https://github.com/meantaran

🔗 **LinkedIn:** https://www.linkedin.com/in/antaran-adhwaryu-1b18983a3/

## ⭐ Support

If you find this project useful or interesting, consider giving this repository a ⭐ on GitHub.

---

**Project Category:** Data Analytics | Business Intelligence | Power BI

**Developed by:** Antaran Adhwaryu
