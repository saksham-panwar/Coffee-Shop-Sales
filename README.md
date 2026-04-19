# ☕ Coffee Shop Sales Dashboard (Excel Project)

## 📌 Overview

This project demonstrates how to build a **fully dynamic sales dashboard in Microsoft Excel** to analyze coffee shop data. The dashboard enables interactive exploration of key metrics such as:

* 💰 Total Sales Revenue
* 👣 Footfall (Customer Count)
* 🧾 Average Bill per Person
* 📦 Average Orders per Person

Users can filter data dynamically by **month, weekday, and hour** using slicers.

---

## 🎯 Project Objective

The goal of this project is to answer key business questions:

* How do sales vary by **day of the week** or **time of day**?
* What are the **peak sales hours**?
* What is the **monthly revenue trend**?
* How do different **store locations** perform?

---

## 📊 Dataset Description

The dataset contains transactional data with the following columns:

* Transaction ID
* Date & Time
* Quantity Sold
* Product ID, Type, Category, Size
* Store ID & Location
* Unit Price

---

## 🛠 Tools & Technologies

* Microsoft Excel
* Power Query Editor
* Power Pivot
* Pivot Tables & Charts
* Slicers

---

## 🔄 Workflow

### 1. Data Import & Cleaning

* Imported data using **Power Query**
* Removed unnecessary columns
* Cleaned product details (removed extra characters, spaces)
* Extracted product size (Small, Regular, Large)

---

### 2. Feature Engineering

Created new columns for better analysis:

* **Total Bill = Unit Price × Quantity**
* Extracted:

  * Month Name
  * Weekday Name
  * Hour

---

### 3. Data Modeling

* Loaded cleaned data into **Excel Data Model**
* Enabled **Power Pivot**
* Created measures for KPIs

---

### 4. Data Analysis (Pivot Tables)

Used pivot tables to:

* Calculate **Total Revenue**
* Count transactions as **Footfall**
* Analyze:

  * Hourly trends
  * Weekly trends
  * Monthly trends

---

### 5. Visualizations

Created charts for insights:

* 📈 Line Chart → Hourly Sales Trends
* 📊 Bar Chart → Sales by Weekday
* 🥧 Pie Chart → Product & Location Distribution

---

### 6. Product & Store Analysis

* Identified top-selling products (e.g., Espresso-based drinks)
* Compared store performance
* Highlighted best-performing locations

---

### 7. Dashboard Design

Enhanced dashboard aesthetics:

* Coffee-themed color palette ☕
* Clear titles and labels
* Rounded borders & gridlines
* Clean layout for readability

---

### 8. Interactivity (Slicers)

Added slicers for:

* Month
* Day

Features:

* Dynamic filtering
* Custom styling
* Controlled report connections

---

### 9. Key Performance Indicators (KPIs)

* **Total Revenue**
* **Total Footfall**
* **Average Bill per Person**
* **Average Order per Person**

Displayed using formatted cards/shapes.

---

## 📐 Core Formulas

```text
Total Bill = Unit Price × Quantity

Footfall = DISTINCTCOUNT(Transaction ID)

Average Bill per Person = SUM(Total Bill) / Footfall

Average Order per Person = SUM(Quantity) / Footfall
```

---

## 🧩 Final Dashboard Features

* Fully interactive dashboard
* Time-based filtering (Month, Day, Hour)
* KPI summary cards
* Multiple visual insights
* Clean and professional design

---

## 🔐 Sheet Protection

* Locked dashboard to prevent accidental edits
* Enabled slicer interaction after protection

---

## 🚀 Deployment & Sharing

### GitHub

* Uploaded:

  * Excel file (.xlsx)
  * Project documentation (PDF)
  * Dashboard screenshots

### LinkedIn

* Shared project with:

  * Description of objectives
  * Tools used
  * Key insights
* Used hashtags and tags for visibility

---

## 📷 Screenshots

*(Add your dashboard screenshots here)*

---

## 📈 Key Learnings

* Data cleaning is crucial for accurate insights
* Excel can be a powerful analytics tool
* Interactive dashboards improve decision-making
* Visualization enhances data storytelling

---

## 💡 Conclusion

This project demonstrates an **end-to-end data analytics workflow in Excel**, from raw data to actionable insights. It is a strong portfolio project for aspiring data analysts and helps in understanding real-world retail analytics.

---

## 📁 Project Structure

```
📦 Coffee-Shop-Sales-Dashboard
 ┣ 📊 Coffee_Shop_Dashboard.xlsx
 ┣ 📄 Project_Report.pdf
 ┣ 📸 Screenshots/
 ┗ 📄 README.md
```

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub and share your feedback!

