# Pizza Sales Dashboard

### Dashboard Link: (pdf) https://drive.google.com/file/d/1PDx8_fUSRyJRJidRGSsLb9hAc4gQzMyB/view
### Dashboard Link: (pbix) https://drive.google.com/file/d/1Eo-z0lDI9OLekB3A2rn4Tt2ez4HFHyVz/view

## Problem Statement

This dashboard provides a comprehensive analysis of pizza sales data to help the business identify trends, optimize inventory, and enhance customer satisfaction. By analyzing various metrics such as sales by pizza type, order count, and revenue distribution across different periods, the business can make data-driven decisions to improve its offerings and boost profitability.

Given that certain pizza types are underperforming, the business can focus on promotional strategies or menu revisions to improve sales. Additionally, by identifying peak sales times, the business can optimize staffing and inventory to meet demand efficiently.

## Steps Followed

- **Step 1: Data Loading**
  - Loaded the pizza sales data into Power BI Desktop from a CSV file.

- **Step 2: Data Cleaning and Transformation**
  - Opened the Power Query Editor to clean and transform the data.
  - Checked "Column Distribution," "Column Quality," and "Column Profile" options in the Data Preview section.
  - Addressed any missing or erroneous values, ensuring data accuracy for analysis.

- **Step 3: Data Modeling**
  - Created relationships between different tables, such as orders, pizza types, and sales, to enable comprehensive analysis.

- **Step 4: Report Design**
  - Selected an appropriate theme to ensure a visually appealing and consistent report layout.
  - Added various visualizations to represent key metrics:
    - **Pie Chart:** Displaying the proportion of sales by different pizza types.
    - **Bar Chart:** Representing order counts by day of the week.
    - **Line Chart:** Tracking revenue trends over time.
    - **Card Visuals:** Showing total sales, average order value, and total number of orders.

- **Step 5: Filter and Slicer Implementation**
  - Implemented slicers for filtering data by pizza type and order date.
  - Enabled interactive filtering, allowing users to drill down into specific data segments.

- **Step 6: DAX Measures and Calculations**
  - Created custom measures to calculate key performance indicators (KPIs) such as total sales, average revenue per order, and most popular pizza type.
    - Example DAX Expression:
      ```DAX
      Total Sales = SUM(PizzaSales[Revenue])
      ```
    - Used DAX to create calculated columns for deriving additional insights, such as sales growth rates and customer segmentation.

- **Step 7: Final Touches**
  - Added text boxes and shapes to enhance report clarity and presentation.
  - Created tooltips for better data interpretation.



## Insights

The Pizza Sales Dashboard provides several critical insights:

### 1. Total Sales and Order Analysis
   - **Total Sales:** The dashboard reveals that the business has achieved a total revenue of **$817.86K**
   - **Order Count:** The business processed a total of 21350 orders, with an average order value of **$38.31**

### 2. Sales by Pizza Type
   - **Top-Selling Pizza:** The **Thai Chicken Pizza** Contributes to Maximum Revenue.
   - **Underperforming Pizza:** The **Brie Carre Pizza** has the lowest sales, suggesting a need for promotional efforts or menu revision.

### 3. Time-Based Analysis
   - **Busiest Months:** There are maximum orders from month of **July** and **January** .
   - **Day of the Week:** The busiest day is **Friday**, while **Sunday** sees the least orders, providing insights for targeted marketing campaigns.

### 5. Seasonal Order Peaks and Lows
   - **Monthly Order Trends:** The dashboard reveals fluctuating order trends throughout the year, with notable peaks in **May (1,853 orders)** and **July (1,935 orders)**. The months of **January (1,845 orders)**, **March (1,840 orders)**, and **August (1,841 orders)** also saw high order volumes, indicating potential seasonal factors or successful campaigns during these periods. Conversely, the lowest number of orders occurred in **September (1,661 orders)** and **October (1,646 orders)**.

## Conclusion

The Pizza Sales Dashboard offers a clear and actionable overview of the business’s performance. By leveraging these insights, the company can make informed decisions to boost sales, enhance customer satisfaction, and streamline operations.
