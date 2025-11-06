#  Banking_Domain_Analysis

## Overview

This project focuses on risk analytics in the banking and financial services sector, analyzing customer data to minimize the risk of loan defaults. By combining Python-based data analysis, SQL database operations, and Power BI visualizations, the project helps banking institutions make informed lending decisions based on applicant profiles and historical banking relationships. The analysis provides actionable insights into customer engagement, loan portfolios, and deposit behaviors.

## Problem Statement

Financial institutions face significant risks when lending money to customers. This project aims to develop a comprehensive understanding of risk analytics in banking by analyzing customer profiles, banking relationships, and financial behaviors to determine loan repayment likelihood and minimize financial losses.

## Dataset

The dataset contains comprehensive banking and client information across multiple interconnected tables:

**Tables:**
- **Banking Relationship**: Details of bank types and relationships
- **Client-Banking**: Core client financial data including loans, deposits, and accounts
- **Gender**: Customer demographic information
- **Investment Advisor**: Advisor-client relationships
- **Period**: Temporal data for time-based analysis

**Key Features:**
- Client demographics (gender, nationality, age)
- Loan information (bank loans, business lending, credit card balances)
- Deposit accounts (savings, checking, foreign currency, bank deposits)
- Banking engagement metrics (joining date, engagement duration)
- Investment advisor assignments
- Fee structures and processing charges

**Data Relationships:** Tables are interconnected using primary and foreign keys for relational analysis

## Tools & Technologies

- **Python 3.x**: Data loading, exploration, and preprocessing
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn
- **SQL**: Complex queries and data manipulation
  - Database: PostgreSQL/MySQL/SQL Server
- **Power BI**: Interactive dashboard development with DAX calculations
- **Gamma**: Professional presentation creation
- **Jupyter Notebook**: Documented analysis workflow
- **MS Word**: Detailed report documentation

## Project Workflow

### 1. Data Loading & Initial Exploration
- Imported multiple relational tables using Python Pandas
- Examined table schemas and relationships
- Identified primary and foreign key connections
- Analyzed data dimensions and structure

### 2. Exploratory Data Analysis (EDA)
- Statistical analysis of loan amounts and deposit patterns
- Distribution analysis of client demographics
- Correlation study between income levels and loan amounts
- Temporal analysis of customer engagement
- Banking relationship type analysis

### 3. Data Cleaning & Feature Engineering

**Created New Columns:**
- **Engagement Timeframe**: Timeline categorization of client banking relationships
- **Engagement Days**: Calculated days from joining date to present using DATEDIFF
- **Income Band**: Categorized estimated income (<100K as Low, <300K as Mid, >300K as High)
- **Processing Fees**: Dynamic fee calculation based on fee structure (0.05 for high fee structure)

**Data Quality Improvements:**
- Handled missing values in financial columns
- Removed duplicate client records
- Standardized date formats across tables
- Validated foreign key relationships
- Created data integrity constraints

### 4. Database Integration & SQL Analysis
- Loaded cleaned datasets into SQL database (PostgreSQL/MySQL/SQL Server)
- Designed normalized database schema with proper indexing
- Executed complex SQL queries for:
  - Customer segmentation by loan risk
  - Revenue analysis from fees and lending
  - Time-series engagement trends
  - Cross-table joins for comprehensive insights
  - Aggregated metrics by bank type and nationality

### 5. Power BI Dashboard Development

**DAX Calculations Implemented**

**i.SUM Functions**

**ii.DISTINCTCOUNT:**

**iii.SUMX (Iterative Calculations):**

**iv.DATEDIFF:**

**v.Composite Measures:**


### 6. Reporting & Presentation
- Compiled findings in detailed Word document
- Created executive presentation using Gamma
- Documented methodology, insights, and recommendations

## Key Performance Indicators (KPIs)

- **Total Clients**: Distinct count of banking customers
- **Total Loan**: Aggregate of all lending products
- **Total Deposit**: Sum of all deposit accounts
- **Total Fees**: Revenue from processing and maintenance charges
- **Engagement Length**: Average customer relationship duration
- **Loan-to-Deposit Ratio**: Risk assessment metric
- **Credit Card Utilization**: Outstanding credit card balances

## Key Insights & Results

1. **Bank Type Analysis**: Private banks have significantly more clients than public banks, indicating market preference and service quality differences

2. **Risk Profiling**: Successfully segmented clients into risk categories based on loan amounts, income bands, and deposit behaviors

3. **Nationality Insights**: Identified nationalities with highest loan amounts, enabling targeted risk assessment strategies

4. **Engagement Patterns**: Longer customer engagement correlates with higher deposit amounts and lower default risk

5. **Fee Revenue**: Calculated total processing fees providing insights into revenue generation from lending operations

6. **Account Diversification**: Clients with multiple account types (savings, checking, foreign currency) show lower risk profiles

## Business Recommendations

- **Lending Strategy**: Approve loans for applicants with strong deposit history and longer engagement periods
- **Risk Mitigation**: Implement stricter verification for high-loan, low-deposit applicants
- **Customer Retention**: Focus on engagement programs to increase customer tenure
- **Market Expansion**: Public banks should adopt private bank strategies to increase client acquisition
- **Product Bundling**: Encourage multi-account relationships for risk reduction

## Technical Highlights

- **Multi-table Relational Analysis**: Handled complex joins across 5 interconnected tables
- **Advanced DAX Calculations**: Implemented SUMX, DATEDIFF, and composite measures
- **Feature Engineering**: Created derived columns for enhanced analytical insights
- **Risk Analytics**: Applied banking domain knowledge for creditworthiness assessment
- **Interactive Dashboards**: Built 4 comprehensive dashboard pages with drill-through capabilities

## Future Enhancements

- **Predictive Modeling**: Implement machine learning for loan default prediction
- **Real-time Integration**: Connect to live banking systems for current data
- **Credit Scoring**: Develop automated credit score calculation algorithm
- **Mobile Dashboard**: Create Power BI mobile-optimized views
- **Alert System**: Implement automated alerts for high-risk loan applications
- **Customer Segmentation**: Apply clustering algorithms for advanced segmentation

## Skills Demonstrated

✅ Risk Analytics & Banking Domain Knowledge  
✅ Python Data Analysis (Pandas, NumPy)  
✅ SQL Database Design & Complex Queries  
✅ Power BI Dashboard Development  
✅ DAX Calculations & Measures  
✅ Data Cleaning & Feature Engineering  
✅ Business Intelligence & Reporting  
✅ Stakeholder Communication  

## Author

[LOKESH C]  
[lokeshlokeshc007@gmail.com]  
[LinkedIn Profile]  
[GitHub Profile]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Project Category:** Banking Analytics | Risk Assessment | Business Intelligence  
**Domain:** Financial Services | Credit Risk Management  
**Status:** Completed

**Note:** This project demonstrates end-to-end data analytics capabilities in the banking domain, from data extraction to actionable business insights.
