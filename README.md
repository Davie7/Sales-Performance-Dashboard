# Sales Performance Dashboard (2023 vs 2024)

This project showcases a fully interactive **Sales Performance Dashboard** built in **Microsoft Excel**, designed to transform raw transactional data into meaningful insights and decision-ready visualizations.  
The dashboard presents key metrics such as Sales, Quantity, Cost, Profit, YoY performance, regional distribution, and product-level trends — all dynamically controlled through slicers and automated calculations.

---

## Dashboard Preview

![Sales Performance Dashboard](https://github.com/Davie7/Sales-Performance-Dashboard/blob/main/sales_performance_dashboard.png)

---

## Files in This Repository

- **Raw Dataset:**  
  ➤ [Freedom_Analytics_Dataset.xlsx](https://github.com/Davie7/Sales-Performance-Dashboard/blob/main/Freedom_Analytics_%20Dataset.xlsx)

- **Completed Project Workbook:**  
  ➤ [Freedom_Analytics_Sales_Performance.xlsx](https://github.com/Davie7/Sales-Performance-Dashboard/blob/main/Freedom_Analytics_%20Sales%20Performance.xlsx)

- **Dashboard Image:**  
  ➤ `sales_performance_dashboard.png`

---

## Project Objective

The goal of this project was to:

- Build an **interactive, insight-driven dashboard** using Excel Pivot Tables & Pivot Charts.  
- Analyze year-over-year performance for Sales, Quantity, Cost, and Profit.  
- Visualize trends over time, across regions, and across product categories.  
- Create a visually compelling dashboard inspired by modern BI tools like Power BI or Tableau.  
- Apply clean design, navigation features, and strong data storytelling principles.

---

## Data Preparation & Transformation

Before analysis, the raw dataset underwent structured preparation:

### ✔ Conversion to Excel Table  
The dataset was converted to an **Excel Table** (`Ctrl + T`) for dynamic referencing and easier pivoting.

### ✔ Date Breakdown  
Using the `TEXT()` function, the **month** (`mmm`) and **year** (`y`) were extracted into new fields, enabling:

- Monthly trend analysis  
- Year-over-year comparisons  
- Time-based grouping in Pivot Tables

### ✔ KPI Calculations  
A new **Profit** metric was defined as:

```

Profit = Sales – Cost

```

This was implemented using a **PivotTable Calculated Field**.

### ✔ Year-on-Year Growth  
YoY % Change was computed using:

```

(Current Year – Previous Year) / Previous Year

```

This provided instant context on performance changes.

### ✔ Dynamic Indicators  
Using the `IF()` function, performance emojis were added:

- ▲ for positive YoY growth  
- ▼ for decline  

Custom number formatting was applied for clean visuals (`0.0,` etc.).

---

## Dashboard Development

### Layout & Design
A dedicated dashboard sheet was created with:

- Removed gridlines  
- Rounded rectangular shapes for KPI cards  
- A modern, dark-themed BI aesthetic  
- Color palette extracted using an image color-picker  
- Consistent spacing and alignment for a professional layout

### Pivot Charts (Interactive)
The dashboard incorporates:

- **Monthly Revenue Trend (2023 vs 2024)**  
- **Product-wise Sales Breakdown** (Laptop, Monitor, Printer)  
- **Regional Sales Distribution** (North, South, East, West)  
- **Mini KPI Trendlines** within the KPI cards

2023 data was styled using a **transparent variant** of the 2024 color to maintain the visual hierarchy.

### Interactivity
The dashboard includes:

- **Category-based Slicers** (e.g., Electronics, Accessories)  
- **Report Connections** linking slicers to *all* Pivot Tables  
- **Navigation Icons** linked to:
  - Data Sheet  
  - Calculation Sheet  
  - Dashboard Home  

The `TODAY()` function was used to dynamically display the current date.

---

## Key Insights

- **Strong YoY performance** across KPIs (e.g., 30% growth in Sales, 34% in Profit).  
- Product category analysis revealed notable contributions from **Monitors and Laptops**.  
- **Regionally**, the East and West performed strongest in 2024.  
- Monthly trends highlight significant spikes in mid-year sales.  
- Costs remained controlled relative to sales growth, improving overall profitability.

---

## Conclusion

This Sales Performance Dashboard demonstrates end-to-end Excel analytics skills:

- Data cleaning & transformation  
- KPI development  
- Pivot Table modeling  
- Dashboard structuring & design  
- Dynamic interactivity using slicers  
- Clear storytelling through visuals  


Just let me know!
```

---

If you want this shortened or made more “portfolio-style storytelling,” I can rewrite it too.
