# Amazon Last Mile Delivery Performance Analysis Excel
An end-to-end Excel analytics project analyzing Amazon last-mile delivery performance. The project cleans raw delivery data using Power Query and builds a KPI-driven dashboard to evaluate on-time delivery, delay drivers, and operational efficiency across area, traffic, and vehicle types.

## 🎯 Objectives
- Measure delivery performance using key KPIs (On-time %, Average Delay, Average Speed).
- Analyze how Area, Traffic conditions, and Vehicle type impact delivery outcomes.
- Provide a clear, business-ready dashboard for operational insights and SLA monitoring.

## 📊 Key KPIs
- Total Deliveries: 43,648  
- On-Time Delivery %: 48.8%  
- Average Delay (minutes): 5  
- Average Speed (km/h): 17.2  

## 🔍 Dashboard Insights (Examples)
- On-time delivery performance varies significantly by *area type* (Metropolitan, Urban, Semi-Urban, Other).
- Traffic conditions strongly influence delays, with traffic jams causing the highest average delays.
- Vehicle type shows performance differences, highlighting efficiency variations across motorcycle, scooter, and van deliveries.

## 🛠 Features
- Power Query used for data cleaning and transformation (repeatable ETL process).
- KPI Summary Sheet for centralized performance metrics.
- Pivot Tables & Pivot Charts to compare delivery performance across dimensions.
- Parameter control (SLA_Minutes) to simulate SLA threshold impact.
- Data Dictionary documenting business meaning of key columns.

## 🧰 Tools Used
- Microsoft Excel  
- Power Query (ETL)  
- Pivot Tables & Pivot Charts  
- KPI calculations (On_Time_Flag, Delay_Minutes, Speed_KMPH)

## 📁 Workbook Structure
- 00_Raw_Amazon_Delivery_Dataset (Raw source data)  
- 01_Clean_Data (Cleaned output from Power Query)  
- 02_Data_Dictionary_Sheets (Column definitions and business context)  
- 03_Parameter (SLA threshold control)  
- 04_KPI_Summary_Sheet (KPI tables and pivot outputs)  
- 05_Dashboard (Final dashboard view)  

## ▶️ How to Use
1. Download the Excel file from this repository.
2. Open in Microsoft Excel (enable editing if prompted).
3. Go to Data → Refresh All to update Power Query and pivot tables.
4. Review KPIs and charts on the Dashboard sheet.
5. To test SLA impact, update SLA_Minutes in the 03_Parameter sheet and refresh.

## ⚠️ Notes / Limitations
- Metrics depend on source data quality; missing values may appear as blanks.
- Pivot-based dashboards require refresh after data updates.

## 🚀 Future Improvements
- Add additional dimensions (Weather, Time of Day) with cleaner category handling.
- Build time-based trend analysis (daily / weekly / monthly).
- Add anomaly flags for extreme delays and outliers.

## 📸 Screenshot
![Dashboard view 1](Screenshots/Screenshot%20(1).png)
