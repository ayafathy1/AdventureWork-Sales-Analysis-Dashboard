# AdventureWork-Sales-Analysis-Dashboard
An interactive Power BI dashboard analyzing sales performance, growth trends, tax impacts, and territory breakdowns using AdventureWorks SQL Server database (DirectQuery) and import mode (Dual storage mode is used).
# 📊 Tools Used:
•Power BI (DirectQuery Mode)

•Power Query

•DAX

•SQL Server (AdventureWorks 2022)

•Tooltip

•DrillThrough & Drill Down

# 📄 Data Source:
•AdventureWorks2022.bak

# ⚙️ Data Preparation:
•Connected to AdventureWorks database via DirectQuery Mode

Imported these views:
•Sales.SalesOrderHeader

•Sales.SalesOrderDetail

•Sales.vSalesPerson (view)

•Sales.SalesTerritory

•Purchasing.ShipMethod

•Production.Product

•Production.ProductSubcategory

•Production.ProductCategory

•Created Dates Table using DAX(Power Query)

Built a clean star schema data model

# 📈 Measures Created:
•No. Orders

•Total Subtotal

•Total Tax

•Total Freight

•Total Due

•No. Quantity

# 📊 Visualizations & Features:
Charts:

•No.orders by ship method

•No.orders and total due by Territory

•No.orders by Top 10 salespersons

•No.orders by status 

•quantity by categoary name

# 🎨 Creative Design Features:
Clean modern layout

Consistent color theme

Performance-optimized in DirectQuery mode

Tooltip toggle experience

# 📎 Project Files:
AdventureWorks_Dashboard.pbix

AdventureWork Dashboard.png

# 📌 Notes:
AdventureWorks is a simulated enterprise sales database widely used for corporate reporting and analytics demos.

This project demonstrates advanced Power BI capabilities including tooltip, drillthrough , drill down .
