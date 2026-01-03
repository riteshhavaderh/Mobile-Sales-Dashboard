# Mobile-Sales-Dashboard

An interactive **Power BI dashboard** built to analyze mobile phone sales transactions across brands, models, time periods, cities, payment methods, and customer ratings.  
This dashboard transforms raw transactional data into actionable business insights using data visualization and analytics.

---

## 1.  Project Title / Headline

 **Mobile Sales Analytics Dashboard**  
A dynamic and interactive Power BI dashboard designed to explore mobile phone sales performance, customer behavior, and revenue trends across multiple dimensions.

---

## 2.  Short Description / Purpose

The Mobile Sales Analytics Dashboard helps users analyze mobile sales data by brand, model, month, city, and payment method.  
It enables stakeholders to monitor performance, understand customer preferences, and support data-driven business decisions.

---

## 3.  Tech Stack

The dashboard was built using the following tools and technologies:

-  **Power BI Desktop** – Main platform for report creation and visualization  
-  **Power Query** – Data cleaning, transformation, and preprocessing  
-  **DAX (Data Analysis Expressions)** – Used to create KPIs and calculated measures  
-  **Data Modeling** – Relationships built across time, sales, and customer attributes  
-  **File Formats** – `.pbix` (development), `.png` (dashboard preview)

---

## 4.  Data Source

**Source:** Simulated / Practice Mobile Sales Transaction Dataset  

The dataset contains transaction-level mobile sales data with the following fields:

###  Dataset Schema

| Column Name | Description |
|------------|-------------|
| **Transaction ID** | Unique identifier for each transaction |
| **Day** | Day of the month |
| **Month** | Month of the transaction |
| **Year** | Year of the transaction |
| **Day Name** | Name of the day (Monday–Sunday) |
| **Brand** | Mobile phone brand |
| **Mobile Model** | Specific mobile model sold |
| **Units Sold** | Number of units sold |
| **Price Per Unit** | Price of one mobile unit |
| **Customer Name** | Name of the customer |
| **Customer Age** | Age of the customer |
| **City** | City of purchase |
| **Payment Method** | Mode of payment (UPI, Debit Card, Credit Card, Cash) |
| **Customer Ratings** | Customer satisfaction rating (1–5) |

###  Derived Metrics
- **Total Sales** = Units Sold × Price Per Unit  
- **Total Transactions** = Count of Transaction ID  
- **Average Rating** = Average of Customer Ratings  

---

## 5.  Features / Highlights

###  Business Problem

Mobile retailers and sales teams often face difficulty in understanding sales trends, customer behavior, and regional performance from raw transactional data.  
Key questions such as:
- Which brands generate the highest revenue?
- Which months show peak sales?
- What payment methods do customers prefer?
- How satisfied are customers?

…are hard to answer without a visual analytics solution.

---

###  Goal of the Dashboard

The goal of this dashboard is to:
- Provide a centralized view of mobile sales performance
- Enable brand-wise and model-wise comparison
- Analyze customer satisfaction and payment behavior
- Support business decisions in sales, marketing, and inventory planning

---

###  Walkthrough of Key Visuals

**Key KPIs**
- Total Sales
- Units Sold
- Total Transactions
- Average Customer Rating

**Month Filter Panel**
- Allows filtering of the entire dashboard from January to December

**Brand-wise Sales Table**
- Displays total sales contribution by each mobile brand

**Units Sold by Brand (Bar Chart)**
- Compares sales volume across different brands

**Units Sold by Brand & Mobile Model (Stacked Bar Chart)**
- Shows model-level contribution within each brand

**Monthly Sales Trend (Line Chart)**
- Identifies seasonal trends and peak sales periods

**Payment Method Distribution (Donut Chart)**
- Visualizes customer payment preferences

**City-wise Sales Map**
- Displays geographical distribution of units sold

**Customer Ratings Distribution**
- Shows rating patterns from 1 to 5

---

###  Business Impact & Insights

-  **Sales Optimization:** Identify high-performing brands and months  
-  **Payment Strategy:** Understand dominant payment methods  
-  **Customer Experience:** Analyze satisfaction using ratings  
-  **Regional Planning:** Target high-demand cities effectively  
-  **Executive Reporting:** Quick KPIs for management review  

---

## 6.  Screenshots / Demo

### Dashboard Preview

![Mobile Sales Dashboard](dashboard.png)


