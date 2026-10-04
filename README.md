# Amazon Sales Performance Analysis Using Excel

##  Project Overview
The **Amazon Sales Performance Analysis** project focuses on analyzing e-commerce order data using **Microsoft Excel** to understand sales performance, customer purchasing patterns, payment preferences, and order fulfillment.

The project follows a complete data analysis workflow, starting from **raw data cleaning and preprocessing** to **PivotTable analysis, dashboard creation, and business insights**.

The objective is to transform raw Amazon sales data into meaningful insights that can support better business and operational decisions.

## Project Objectives

###### Analyze overall sales performance.

###### Identify the highest-performing product categories and products.

###### Analyze sales performance across customer locations.

###### Understand customer payment method preferences.

###### Evaluate order status and fulfillment performance.

###### Identify top customers based on total spending.

###### Create an interactive Excel dashboard.

###### Generate actionable business insights from the analysis.

##  Business Problem

E-commerce businesses generate large amounts of transactional data, but raw data alone does not provide clear business insights.

This project addresses key business questions such as:

###### Which product category generates the highest sales?

###### Which products contribute the most to total sales?

###### Which customer locations generate the highest sales?

###### Which payment methods are most frequently used?

###### What is the distribution of delivered, cancelled, and pending orders?

###### Which customers have the highest total spending?

The analysis helps convert transactional sales data into useful information for **sales planning, inventory management, customer understanding, and operational improvement**.

##  Dataset

The dataset contains Amazon order-level transactional information.

### Key Columns

| Column            | Description                      |
| ----------------- | -------------------------------- |
| Order ID          | Unique identifier for each order |
| Date              | Date of the order                |
| Product           | Name of the product              |
| Category          | Product category                 |
| Price             | Price per unit                   |
| Quantity          | Number of units ordered          |
| Total Sales       | Total sales amount               |
| Customer Name     | Name of the customer             |
| Customer Location | Customer's city/location         |
| Payment Method    | Method used for payment          |
| Order Status      | Current status of the order      |

##  Project Workflow

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Preprocessing
     ↓
Calculated Columns
     ↓
PivotTable Analysis
     ↓
Charts & Visualizations
     ↓
Interactive Dashboard
     ↓
Business Insights
     ↓
Recommendations
```

##  Data Cleaning & Preprocessing

The following data preparation activities were performed:

###### Checked for missing values.

###### Identified duplicate records.

###### Standardized date formats.

###### Cleaned inconsistent text values.

###### Standardized category and location names.

###### Verified numerical fields such as Price, Quantity, and Total Sales.

###### Validated the Total Sales calculation.

###### Created additional analytical columns such as Month and Day of Week.

## PivotTable Analysis

PivotTables were created to analyze different aspects of Amazon sales performance.

### 1. Category-wise Total Sales

###### **Question:** Which category generates the most sales?

###### **Rows:** Category

###### **Values:** Total Sales

###### **Aggregation:** Sum

### 2. Product-wise Performance

###### **Question:** Which products generate the highest sales?

###### **Rows:** Product

###### **Values:** Total Sales

###### **Aggregation:** Sum

###### **Sorting:** Largest to Smallest

### 3. City-wise Total Sales

###### **Question:** Which customer locations contribute the most sales?

###### **Rows:** Customer Location

###### **Values:** Total Sales

###### **Aggregation:** Sum

### 4. Payment Method Usage

###### **Question:** Which payment method is most frequently used?

###### **Rows:** Payment Method

###### **Values:** Order ID

###### **Aggregation:** Count

### 5. Order Status Distribution

###### **Question:** How many orders are Delivered, Cancelled, or Pending?

###### **Rows:** Order Status

###### **Values:** Order ID

###### **Aggregation:** Count

### 6. Top Customers by Total Spending

###### **Question:** Which customers spend the most?

###### **Rows:** Customer Name

###### **Values:** Total Sales

###### **Aggregation:** Sum

###### **Sorting:** Largest to Smallest

##  Dashboard

An interactive **Amazon Sales Performance & Insights Dashboard** was created using Excel.

### Dashboard Components

###### Total Sales

###### Total Orders

###### Average Order Value

###### Delivery Rate

###### Total Sales by Category

###### Top Products by Sales

###### Sales by Customer Location

###### Order Status Distribution

###### Payment Method Distribution

### Interactive Filters

The dashboard includes slicers for:

###### Category

###### Customer Location

###### Order Status

###### Month

These slicers allow users to interactively filter the dashboard and explore different aspects of sales performance.

## Key Business Insights

The final insights are derived from the PivotTables and dashboard.

| Analysis Area            | Finding           | Business Insight                                       |
| ------------------------ | ----------------- | ------------------------------------------------------ |
| Highest-Selling Product  | Based on analysis | Identifies the product generating the highest sales    |
| Top Cities               | Based on analysis | Identifies locations contributing the most sales       |
| Cancellation vs Delivery | Based on analysis | Evaluates order fulfillment performance                |
| Payment Mode Popularity  | Based on analysis | Identifies customer payment preferences                |
| Category Performance     | Based on analysis | Identifies the strongest-performing product categories |
| Top Customers            | Based on analysis | Identifies high-value customers                        |

> **Note:** Findings and values are based on the actual results obtained from the Excel analysis.

## Business Value

The analysis demonstrates how **Microsoft Excel can transform raw e-commerce transaction data into meaningful business insights**.

The findings can help businesses:

###### Identify high-performing products and categories.

###### Understand customer purchasing patterns.

###### Recognize high-value customer segments.

###### Identify strong-performing locations.

###### Monitor order fulfillment performance.

###### Understand preferred payment methods.

###### Support inventory and sales planning.

###### Make data-driven business decisions.

## Tools & Technologies

###### Microsoft Excel

###### PivotTables

###### PivotCharts

###### Excel Formulas

###### Slicers

###### Data Cleaning

###### Data Analysis

###### Data Visualization

## Project Structure

```text
Amazon-Sales-Performance-Analysis/
│
├── Amazon_Sales_Performance_Analysis.xlsx
│
├── Amazon_Sales_Raw_Data.csv
│
├── README.md
│
└── screenshots/
    └── Amazon_Sales_Dashboard.png
```

### Excel Workbook Structure

```text
Amazon_Sales_Performance_Analysis.xlsx
│
├── Raw Data
├── Cleaned Data
├── PivotTables
├── Dashboard
├── Insights
└── Documentation
```

## Dashboard Preview

Add your dashboard screenshot here after completing the dashboard.

```markdown
<img width="1756" height="867" alt="image" src="https://github.com/user-attachments/assets/181b876b-1d77-478c-b2ef-82eeb1723ce3" />

```

##  Key Learning Outcomes

Through this project, I gained practical experience in:

###### Data cleaning and preprocessing using Excel.

###### Working with transactional sales data.

###### Creating and analyzing PivotTables.

###### Creating interactive dashboards.

###### Using slicers for dynamic analysis.

###### Performing comparative sales analysis.

###### Identifying business trends and patterns.

###### Converting data analysis results into business insights.


###### **Skills:** `Microsoft Excel` `Data Analysis` `PivotTables` `Data Visualization` `Dashboard Development`

##  Conclusion

The **Amazon Sales Performance Analysis** project demonstrates an end-to-end Excel-based data analytics workflow, from raw transactional data to an interactive dashboard and actionable business insights.

It highlights how data analysis and visualization can support better understanding of **sales performance, customer behavior, payment preferences, and operational efficiency**.
