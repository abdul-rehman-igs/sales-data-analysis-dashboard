
# Sales Data Analysis & Dashboard (Excel, Power BI, Python)

## **Project Overview**
This project focuses on analyzing historical sales data to extract key business insights, forecast future revenue, and present the findings through an interactive Power BI dashboard. The project is divided into three phases:

1. **Phase 1:** Data Cleaning & Initial Analysis (Python)
2. **Phase 2:** Advanced EDA & Forecasting (Python)
3. **Phase 3:** Dashboard Design (Power BI)

---

## **Objectives**
- Preprocess and clean raw sales data.
- Identify sales trends, top-performing products, and customers.
- Analyze regional and shipping mode performance.
- Forecast revenue for the next 6 months using time-series models.
- Build a professional Power BI dashboard for visualization.

---

## **Tools & Technologies**
- **Python:** Pandas, Matplotlib, Seaborn, Statsmodels
- **Power BI:** For interactive dashboards and KPIs.
- **Excel:** Initial exploration and data verification.
- **Jupyter Notebook:** For interactive data analysis.

---

## **Phase 1: Data Cleaning & Initial Analysis**
- Loaded and explored the raw dataset.
- Cleaned and formatted dates (`Order Date`, `Ship Date`).
- Filled missing values (e.g., Postal Codes).
- Created new columns: Year, Month, Month Name.
- Aggregated **monthly sales**.
- Generated:
  - `cleaned_sales_data.csv`
  - `monthly_sales.csv`
  - `monthly_sales_trend.png`

---

## **Phase 2: Advanced EDA & Forecasting**
- **Advanced EDA:**
  - Top 10 Products by revenue.
  - Top 10 Customers by revenue.
  - Sales distribution by Shipping Mode and Category.
- **Forecasting:**
  - Built a time-series model using **Exponential Smoothing**.
  - Forecasted the next **6 months of revenue**.
  - Visualized **Actual vs Forecasted Sales**.
- Exported:
  - `top_products.csv`
  - `top_customers.csv`
  - `ship_mode_sales.csv`
  - `sales_forecast.csv`
  - `monthly_revenue.csv`

---

## **Phase 3: Interactive Power BI Dashboard**
- KPI Cards: Total Sales, Total Orders, Top Product, Top Customer.
- Visuals:
  - Line Chart: Monthly Sales Trend.
  - Bar Chart: Top 10 Products.
  - Pie Chart: Sales by Category.
  - Map Chart: Sales by Region/State.
  - Forecast Chart: Actual vs Forecasted Sales.
- Filters (Slicers): Year, Region, Category, Shipping Mode.

---

## **Key Insights**
- Technology category generated the **highest revenue**, followed by Furniture and Office Supplies.
- West and East regions dominated sales.
- A few high-value products and customers drive a significant portion of revenue.
- Forecast predicts **steady revenue growth** in the next 6 months.

---

## **How to Run This Project**
### **Phase 1 & 2 (Python Notebooks)**
1. Open `Phase1_Sales_Analysis.ipynb` and `Phase2_Advanced_EDA_Forecasting.ipynb` in Jupyter Notebook.
2. Run each cell to generate cleaned data, analysis, and visualizations.

### **Phase 3 (Power BI)**
1. Open `sales_dashboard.pbix` in Power BI Desktop.
2. Interact with filters and visuals to explore insights.

---

## **Project Deliverables**
- **Notebooks:**  
  - `Phase1_Sales_Analysis.ipynb`
  - `Phase2_Advanced_EDA_Forecasting.ipynb`
- **Data Outputs:**  
  - Cleaned and aggregated CSV files in `output_phase1/` and `output_phase2/`.
- **Power BI File:**  
  - `sales_dashboard.pbix`
- **Visual Assets:**  
  - Sales trends, forecast plots, and KPI charts.

---

## **Author**
*Developed as part of a data analytics and visualization project to showcase real-world business insights using Python and Power BI.*
