extract-transform-load-powerbi/
│
├── data/
│   ├── Order2022.xlsx
│   ├── Order2023.xlsx
│   ├── OrderDetails.xlsx
│
├── screenshots/
│   ├── data-profiling.png
│   ├── append-queries.png
│   ├── merge-queries.png
│
├── project-file/
│   ├── Project - Transforming Multiple Data Source.pbix
│
├── README.md

 🚀 Extract, Transform, and Load (ETL) Data in Power BI

 📚 Project Overview
This project showcases an end-to-end ETL (Extract, Transform, Load) process using Microsoft Power BI, as part of the Microsoft Power BI Data Analyst Professional Certificate.
I worked with multiple raw data sources from Adventure Works to clean, transform, append, and merge datasets,
while also identifying and removing data anomalies through data profiling techniques.

 🎯 Objectives
- Connect to multiple data sources 
- Perform data cleaning (fix errors, remove duplicates, correct anomalies)
- Profile data for validation (nulls, outliers, inconsistent types)
- Append datasets across years
- Merge detailed sales data with order-level data
- Prepare a final clean dataset for analysis

 🛠️ Tools Used
- Power BI Desktop
- Power Query Editor
- Excel
- M Language (Advanced Editor)

 🗂️ Files Included
-Order2022.xlsx: Sales orders from 2022
- Order2023.xlsx: Sales orders from 2023
- OrderDetails.xlsx: Detailed order information
- ETL_AdventureWorks.pbix: Completed Power BI project file
- Screenshots: Key transformation steps

 🧩 ETL Workflow

Step 1: Connect and Import Data
- Loaded three Excel datasets into Power BI.

 Step 2: Data Cleaning and Transformation
- Selected relevant columns: `SalesOrderID`, `ProductID`, `OrderQty`, `UnitPrice`.
- Profiled data using Column Quality, Column Distribution, and Column Profile.
- Identified and removed outliers in `UnitPrice`.
- Fixed missing or incorrect values.
- Changed data types to appropriate formats (Decimal, Whole Number, etc.).

### Step 3: Append and Merge
- Appended `Order2022` and `Order2023` into a master `Orders` table.
- Merged `OrderDetails` with `Orders` on `SalesOrderID`.
- Expanded `OrderDate` field into the final dataset.

 Step 4: Final Dataset
- Clean, consistent, and ready for data modeling and reporting in Power BI.

 📊 Key Concepts Demonstrated
- Data Profiling (valid, distinct, unique, nulls, errors)
- Advanced Transformation (column removal, type changing, anomaly detection)
- Appending Queries (combining tables across years)
- Merging Queries (joining Order Details and Orders on keys)
- Error Handling and Data Validation

📈 Outcome
The dataset was successfully cleaned, anomalies were identified and removed, and the final dataset is fully prepared for building dashboards,
KPIs, and reports to support sales insights for Adventure Works.

🌟 Certificate Context
This project was completed as part of the Microsoft Power BI Data Analyst Professional Certificate offered on Coursera.


🔗 Connect With Me
LinkedIn: www.linkedin.com/in/chinelo-nweke | Portfolio Website: https://www.notion.so/Chinelo-Nweke-Business-Intelligence-Portfolio-and-Projects-1d973825d9cb80a2a37afa4b69168658?pvs=4  | Email: Nwekecl16046@gmail.com

#PowerBI #ETL #DataCleaning #DataTransformation #BusinessIntelligence #MicrosoftPowerBI #DataAnalytics
