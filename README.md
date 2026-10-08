**📊 SUPERSTORE SALES DASHBOARD**

**Project Overview**

This project is an interactive **Superstore Sales Dashboard** developed using **Microsoft Power BI**. The dashboard analyzes sales performance, profitability, orders, customer segments, product categories, shipping methods, and monthly sales trends.

The main objective of this project was to transform a sales dataset into an interactive dashboard that provides clear **business insights and performance metrics**.

**🛠️ TOOLS & TECHNOLOGIES**

• Microsoft Power BI
• DAX
• Data Visualization
• Data Analysis

**📁 DATASET**

The Superstore dataset contains sales and order-related information, including:

• Order ID
• Order Date
• Ship Date
• Ship Mode
• Customer ID
• Customer Name
• Segment
• Region
• Category
• Sub-Category
• Product Name
• Sales
• Quantity
• Discount
• Profit

**🔄 PROJECT WORKFLOW**

**1. Data Import & Understanding**

• Imported the Superstore dataset into Power BI.
• Reviewed the available columns and identified the fields required for analysis.
• Used important fields such as Sales, Profit, Order ID, Order Date, Category, Sub-Category, Segment, and Ship Mode.

**2. DAX Measures**

Created the following DAX measures:

**Total Sales**

Total Sales = SUM(Superstore[Sales])

**Total Profit**

Total Profit = SUM(Superstore[Profit])

**Total Orders**

Total Orders = DISTINCTCOUNT(Superstore[Order ID])

**Profit Margin**

Profit Margin = DIVIDE([Total Profit], [Total Sales])

The Profit Margin measure was formatted as a percentage and displayed as **11.3%** in the dashboard.

**📈 DASHBOARD FEATURES**

**KPI Cards**

• Total Sales
• Total Profit
• Total Orders
• Profit Margin

**Monthly Sales Trend**

Created a **monthly sales trend** to understand how sales performance changes over time.

**Category & Sub-Category Analysis**

Analyzed sales performance across different product categories and sub-categories, helping identify differences in product-level sales contribution.

**Interactive Slicers**

Added interactive slicers for:

• Date
• Category
• Segment
• Ship Mode

These slicers allow users to filter the dashboard and analyze specific parts of the business.

**💡 KEY INSIGHTS**

Added a **Key Insights** section to highlight important observations from the dashboard, including:

• Category and sub-category sales performance
• Customer segment contribution
• Monthly sales variations
• Profitability patterns
• Relationship between discounts and profit

**🎨 DASHBOARD IMPROVEMENTS**

The dashboard was refined to improve readability and presentation by:

• Using proper **Card visuals** for KPIs.
• Formatting Profit Margin as **11.3%** instead of 0.113.
• Changing the sales trend from yearly to **monthly analysis**.
• Adding four interactive slicers.
• Reducing unnecessary empty space.
• Aligning and resizing visuals consistently.
• Applying a consistent **2–3 color theme**.
• Adding a Key Insights section.
• Fixing title overlap and removing unnecessary text.

**🔎 KEY FINDINGS**

The dashboard helped identify:

• Overall sales and profit performance.
• An overall **profit margin of approximately 11.3%**.
• Monthly variations in sales performance.
• Differences in sales contribution across categories and sub-categories.
• Sales performance across different customer segments.
• The relationship between discounts and profitability.
• The contribution of different shipping methods to sales performance.

**🎯 SKILLS DEMONSTRATED**

• Power BI Dashboard Development
• DAX Measures
• Data Analysis
• Data Visualization
• KPI Creation
• Interactive Slicers
• Business Insights
• Dashboard Formatting
• Basic Business Analytics

**🏆 PROJECT OUTCOME**

The final result is an **interactive and visually organized Power BI dashboard** that converts raw Superstore sales data into meaningful business information.

Users can filter the dashboard using different slicers and quickly understand **sales, profit, orders, profitability, category performance, customer segments, and monthly trends**.

This project demonstrates my ability to use **Power BI and DAX to analyze data, create meaningful visualizations, and communicate business insights through an interactive dashboard**.
