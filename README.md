# 💸 Personal Finance Tracker Dashboard – Excel

A comprehensive and interactive **Personal Finance Tracker Dashboard** built using **Microsoft Excel**. This project was inspired by a workshop session led by **Freedom** and hosted by **Evergreen Digital Tech Solution**. The aim was to enhance financial visibility using a user-friendly and visually appealing dashboard design.

## 🧩 Problem Statement

Design and develop a **Personal Finance Tracker Dashboard** in Excel that offers a seamless user experience with advanced UX elements. The dashboard should help users:

- Track income and expenses
- Visualize category-wise spending
- Understand saving patterns
- Interact with data dynamically

## 📸 Visual Preview
![Finance Dashboard Preview](https://github.com/naheeda78/Personal-Finance-Tracker-Dashboard/blob/main/Personal%20finance%20tracker%20dashboard.png)


## 🛠️ Tools & Features Used


- Microsoft Excel
- Pivot Tables
- Slicers
- Custom Icons from [Flaticon](https://www.flaticon.com/)
- Wireframing and Layout Planning
- UX-focused Dashboard Design

## 🧾 Dataset Description

The dataset used in this project captures real-life finance entries across various categories:

| Column Name      | Description                                   |
|------------------|-----------------------------------------------|
| `Date`           | Date of the transaction (dd-mm-yyyy)          |
| `Type`           | Income or Expense                             |
| `Category`       | Spending/earning category (e.g. Housing, Job) |
| `Amount`         | Transaction amount                            |
| `Source`         | Platform/source of income (YouTube, Job, etc) |
| `Day`            | Weekday name (Mon, Tue, etc.) for trend analysis |
| `Month`          | Month name (Jan, Feb, etc.) for trend charts  |

## ✅ Project Steps

### 1. **Data Cleaning & Preparation**
- Identified and cleaned data anomalies (if any).
- Added helper columns to simplify calculations (e.g., Month, Month Number, Net Amount, etc.).
- Ensured consistent formatting and data types.

 ### 2. **Data Analysis**
- Created **Pivot Tables** to calculate:
  - Total Income & Expense
  - Category-wise breakdown
  - Monthly & Weekly trends
  - Net Savings
- Finalized color themes, layout structure, and visual hierarchy.
- Used custom icons and labels for intuitive understanding.

### 3. **Dashboard Design**
- Built an interactive dashboard layout with:
  - Key Metrics Cards (Total Income, Expense, Savings)
  - Monthly and Monthly Trend Charts
  - Slicers for dynamic filtering (e.g., by Month)
- Enhanced navigation and user flow using a clean, structured design.

## 🧪 Feature Engineering (Excel Formula-Based)

To enhance analysis and build insightful visualizations, we performed **feature extraction** from the raw `Date` column:

| New Column | Formula Used (in Excel) | Description |
|------------|--------------------------|-------------|
| `Month`    | `=TEXT(A2, "mmm")`       | Extracts 3-letter month name from Date |
| `Day`      | `=TEXT(A2, "ddd")`       | Extracts weekday name (Mon, Tue, etc.) from Date |

These columns are crucial for:
- **Monthly trend analysis** in bar charts
- **Weekday spending pattern** visualization
- **Grouping data** in Pivot Tables dynamically

> 🧠 These transformations allow the dashboard to stay dynamic, filterable, and timeline-aware.

## 🔍 Primary Analysis (Pivot Table Layer)

The `Calculations` sheet is dedicated to:
- Creating **Pivot Tables** for income and expense aggregation
- Calculating KPIs like **total income**, **total spending**, **available balance**
- Deriving **monthly** and **weekly trends**
- Feeding structured results into the dashboard using linked cells

  ## 📊 Key Dashboard Metrics

| Metric                  | Value     |
|------------------------|-----------|
| 💰 Available Balance   | $35,249   |
| 📥 Total Income        | $65,440   |
| 📤 Total Spending      | $30,191   |
| 🧾 Max Income Source   | Data with Decisions - $50,000 |
| 🏠 Top Spending        | Housing - $9,000 |
| 📅 Max Weekly Spending | Monday - Highest |
| 📆 Max Monthly Income  | October - $5,000 |

---

## 🧩 Dashboard Features

- 💳 **Credit Card-Style Balance Card** showing available funds
- 📈 **Monthly Trends** (bar chart) for income and expenses
- 📊 **Top 5 Expense Categories** visualized as colored KPI blocks
- 🕒 **Weekly Trend Chart** to analyze weekday spending habits
- 🍩 **Income Source Distribution** with percentage-wise donut chart
- 🌘 **Dark Theme Dashboard** for a clean and modern user experience
