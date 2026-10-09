# 📊 Production Analytics Dashboard

An interactive **Production Analytics Dashboard** developed using Microsoft Power BI, SQL Server 2019, and DAX.

**Portfolio project:** All production data and results are **synthetic** and do not represent a real company.

The dashboard provides insights into production performance, planned vs. actual costs, downtime, and quality metrics.

## 🛠️ Technologies
- Microsoft Power BI
- Microsoft SQL Server 2019
- DAX
- Data Modeling
- Business Intelligence

## 📈 Key Features
- Production KPI monitoring
- Planned vs. actual production analysis
- Production cost analysis
- Downtime and quality monitoring
- Interactive year and month filters
- Dynamic chart titles

The dashboard provides an overview of production performance based on synthetic data for 2025.
📈 KPI	              📊 Value	              Description
🎯 Planned Production	775,624	Target production volume
🏭 Actual Production	750,701	Total completed production
✅ Plan Achievement	96.79%	Percentage of production target achieved
📉 Production Variance	−24,923	Difference between actual and planned production

## 📊 Dashboard Preview
<img width="1046" height="591" alt="Dashboard_ProductionAnalytics" src="https://github.com/user-attachments/assets/83c6d838-9e7e-41c3-8334-7c638c3b4645" />

## 📁 Project Files

The repository includes the Power BI Desktop (`.pbix`) file for exploring the report, data model, DAX measures, and visualizations.

## 🗂️ Data Model

The report uses a production fact table (`FactProdukcja`) connected to a date dimension (`DimData`) through `DataID`, enabling consistent time-based analysis.
<img width="866" height="542" alt="obraz" src="https://github.com/user-attachments/assets/3fadd1c3-66e6-40f2-895e-2f93321bfba4" />


## 📌 Data Information

This portfolio project uses **synthetic production data** for demonstration purposes. The dashboard interface is in Polish.

A local SQL Server connection may need to be reconfigured to refresh the data.

