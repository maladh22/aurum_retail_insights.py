# aurum_retail_insights.py
Automated Multi-Location Sales Reporting Tool
# Aurum Analytics | Sales & Returns Report Generator

This Python script generates an automated Excel report for a multi-location retail business. It processes both **sales** and **return** data and outputs a clean, Excel-formatted report with subtotals, net sales, and SKU-level details.

---

## 📊 Features

- Filters relevant records with statuses: **Shipped** or **Returned**
- Aggregates **Sales** and **Return Item Quantities**
- Calculates **Net Sales** per SKU
- Adds **Subtotal Rows**
- Generates **separate Excel sheets** for each location

---

## 📂 Input Files

- `sales_test.csv`: Sales transactions
- `return_report.csv`: Return transactions

**Required Columns:**  
`Company Name`, `Order Status`, `Item Quantity`, `MP Name`, `Sales Channel`, `Component SKU`

---

## 📄 Output

- `Aurum_Analytics_Sales_Report.xlsx`: A multi-sheet Excel workbook with data for:
  - Bangalore  
  - Kolkata  
  - Mumbai  
  - Bilaspur

---

## 🧠 Skills Demonstrated

- Data Cleaning & Filtering  
- Grouping and Aggregating with `pandas`  
- Multi-sheet Excel report creation using `openpyxl`  
- Modular, Reusable Code  

---

## 🚀 How to Run

```bash
python aurum_sales_returns_report.py

