# Electronics Supply Chain Analytics & Predictive Intelligence

### End-to-End Data Analytics | Business Intelligence | Machine Learning

A comprehensive Electronics Supply Chain Analytics project designed to transform raw business data into meaningful insights through data analysis, business intelligence, and predictive modeling.

The project integrates SQL, Python, Excel, Power BI, Tableau, and Machine Learning to analyze business performance, evaluate operational efficiency, identify profitability challenges, and support data-driven decision-making.

---

# 1. Project Overview

Supply chain management involves multiple interconnected business operations, including sales, inventory management, customer experience, supplier performance, and shipping logistics.

Understanding these operations is essential for improving efficiency, controlling costs, optimizing resources, and maintaining sustainable profitability.

This project provides an integrated analytical solution for an Electronics Supply Chain business, covering the complete data analytics lifecycle, from data preparation and exploratory analysis to interactive dashboards and predictive forecasting.

The project is structured around five major analytical domains:

- Commercial Insights & Business Performance
- Inventory Performance & Optimization
- Customer Experience & Returns
- Supplier Performance
- Shipping & Logistics Performance

Each domain is supported by dedicated Key Performance Indicators (KPIs) and Business Insights to provide a comprehensive understanding of supply chain operations.

---

# 2. Project Objectives

The main objectives of this project are:

- Analyze overall business performance and financial indicators.
- Evaluate revenue, profit, and profitability trends.
- Understand product performance and sales channel contribution.
- Monitor inventory levels, production, and stockout risk.
- Analyze customer satisfaction and product return behavior.
- Evaluate supplier quality, reliability, and performance.
- Monitor shipping costs and delivery efficiency.
- Identify operational inefficiencies and profitability challenges.
- Develop predictive models for Revenue and Profit forecasting.
- Support strategic business decisions through data-driven insights.

---

# 3. Technology Stack

| Technology | Purpose |
|---|---|
| SQL Server | Data Cleaning, Transformation & Analysis |
| Python | Data Analysis & Machine Learning |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| XGBoost | Predictive Forecasting |
| Excel | Data Analysis & Reporting |
| Power BI | Interactive Business Intelligence |
| Tableau | Data Visualization |
| Jupyter Notebook | Analytical Development |

---

# 4. Data Preparation & Engineering

Data preparation was a fundamental stage of the project to ensure data quality, consistency, and analytical reliability.

The preparation process included:

- Data structure inspection.
- Missing value identification and treatment.
- Duplicate record detection.
- Standardization of categorical values.
- Text cleaning and formatting.
- Correction of inconsistent records.
- Business-rule-based data transformation.
- Preparation of analytical datasets.

SQL Server was used for structured data cleaning and transformation, while Python supported additional analytical preparation.

---

# 5. Business Intelligence & Dashboard Analysis

The project includes five interactive Power BI dashboards designed to analyze different aspects of Electronics Supply Chain operations.

Each dashboard contains dedicated Key Performance Indicators (KPIs) and Business Insights that provide visibility into specific business dimensions.

## 5.1 Commercial Insights & Business Performance

### Key Performance Indicators (KPIs)

| KPI | Value | YoY Change |
|---|---:|---:|
| Total Revenue | $183M | +2.1% |
| Total Profit | $86M | -3.2% |
| Profit Margin | 46.8% | -0.5 PP |
| Average Discount | 7.5% | +6.1 PP |

### Business Insights

- Revenue & Profit by Product
- Revenue & Profit Trend (Quarterly)
- Profit & Units Sold by Sales Channel
- Profit Margin % by Region
- Discount % Distribution
- Revenue & Profit by Discount
- Revenue & Profit by Gender

## 5.2 Inventory Performance & Optimization

### Key Performance Indicators (KPIs)

| KPI | Value | YoY Change |
|---|---:|---:|
| Production Volume | 894K | -0.01% |
| Total Units Sold | 375K | +9.0% |
| Total Stock | 231K | +5.1% |
| Inventory Gap | 288K | -0.2 |
| Products | 1,500 | +6.7% |

### Business Insights

- Stockout Risk
- Production Volume by Product Type
- Profit Margin vs. Units Sold by Products
- Inventory Gap & Stock Level by Product Type
- Top vs. Bottom 5 SKUs by Units Sold
- SKUs by Price Range & Profit Margin
- Defect Rates by Product Type

## 5.3 Customer Experience & Returns

### Key Performance Indicators (KPIs)

| KPI | Value | YoY Change |
|---|---:|---:|
| Average Return Rate | 7.4% | +2.1% |
| Total Units Returned | 27.6K | +11.3% |
| Total Estimated Return Loss | $13M | +9.7% |
| Average Satisfaction Score | 3.28/5 | 0.0% |

### Business Insights

- Average Satisfaction Score by Gender
- Customer Satisfaction & Units Returned by Sales Channel
- Return Rate vs. Return Loss by Region
- Units Returned by Product Type
- Number of Product Returns by Region

## 5.4 Supplier Performance & Quality

### Key Performance Indicators (KPIs)

| KPI | Value | YoY Change |
|---|---:|---:|
| Average Quality Score | 50.2% | +3.1% |
| Average Reliability Score | 65.3% | +0.07% |
| Average Return Rate | 7.4% | +2.1% |
| Average Defect Rate | 5.0% | -0.1 |

### Business Insights

- Quality vs. Manufacturing Cost
- Supplier Value Score
- Supplier Profit & Quality
- Defect Rate by Supplier
- Average Return Rate by Supplier

## 5.5 Shipping & Logistics Performance

### Key Performance Indicators (KPIs)

| KPI | Value | YoY Change |
|---|---:|---:|
| Total Shipping Cost | $262.4K | +6.7% |
| Average Shipping Cost | $176 | +0.7% |
| Average Shipping Days | 6.9 Days | -0.04% |
| Average Lead Days | 13.5 Days | -0.02% |

### Business Insights

- Regional Shipping Performance
- Order Delivery Status
- Average Shipping Days by Region
- Profit by Delivery Status
- Shipping Performance: Units & Total Cost by Product Type
- Delivery Performance by Region

---

# 6. Machine Learning & Predictive Forecasting

Machine Learning was integrated into the project to extend the analysis beyond historical reporting and provide predictive business insights.

Two independent XGBoost Regression models were developed.

### Revenue Prediction Model

Designed to forecast future revenue based on historical business patterns and time-related features.

### Profit Prediction Model

Designed to estimate future profit and support financial performance planning.

### Feature Engineering

The models incorporate:

- Monthly features.
- Seasonal features.
- Historical lag features.
- Historical observations from 2022 to 2024.

### Modeling Approach

XGBoost Regression was selected to capture nonlinear relationships and patterns within historical business data.

The predictive component complements descriptive analytics by providing an additional perspective for future business planning.

---

# 7. Key Business Findings

The analysis revealed several important business performance indicators:

| Business Metric | Finding |
|---|---|
| Total Revenue | Approximately $183M |
| Total Profit | Approximately $86M |
| Revenue Growth | +2.1% YoY |
| Profit Growth | -3.2% YoY |
| Profit Margin | 46.8% |
| Average Discount | 7.5% |
| Total Shipping Cost | $262.4K |
| Average Shipping Cost | $176 |
| Average Shipping Days | 6.9 Days |
| Average Lead Days | 13.5 Days |

### Financial Performance

Revenue increased while total profit declined, highlighting a potential profitability challenge.

This indicates the importance of evaluating discount strategies, operational expenses, and product-level profitability.

### Inventory Performance

Production volume, total stock, and units sold provide complementary perspectives for monitoring inventory performance and identifying potential stockout risks.

### Customer Experience

The increase in returned units and estimated return losses highlights the importance of monitoring product returns and customer satisfaction.

### Supplier Performance

Supplier quality, reliability, manufacturing costs, and defect rates provide a foundation for evaluating supplier performance.

### Shipping Performance

Increasing shipping expenses alongside relatively stable shipping and lead times highlight opportunities to investigate logistics cost drivers.

---

# 8. Project Workflow

The project follows an integrated analytical workflow:

1. Business Understanding
2. Data Collection
3. Data Inspection
4. Data Cleaning & Transformation
5. Exploratory Data Analysis
6. SQL-Based Analysis
7. Excel-Based Analysis
8. Business Intelligence Development
9. Dashboard Design & Visualization
10. Machine Learning Development
11. Predictive Forecasting
12. Business Insights & Recommendations

---

# 9. Repository Structure

```text
Electronics_Supplychain/
│
├── data/
│   └── electronics_supplyChain.csv
│
├── documentation/
│   ├── Final docummentation.docx
│   └── Final docummentation.pdf
│
├── excel/
│   └── Depi Project Excel.xlsx
│
├── Model/
│   ├── Analyzier & Prediction.zip
│   └── Model.md
│
├── powerbi/
│   ├── Dashboards/
│   │   ├── Overview.PNG
│   │   ├── Inventory.PNG
│   │   ├── Customer & Returns.PNG
│   │   ├── Supplier Performance.PNG
│   │   └── Shipping.PNG
│   │
│   └── Supply Chain Project.pbix
│
├── Presentation/
│   ├── Supply Chain Presentation.pdf
│   ├── Supply Chain Presentation.pptx
│   └── supply_chain_simulator.md
│
├── python/
│   ├── Supply Chain.ipynb
│   └── electronics_supplyChain_clean.csv
│
├── sql/
│   ├── Supply Chain data analysis.sql
│   └── electronics_supplyChain.bak
│
└── Tableau/
    ├── Dashboards/
    └── Supply Chain Dashboards.twbx
```

---

# 10. Project Deliverables

The repository includes:

- Raw and cleaned datasets.
- SQL scripts and database backup.
- Python analytical notebooks.
- Machine Learning resources.
- Excel analysis workbook.
- Power BI dashboards and project file.
- Tableau dashboards and packaged workbook.
- Technical documentation.
- Final project presentation.

---

# 11. Business Recommendations

Based on the analytical findings, several improvement opportunities can be considered:

**Profitability Management**

Investigate the factors contributing to declining profit despite revenue growth, with particular attention to discount strategies and operational expenses.

**Inventory Optimization**

Monitor inventory levels, stockout risk, and product demand to support more effective stock allocation.

**Customer Experience Improvement**

Investigate product return patterns and customer satisfaction indicators to identify potential improvement opportunities.

**Supplier Evaluation**

Monitor supplier quality, reliability, manufacturing costs, and defect rates to support supplier assessment.

**Shipping Cost Optimization**

Investigate increasing shipping expenses and evaluate regional logistics performance to identify potential cost-saving opportunities.

**Predictive Business Planning**

Integrate revenue and profit forecasts into business planning and performance monitoring.

---

# 12. Conclusion

This project demonstrates an integrated approach to Electronics Supply Chain Analytics by combining data preparation, exploratory analysis, business intelligence, and predictive modeling.

Through five dedicated analytical dashboards, the solution provides visibility into financial performance, inventory efficiency, customer experience, supplier quality, and logistics operations.

By connecting operational metrics with financial indicators and predictive insights, the project demonstrates how data analytics can help organizations understand business performance, identify operational challenges, and make more informed strategic decisions.

---

# Author

**Mohamed Hany**

Data Analyst | SQL | Python | Excel | Power BI | Tableau | Machine Learning

GitHub: [MohamedHany199](https://github.com/MohamedHany199)

Project Repository: [Electronics Supply Chain](https://github.com/MohamedHany199/Electronics_Supplychain)

---

**Project Domain:** Electronics Supply Chain Analytics

**Project Type:** End-to-End Data Analytics & Machine Learning

**Core Focus:** Business Intelligence, Operational Analytics, Financial Performance, Predictive Forecasting
