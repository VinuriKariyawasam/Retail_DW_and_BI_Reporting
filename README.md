

# Retail Data Warehouse & Business Intelligence Reporting

A comprehensive BI solution leveraging Microsoft's data platform for analytics and reporting.

## 📌 Overview
- This project demonstrates a complete BI solution using SQL Server Data Tools (SSDT), SSAS, Excel, and Power BI. It includes:

- Data Warehouse Design: ETL pipeline to populate dimension and fact tables from source systems.

- SSAS Cube: Multidimensional model with hierarchies, measures, KPIs, and user roles.

- Excel Reports: OLAP operations such as drill-down, roll-up, slice, and dice using PivotTables.

- Power BI Dashboards: Visual reports with matrix views, cascading filters, drill-down, and drill-through navigation.

- Tools Used: SQL Server, SSIS, SSAS, Visual Studio, Power BI Desktop, Power BI Service.


## 🛠️ Tech Stack
- SQL Server
- SSIS
- SSAS
- Visual Studio
- Power BI Desktop
- Power BI Service

## 🔄 Implementation Workflow

Source Systems → (Extracted via SSIS) → Staging Area
Staging Area → (Transformed via SSIS) → Data Warehouse
Data Warehouse → (Modeled in SSAS) → OLAP Cube
OLAP Cube → (Used in):
Excel Pivot Tables → Operational Reports
Power BI Dashboards 
