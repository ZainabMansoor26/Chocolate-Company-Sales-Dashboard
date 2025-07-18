# Chocolate-Company-Sales-Dashboard
This project is a Power BI sales dashboard for Chocolate company. It offers insights on sales, costs, profits, and product and salesperson performance, with visualizations, data modeling, and DAX measures.
Overview
This project presents a Power BI sales analytics dashboard for the chocolate company.Power BI is a powerful data visualization platform that enables users to transform raw data into insightful reports, share results easily, and collaborate effectively. After conducting thorough data analysis, cleaning, and data wrangling in Excel, the dataset was prepared for visualization. The dashboards provide comprehensive insights into sales performance, shipment distribution, and product profitability.
• Data Model
    ◦ Describe the underlying data setup, noting that it uses a simplified star schema.
    ◦ Five tables Used: a central fact table called 'shipments' and four dimension tables: 'salesperson', 'product', 'geography', and 'calendar' (or date).
    ◦ Explain that the 'shipment' table has one row per shipment, detailing salesperson, product, geography, date, sales amount, and boxes shipped.
• Key Measures & KPIs
    ◦ Primary Key Performance Indicators (KPIs) and measures calculated in the dashboard are:
        ▪ Total Sales (Total Revenues)
        ▪ Total Boxes
        ▪ Total Shipments (Count of rows in shipments table)
        ▪ Total Cost (Calculated based on boxes and cost per box from product table)
        ▪ Total Profit (Total Sales minus Total Costs)
        ▪ Profit Percentage
        ▪ Low Box Shipments Count (Shipments with less than 50 boxes)
        ▪ Low Box Shipments Percentage (LBS count divided by total shipments)
        ▪ Month-on-Month Changes for key metrics like sales, boxes, costs, profit, and shipments.
        ▪ Latest Month Sales and Latest Month-on-Month Sales Change for card visuals.
• Dashboard Features
    ◦ Interactive KPI Cards: Displaying key measures with month-on-month change context and conditional formatting for negative values. Icons are also used for visual identification.
    ◦ Dynamic Trend Analysis: A line chart that allows users to switch between different measures (Sales, Boxes, Shipments, Costs, Profit, Profit Percentage) using a field parameter slicer.
    ◦ Shipment Distribution (Histogram): Visualizing the spread of shipments by box bins using a column chart and a zoom slider. Includes Low Box Shipments analysis.
    ◦ Detailed Performance Tables: Two tables showcasing performance:
        ▪ Salesperson Performance: Details total sales, profit, profit percentage, LBS, and a profit target indicator with conditional formatting icons (green check, amber warning, red X) and data bars.
        ▪ Product Performance: Similar detailed view for products.
    ◦ Bookmarks for View Switching: Allows users to toggle between Salesperson and Product detail tables seamlessly. Bookmarks are configured to maintain filter context (data status).
    ◦ Interactive Filters/Slicers: Custom-styled slicers for Product Category and Geography to enable deeper analysis.
    ◦ Custom Tooltips: A dedicated tool tip page providing a donut chart breakdown by geography when hovering over trend data points.
• Technologies Used
    ◦ Power BI Desktop.
    ◦ DAX (Data Analysis Expressions) for calculations and time intelligence.
    ◦ Power Query for data transformation and adding calendar columns.
• Author/Credits
    ◦ syedazainabmansoor26@gmail.com
