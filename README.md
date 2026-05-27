<img width="1369" height="753" alt="image" src="https://github.com/user-attachments/assets/16139b8c-06ac-4ce2-904c-07877b48c05a" />

☕ Excel Coffee Sales Data Model & Dashboard
This project transforms raw, scattered transactional data into a fully interactive, interconnected sales dashboard using Microsoft Excel. It’s an end-to-end demonstration of data cleaning, relational data modeling, and business intelligence reporting.
* To access all project elements/content file must be opened in desktop app

📦 Project Contents:

orders.csv (Fact Table): Over 1,000 historical transaction records spanning from 2019 to 2022.

customers.csv (Dimension Table): Granular contact, geographic, and loyalty data for our global customer base.

products.csv (Dimension Table): Pricing, sizing, and roast specifications for four distinct coffee types (Arabica, Excelsa, Liberica, Robusta).

From this raw data, I engineered summarized tables to feed the dashboard:

Total Sales Timeline: A cross-tabulation of monthly and yearly sales categorized by coffee type.

Top 5 Customers: A VIP leaderboard to identify our most valuable buyers (shoutout to Allis Wilmore and Brenn Dundredge!).

Country Bar Chart: Aggregated total revenue segmented by the US, UK, and Ireland.

🛠️ Core Skills & Methodology
Relational Data Modeling: Instead of relying on one massive, messy spreadsheet, I maintained a clean database structure. I linked the central Orders table to the Customers and Products tables to create a robust data model.

Advanced Lookup Functions: Automated data retrieval across sheets using complex formulas. This includes utilizing XLOOKUP for precise 1-to-1 matching and nested INDEX/MATCH functions to perform dynamic two-way lookups (e.g., matching a Product ID row with a dynamic header column).

Data Aggregation & Pivot Tables: Designed optimized Pivot Tables to summarize four years of data, creating the specific KPIs and cuts of data needed for the final presentation.

Interactive Dashboard Design: Built a front-end user interface utilizing Pivot Charts and Slicers, allowing stakeholders to seamlessly filter data by date ranges, roast types, and geographic locations.
