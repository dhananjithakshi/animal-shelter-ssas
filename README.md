# Austin Animal Center Data Warehouse and BI Solution

## Project Overview
This project involves designing and implementing a data warehouse and an OLAP cube to support multidimensional analysis of animal intake and outcome data from the Austin Animal Center dataset (October 2013 - March 2021).

The project covers:
- Data Warehouse design using a snowflake schema
- SQL Server Analysis Services (SSAS) cube creation and deployment
- Demonstration of OLAP operations (Roll Up, Drill Down, Slice, Dice, Pivot)
- Creating interactive Power BI reports connected to the SSAS cube

---

## Data Warehouse Schema
- Snowflake schema containing:
  - 6 dimension tables: DimStrayMap, DimColor, DimBreed, DimAnimal, DimSexType, DimDate
  - 1 fact table: FactAnimalEvent

---

## SSAS Cube
- Created using SQL Server Data Tools (SSDT)
- Data source and data source view (DSV) connected to the data warehouse
- Dimensions, hierarchies, and measure groups defined
- KPIs implemented for performance measurement
- Cube deployed to SQL Server Analysis Services server

---

## OLAP Operations Demonstrated
- Connection to the SSAS cube from Microsoft Excel
- Operations shown include:
  - Roll Up
  - Drill Down
  - Slice
  - Dice
  - Pivot

---

## Power BI Reporting
- Connected Power BI Desktop to the deployed SSAS cube
- Created interactive reports including:
  - Matrix report with multiple values
  - Cascading slicers for filtering
  - Drill-down reports
  - Drill-through reports
- Published reports to Power BI Service for sharing and collaboration

---

## Technologies Used
- SQL Server (Database and Analysis Services)
- SQL Server Data Tools (SSDT)
- Microsoft Excel
- Microsoft Power BI Desktop and Power BI Service

---

## How to Use

1. **Set up the Data Warehouse**  
   Create the schema and load data into SQL Server tables as per the snowflake schema.

2. **Build and Deploy the SSAS Cube**  
   Use SSDT to create the cube from the data source, define dimensions, hierarchies, and KPIs, then deploy to your SSAS server.

3. **Perform OLAP Analysis**  
   Connect to the cube via Excel for ad-hoc data exploration and apply OLAP operations.

4. **Create Power BI Reports**  
   Connect Power BI Desktop to the deployed cube and build reports using slicers, drill-downs, and drill-throughs. Publish reports to Power BI Service for access online.

---

## Notes
- Ensure you have SQL Server Analysis Services installed and configured.
- Appropriate user permissions are required for database and SSAS access.
- Power BI Service requires a Power BI Pro or Premium license for report publishing and sharing.


