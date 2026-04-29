📊 DAX Depo – Advanced DAX Calculations in Power BI

This project focuses on building a backend data model and advanced analytical calculations using DAX in Power BI, without relying on standard visuals (except Matrix).

🚀 Objective

Develop a robust data model to analyze Sales and Returns performance using pure DAX logic, enabling deeper insights into KPIs and business metrics.

📂 Dataset Tables
Sales_Fact
Returns_Fact
Customer_Dim
Product_Dim
Date_Dim
Region_Dim
⚙️ Key Implementations
🔹 Calculated Columns
Profit = SalesAmount - Cost
Return Flag (Returned / Not Returned)
Customer Full Name (First + Last Name)
🔹 Measures
Total Sales
Total Cost
Total Profit
Return Rate (%)
Average Sales per Transaction
🔹 Time Intelligence
Year-over-Year Sales Growth
Month-over-Month Sales Difference
Running Total using CALCULATE & DATESBETWEEN
🔹 Advanced DAX Usage
Filter Context: ALL(), FILTER(), CALCULATE()
Iterators: SUMX(), AVERAGEX()
Logical Functions: IF(), SWITCH()
Aggregations: SUM(), AVERAGE(), COUNTX()
Relationships: RELATED()
📊 Output Constraint

All insights are displayed only using Matrix visuals, grouped by:

Region
Month
Product Category
Customer Segment

(No charts, no shortcuts — pure analytical modeling.)

🎯 What This Project Proves
Strong understanding of DAX fundamentals + advanced concepts
Ability to handle filter context and time intelligence correctly
Clean data modeling mindset (not just dragging visuals)
