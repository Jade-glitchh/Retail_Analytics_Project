# Retail Analytics Dashboard — Global Superstore


## Dashboard Preview

![Power BI Dashboard](dashboard.png)

### End-to-End Data Analytics | Python | Power BI | Business Intelligence

This project analyzes the **Global Superstore** dataset to uncover trends in sales, profit, discounting, and regional performance.
It demonstrates an end-to-end data analytics workflow — from cleaning and transformation in Python to interactive visualization in Power BI.

---

## Project Objectives

- Clean and prepare real-world retail data for analysis.
- Create business KPIs that summarize company performance.
- Build an interactive **Power BI dashboard** to visualize insights.
- Support data-driven decisions on sales, profitability, and customer behavior.

---

## Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **Power BI:** Data modeling, interactive visuals
- **Jupyter Notebook:** Exploratory data analysis & documentation

---

## Project Steps

### Data Loading & Exploration
- Imported the **Global Superstore dataset** into a Pandas DataFrame.
- Performed an initial exploration using `.info()`, `.describe()`, and `.value_counts()` to understand the data structure.

### Data Cleaning
- Removed duplicates and handled missing values.
- Standardized **category** and **region** names for consistency.
- Converted date columns to proper datetime format.
- Ensured no missing values in key fields like **Sales**, **Profit**, and **Region**.
- Added a new calculated column where necessary.

### Power BI Integration
- Imported the cleaned dataset into Power BI.
- Created key metrics (using DAX where needed):
- **Total Sales**
- **Total Profit**
- **Average Discount**
- **Order Count**

### Visualization
Built an interactive Power BI dashboard featuring:
- **Sales by Region** 
- **Profit by Category**
- **Sales Trend over Time**
- **Profit vs Discount** 
- **Interactive Filters (Slicers):** Region, Category, Segment

### 5Design & Presentation
- Applied a consistent **color palette** and clean layout.
- Added KPI cards at the top for Total Sales, Profit, and Discount metrics.
- Included descriptive titles and labels for clarity.

---

## Key Insights

- **Sales vs Profit:** Certain product categories drive high sales but low profits due to heavy discounting.
- **Regional Performance:** Some regions consistently outperform others in both sales and profitability.
- **Discount Sensitivity:** High discount rates often correlate with reduced profit margins.
- **Customer Segmentation:** Business customers generate steady profit with lower discount sensitivity.


---

##  Outcome

This project showcases practical, business-ready data analytics skills:
- Data Cleaning & Transformation with Pandas
- Visualization & Storytelling with Power BI
- KPI Development & Business Insight Generation
