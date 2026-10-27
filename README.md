# Online Retail Data Warehouse & Power BI Analytics

An enterprise business intelligence and data warehousing solution analyzing **392,692 cleaned transaction records** from a UK-based online retail enterprise using Microsoft Power BI and advanced DAX measures.

## 📌 Business Problem
E-commerce businesses require real-time visibility into customer spending habits, international sales distribution, order volumes, and revenue trends across multiple product lines to optimize pricing and inventory allocation.

## 🚀 Key Highlights & DAX Modeling
- **Data Preprocessing:** Cleaned raw transaction logs by removing nulls, negative returns, and cancellations; engineered calculated fields (`Revenue`, `Order_Year`, `Month_Name`, `Revenue_Tier`, `Is_International`).
- **Star Schema Data Modeling:** Structured fact and dimension tables optimized for analytical query performance.
- **10 Core DAX Measures:**
  - Aggregations: `SUM`, `AVERAGE`, `COUNT`, `DISTINCTCOUNT`, `MIN`, `MAX`
  - Context Modifiers & Logic: `CALCULATE`, `FILTER`, `ALL`, `IF`
- **5 Interactive Dashboards:**
  1. **Executive Overview:** Key performance indicators (Total Revenue, Transactions, Customer Count).
  2. **Sales Trend Analysis:** Monthly and seasonal growth patterns (2010–2011).
  3. **Category & Product Performance:** Top-selling SKUs and Pareto revenue breakdown.
  4. **Geographical Distribution:** UK domestic vs. international market revenue distribution.
  5. **Transaction Drilldown:** Filterable granular order analysis.

## 📂 Repository Contents
```
Online-Retail-Data-Analysis-/
├── DWM FINAL PROJECT.pbix             # Full interactive Microsoft Power BI workbook
├── online_retail_cleaned_dataset.xlsx  # 392,692 cleaned e-commerce transactions
├── Report DWM.pdf                      # Comprehensive academic project report
└── README.md                           # Documentation
```

## 👩‍💻 Author & Attribution
- **Bhumika R** (Reg No: 2411021240026)  
- Course: Data Warehousing and Mining (DWM), BCA Semester IV  
- Alliance University, Bengaluru.
