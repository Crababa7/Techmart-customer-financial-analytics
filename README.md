# Tech Mart Retail Ltd — Sales Analytics Dashboard

## Project Overview
An end-to-end Power BI sales analytics project for Tech Mart Retail Ltd. The dashboard turns retail sales and customer data into interactive views for executive, customer, product, regional, and employee performance analysis.

## Business Objectives
- Monitor sales, profit, orders, and margin.
- Analyse monthly sales and profit trends.
- Understand customer demographics and purchasing behaviour.
- Identify high- and low-performing products and brands.
- Compare regional and store performance.
- Monitor employee sales and target achievement.

## Dashboard Pages

### Executive Dashboard
KPIs include Total Sales (₦1.13M), Total Profit (₦274.56K), Total Orders (1K), and Profit Margin (24.38%). Visuals include Monthly Sales, Sales Trend, Profit Trend, Profit Margin, and time filters.

![Executive Dashboard]


### Customer Dashboard
KPIs include 200 customers, ₦1.13K average order value, and ₦5.63K average customer spend. Visuals cover age, gender, income group, and payment method.

![Customer Dashboard](power-bi/screenshots/customer-dashboard.png)

### Product Dashboard
KPIs include ₦412.55K sales growth, 24.38% profit margin, and Product 50 as the top product. Visuals cover top/bottom products, category sales, and brand performance.

![Product Dashboard](power-bi/screenshots/product-dashboard.png)

### Regional Dashboard
Compares West, North, South, and East using sales, profit, region map, and store comparison visuals.

![Regional Dashboard](power-bi/screenshots/regional-dashboard.png)

### Employee Dashboard
Shows the top employee, employee count, sales targets, and performance ranking.

![Employee Dashboard](power-bi/screenshots/employee-dashboard.png)

## Tools & Technologies
- Power BI — dashboard development, data modelling, DAX, and visualisation
- Power Query — data preparation and transformation
- PivotTables — analysis and validation
- GitHub — portfolio documentation and version control

## Data Preparation
The workflow included reviewing the source data, handling nulls, correcting data types, transforming fields with Power Query, preparing data for analysis, and validating results with exploratory analysis and PivotTables.

## Key Findings
- West is the highest-performing region by sales.
- East has the lowest regional sales and profit.
- Product 50 leads the displayed top-product analysis.
- Furniture is the strongest displayed category by sales.
- Employee E014 leads the displayed employee sales ranking.
- Monthly sales and profit vary noticeably across the year.

## Repository Structure
```text
prime-mart-sales-analytics/
├── README.md
├── data/
│   ├── raw/
│   └── cleaned/
├── power-bi/
│   ├── Prime_Mart_Sales_Dashboard.pbix
│   └── screenshots/
└── documentation/
    ├── data-cleaning.md
    └── data-model.md
```

## Skills Demonstrated
Data cleaning, Power Query, data modelling, DAX, KPI development, trend analysis, customer analysis, product analysis, regional analysis, employee performance analysis, SQL, business storytelling, and GitHub documentation.

