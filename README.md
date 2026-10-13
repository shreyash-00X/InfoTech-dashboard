# 📊 InfoTech Sales Analytics – Power BI Dashboard

## 📌 Project Overview

The **InfoTech Sales Analytics Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI**.

The dashboard analyzes sales opportunities, deal performance, pipeline value, win rate, close rate, and average closing time. It provides interactive visualizations and KPIs to help monitor sales performance and understand deal distribution across different stages and pipelines.

---

## 🎯 Project Objectives

* Analyze total sales and pipeline value.
* Monitor win rate and close rate.
* Calculate the average number of days required to close deals.
* Analyze deal distribution by sales stage.
* Compare sales performance across different deal stages.
* Monitor open deal trends over time.
* Analyze deals across different sales pipelines.
* Identify individual deals and their owners.
* Provide interactive filtering by deal owner and pipeline.
* Present sales insights through an easy-to-use Power BI dashboard.

---

## 📁 Dataset

The dataset contains sales deal records with fields related to deal names, owners, stages, pipelines, values, and closing dates.

Key fields used in the analysis include:

* `Deal_Name` – Name of the sales opportunity.
* `Deal_Owner` – Employee responsible for the deal.
* `Deal_Stage` – Current stage of the deal.
* `Pipeline` – Sales pipeline associated with the deal.
* `Deal_Value` – Monetary value of the deal.
* `Close_Date` – Date when the deal was closed.
* `Created_Date` – Date when the deal was created.

*Note: The exact dataset column names may differ depending on the source file.*

---

## 🛠️ Technologies Used

### 🔹 Business Intelligence & Visualization

* Microsoft Power BI Desktop
* Power BI Visualizations
* Power BI Data Modeling

### 🔹 Data Preparation

* Power Query
* Data Cleaning
* Data Transformation
* Data Type Management

### 🔹 Data Analysis

* DAX (Data Analysis Expressions)
* DAX Measures
* KPI Calculations
* Aggregations
* Time-Series Analysis
* Sales Performance Analysis

### 🔹 Power BI Interactive Features

* Slicers
* Interactive Filters
* Cross-Filtering
* Dynamic Visualizations
* Drill-down and data exploration, where configured

### 🔹 Visualization Techniques

* KPI Cards
* Line Charts
* Doughnut Charts
* Column Charts
* Sales Stage Analysis
* Pipeline Analysis
* Deal Trend Analysis
* Tabular Deal Details

---

## 📊 Dashboard Structure

The dashboard presents sales performance through five KPI cards and multiple analytical visualizations.

### 1️⃣ Sales Overview

The overview section provides a high-level summary of the organization's sales performance.

**Key Components:**

* Total Sales
* Win Rate
* Close Rate
* Average Days to Close
* Pipeline Value
* Deal Owner slicer
* Pipeline slicer

### 2️⃣ Last 12 Months

A line chart displaying sales performance over time.

**Purpose:**

* Monitor sales trends across years.
* Identify increases and decreases in sales.
* Understand changes in overall sales performance.

### 3️⃣ Deal by Stage

A doughnut chart showing the distribution of deal values across different sales stages.

**Deal stages include:**

* Lead
* Closed Won
* Proposal
* Negotiation
* Closed Lost
* Contact Made

**Purpose:**

* Understand how deal value is distributed.
* Compare the contribution of different stages.
* Identify the proportion of deals at each stage.

### 4️⃣ Sales by Deal Stage

A column chart comparing sales values across deal stages.

**Purpose:**

* Compare sales performance across stages.
* Identify stages contributing the highest sales.
* Evaluate the distribution of sales opportunities.

### 5️⃣ Open Deal Trend

A line chart showing changes in open deal metrics over time.

**Purpose:**

* Monitor open deal trends.
* Identify changes in the open sales pipeline.
* Understand how the open deal position changes over time.

### 6️⃣ Deals by Pipeline

A doughnut chart showing deal distribution across different sales pipelines.

**Pipelines include:**

* SMB
* Mid-Market
* Startup
* Enterprise

**Purpose:**

* Compare deal distribution across business segments.
* Understand pipeline contribution.
* Identify the relative share of each pipeline.

### 7️⃣ Deal Details Table

A detailed table displaying individual sales opportunities and their owners.

**Purpose:**

* Identify individual deals.
* Review deal ownership.
* Explore deal-level information.
* Support detailed sales analysis.

---

## 📈 Key Dashboard Metrics

### Total Sales

Displays the total value of sales generated from the deals included in the analysis.

### Win Rate

Measures the proportion of deals won relative to the total deals considered in the win-rate calculation.

### Close Rate

Measures the proportion of deals closed relative to the deals considered in the close-rate calculation.

### Average Days to Close

Shows the average time taken to close deals, helping evaluate sales cycle efficiency.

### Pipeline Value

Displays the total value of deals currently represented in the sales pipeline, according to the report's calculation.

*The exact definitions of Win Rate, Close Rate, Total Sales, and Pipeline Value depend on the DAX measures and filters configured in the Power BI model.*

---

## 🎛️ Interactive Features

The dashboard includes:

* 🔽 Deal Owner slicer
* 🔽 Pipeline slicer
* 📊 Interactive KPI cards
* 📈 Dynamic sales trend charts
* 🍩 Deal-stage distribution analysis
* 🍩 Pipeline distribution analysis
* 📋 Detailed deal table
* 🔄 Cross-filtering between visuals, where enabled
* 📌 Deal-level exploration

### Deal Owner Filter

Allows users to analyze sales performance for a particular deal owner or compare the overall results.

### Pipeline Filter

Allows users to focus on a specific sales pipeline, such as SMB, Mid-Market, Startup, or Enterprise.

These filters make it easier to explore sales performance across different employees and business segments.

---

## 💡 Dashboard Insights

The dashboard enables users to analyze:

* Overall sales performance.
* Total value of the sales pipeline.
* Win rate and close rate.
* Average sales cycle duration.
* Deal distribution across sales stages.
* Sales contribution by deal stage.
* Changes in sales over time.
* Open deal trends.
* Deal distribution across business pipelines.
* Individual deal ownership.
* Sales performance by owner and pipeline.

---

## 🎯 Key Outcomes

* Developed an interactive Power BI sales analytics dashboard.
* Created KPI cards for sales performance monitoring.
* Analyzed win rate, close rate, and average closing time.
* Visualized deal distribution across sales stages.
* Compared sales values across deal stages.
* Built time-series charts for sales and open deal trends.
* Analyzed deals across multiple pipelines.
* Added interactive Deal Owner and Pipeline slicers.
* Created a detailed deal information table.
* Designed a centralized view for sales performance analysis.

---

## 🎨 Dashboard Design

The dashboard uses a clean, professional **blue-and-white Business Intelligence theme**.

### Color Palette

* **Primary Background:** Light Blue
* **KPI Card Background:** Blue
* **Chart Background:** White
* **Primary Accent:** Bright Blue
* **Secondary Accents:** Purple, Orange, and Dark Blue
* **Primary Text:** Dark Gray
* **Secondary Text:** Gray

The design focuses on readability, clear KPI presentation, consistent chart layouts, and convenient access to sales information.

---

## 📂 Repository Structure

```text
InfoTech-Sales-Analytics-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── InfoTech_Sales_Analytics.pbix
│
└── Screenshots/
    └── InfoTech_Sales_Dashboard.png
```

*Update the folder and file names to match your actual repository.*

---

## 🖼️ Dashboard Preview

### InfoTech Sales Analytics Dashboard

<img width="1380" height="775" alt="image" src="https://github.com/user-attachments/assets/5982ef66-df90-471b-b3b3-66ab30f4a16c" />


---

## 📦 Project Deliverables

* 📊 Power BI Dashboard (`.pbix`)
* 📁 Sales Dataset (`.csv`)
* 🖼️ Dashboard Screenshot (`.png`)
* 📖 Project Documentation (`README.md`)

---

## 💼 Business Value

The dashboard provides a centralized view of sales performance and helps users:

* Monitor sales results and pipeline value.
* Evaluate win rate and closing efficiency.
* Understand deal-stage distribution.
* Track changes in sales over time.
* Compare performance across pipelines.
* Review individual deals and their owners.
* Support data-driven sales decisions.

---

## 🚀 Project Highlights

* ⭐ Interactive Power BI Dashboard
* ⭐ Professional blue-and-white UI
* ⭐ 5 KPI metrics
* ⭐ Sales trend analysis
* ⭐ Deal-stage analysis
* ⭐ Pipeline distribution analysis
* ⭐ Open deal trend monitoring
* ⭐ Deal Owner and Pipeline slicers
* ⭐ Detailed deal information table
* ⭐ Business-focused data visualization

---

## 👨‍💻 Author

### Shreyash Chaurasia

---

## ⭐ Project

**Built with Microsoft Power BI for interactive sales performance analysis.**
