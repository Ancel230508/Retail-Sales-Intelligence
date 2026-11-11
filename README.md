# Retail Sales Intelligence Dashboard

**A Data Analytics and Business Intelligence Project using Python, Pandas and Microsoft Power BI**

## 1. Project Overview

Retail Sales Intelligence is an end-to-end data analytics project designed to analyze retail transaction data and convert raw sales records into actionable business insights.

The project uses Python for data cleaning, exploratory data analysis, KPI calculations and business recommendations. Microsoft Power BI is used to develop an interactive dashboard for monitoring business performance.

**Note:** This project uses a simulated retail dataset for educational and portfolio purposes. It does not contain actual company financial data.

## 2. Project Objectives

- Analyze retail sales and profitability.
- Identify top-performing products and categories.
- Understand regional and monthly sales performance.
- Analyze customer spending patterns.
- Evaluate the relationship between discounts and profit margins.
- Build an interactive business intelligence dashboard.
- Generate data-driven business recommendations.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab | Python development environment |
| Microsoft Power BI | Interactive dashboard |
| Microsoft Excel | Analytical reporting |

## 4. Dataset Information

The simulated dataset contains:

- 1,200 transactions
- 297 unique customers
- 14 products
- 3 product categories
- 4 geographical regions
- 12 original columns

### Dataset Columns

Order ID, Order Date, Customer ID, Product, Category, Region, City, Quantity, Unit Price, Discount, Sales and Profit.

## 5. Data Cleaning and Preparation

The following operations were performed:

- Checked missing values.
- Identified duplicate records.
- Standardized text fields.
- Converted order dates into datetime format.
- Validated quantity and unit price values.
- Checked discount ranges.
- Verified sales calculations.
- Prepared a cleaned dataset for analysis.

## 6. Key Business KPIs

| KPI | Result |
|---|---:|
| Total Revenue | ₹9,601,799.50 |
| Total Profit | ₹1,463,519.03 |
| Total Orders | 1,200 |
| Average Order Value | ₹8,001.50 |
| Profit Margin | 15.24% |
| Units Sold | 3,560 |
| Unique Customers | 297 |
| Average Discount | 7.62% |

## 7. Key Business Insights

### Product Performance
- Monitor generated the highest revenue.
- Pen Set had the highest profit margin.
- Monitor generated the highest total profit.

### Category Performance
- Electronics generated the highest category revenue.
- Furniture was a close second.
- Office Supplies generated comparatively lower revenue.

### Regional Performance
- North generated the highest regional revenue.
- Kochi was the highest-revenue city.

### Monthly Performance
- July recorded the highest monthly revenue.
- August recorded the lowest monthly revenue.

### Customer Analysis
- The top 10 customers contributed 12.09% of total revenue.
- Customer spending patterns can help inform retention strategies.

### Discount Analysis
- Higher discount levels were associated with lower profit margins in this simulated dataset.
- Discount effectiveness should be evaluated before launching promotions.

## 8. Power BI Dashboard

The interactive dashboard includes:

- Total Revenue
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin
- Monthly Revenue Trend
- Revenue by Product Category
- Top 10 Products by Revenue
- Profit Contribution by Region

### Interactive Filters

- Date
- Region
- Product Category

## 9. Business Recommendations

1. Develop retention strategies for high-value customers.
2. Promote products with strong profitability.
3. Review pricing and costs for low-margin products.
4. Evaluate promotional discounts carefully.
5. Investigate regional and city-level performance.
6. Analyze monthly revenue fluctuations.

These are recommendations based on the simulated data, not verified causes of business performance.

## 10. Project Structure

```text
Retail-Sales-Intelligence/
│
├── dataset/
│   ├── retail_sales_dataset.csv
│   └── cleaned_retail_dataset.csv
│
├── analysis/
│   └── Retail_Sales_Analysis.ipynb
│
├── dashboard/
│   └── Retail_Sales_Intelligence.pbix
│
├── reports/
│   ├── Retail_Sales_Analysis.xlsx
│   ├── Business_Recommendations.txt
│   └── charts/
│
└── README.md
```

## 11. Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Python Programming
- Pandas and NumPy
- Data Visualization
- Business KPI Development
- DAX Measures
- Power BI Dashboard Development
- Business Intelligence
- Analytical Thinking
- Data-Driven Decision Making

## 12. Conclusion

This project demonstrates an end-to-end analytical workflow, starting with raw retail transaction data and progressing through data preparation, analysis, visualization and business recommendations.

It showcases the practical application of Python and Power BI to support business performance monitoring and decision-making.

---

**Project Type:** Data Analytics / Business Intelligence  
**Dataset:** Simulated Retail Transaction Data  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Power BI and Excel
