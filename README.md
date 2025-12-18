# PowerBI-V
This project guides me through the end-to-end process of designing a professional, interactive three-page Power BI report and publishing it to the Power BI service. I have configure visuals, apply consistent filtering with synced slicers, implement page-level filters for personalized views and explore user interactions such as cross-filtering, drill-downs and focus mode in the published report.

Report Structure
Page 1: Overview
Features the Adventure Works logo and two slicers:
Year (dropdown style, defaults to FY2020)
Region (list style)
Contains three key visuals:
Line and Stacked Column Chart: Monthly Sales (columns) and Profit Margin (line), configured to show all months—including those with no data.
Stacked Column Chart: Sales by Region Group, segmented by Product Category.
Stacked Bar Chart: Quantity sold by Product Category, with data labels and coordinated color formatting.
Page 2: Profit
Includes a Region slicer with “Select all” enabled.
A Matrix visual displays fiscal-year drill-down (Year → Quarter → Month) with metrics:
Orders | Sales | Cost | Profit | Profit Margin
Uses page-level filters (not slicers) for Product Category, Subcategory, Product, and Color to conserve space while enabling detailed filtering.
Page 3: My Performance
Simulates a personalized dashboard using a page-level filter on Salesperson (Performance) | Salesperson (e.g., Michael Blythe).
Features:
A Year slicer (dropdown, defaults to FY2019)
A Multi-row Card showing Sales, Target, Variance, and Variance Margin with enlarged callout values
Two comparative visuals:
Clustered Bar Chart: Monthly Sales vs. Target
Clustered Column Chart (duplicate, alternate view)
Key Techniques Implemented
Synced Slicers:
Year slicer synced between Overview and My Performance
Region slicer synced between Overview and Profit
Ensures consistent filtering context across pages
Visual Formatting:
Dropdown slicers for compact year selection
Data labels, color coordination, and font sizing for readability
Publishing & Interaction:
Report published to Power BI service under My Workspace
Demonstrated end-user capabilities:
Cross-filtering by selecting chart elements
Drilling into hierarchies
Using Focus mode for detailed inspection
Viewing active filters via the filter icon
Full-screen navigation
Outcome
This lab delivers a production-ready, user-friendly report that balances visual clarity, interactive exploration and business relevance—ready for deployment in enterprise analytics environments.

Prepared by: Pang Kah Hwee
December 2025
