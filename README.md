# End-to-End Sales Data Warehouse Project

## 📌 Overview
This project was developed as part of my learning journey in Data Engineering. It demonstrates a complete BI pipeline for a Sales business case, covering data extraction, transformation, and visualization.

## 🛠️ Tech Stack
- **SQL Server**: For Data Warehouse hosting and staging.
- **SSIS (SQL Server Integration Services)**: For ETL processes.
- **Power BI**: For building interactive business dashboards.

## 🏗️ Data Architecture (Star Schema)
I implemented a **Star Schema** to optimize query performance. It consists of:
- **Fact_Sales**: Central table containing measures (Quantity, Total Price).
- **Dimension Tables**: DimProduct, DimCustomer, DimSalesMan, DimDate, and DimTime.

![Star Schema](Screenshots\PI_ERD.png)

## 🔄 ETL Process (SSIS)
The ETL pipeline handles data cleaning and historical tracking.
- **SCD Type 2**: Implemented for tracking changes in customer and product data.
- **Incremental Loading**: Used to load only new sales records.

![SSIS Process](Screenshots/اسم_صورة_الـSSIS.png)

## 📊 Dashboard
The final step was building a dashboard to track key business metrics like Total Revenue and Salesman Performance.

![Power BI Dashboard](Screenshots/اسم_صورة_الداشبورد.png)

## 🎓 Acknowledgments
This was a **Guided Project** during my training at [اسم المبادرة]. All SQL logic and ETL workflows were implemented following the instructor's best practices.
