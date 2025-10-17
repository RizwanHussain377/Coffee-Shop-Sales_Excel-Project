# ☕ **Coffee Shop Sales Analysis — Excel Project**

A **professional, easy-to-read Excel workbook** that turns coffee shop POS transactions into **clear business insights**.
The workbook focuses on **sales trends, product performance**, and **customer behaviour** — featuring a **polished dashboard** for quick decision-making.

---

## 📘 **Table of Contents**

* [Overview](#overview)
* [Screenshot](#screenshot)
* [Files included](#files-included)
* [Tools used](#tools-used)
* [How to open & use](#how-to-open--use)
* [Analysis & methodology](#analysis--methodology)
* [Key insights](#key-insights)

---

## 🧾 **Overview**

This project transforms **raw point-of-sale (POS) export data** into an **actionable sales analysis and visual dashboard**.
It helps coffee shop owners and managers quickly understand **revenue trends**, **top-performing items**, and **customer ordering patterns** so they can make **informed staffing, menu, and promotion decisions**.

**Primary objectives:**

* 📈 Track **revenue and sales volume** over time.
* ☕ Identify **top and under-performing products and categories**.
* 💰 Measure **average order value (AOV)** and **units per transaction**.
* 📊 Provide a **concise, interactive dashboard** for daily/weekly/monthly reviews.

---

## 🖼️ **Screenshot**

![Dashboard preview](https://github.com/RizwanHussain377/Excel-Projects/blob/main/Coffee%20Shop%20Sales%20Project/ScreenShot%20CoffeeShopSales.png)

> **Coffee shop sales dashboard** showing KPIs (Total Sales, AOV), Monthly Sales Trend, Top Products Bar Chart, and Interactive Slicers.

---

## 📂 **Files Included**

* **Coffee Shop Sales.xlsx** — Main Excel workbook containing:

  * 📄 *Raw Data* sheet (original transactions)
  * 🧹 *Cleaned Data* sheet (normalized for analysis)
  * 📊 *PivotTables & Calculations* sheets
  * 📈 *Dashboard* sheet (KPIs, charts, slicers/timelines)
  * 🗂️ *Lookup/support tables* (product master, categories)

* **README.md** — Project overview *(this file)*

* **assets/screenshots/dashboard-preview.png**

---

## 🛠️ **Tools Used**

* **Microsoft Excel** *(recommended: Excel 2016 or later; Office 365 preferred)*

**Excel features applied:**

* 📋 Tables (structured ranges)
* 📊 PivotTables & PivotCharts
* 🎛️ Slicers and Timeline controls
* 🎨 Conditional Formatting and KPI Cards
* 🧮 Formulas: `SUMIFS`, `AVERAGEIFS`, `COUNTIFS`, `INDEX/MATCH`, or `XLOOKUP`
* ⚙️ **Power Query** for repeatable ETL and large datasets
* 💡 **Power Pivot** for analyzing large data and creating relationships between tables

---

## 🚀 **How to Open & Use**

1. Open **Coffee Shop Sales.xlsx** in Excel and **enable editing**.
2. Start on the **Dashboard** sheet to view **high-level KPIs and charts**.
3. Use **slicers and timeline** to filter by *date range*, *product category*, and *store location (if available)*.
4. Inspect the **Cleaned Data** or **Pivot** sheets to validate calculations or drill into transactions.
5. If using **macros**, enable them only from a **trusted source**.

**Quick tips:**

* 🔄 Turn on *Excel’s Full Calculation mode* if figures don’t update immediately.
* 🕵️‍♀️ Use the built-in *Pivot Drill-Down* (double-click a pivot value) to view underlying transactions.

---

## ⚙️ **Analysis & Methodology**

**Typical data pipeline inside the workbook:**

1. **Import:** Load raw POS CSV/XLSX into the *Raw Data* sheet.
2. **Clean:** Normalize date/time, product names, fix missing categories, and remove duplicates.
3. **Enrich:** Add calculated columns *(Total Sale, AOV, Units per Transaction)*

   * 💵 *Total Sale = Quantity × Unit Price - Discount*
   * 📊 *AOV = Total Sales ÷ Number of Orders*
4. **Aggregate:** Build *PivotTables* for time-series, product/category ranking, and customer segmentation.
5. **Visualize:** Create charts and KPI cards on the *Dashboard* with slicers for interactive exploration.

**Design considerations:**

* 🧱 Keep **source data untouched**; perform transformations on separate sheets.
* 🧩 Use **structured Tables** to make formulas and pivots resilient to added rows.
* 🏷️ Use **named ranges** for key metrics to make dashboard formulas clearer.

---

## 💡 **Key Insights**

Below are the kinds of insights this workbook is designed to surface. *(Replace placeholders with your workbook’s actual values from the pivot outputs.)*

* ⏰ **Sales cadence:** Typical peaks during **morning rush (7–10 AM)** and **late afternoon on weekends**.
* 📅 **Monthly trend:** Month-over-month revenue growth/decline *(replace with computed %)*.
* 🥇 **Top products:** Top 5 SKUs contributing the majority of revenue.
* 🍩 **Category split:** Beverages vs. food — share of revenue and units sold.
* 💵 **Average Order Value (AOV):** Current AOV and suggestions to lift it *(upsell combos, promotions)*.
* 👥 **Customer behaviour:** Repeat vs. new customer ratio and frequency *(if Customer ID is available)*.
* 📦 **Inventory signals:** Slow-moving SKUs *(bottom X%)* that could be promoted or delisted.
