# 📈 Sales Dashboard – Power BI

## 📌 Project Overview
This project is an interactive **Sales Dashboard** created in Power BI.  
The goal was to analyze sales performance, product performance, customer behavior, and time-based sales trends using powerful DAX calculations.

## 🔗 Live Dashboard
[👉 View the live Power BI report](https://app.powerbi.com/view?r=eyJrIjoiZTAzZjlmOTUtYmFhZS00YjMxLWJmYjItMDBmNDc3OTU1ZTM2IiwidCI6IjQ2YWMwMGEyLTBkNjMtNDI5MS1hOGIzLTE3MmI4MDc2OGZhNyJ9)

## 🎯 Objectives
- Understand business problem around Sales data  
- Build a complete Sales Data Model  
- Create time-intelligence measures using DAX  
- Visualize product, region, and customer performance  
- Improve dashboard interactivity & usability  
- Publish report to Power BI Service  

---

## 🛠 Tools & Technologies
- Power BI Desktop  
- Power Query  
- DAX (Time Intelligence: YTD, MTD, QoQ)  
- Excel/CSV (source data)  
- Data Modeling (Star Schema)  

---

## 🔧 Steps Followed

### **1. Gathering & Loading Data**
- Imported data from multiple sources (Excel/CSV)  
- Ensured consistency before modeling  

### **2. Data Cleaning & Transformation**
- Handled null values  
- Standardized column formats  
- Added custom calculated columns  
- Ensured clean fact and dimension tables  

### **3. Creating Date Table (Using DAX)**
- Used `CALENDAR()`  
- Added columns:  
  - Month  
  - Quarter  
  - Year  
  - Month-Year  
- Marked as **Date Table**  

### **4. Data Modeling**
- Built relationships between Fact Sales & Dimensions (Date, Customer, Product, Region)  
- Ensured one-to-many relationships  

### **5. DAX Measures**
Created measures for:
- Total Sales  
- Total Profit  
- Profit %  
- YTD Sales  
- MTD Sales  
- Category performance  
- Customer segmentation metrics  

### **6. Visual Design**
- Bar charts, Line charts, Pie charts  
- Matrix table  
- KPI cards  
- Filters & Slicers  
- Regional maps  

### **7. Interactive Tooltips**
- Designed tooltip pages showing detailed insights  

### **8. Publishing to Power BI Service**
- Uploaded dashboard online  
- Enabled sharing & interactive insights  

---

## 📊 Dashboard Features
- Total Sales, Profit & Profit % KPIs  
- Region-wise Sales map  
- Product category performance  
- Customer segmentation  
- Time intelligence analysis (YTD, MTD)  
- Interactive tooltips & slicers  

---


## 📁 Project Structure

```text

sales-dashboard/
├── Sales Dashboard.pbix
├── README.md
├── image/
│   ├── Sales_Overview.png
│   └── Sales Overview.png
└── data/
    └── Sales Analysis Report.xlsx
