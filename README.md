# da-task-7
Power-BI-Dashboard
Dataset Name: Global Superstore Dataset

Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Microsoft Excel (for initial data inspection)

DAX Measures Created

The following calculated measures were created to support analysis:

Total Sales

Total Sales = SUM('Global_Superstore2'[Sales])

Total Profit

Total Profit = SUM('Global_Superstore2'[Profit])

Profit Margin

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

Dashboard Visuals 1️ Sales by Category

Bar chart showing total sales across product categories

Helps identify top-performing product segments

2️ Sales by Region

Column chart visualizing regional sales contribution

Supports regional performance comparison

3️ Profit Trend Over Time

Line chart displaying profit changes over time

Useful for identifying seasonal and long-term trends

nteractive Features

Slicers added for:

Region

Segment

Year (Order Date)

All visuals and KPIs update dynamically based on slicer selections

KPI Cards

The dashboard includes key KPI cards at the top:

Total Sales

Total Profit

Profit Margin

Dashboard Design Principles

Clean and aligned layout

Consistent formatting and color theme

Clear titles and labels

Business-oriented structure similar to enterprise dashboards
