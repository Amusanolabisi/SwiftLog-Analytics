# SwiftLog Logistics Supply Chain Analytics (Week 5, Data Analytics)
AnalystLab Africa Experience Lab | Author: Olabisi Amusan

## Overview
A 5-page Power BI solution for SwiftLog Logistics Limited covering executive KPIs,
customers, inventory and warehouses, shipments and delivery, and suppliers and products.

## Folder structure
Data/ original CSV files
Dashboard/ SwiftLog_Analytics.pbix
Report/ Executive_BI_Report.pdf, Dashboard_Screenshots.pdf
Presentation/ Executive_Presentation.pptx
Images/ dashboard and data model screenshots
References/

## Tools
Power BI Desktop, Power Query, DAX

## Method
1. Imported 11 CSV files; cleaned in Power Query (types, trimming, dates,
   Month/Year/Quarter, duplicate removal, inventory grouping).
2. Built relationships (star-style model).
3. Created 25+ DAX measures (revenue, orders, delivery, inventory, returns, retention).
4. Built 5 report pages with slicers, navigation, conditional formatting,
   a What-If parameter, dynamic titles, drill-through, tooltips, bookmarks and a mobile layout.

## Key assumptions
- Revenue = Quantity x UnitPrice, excluding cancelled orders.
- On Time = DelayDays 0 (source Status contradicts DelayDays on 1,203 shipments).
- Warehouse capacity is a What-If assumption (no capacity in the data).
- Supplier performance not scored: no supplier link in the data.
- Return rate by product is estimated: Returns has no ProductID.

## Key findings
Revenue N14.44M; on-time 12.22%; average delay 3.57 days; return rate 9.46%;
32.5% of orders cancelled; inventory turnover 0.08.

## Status
Dashboard polish in progress; final .pbix will be re-uploaded.
