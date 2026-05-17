# Interactive Employee Performance & Efficiency Dashboard

An interactive, application-style Excel dashboard designed to track employee metrics, working hours, active engagement, and call volumes. This project utilizes advanced data transformations, dynamic PivotTables, and native form controls to deliver clear, actionable operational insights.

## 📊 Dashboard Preview
![Dashboard View](dashboard_preview.png)

## 🎯 Key Features & Technical Implementations

* **Dynamic 'Top X' Spinner Filters**: Integrated interactive numeric spinners linked directly to PivotTable filters. This allows users to dynamically toggle the display from Top 3 to Top 6 performers across different reports instantly.
* **Aesthetic UI Cleanup**: Stripped out default Excel gridlines and redundant system charts field buttons to create a clean, modern, executive-ready interface.
* **Duration Data Transformation**: Converted raw clock-time timestamps into accurate numeric decimal durations (e.g., `32.80` hours). This corrected an underlying Excel scaling bug, ensuring bar chart heights mathematically match actual hours worked.
* **Data-Driven Visualization Structure**: 
  * **Report 1 (Employee Working Hours)**: Vertical column chart showing true total hours worked per employee.
  * **Report 2 (Active with Customer)**: Proportional breakdown tracking individual employee performance metrics.
  * **Report 3 (Emp Calls Attended)**: High-to-low sorted performance metric line graph mapping total call volumes.

## 🛠️ Excel Skills & Functions Demonstrated
* **PivotTables & PivotCharts**: Built dynamic data structures pulling from raw multi-sheet transactional data.
* **Form Controls**: Implemented interactive Spinner buttons to drive user-controlled filtering.
* **Advanced Data Formatting**: Applied custom time formats (`[h]:mm:ss`) and numerical scaling factors (`=Time * 24`) to handle core business metric logic.
* **Visual Storytelling**: Styled charts with a unified color palette and eliminated clutter like default axis data labels to focus entirely on trend analysis.

## 📂 Project Structure
* `Employee_Performance_Dashboard.xlsx` - The main interactive workbook file.
* `dashboard_preview.png` - High-resolution screenshot used for portfolio documentation.

## 💡 Key Insights Captured
* **Ashok Kumar** is the top operational driver across multiple categories, contributing the highest number of working hours (**32.80 hours**) and leading customer outreach with **322 attended calls**.
* The dataset highlights clear tiers of activity, allowing operations managers to quickly spot under-utilization or standout individuals at a single glance.
