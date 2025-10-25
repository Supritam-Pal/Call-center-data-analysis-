
**Call Center Performance Dashboard**
🚀 Overview
This project features a comprehensive Call Center Performance Dashboard designed to provide real-time and historical insights into call center operations, customer satisfaction, and representative performance.

The dashboard allows managers and stakeholders to quickly monitor key operational metrics, identify trends, and make data-driven decisions to optimize service quality and efficiency.

**📊 Key Metrics & KPIs**
The dashboard focuses on the following primary Key Performance Indicators (KPIs) and metrics, derived from the raw call data:

Metric	Description
Call Count	Total number of calls recorded in the period.
Total Duration	The sum of all call durations (a measure of operational load).
Average Rating (Avg. Rating)	The mean customer satisfaction rating (on a scale of 1-5).
5* Calls	Count of calls that received the highest satisfaction rating (5 stars).
Total Purchase Amount	The aggregate value of purchases made during the calls (if applicable).
Performance by Representative	Breakdown of metrics by individual representatives (R01 to R05), including their call volume rank and amount rank.
Demographic Breakdown	Call and amount volume segmented by City, Gender, and Age.

Export to Sheets

**📁 Data Source**
The dashboard is powered by underlying data extracted from the following files, which collectively form the complete data model:

Call center dashboard.xlsx - Data.csv: Contains the raw, call-level data, including Call number, Customer ID, Duration, Representative, Date of Call, Purchase Amount, and Satisfaction Rating.

Call center dashboard.xlsx - Pivots.csv: Contains aggregated data and pivot tables used to calculate the primary KPIs and various slicers (e.g., by month, day of week, city).

Call center dashboard.xlsx - Customer Centre Report.csv: Contains a detailed summary report, likely for specific customer or representative analysis.




**⚙️ Setup and Usage**
This dashboard was originally created in Microsoft Excel (or a similar tool like Power BI/Tableau, based on the .xlsx origin).

**Prerequisites**
Microsoft Excel or compatible spreadsheet software (if the dashboard is an Excel workbook).

Access to the original data source files.

**Viewing the Dashboard**
Open the Dashboard File: Locate and open the primary dashboard file (e.g., Call center dashboard.xlsx).

**Ensure Data Connection:** Verify that the pivot tables and charts are correctly connected to the data tabs/files (like the CSV extracts provided).

**Use Slicers:** Utilize the interactive filters (slicers) on the dashboard to segment the data by Representative, City, Time Period (Month/Day), or other dimensions to drill down into performance.
