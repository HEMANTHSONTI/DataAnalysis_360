# DataAnalysis_360
Created multiple dashboards and tables in Power BI to analyze data. The project involved several stages, including data pre-processing, cleaning, and visualization.

## Project Overview
AtliQ Hardware, a rapidly growing company, is adopting Power BI for data analytics to achieve a competitive advantage. This project offers insights into finance, sales, marketing, and supply chain operations to foster data-driven decision-making.


## Technology Stack
- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for report optimization)

## Key Takeaways
- Defining project goals and stakeholder expectations
- Creating calculated columns and measures using DAX
- Enhancing user experience with bookmarks and navigation
- Preventing zero-division errors using the DIVIDE function
- Implementing dynamic titles and KPI indicators
- Applying conditional formatting for better visualization
- Data validation 
- Publishing and automating report updates in Power BI Services
- Managing workspaces, access permissions, and collaboration

## Business Metrics & Key Terms
- **Revenue Metrics:** Gross Price, Net Invoice Sales, Gross Margin, Net Sales, Net Profit
- **Cost Components:** COGS (Cost of Goods Sold), Pre/Post-Invoice Deductions
- **Performance Indicators:** YTD (Year to Date), YTG (Year to Go)
- **Sales Channels:** Direct Sales, Retailers, Distributors
- **Customer Segments:** Consumers, Businesses

## Company Background
AtliQ Hardware, a global computer hardware and accessories provider, operates through Retailers, Direct Sales, and Distributors. Because of losses in the U.S. market, the company is investing in data analytics for better strategic planning.

## Project Kickoff: Key Questions
- **What is the main objective of this dashboard?**
- **What is the project timeline?**
- **Are stakeholder previews required?**
- **What expectations and concerns do stakeholders have?**
- **Who are the primary dashboard users?**
- **What potential challenges might arise?**
- **What data and resources are needed?**
- **Are there design or visualization preferences?**

## Data Structure Overview
Data is categorized into:
- **Dimension Tables** – Static details about customers, markets, and products
- **Fact Tables** – Transactional data for analysis

### Key Datasets
#### **Customer & Market Data (gdb041)**
- **dim\_customer**: 75 customers across 27 markets, operating via Brick & Mortar and E-commerce
- **dim\_market**: 27 markets grouped into 7 sub-zones and 4 regions (APAC, EU, NAN, LATAM)
- **dim\_product**: Product classifications – Peripherals, Accessories, PCs, Networking, and Storage

#### **Sales & Forecast Data**

- **fact\_forecast\_monthly**: Forecasted demand for inventory optimization
- **fact\_sales\_monthly**: Actual sales data for performance tracking

#### **Cost & Pricing Data (gdb056)**

- **freight\_cost**: Market-wise shipping and transportation costs
- **gross\_price**: Product pricing details
- **manufacturing\_cost**: Production costs per product and year
- **pre\_invoice\_deductions**: Customer-specific deductions before invoicing
- **post\_invoice\_deductions**: Additional deductions after invoicing

## Data Integration into Power BI
Data is extracted from **MySQL** and imported into Power BI. Proper structuring ensures efficient performance and accuracy.

## Data Modeling & Report Optimization
A well-structured data model is critical for efficient report performance. Poor modeling can impact accuracy and speed. Key considerations include:
- Establishing optimized data relationships
- Ensuring efficient query execution
- Enhancing visualization and interactivity
  
