# 📊 Final Project – Sales & Customer Intelligence Dashboard

## 📌 Project Overview
This Power BI project focuses on analyzing **Sales, Returns, Customer Behavior, and Regional Performance** over the last three years. The dashboard is designed to provide actionable business insights through interactive visualizations, advanced DAX calculations, and a well-structured star schema data model.

---

## 🎯 Objectives

- Build a robust **Star Schema Data Model**
- Create advanced **DAX Measures & KPIs**
- Apply **Time Intelligence Functions**
- Design a fully interactive **Multi-Page Dashboard**
- Implement **Drillthrough, Navigation, and Mobile Layout**
- Configure **Row-Level Security (RLS)** for regional managers

---

## 📂 Dataset Information

The project uses the following tables:

| Table Name | Type |
|------------|------|
| Date_Dim | Dimension |
| Customer_Dim | Dimension |
| Product_Dim | Dimension |
| Region_Dim | Dimension |
| Sales_Fact | Fact |
| Returns_Fact | Fact |

---

## 🏗 Data Modeling

### Star Schema Design
- Created relationships using Primary & Foreign Keys
- Connected Fact and Dimension tables
- Hidden unnecessary columns
- Applied proper naming conventions

### Data Model Structure

- Sales_Fact → Date_Dim
- Sales_Fact → Customer_Dim
- Sales_Fact → Product_Dim
- Sales_Fact → Region_Dim
- Returns_Fact → Date_Dim
- Returns_Fact → Product_Dim
- Returns_Fact → Region_Dim

---

## 📈 DAX Measures

Implemented measures using:

- CALCULATE()
- FILTER()
- ALL()
- SUMX()
- COUNTX()
- AVERAGEX()
- SWITCH()

### Sample KPIs
- Total Sales
- Total Profit
- Total Returns
- Return Rate %
- Profit Margin %
- Average Order Value
- Customer Count

---

## 🧮 Calculated Columns

Created calculated columns for:

- Customer Full Name
- Profit Margin Classification
- Year-Month Formatting
- KPI Category Classification

---

## ⏳ Time Intelligence Analysis

Implemented:

- Year-over-Year (YOY)
- Month-over-Month (MOM)
- Year-to-Date (YTD)

Business Insights:
- Sales Trend Analysis
- Return Trend Analysis
- Seasonal Performance Identification

---

## 📊 Dashboard Pages

### Page 1 – Executive Summary
- KPI Cards
- Sales Trend Analysis
- Regional Performance Overview
- Return Analysis

### Page 2 – Detailed Analysis
- Product Performance
- Customer Insights
- Matrix Visuals
- Top N Products

### Page 3 – Drillthrough Page
- Detailed Customer Analysis
- Product-Level Breakdown
- Regional Insights

---

## 🎨 Visualizations Used

- KPI Cards
- Line Charts
- Bar Charts
- Donut Charts
- Matrix Visuals
- Slicers
- Drillthrough Reports
- Tooltips

---

## 🔍 Filtering & Interaction

Implemented:

- Product Slicer
- Customer Segment Slicer
- Region Slicer
- Date Slicer
- Drill Up / Drill Down
- Drillthrough Filters
- Numeric Range Parameters

---

## 🧭 Navigation & User Experience

Features Included:

- Custom Navigation Buttons
- Bookmarks
- Collapsible Slicer Panel
- Interactive Tooltips
- Conditional Formatting

---

## 📱 Mobile Layout

- Optimized dashboard pages for mobile devices
- Prioritized KPI Cards and Top N visuals
- Responsive report navigation

---

## 🔒 Security

Implemented Row-Level Security (RLS):

- Region Manager Role
- Region-wise Data Access Control

---

## 📦 Deliverables

- Power BI Report (.pbix)
- Mobile Layout Preview
- DAX Measure Documentation
- Dashboard Walkthrough

---

## 🛠 Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Excel

---

## 📁 Project Files

```text
Final Project/
│
├── Dataset/
│   └── FinalProject_Dataset.xlsx
│
├── PowerBI/
│   └── Sales_Customer_Intelligence.pbix
│
├── Screenshots/
│   ├── Executive_Summary.png
│   ├── Detailed_Analysis.png
│   └── Drillthrough_Page.png
│
└── README.md
```

---

## ✅ Key Learning Outcomes

- Star Schema Modeling
- Advanced DAX Calculations
- Time Intelligence Functions
- Interactive Dashboard Design
- Mobile Report Optimization
- Row-Level Security (RLS)
- Business Insight Generation

---

### 👨‍💻 Developed By
**Kunj Mistry**

