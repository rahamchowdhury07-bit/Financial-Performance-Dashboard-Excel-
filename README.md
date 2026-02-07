Financial Performance Dashboard (Excel)


📄 Project Overview


This project is a dynamic Financial Performance Dashboard designed to track and visualize sales metrics, profitability, and cost distributions for a beverage distribution business. It transforms over 80,000 rows of raw transactional data into actionable insights, allowing stakeholders to analyze "Net Sales" and "Gross Profit %" trends over time, by product brand, and by client type.

The dashboard features a professional UI with interactive slicers and toggleable timeframes (YTD vs. LTM), providing a high-level view of business health at a glance.

🏗️ Project Structure


The workbook is organized into five distinct layers to ensure data integrity and easy maintenance:

raw_data: The source data containing transactional records (Month, Year, Material Number, Volume, Gross Sales, etc.).

references: Contains mapping tables, such as Date tables, used to create consistent timelines across the report.

pivot_financials: The calculation engine. This sheet houses various PivotTables that aggregate raw data into manageable summaries.

tables: A staging area for final calculations. It uses Excel formulas to pull data from pivots and prepare it specifically for chart rendering.

dashboard: The final presentation layer. Includes interactive slicers, the "Net Sales and GP% Development" combo chart, and horizontal bar charts for Volume analysis.

🔍 Key Findings


Based on the current visualization (July 2020 LTM):

Seasonality: There is a notable peak in Net Sales and GP% during the June/July period, suggesting high summer demand.

Profitability: The average Gross Profit % fluctuates around the 44-45% mark, showing strong stability despite cost variations.

Distribution Channels: Supermarkets represent the largest volume driver by a significant margin, followed by the "Big-box" segment.

Cost Management: Average Discounts (-3.03%) and Distribution Costs (-3.09%) are being tracked as key KPIs to ensure margin preservation.

🛠️ Tools & Techniques Used


Data Modeling: Established relationships between time dimensions and financial metrics.

PivotTables & PivotCharts: For efficient data aggregation and multi-dimensional analysis.

Advanced Formulas: Utilized AVERAGE, SUMIFS, and dynamic references to populate the tables sheet.

Interactive UI/UX: * Slicers: Added for "Brand" filtering to allow brand-manager level views.

Timeline Logic: Implementation of LTM (Last Twelve Months) and YTD (Year To Date) logic for flexible reporting.

Data Visualization: Custom combo charts (Line + Clustered Column) and formatted bar charts for clear comparative analysis.

🚀 How to Use


Select a Brand: Use the Brand Slicer at the top of the dashboard sheet to filter the entire report for a specific product line (e.g., "Dundy Diet" or "Crocky").

Toggle Timeframe: Use the radio buttons on the left to switch between LTM (Rolling 12 months) and YTD (Cumulative year performance).

Analyze Trends: Review the center chart for the correlation between sales volume and profit margins.

Update Data: To add new data, paste new records into the raw_data sheet and click Data > Refresh All.

✍️ Author
MD.RAHAM ULLAH CHOWDHURY

Data Analyst & Excel Specialist

📢 Disclaimer

This dashboard is for demonstration purposes only. The data used is simulated to represent real-world business scenarios and does not represent the actual financial standing of any specific company.
