# 📊 Financial Performance & Profitability Analysis Dashboard

## 📌 Project Overview

The Financial Performance & Profitability Analysis Dashboard is a data analytics project developed using **Microsoft Excel and Power BI**.

The project analyzes financial data to understand revenue, expenses, profit, profit margins, and budget performance. It presents important financial insights through interactive visualizations and KPI cards.

## 🎯 Project Objectives

- Analyze total revenue, expenses, and profit.
- Calculate overall profit margin.
- Monitor monthly financial performance.
- Compare actual revenue with budgeted revenue.
- Compare actual expenses with budgeted expenses.
- Analyze department-wise profitability.
- Identify revenue variations.
- Support data-driven business decisions.

## 🛠️ Tools & Technologies

- Microsoft Excel – Data preparation
- Microsoft Power BI Desktop – Data visualization
- DAX – Financial calculations and measures

## 📂 Project Structure

```text
Financial_Performance_Analysis_Dashboard/
│
├── Financial_Dashboard.pbix
├── Financial_Dataset.xlsx
├── Financial_Dashboard_Documentation.docx
├── README.md
│
└── Dashboard_Screenshots/
    ├── Dashboard_Overview.png
    ├── Monthly_Analysis.png
    └── Budget_Analysis.png
```

## 📈 Dashboard Features

### 1. Key Performance Indicators (KPIs)
- Total Revenue
- Total Expenses
- Total Profit
- Overall Profit Margin

### 2. Financial Trend Analysis
- Monthly Revenue Trend
- Monthly Expenses Trend
- Monthly Profit Trend

### 3. Department Analysis
- Department-wise Profit Analysis

### 4. Budget Analysis
- Budget vs Actual Revenue
- Budget vs Actual Expenses
- Monthly Revenue Variance Analysis

### 5. Interactive Filters
- Month Slicer
- Department Slicer

## 🧮 DAX Measures

**Total Revenue**
```DAX
Total Revenue = SUM(Table1[Revenue])
```

**Total Expenses**
```DAX
Total Expenses = SUM(Table1[Expenses])
```

**Total Profit**
```DAX
Total Profit = SUM(Table1[Profit])
```

**Overall Profit Margin**
```DAX
Overall Profit Margin =
DIVIDE(
    SUM(Table1[Profit]),
    SUM(Table1[Revenue]),
    0
)
```

## ⚙️ How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. If prompted, locate the Excel dataset.
4. Refresh the data if required.
5. Explore the dashboard using the Month and Department slicers.

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Financial data analysis.
- Data preparation using Excel.
- Creating interactive dashboards using Power BI.
- Writing basic DAX measures.
- KPI development.
- Trend and variance analysis.
- Presenting business insights visually.

## 🚀 Future Enhancements

- Financial forecasting.
- Automated report generation.
- Real-time financial data integration.
- Advanced business performance analysis.

## 👩‍💻 Author

**Singam Anusha**

B.Tech – Information Technology  
CMR Technical Campus  
Graduation: 2027

---

⭐ This project demonstrates practical applications of Business Analytics and Financial Data Analytics using Excel and Power BI.