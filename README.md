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
  
  <img width="629" alt="model view" src="https://github.com/user-attachments/assets/4497d821-8c93-460d-8951-1f06ba0656d1" />

  Based on the requirements and mock diagrams from the stakeholders, I started to build dashboards as per their expectations.

  Initially,  when landing we can see the  Home page. From there we can navigate to any page simply by performing click action on the respective icon.

  ## Home
  <img width="727" alt="home" src="https://github.com/user-attachments/assets/e5345d6c-6f5a-4178-bf88-f3a38af86ba5" />

  ## Finance View
  <img width="738" alt="finance view" src="https://github.com/user-attachments/assets/ff3bf25d-fcd8-4a03-95ba-67c07950b1bb" />

  ## Sales View
  <img width="727" alt="sales view" src="https://github.com/user-attachments/assets/63bd7a02-0a48-46e3-9f69-0a1330f49533" />

  ## Supply Chain View
  <img width="726" alt="supply chain view" src="https://github.com/user-attachments/assets/b2c56bab-497e-4633-abdd-53806713f55f" />

  ## Marketing View
  <img width="724" alt="Marketing view" src="https://github.com/user-attachments/assets/7fac5238-9cd5-48f1-85a1-91e27ad145e8" />

  ## Executive View
  <img width="722" alt="Executive view" src="https://github.com/user-attachments/assets/ca488bc0-6cc4-4ef5-b993-0858811a306a" />

  ## Outcome
  This project provided hands-on experience in end-to-end Power BI implementation, covering data extraction, modeling, visualization, and stakeholder collaboration. These
  insights will enable AtliQ Hardware to make data-driven business decisions effectively.




  




  

