# Internship-task-8

## 📌 Project Objective
The objective of this task was to create a basic interactive dashboard to analyze sales performance by product, region, and month using the Superstore dataset. The goal was to build a clean interface that allows business users to identify top-performing areas at a glance.

## 🛠️ Tools Used
* **Tableau Public:** For creating the interactive dashboard and visualizations.
* **Data Source:** `Orders.csv` (Sample - Superstore Dataset).

## 📊 Dashboard Features
The dashboard includes the following key visualizations:
1.  **Monthly Sales Trend (Line Chart):** analyzing how sales fluctuate over time (Seasonality).
2.  **Sales by Region (Bar Chart):** Comparing performance across West, East, Central, and South regions.
3.  **Sales by Category (Donut Chart):** displaying the percentage share of sales for Technology, Furniture, and Office Supplies.
4.  **Interactive Filters:** A global slicer allowing users to filter the entire view by **Region**.

## 📷 Dashboard Screenshot
<img width="1654" height="794" alt="Screenshot" src="https://github.com/user-attachments/assets/14439b13-b07c-4a4f-8b12-b30235c17e41" />

## 💡 Key Insights
Based on the analysis of the dataset, the following trends were observed:

1.  **Top Performing Region:** The **West** region generates the highest revenue (~$725k), followed closely by the East region. The South region has the lowest sales volume.
2.  **Best Selling Category:** **Technology** is the dominant category, driving the majority of total sales (~$836k), followed by Furniture.
3.  **Seasonality:** Sales show a consistent upward trend towards the end of the year, with significant spikes in **November and December**, likely due to holiday shopping seasons.

## 📝 Process Documentation
1.  **Data Cleaning:** Connected `Orders.csv` to Tableau and converted the `Order Date` field to a custom "Month / Year" format.
2.  **Visualization:**
    * Created a standard Line Chart for trends.
    * Used a Sorted Bar Chart for regional comparison.
    * Implemented a Dual-Axis methodology to create a custom Donut Chart for categories.
3.  **Dashboarding:** Assembled the charts into a single view and applied a "Global Filter" on Region to ensure all charts update simultaneously.
